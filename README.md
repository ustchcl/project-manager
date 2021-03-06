# project-manager

1. 重写所有数据逻辑
2. 完成服务器联调
3. 服务器: 用户的默认配置
4. 登陆逻辑

## features

### concept1
Project 
 - several views: Board, Calendar, List and Gantt.
 - team-member
 - Only administrators and managers can create projects for Multiple Users
 - tags

Milestone
- title
- description
- deadline


User
 - role: Project Manager & Team Member

Task
 - Title: The title of your task, which will be displayed on the board.
 - Description: Description that use the Markdown syntax.
 - Tags: The list of tags associated to tasks.
 - Create another task: Check this box if you want to create a similar task (some fields will be pre-filled).
 - Color: Choose the color of the card.
 - Assignee: The person that will work on the task.
 - Category: Only one category can be assigned to a task (visible only if the projects have categories).
 - Column: The column where the task will be created, your task will be positioned at the bottom.
 - Priority: Task priority, the range can be defined in the project settings, default values are P0 to P3.
 - Complexity: Used in agile project management (Scrum), the complexity or story points is a number that tells the team how hard the story is. Often, people use the Fibonacci series.
 - Reference: External ID for the task, for example it can be ticket number that come from another system
 - Original Estimate: Estimation in hours to complete the task.
 - Time Spent: Time spent working on the task.
 - Start Date: This is a date time field.
 - Due Date: Overdue tasks will have a red due date and upcoming due dates will be black on the board. Several date format are accepted in addition to the date picker.