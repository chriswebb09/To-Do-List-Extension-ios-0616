# To Do List Extension

## Goals
Before starting this lab, you should have completed Tutorial 2 of Ray Wenderlich's iOS Apprentice (Beginning iOS Development with Swift 2). That tutorial continued your introduction to the Swift programming language and introduced table views, navigation controllers, and delegates. With this extension you'll get additional practice working on these concepts. The Advanced section will also test your ability to search for and implement third-party code.

## Separate checklists based on completion status
Instead of grouping all of our checklists together, let's add sections to the `AllListsViewController` to differentiate complete checklists from those still in progress. Checklists which have not yet been completed should appear in a section titled *In Progress*. Checklists whose items have all been checked off will fall into the *Completed* section with their titles grayed out.

### Update the Checklist to include a Completion Status attribute
* Edit the Checklist class
* Edit the Checklist data model
* Every time a task is completed, a check to see if the checklist is completed should be run and the isCompleted property of that checklist should be changed when necessary

### Create separate sections in the AllListsViewController
* Create two sections. Set the section header titles appropriately.

### Read the Completion Status of the checklists and sort them appropriately
* Every time we load the `AllListsViewController`, the `isCompleted` property on each checklist should be read. Checklists should be sorted into the appropriate section.
* Lists in the *Completed* section should appear visibly different from those in the *In Progress* section.

## Add sub-lists to items in the ChecklistViewController
Often times it's useful to have lists within a single task on a list. A simple example is a high-level list titled *Home*, which contains tasks such as:

* Do Laundry
* Clean up from last night's ice cream party
* Locate missing ice cream scoop
* Get Groceries

But what if we want more detail for a certain item on that list? Say we want to describe all the groceries we need to speed up our shopping trip. One way to do this would be to have a list of sub-items for the *Get Groceries* task:

* Get Groceries
  * Ice cream
  * Chocolate syrup
  * Sprinkles

Here are the criteria for our multilevel list extension: Tapping on a task should show its sub-items, if any exist. Tapping on a sub-item should mark it as complete. Once all sub-items are marked as complete, the task should also be marked as complete. If no sub-items exist for a task, tapping on a task should mark it as complete.

## Advanced (Optional)

### Reordering
Find a way to enable users to reorder lists and items. [This tutorial](https://www.raywenderlich.com/63089/cookbook-moving-table-view-cells-with-a-long-press-gesture) will be of help.

### Expanding table view cells
Instead of displaying a task's sub-items as table view cells when the task is tapped, expand the task's cell and display the sub-items within that cell. This will be an exercise in googling. Look for Cocoapods to help you accomplish this portion of the assignment.