<%*
// Base path of the current folder
const basePath = tp.file.folder(true);

// Function to recursively list files and folders
function listFiles(basePath, parentName, depth = 0) {
  let fileIndex = '';
  let files = app.vault.getFiles().filter(file => file.path.startsWith(basePath) && file.path !== basePath);
  let folders = [];

  files.forEach(file => {
    let relativePath = file.path.substring(basePath.length + 1);
    if (relativePath.includes('/')) {
      let folderPath = relativePath.substring(0, relativePath.indexOf('/'));
      if (!folders.includes(folderPath)) {
        folders.push(folderPath);
      }
    } else {
      // Exclude files that have the same name as their parent folder
      if (file.basename !== parentName) {
        fileIndex += '  '.repeat(depth) + `- [[${file.path}|${file.basename}]]\n`;
      }
    }
  });

  folders.forEach(folder => {
    let folderPath = basePath + '/' + folder;
    fileIndex += '  '.repeat(depth) + `- **${folder}/**\n`;
    fileIndex += listFiles(folderPath, folder, depth + 1);
  });

  return fileIndex;
}

// Generate the index
const indexContent = listFiles(basePath, tp.file.title);

// Output the index
tR += indexContent;
%>