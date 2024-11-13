# Index of <%*
let title = tp.file.title; // Gets the current file's title
if (tp.frontmatter.aliases && tp.frontmatter.aliases.length > 0) {
    title = tp.frontmatter.aliases[0]; // Use the first alias if it exists
} else {
    // If no alias, replace hyphens with spaces and convert to title case
    title = title.replace(/-/g, ' ').split(' ')
                 .map(word => word.charAt(0).toUpperCase() + word.slice(1).toLowerCase())
                 .join(' ');
}
tR += title;
%>

<%* tR += '%% ' + 'Waypoint ' + '%%'; %>