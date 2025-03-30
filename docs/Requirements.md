ID Number: 1
Type: Functional 
Description: The ability to create tasks that have a name, description, start date, end date
Rationale: The main focus of the program is on user tasks so the user must be able to create tasks.
Fit Criterion: A button that causes a form to appear with the text fields Name, Description, Start Date, End Date and prerequisite once submitted causes a box to appear in the schedule. 
Priority: High
Dependencies: 
---
ID Number: 2
Type: look and feel
Description: when creating a task have a pop up appear at the corner of the screen that confirms the creation of the task.
Rationale: The user may require feedback on their action to confirm their action took place correctly.
Fit Criterion: Once a task has been created a confirmation message should appear.
Priority: low
Dependencies: ID 1
---
ID Number: 3
Type: Functional
Description: Ability to delete tasks.
Rationale: Wrongful creation of tasks may occur or the task is no longer needed. So the ability for users to remove tasks is needed.
Fit Criterion: After Clicking on a task that option to delete the task should appear. A pop up will appear once the option is selected asking to confirm deletion of the task. After the confirmation check of deleting the task the box of the corresponding task should disappear from the schedule.
Priority: High
Dependencies: ID1
---
ID Number: 4
Type: look and feel
Description: when deleting a task have a pop up appear at the corner of the screen that confirms the creation of the task.
Rationale: The user may require feedback on their action to confirm their action took place correctly.
Fit Criterion: Once a task has been created a confirmation message should appear.
Priority: Low
Dependencies: ID 3
---
ID Number: 5
Type: Functional 
Description: Ability to modify existing tasks.
Rationale: Mistakes can occur in the creation of tasks or changes may be necessary after creation. So the ability to modify tasks is needed.
Fit Criterion: when selecting a task the option to modify it can be selected. Once selected the detail form of the task should appear that can be edited. The changed data of the task is reflected on the viewing of the task
Priority: High-Mid
Dependencies: ID1
---
ID Number: 6
Type: Functional
Description: Ability to mark tasks status(i.e. To do, in progress, done).
Rationale: Users may want to keep track of progress on tasks.
Fit Criterion: A button on the toolbar will have a drop down of statuses after clicking on the status the next task selected will change to the status. The task box in the schedule will change color based on status selected. 
Priority: Mid-Low
Dependencies: ID1, ID5
---
ID Number: 7
Type: Functional 
Description: Ability Mark the importance of the task(i.e. Low priority, mid priority and high priority). 
Rationale: Users may want to focus on tasks that are more important than others. 
Fit Criterion: A button on the toolbar will have a drop down of statuses after clicking on the status the next task selected will change to the status. The task box in the schedule will change border color based on status selected based. 
Priority: Mid-Low
Dependencies: ID1, ID5
---
ID Number: 8
Type: Usability
Description: Ability to drag tasks to different starting dates.
Rationale: Instead of opening up the task detail form to change the starting date it would be easier for the user to just drag the task.
Fit Criterion: Once dragged to a new date the detail form of the task should reflect the changed date.
Priority: Mid
Dependencies: ID1
---
ID Number: 9
Type: Functional 
Description: Ability to link tasks for the purpose of creating prerequisite tasks that need to be completed before the other task.
Rationale: Some tasks may need to be completed before other tasks can begin. To be able to connect them together will help the user to remember the tasks prerequisite. 
Fit Criterion: There will be a button for linking tasks once clicked the user will click on both of the tasks they wish to connect starting with the prerequisite. A visual indication on the respective task that shows a connection with another task after being marked by the user action. The detailed form of the task will also be editable to link tasks by name.
Priority: High-Mid
Dependencies: ID1
---
ID Number: 10
Type: Functional 
Description: Ability to unlink tasks.
Rationale: The user may be mistaken in thinking certain tasks need to be completed before others and have linked them. So they may require the ability to undo the linking process.
Fit Criterion: Once the action to unlink occurs the visual indication of the link should disappear from the respective tasks.
Priority: Mid
Dependencies: ID9
---
ID Number: 11
Type: Functional
Description: Ability to group tasks to help organize all tasks.
Rationale: Some tasks may be for different projects that require the ability to distinguish what tasks are related to each other. Groups allow the user to create that distinction. 
Fit Criterion: Next to the group name there should be an add and remove button. The task name should appear on the list of the group.
Priority: Mid
Dependencies: ID1
---
ID Number: 12
Type: functional 
Description: Ability to remove tasks from the group.
Rationale: Users may need to reorganize the groups so the ability to remove them is necessary.
Fit Criterion: The Task should no longer appear in the group.
Priority: Mid
Dependencies: ID11
---
ID Number: 13
Type: Usability 
Description:  Ability to highlight all tasks of a certain group.
Rationale: Users may want to see all tasks of a group more easily on the schedule so making them more noticeable from other tasks should help.
Fit Criterion: A clear visual change on the schedule differentiating the group tasks from other tasks.
Priority: Low
Dependencies: ID11
---
ID Number: 14
Type: Usability 
Description: When hovering over buttons provide feedback to the user by changing its color or some similar effect. 
Rationale: The user may find it helpful that the button shows indication that it will be pressed before pressing to confirm they are selecting the right button and will actually trigger the tool.
Fit Criterion: Buttons will change color when hovering on them.
Priority: Low
Dependencies: 
---
ID Number: 15
Type: Usability 
Description: When clicking on buttons provide feedback to the user by changing its color or some similar effect. 
Rationale: The user will probably find it helpful that the button shows indication that it has been clicked to confirm the user's action.
Fit Criterion: Buttons will change color when clicking on them.
Priority: Low
Dependencies: 
---
ID Number: 16
Type: Usability 
Description: Ability to view all tasks in a list order by date
Rationale: This may be preferable at certain times to simplify the order in which one does tasks.
Fit Criterion: A button that changes the view into a list of tasks ordered by date
Priority: Mid-Low
Dependencies: ID1
---
ID Number: 17
Type: Look and feel
Description: Toolbar on top of screen with all user actions(i.e. Create tasks, groups, mark status, mark priority, link) in the form of buttons to initiate actions. The UI for the tool bar must be simple and tools clear in use.
Rationale: Keeping all the user tools in one location with clear icons will make it easier for user to understand how to use the product
Fit Criterion: Toolbar on top of screen
Priority: Mid
Dependencies:
---
ID Number: 18
Type: Look and feel
Description: To avoid cluttering the toolbar more options for certain user actions will be displayed upon selecting the action through a drop down menu. Not all user actions will need the drop down menu but things like groups for tasks need to have the ability to create groups, show existing groups, adjust the groups whether it be adding or removing tasks. The drop down menu will help free up the visual space of the product. 
Rationale: There are a lot of actions the user can take but consuming too much screen space will limit the ability to view the actual tasks on the schedule. So having the actions grouped up into drop down menus will alleviate the issue.  
Fit Criterion: Once a button is clicked that has more tools available a drop down menu will appear.
Priority: Mid
Dependencies: ID17
---
ID Number: 19
Type: Look and feel
Description: A Bar below the toolbar to display the timeframe being displayed to the user. The timeframe will be by default a week and only showing tasks that are in that week. The bar will have marks indicating days almost like a ruler.
Rationale: This helps the user visualize the time that tasks start and end  instead of having to open up the task details.
Fit Criterion: A bar that helps show the days tasks begin and end above the task schedule.
Priority: Mid
Dependencies:
---
ID Number: 20
Type: functional 
Description: The ability to change the time frame the schedule shows to a day or month or 3 months.
Rationale: Depending on how the user is planning it may be necessary for them to view a time frame of greater time then the default of a week. They could also only want to plan for the more immediate or simply focus on the more upcoming tasks so switching to a smaller time frame could give them that focus.  
Fit Criterion: A button is available in the toolbar to toggle through the various time frames.
Priority: Mid
Dependencies: ID19
---
