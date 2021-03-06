# MarkDown To-Do

- [ ] Do this
- [ ] Do that
- This is not a valid to-do item: [ ] Do not do anything

## Features

- Watches for new files being created and shows them in the To-Do tree view
- Updates the tree view by updating the headers and to-do items of changed files
- Removes changes files from the tree view if they no longer contain any to-do items
- Handles file detetions by removing the affected files fully from the tree view
- Contributes a context menu command for removing and toggling to-do items
- Indexes the workspace in memory after activation and displays the initial tree of workspace files, their headers and to-do items
- Has in-tree icons for toggling and removing checkboxes
- Contributes a command for refreshing (for projecting changes without saving)
- Contributes a command for toggling visibility of ticked to-do items in the tree view
- Contributes a command for toggling between sorting by file name or file unticked checkbox count
- Contributes a code lens for each MarkDown checkbox with commit date, remove command and contextual tick/untick command
