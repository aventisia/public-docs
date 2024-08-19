# Activities library
### Understand the activities that power workflows.

This is your comprehensive guide to understanding and leveraging the activities that power workflows. Workflows gives you complete control and flexibility to build out virtually any  new process, automate existing processes and designing new products and solutions.

We’ll break down the various triggers and actions that you can use to automate your processes. At the heart of workflows are two primary components: trigger activities that initiate the workflow, and action activities that execute specific tasks.

## Trigger activities

Trigger activities are the starting point of any workflow. They determine when a specific workflow should be initiated and what data will be passed to subsequent activity. Here is an overview of the available triggers.

### Manual triggers
A manual trigger refers to an action initiated by a user to start an automated process or workflow. Unlike automated triggers that are activated by predefined conditions or system events, manual triggers require human intervention to initiate the process.

Manual triggers are often used in scenarios where:

+ Immediate human oversight is required to start the process.
+ Specific conditions need to be confirmed or verified before the automation begins.
+ The process is infrequently needed and doesn't warrant constant monitoring or automated triggers.

Manual triggers provide flexibility and control, allowing users to start processes as needed based on real-time requirements or operational needs.

### Scheduled triggers
Scheduled triggers are configurations that initiate automated execution of workflows at predetermined times or intervals. These triggers are designed to automate repetitive tasks based on a schedule, ensuring that processes run at specific times or under specific conditions without manual intervention.

Scheduled triggers are ideal for tasks that follow a regular pattern and do not require immediate or ad-hoc execution. They help maintain operational efficiency and ensure that routine processes are executed reliably and on time.

### Event-based triggers
Event-based triggers are mechanisms that initiate automated execution of workflows based on specific events or conditions rather than on a fixed schedule. These triggers respond to changes or occurrences in the system or environment, allowing to start a process when certain criteria are met.

Types of Event-Based Triggers:

#### File System Events:
+ **File Creation**: Trigger an automation when a new file is added to a specific directory.
+ **File Modification**: Start a process when an existing file is updated.
+ **File Deletion**: Initiate an action when a file is removed from the system.

#### Email Events:
+ **Email Received**: Trigger the automation when an email is received in a specified inbox or meeting certain criteria (e.g., subject line or sender).

#### Database Events:
+ **Record Changes**: Start a process when new records are inserted, or existing records are updated in a database.

#### User Actions:
+ **Form Submission**: Trigger an automation when a user submits a form or completes a specific action in an application.
+ **Button Click**: Start a process when a user clicks a specific button or link in a web application.

#### System Events:
+ **Application State Changes**: Trigger actions based on changes in the state of an application, such as a completed job or system alert.
+ **Error Detection**: Initiate an automation in response to specific error messages or failure conditions.

#### Message Queues:
+ **Queue Messages**: Trigger processes based on messages or events in a messaging queue or system.

#### Webhooks:
+ **External Webhooks**: Start an automation based on webhook calls from external systems or services.


## Action activities

Once a workflow is triggered, the action activities dictate what operations or processes should take place, and what data, if any, will be passed to subsequent activity. Here is an overview of the available action activities.

### Records actions

#### Create or update record
Checks for and updates a record if it already exists, or creates a new record if it does not exist yet. Provides the created or updated record’s data as variable inputs you can use in subsequent activities.

Inputs:

+ Object: Select the object of the records you want to create or update.

+ Matching attribute: Select a unique attribute, e.g., Domain for Companies, Email for People, or ID for Users or Workspaces. This will be used to check whether a record with a matching value already exists. If it does, the matching record will be updated. If it doesn't exist yet, a new record will be created.

+ Object attributes (optional): Optionally, designate the values that should be assigned to other object attributes. You can use variables to bring in dynamic values from previous workflow activity steps.

+ Overwrite multi-select values (optional): When unchecked (default setting), any multi-select attributes listed above will have the new values added to the existing values, rather than replacing the existing values. Check the box if you want to instead replace existing values for multi-select attributes.

#### Create record
Creates a new record. Keep in mind, if the record may already exist, you may want to use “Create or update record” instead. Provides the created record’s data as variables you can use in subsequent activities.

Inputs:

+ Object: Select the object of the records you want to create.

+ Object attributes (optional): Optionally, designate the values that should be assigned to other object attributes. You can use variables to bring in dynamic values from previous workflow activity steps.

#### Find records
Finds records that match filter conditions so that you can use those records in subsequent activities.

Inputs:

+ Object: Select the object of the records you want to find.

+ Condition: Set the filter(s) that will return the records you want to find. Learn how to set filter conditions or groups.

+ Limit: Designate the maximum number of records to find. Currently, there is a maximum limit of 100 records that you can find at once. Setting a limit is required.

Provides the following as variable inputs you can use in subsequent activities:

+ Matching Records: The records found that met the filter conditions.

+ Number of matches: The number of records found that met the filter conditions.

#### Update record
Updates an existing record’s attribute values.

Inputs:

+ Object: Select the object of the records you want to update.

+ Record: Select the record you want to update. Either manually select a specific record if you want to update the same record each time the workflow runs, or use a variable to select a record involved in a previous workflow activity that you want to update.

+ Attributes to update: Check the box next to each object attribute you want to update for the record. Then designate for those attributes what the value should update to. Manually select a value if it should always update to the same value each time the workflow runs, or use a variable to update to a dynamic value based on previous workflow activities each time the workflow runs.

### List actions

#### Add record to the list
Adds a record to a specific list. Provides the created list entry’s data as variable inputs for subsequent activities.

Inputs:

+ List: Select the list where the record should be added.

+ Record: Select the record you want to update. Either manually select a specific record if you want to add the same record to the list each time the workflow runs, or use a variable to select a record involved in a previous workflow activity that you want to add to the list.

+ List attributes (optional): Optionally, designate the values that should be assigned to the entry’s list attributes. You can use variables to bring in dynamic values from previous workflow activity steps.

#### Delete list entry
Deletes a specific entry from a list.

Inputs:

+ List: Select the list the entry is in that you want to delete.

+ Entry: Select the list entry you want to delete. Use a variable if you want to select an entry involved in a previous workflow activity that you want to delete. Note that you must select an entry specifically, not a record, for this activity to run successfully.

#### Find list entries
Finds list entries that match filter conditions so that you can use those entries in later activities.

Inputs:

+ List: Select the list containing the entries you want to find.

+ Condition: Set the filter(s) that will return the list entries you want to find. 

+ Limit: Designate the maximum number of entries to find. Currently, there is a maximum limit of 100 entries that you can find at once. Setting a limit is required.

Provides the following as variable inputs you can use in subsequent activities:

+ Matching list entries: The list entries found that met the filter conditions.

+ Number of matches: The number of list entries found that met the filter conditions.

#### Update list entry
Modifies a specific entry within a list.

Inputs:

+ List: Select the list the entry is in that you want to update.

+ Entry: Select the list entry you want to update. Use a variable if you want to select an entry involved in a previous workflow activity that you want to update. Note that you must select an entry specifically, not a record, for this activity to run successfully.

+ Attributes to update: Check the box next to any list attributes you want to update for the entry. Then designate for those attributes what the value should update to. Manually select a value if it should always update to the same value each time the workflow runs, or use a variable to update to a dynamic value based on previous workflow activities each time the workflow runs.

### Tasks actions

#### Complete task
Marks a specified task as complete.