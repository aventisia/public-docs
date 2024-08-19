# Create a workflow
Learn how to navigate and build workflows.

⁠Workflows allow you to build out powerful and flexible automated processes. While Getting started with Workflow Builder provides an overview of workflows, here you will find an in-depth guide to navigating and building out your workflows.

## Navigate the workflows canvas
The workflow canvas is the backdrop on which you will add and order the trigger and activities that make up your workflow. Utilize the following options to move around the canvas:

+ **Drag mode**: The default mode, it allows you to move around the canvas by scrolling with a trackpad. 

+ **Zoom**: Adjust your zoom settings to magnify or decrease the size of workflow on the canvas. Click the magnifying plus and minus signs in the right-bottom on the screen to zoom in, out, or to a set percentage. You can also click on the dotted square symbol, to fit your workflow to screen size. 

+ **Lock**: Click the lock icon at the bottom-rigth of the screen to ...

+ **Undo/Redo**: You can click the undo or redo buttons on the top-right of the screen to reverse or reapply your actions.

+ **Mini-map**: This is at the bottom-left of the screen and gives you a one eye view of the workflow as you build it. 

+ **Preferences**: This functionality is at the top-left of the screen and helps you hide or unhide the above functionalities to enable you to customize your screen as required. You also have an option to choose your layout option for your workflow here, you can choose Left to Right or Top to Bottom depending upon your preference. 

+ **Right Click on Canvas**: If you have changed your layout option in the preferences section, you can right click anywhere on the canvas and click organize for the layout to change. You also get some common editing options when you right click on the canvas, like cut, copy, paste, delete. 

+ **Switching Workflows**: You can see the name and version number of the workflow you are building on the top-left corner of the screen. By clicking on it you can switch between workflows if you have more than one workflow open. You can also start a new workflow by clicking on the plus sign on the pop-up window that opens up. 

+ **Notifications**: Click on the bell icon on the top-left corner of the screen to see any notifications sent to you. 

## Build a workflow

### Create a new workflow
Follow these steps to create a new workflow:

+ Click Automations in the left-hand sidebar

+ Click on the plus (+) sign in the upper-right, or click the ⋮ icon to the right of an existing workflow and choose Duplicate workflow to start with a copy of it

### Choose a template or trigger
Choose whether you want to begin with a pre-built template or start from scratch.

#### Start with a template
If you want to begin with a pre-built flow, you can select a template to utilize as a starting point or inspiration. Click the Start with a template button on the canvas, then select a template and click Use this template.

You can also change to a template at any time by selecting Templates in the lower-right, but keep in mind that selecting a template will delete any activities you have already added since your workflow will reset to the template.

#### Start from scratch
If you are starting from scratch, begin by choosing a trigger. The trigger is the condition that, when met, causes your workflow to run. For example, you may want your workflow to run each time a new record is created, or each time a form is submitted. Find an explanation of each available trigger in our workflows [Activities library](aventisia/public-docs/Flow-Builder/activities-library.md).

Once you’ve selected a trigger, you may be required to define an Input, which tells the workflow more specifically when you want it to run. For example, if you’ve selected the Record created trigger, you could select Customer for the Object Input if you want the workflow to run whenever a Customer record is created.

To change the trigger selected for a workflow, simply select it and click Edit to choose a different option.

### Add action activity
Action activity defines what a workflow will do once the trigger conditions are met. Action activities can do things like:

+ Apply logic to your workflows, such as filtering, if/else statements, and delays

+ Perform calculations on attributes and records

+ Create and modify records and attributes

+ Take action and send data in other applications via integrations

⁠For a complete library of each available action block, see our workflows [Activities library](aventisia/public-docs/Flow-Builder/activities-library.md).

To add an action activity, either click the + on the canvas. Once you have selected an activity, you can optionally add a description to explain what the activity will do under the activity name where it says **Add a description**.

### Inputs and variables
Once you have chosen an action, add Inputs where relevant to give the workflow more information about what you want it to do. Depending on the input, you may be able to type in a value manually, or click the {x} icon to use a variable.

Variables allow you to add entities or values from previous activities. Variables are dynamic in that each time the workflow runs, they can contain different data based on what is passing through the workflow on that run.

As one example, you may want to create a task with a due date, a certain number of days after a deal moved into a particular status. You would use an Adjust time block to designate the number of days you want to offset. Then in your Create task block, for the Due input you would use a variable to select the Adjusted timestamp from the previous step.

As another example, with a Filter activity you can specify conditions that have to be met for the workflow to continue. Once you’ve added a Filter activity, you need to set the Filter input. If you select the attribute “Country”, and set the criteria to “Canada”, your workflow would only continue if the company which triggered it was in Canada.

If an added variable is highlighted in yellow, this indicates that you can add a fallback to be used in any case where the workflow runs and the variable has no value. Click the variable to add the fallback value. A variable highlighted in blue has a fallback value set.

If you have made changes to your data, such as creating new attributes or objects, and that data isn’t reflected in a activity, click **Refresh block** at the bottom of the right-hand panel.

### Reorder, organize, and delete activities

#### Connect and disconnect activities
Click the arrow between two activities and press delete on your keyboard to remove the connection between them. You can click and drag the small circle on a activity to another activity to connect the two.

You will not be able to publish a workflow until all activities are complete and connected by blue lines. Grey lines indicate there is a activity that is incomplete or disconnected.

#### Organize activities
To move your activities into an orderly structure on your canvas, click Organize activities in the toolbar. This will reorganize your activities to reflect the order of the setup.

#### Delete activities
To remove an activity, select it and click Delete activity in the lower-right, or press delete on your keyboard. To bulk delete activities, you can select multiple activities by clicking, holding, and dragging your cursor over them, or by holding the shift key while clicking on individual activity.

### Add notes to the canvas

Optionally, add Notes to the workflow canvas to provide additional information about your workflow or link to documentation. Notes you add will be visible to everyone who can see the workflow, and each note shows the name of the team member who created the note.

To add a note, click the note icon in the toolbar at the bottom of the canvas, then hover over the place you want to put the note, and click to place it. You can change the color of the note from the color picker, and click and drag a note to reposition it.

If you use a template for a workflow, you will also see notes on the canvas with an explanation next to each step.

### Add a name and description

Give the workflow a name and description to indicate what it does. If the right-hand panel is focused on activities, click the ← button at the top. Click into the text box where it says New Workflow and type in a name for the workflow.

You can click into the text box under the workflow title where it says Add a description… to further explain what the workflow is set up to do.

## Publish a workflow

Once you have finished setting up your workflow, click Publish workflow at the top to set it live. If there are any unfinished configurations, the workflow won’t be published and you will see error indicators on the activities that still need to be completed. Once a workflow is published, it is live, meaning every time in the future the trigger conditions are met, the workflow will run.

If you make changes to a workflow that is published and live, your changes will not go into effect immediately. To publish changes you’ve made to a live workflow, click Publish changes at the top. Alternatively, if you want to discard changes you’ve made and revert the workflow to the published version, click Discard changes.

To pause a workflow, open it and click the toggle next to Live in the upper-right, then confirm you’d like to pause it. While a workflow is paused, no new runs will be triggered for that workflow, but if any runs are already in progress, they will continue on to completion.

Learn how to see runs for published workflows, resolve errors, and track credit usage in our [Troubleshooting workflows](aventisia/public-docs/Flow-Builder/troubleshooting-workflows.md) guide.