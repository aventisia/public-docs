# Open Terminal Session

## Description

This screenshot demonstrates an interface for opening a terminal session using **Micro Focus Reflection** as the provider. The interface allows users to configure settings such as the HLLAPI DLL path, session name, host type, and host address.

![alt text](../../assests/app-integrations/assests%20terminal%20emulation/open-termianl-session.png)

---

## Configuration

### Provider

- **Option**: Select the provider (e.g., Micro Focus Reflection).

### HLLAPI DLL Path

- **Field**: Specify the installation path for the HLLAPI DLL.

- **Option**: Use an existing profile or create a new one.

### Session Name

- **Field**: Enter a name for the terminal session.

### Host Type

- **Option**: Select the host type (e.g., IBM 3270).

### Profile

- **Field**: Specify the profile to use for the session.

### Host Address

- **Field**: Enter the address of the host to connect to.

### Port

- **Field**: Specify the port number for the connection.

---

## Output

- **TerminalSession**: The specific terminal session object created for use with later terminal emulation commands.

---

## Example: Configuring a Terminal Session

### Scenario

You need to connect to a mainframe system using a terminal emulator. The mainframe has the following details:

- **Host Address**: `mainframe.example.com`
- **Port**: `23` (commonly used for Telnet connections)

---

### Steps to Configure

1. **Open the Terminal Session Configuration Interface**:
   - Navigate to the terminal emulator tool (e.g., Micro Focus Reflection).

2. **Enter Host Address**:
   - In the **Host Address** field, enter:

    ```plaintext
     mainframe.example.com
    ```

3. **Specify Port**:
   - In the **Port** field, enter:

    ```plaintext
     23
    ```

4. **Output**:
   - After submitting the configuration, the system generates a `TerminalSession` object. This object can be used in subsequent commands, such as:
     - Sending commands to the mainframe.
     - Retrieving data from the mainframe.

---

### Example Code (Pseudocode)

```plaintext
# Configure Terminal Session
TerminalSession session = new TerminalSession(
    HostAddress: "mainframe.example.com",
    Port: 23
);

# Use the TerminalSession object for emulation commands
session.SendCommand("LOGIN USER123");
session.SendCommand("RUN REPORT1");
