# Wait for Mouse  

## Description

This feature allows users to wait for the mouse pointer to change to a specific state, such as becoming an arrow or another predefined cursor. It is useful for synchronizing automation workflows with user interactions or system events.  

![Wait for Mouse](wait-for-mouse.png)  

## Fields and Options  

### 1. **Wait for Mouse Pointer To** 🛈

- **Description**: Choose the condition to wait for:  
  - **Become**: Wait for the mouse pointer to change to a specific cursor type.  
- **Purpose**: This ensures the correct condition is monitored.  

### 2. **Mouse Pointer** 🛈

- **Description**: Select the cursor type to wait for:  
  - **Arrow**: Wait for the mouse pointer to become an arrow.  
  - **Other Cursors**: Wait for other predefined cursor types (if applicable).  
- **Purpose**: This ensures the desired cursor type is monitored.  

### 3. **Output** 🛈

- **Description**: Retrieve the result of the mouse pointer state change (if applicable).  
- **Purpose**: This provides feedback or results for further use in the workflow.  

### 4. **On Error**

- **Description**: Define how errors should be handled during execution (e.g., fail, retry, ignore).  
- **Purpose**: This ensures proper error handling in case the mouse pointer does not change as expected.

## Use Cases

- **User Interaction Synchronization**: Waiting for the mouse pointer to change before proceeding with automation tasks.  
- **System Event Monitoring**: Detecting changes in the mouse pointer state as part of system events.  
- **Workflow Coordination**: Ensuring the mouse pointer is in the correct state before performing actions.  

## Summary

The **Wait for Mouse** action provides a way to wait for the mouse pointer to change to a specific cursor type, such as an arrow. It ensures synchronization with user interactions or system events, making it ideal for automation workflows that depend on mouse pointer states.
