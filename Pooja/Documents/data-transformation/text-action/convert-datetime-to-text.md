# 🕒 Convert Datetime to Text

## Description

The **"Convert datetime to text"** action allows you to **transform a datetime value** (such as `04/10/2025 14:30`) into a **formatted string** representation like `"April 10, 2025"` or `"10/04/2025"` depending on the format you choose. This is helpful when presenting dates/times to users or passing them to systems that expect date information in string format.

![Convert datetim to text](../../assests/data-transformation/assests%20text-action/covert-date-time-to-text.png)
---

## Fields Breakdown

| Field | Description |
|-------|-------------|
| **Datetime to convert** | The input field for your **datetime variable** (e.g., `CurrentDateTime`). This could be a static datetime, a flow variable, or an output from another action. |
| **Format to use** | You can select one of the formatting modes:<br>- `Standard`: Use predefined common date formats.<br>- `Custom`: Allows you to specify a custom format pattern (like `yyyy-MM-dd`). |
| **Standard Format** | Appears only if **Standard** format is selected. You can pick from options such as:<br>**Short Date**: `MM/dd/yyyy`<br>**Long Date**: `dddd, MMMM dd, yyyy`<br>**Short Time**: `hh:mm tt`<br>**Long Time**: `hh:mm:ss tt`<br>**Full DateTime**: Combines full date and time. |
| **Output** | This is where the **converted string** will be stored. You can rename this variable from the default if needed for better readability in your flow. |

---

## When and Why to Use It

- **Display purposes**: Format dates before showing them in messages, logs, UI elements.
- **Interoperability**: Convert datetime to string when integrating with systems that don’t accept datetime objects.
- **Reporting**: Export formatted dates in reports or emails.

---

## Example

Let’s say your flow generates the current datetime as `2025-04-10 14:30:00`. Using this action:

- **Format to use**: `Standard`
- **Standard Format**: `Long Date`
- **Output**: `"Thursday, April 10, 2025"`

---

## Note

- If your target system needs a specific format like `yyyy-MM-dd`, use the **Custom** format option.
- Ensure the datetime variable is not null or empty to avoid runtime errors.
- Combine with **Convert text to datetime** action to reverse the process if needed.
