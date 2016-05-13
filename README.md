# To-Do-List-Extension

## Separate checklists based on completion status
Add sections to the `AllListsViewController` for incomplete and complete checklists. Checklists which have not yet been completed should appear in a section titled *In Progress*. Checklists whose items have all been checked off will fall into the *Completed* section with their titles grayed out.

## Add sublists to items in the ChecklistViewController
Tapping on a task should show its sub-items if any exist. Tapping on a sub-item should mark it as complete. Once all sub-items are marked as complete, the task should also be marked as complete. If no sub-items exist for a task, tapping on a task should mark it as complete.
