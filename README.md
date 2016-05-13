# To-Do-List-Extension

## Separate checklists based on completion status
Add sections to the `AllListsViewController` for incomplete and complete checklists. Checklists which have not yet been completed should appear in a section titled *In Progress*. Checklists whose items have all been checked off will fall into the *Completed* section with their titles grayed out.

## Add sublists to items in the ChecklistViewController
Tapping on a task should show its sub-items if any exist. Tapping on a sub-item should mark it as complete. Once all sub-items are marked as complete, the task should also be marked as complete. If no sub-items exist for a task, tapping on a task should mark it as complete.

## Advanced (Optional)
### Reordering
Find a way to allow users to tap and hold a table view cell to drag and reorder it within a list.

### Expanding table view cells
Instead of displaying a task's sub-items as table view cells when the task is tapped, expand the task's cell and display the sub-items within that cell. This will be an exercise in googling, and you may wind up using a cocoapod to accomplish this portion of the assignment.