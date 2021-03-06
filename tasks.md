# Task Scheduler

The task scheduler is a great way to run scripts in a periodic fashion. You may find the need to automatically archive log files into a compressed file. Perhaps send an email with a generated report based on stale site content. 

### Video Tutorial

[![Scheduled Task Editor](http://img.youtube.com/vi/Q6QKqRwrkuU/0.jpg)](https://youtu.be/Q6QKqRwrkuU "Click for a quick demo")

### Scheduled Task Command

To help make the setup simple, we've provided a *Task Command*.

![PowerShell Script Command](images/screenshots/tasks-powershellscriptcommand.png)

The command shown above is simply a type exposed as a public method in the *Cognifide.PowerShell* assembly. There exists an update method which accepts one or more items and executes the associated script.

Beneath *Schedules* you can create as many tasks as Sitecore will allow. Configure the *Command* and *Items* fields like that shown below.

![PowerShell Script Task](images/screenshots/tasks-archiveschedule.png)

The *Items* field contains the path to a script in the *Script Library*. 

Below are some of the scripts found out-of-the-box with SPE.

| Module | Script |
| ------ | ---- |
| System Maintenance | Archive Sitecore logs, Clean up deleted items older than 30 days |
| User Session Management | Remove idle user sessions |

### Create and Manage Tasks

We've added a context menu item to provide you with a shortcut to the Task Scheduler Editor.

Create a new scheduled task:

![Insert Option for Task](images/screenshots/task-inserttask.png)

Run or edit the scheduled task:

![Run or Edit Task Schedule](images/screenshots/task-runedittask.png)

The scheduled task is capable of running 1-to-many scripts. Choose all that apply for the selected task.

![Dialog to Select Task Scripts](images/screenshots/task-createtaskwithscripts.png)

The task schedule has an intuitive dialog for working with and changing the frequency. 

![Dialog to Edit Task Schedule](images/screenshots/task-edittaskschedule.png)

**Note:** Examples included are in the following modules
* License Expiration
* Media Library Maintenance
* System Maintenance

See how Adam added [powershell driven Sitecore scheduled tasks][1].

[1]: http://blog.najmanowicz.com/2011/11/29/powershell-driven-sitecore-scheduled-tasks/