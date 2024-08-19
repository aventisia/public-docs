# Troubleshooting workflows
Learn how to troubleshoot your workflows.

Troubleshooting plays a vital role in building and managing your workflows, whether you're aiming to understand why your workflow didn't run as anticipated or you simply want to track your credit usage.

## Accessing the run viewer

To view all runs for a live or paused workflow, follow these steps:
1. Navigate to the workflow you want to troubleshoot.

2. Click on the Runs button in the top left.

3. Browse the list of runs and click to view details about that specific run.

## Run viewer overview
The run viewer is divided into two main sections: a read-only view of the workflow on the left and a sidebar on the right that provides high-level statistics about the workflow and a list of all its runs.

By default, you will be presented with the latest run of the workflow. In the sidebar, you can see the status of each run, and hovering over each run will reveal more details such as the start and end times, as well as the number of credits consumed by the run.

Clicking on a run opens it on the canvas and allows you to review the executed activities. In the case that the run failed, you can also access details about what went wrong.

## Viewing a specific run
Once a specific run is selected, the view of your workflow displays the list of activities that were actually executed. For example if your workflow has an If / else activity, you’ll see which path was taken and the next steps that fired.

Clicking on any activity will replace the sidebar with a deeper view of the configuration. You’ll see the inputs that were set at the time of execution, as well as outputs for each activity. For instance, a Formula activity will display the calculated value, and a Create Record activity will show the created record as well as who and when it was created.

Any activity that fails to execute will be highlighted red, and clicking the failed activity will show a more detailed error message to help resolve the issue and fix your workflow. Failed activity executions do not count towards credit usage.

If your workflow contains a Loop activity, click the < and > buttons above the activity on the canvas to navigate between loop iterations.

If your workflow contains a Research record activity, you can see what steps the agent took to research each question and what the outputs were. If the agent was not able to find an answer to a question, the output for that question will be empty.

## Canceling a run

Runs that are still executing can be canceled by clicking the red Cancel run button in the top right of the toolbar. This will prevent any more activities in the run from being executed. Depending on the activity, the currently executing step may still complete, and if it does it will count towards credits usage. Steps after the currently executing step will not count towards credit usage.