# **Get Current Date and Time**

## **Description**

This operation retrieves the current date and time based on the specified time zone settings.

![alt text](../../assests/data-transformation/assests%20date-time/get-current-date-and-time.png)

## **Input Parameters**

| Parameter            | Value                  | Description |
|----------------------|------------------------|-------------|
| **Retrieve**        | `Current date and time` | Retrieves the current timestamp. |
| **Time zone**       | `System time zone`      | Uses the system's time zone for retrieval. |
| **Country/Region**  | `Europe/Bucharest`      | Specifies the country/region for date and time calculation. |
| **Windows Time Zone** | `(UTC) Coordinated Universal Time` | The corresponding Windows time zone. |
| **Input Type**      | `Offset`                | Defines how the time zone offset is handled. |
| **Offset**          | *(User-defined value)*  | Adjusts the time offset based on user input. |

## **Output**

- The retrieved current date and time based on the specified time zone.
- The output can be used for logging, scheduling, or timestamping events.

## **Example Use Case**

- **Scenario:** A user in Bucharest wants to log the current timestamp in their system.
- **Configuration:**
  - Time zone: `Europe/Bucharest`
  - Offset: `+2 hours` (if applicable)
- **Result:** The system fetches and stores the exact time according to Bucharest's local settings.

---
