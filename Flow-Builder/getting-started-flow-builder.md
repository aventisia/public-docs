# Getting started with Workflow Builder
Understand the basics and start building a workflow.

Flow Builder gives you complete control and flexibility to automate or build out virtually any process. Let's dive-in to understand the basics and get you started on building your first workflow.

## What are workflows?
Workflows are created in a visual workflow builder. You can design powerful, intricate, and time-saving systems that can be iterated on demand.

Whether you're looking to automate repetitive tasks, create a new process, or implement a comprehensive data integration system, workflows have you covered. From sales to marketing, to  operations, if you can think it, you can build it with our workflow builder.

## Components of a workflow
Understanding the components of a workflow will give you a clearer picture of how to create, run, and refine your processes:

+ **Canvas**: This is your primary workspace, where you'll piece together the different blocks of your workflow.

+ **Triggers**: This defines when your workflow starts and what data will be passed into it. It could be an event, like a new record being created, or maybe a specific date and time or any other custom trigger you define.

+ **Activity**: Think of these as individual actions or steps in your workflow. They can range from sending emails, updating attributes, to even more complex operations. [See all actions available in our Activities library](aventisia/public-docs/Flow-Builder/activities-library.md).

+ **Paths**: These are the connectors between activities, dictating the flow and sequence of actions within your workflow.

+ **Inputs**: Information or data that is required for a activity to run.

+ **Variables**: These are dynamic input values. For instance, the name of a new customer to use in subsequent steps. The value will be different for every run of the workflow.

+ **Runs**: Each execution of a workflow is called a 'run'. This can help you track individual instances of a workflow.

+ **Credits**: Consider these as the fuel for your workflow. The complexity of a workflow determines the number of credits consumed per run. More intricate workflows will require more credits.

+ **Templates**: Pre-built flows that you can utilize as starting points or inspiration.

+ **Notes**: Use notes to add more information about your workflow or link to documentation.

## Building a workflow
To build a workflow you can either start from scratch or use a template. Here's a step-by-step guide:

+ **Choose your starting point**:

  + Begin with a blank canvas for full customization.

  + Or, use one of the available templates to get a head start.


+ **Choose a trigger**: Determine when your workflow should kick off and what data get passed to each run.

+ **Add activities**: Hover over your trigger and click the + icon to add the next activity to your canvas. [See our Activity library](aventisia/public-docs/Flow-Builder/activities-library.md)

+ **Set inputs**: Define the data each activity needs to execute correctly in the configuration panel that pops-up when you choose an activity.

+ **Using variables**: Click the {x} icon to set dynamic values for your input. Use variables to add entities or values from previous activities. These will change based on what data is passing through the workflow on that run.

+ **Deleting activities**: Simply select the unwanted activity and hit backspace or click delete.

+ **Reordering activities**: Select the paths you’d like to remove and hit backspace. Click and drag the blue connecting node to another activity to create a new path.

+ **Publishing**: Click Publish to take your workflow out of the draft stage and allow it to be run when the trigger condition is met.

+ **Pausing**: Click the published toggle to pause a workflow and stop it running.

## Running a workflow
There are two ways to run a workflow:

1. **Automatically**: Set up conditions that when met cause the workflow to run automatically, without any manual intervention. Often this is on the creation or update of a piece of data.

2. **Manually**: Choose this when you need to execute a workflow on-demand. The Execute trigger on the top-left side on the screen will let you do this.

**⁠Congratulations!** You are now equipped with the foundational knowledge to harness the power of workflows. As you continue to explore and experiment, remember that workflows provides a canvas to bring your unique visions for automations and process designs to life. Happy building!

## Up next
Next, learn how to [create workflows](aventisia/public-docs/Flow-Builder/create-workflow.md)

