# To Do List Extension

## Goals
Before starting this lab, you should have completed Tutorial 2 of Ray Wenderlich's iOS Apprentice (Beginning iOS Development with Swift 2). That tutorial continued your introduction to the Swift programming language and introduced table views, navigation controllers, and delegates. With this extension you'll get additional practice working on these concepts. The Advanced section will also test your ability to search for and implement third-party code in the form of Cocopods.

## Separate checklists based on completion status
Add sections to the `AllListsViewController` for incomplete and complete checklists. Checklists which have not yet been completed should appear in a section titled *In Progress*. Checklists whose items have all been checked off will fall into the *Completed* section with their titles grayed out.

### Update the Checklist to include a Completion Status attribute

* Edit the Checklist class
* Edit the Checklist data model

### Create separate sections in the AllListsViewController

### Read the Completion Status of the 


## Add sublists to items in the ChecklistViewController
Tapping on a task should show its sub-items if any exist. Tapping on a sub-item should mark it as complete. Once all sub-items are marked as complete, the task should also be marked as complete. If no sub-items exist for a task, tapping on a task should mark it as complete.

## Advanced (Optional)

### Reordering
Find a way to allow users to tap and hold a table view cell to drag and reorder it within a list.

### Expanding table view cells
Instead of displaying a task's sub-items as table view cells when the task is tapped, expand the task's cell and display the sub-items within that cell. This will be an exercise in googling, and you may wind up using a cocoapod to accomplish this portion of the assignment.