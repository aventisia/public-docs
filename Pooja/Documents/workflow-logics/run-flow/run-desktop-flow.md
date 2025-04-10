# Run Desktop Flow

## Description

The **Run Desktop Flow** dialog is used to invoke another desktop flow from the current automation. This is useful for modularizing tasks and reusing flows across different processes.

![Run Desktop Flow UI](../../assests/workflow-logics/assests%20run-flow/run-desktop-flow.png)

## Fields and Options

### **1. Desktop Flow** (Required)

- A dropdown where you select an existing desktop flow to run.
- This is a mandatory field and must be selected before saving.

### **2. Wait for Flow to Complete**

- **Description:**

  If enabled, the parent flow pauses until the invoked desktop flow finishes execution. Once completed, any output variables from the child flow are made available to the current flow.

- **Behavior:**
  - **Enabled:** Flow runs sequentially. Output variables from the invoked flow can be used.
  - **Disabled:** Flow runs concurrently. Output variables are ignored.

- **Toggle Switch:**  
  On by default (enabled), represented by a blue switch.

## Use Cases

- **Sequential task execution:** When one flow depends on another’s results.
- **Parallel processing:** Speed up workflows by executing flows simultaneously when output isn't required.
- **Flow reusability:** Modularizing large automations into smaller, manageable units.
