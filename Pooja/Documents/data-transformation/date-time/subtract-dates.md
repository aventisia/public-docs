# **Subtract Dates**

## **Description**

This operation calculates the difference between two dates and returns the result in different time units.

![alt text](../../assests/data-transformation/assests%20date-time/substract-dates.png)

## **Example Scenario**

Consider two dates:

- **Start Date:** `14-02-2025`
- **Subtract Date:** `08-01-2025`

We will calculate the time difference in **Seconds, Minutes, Hours, and Days**.

## **Calculation Example**

| Time Unit | Calculation |
|-----------|-------------|
| **Days** | `14-02-2025 - 08-01-2025 = 37 days` |
| **Hours** | `37 days × 24 hours = 888 hours` |
| **Minutes** | `888 hours × 60 minutes = 53,280 minutes` |
| **Seconds** | `53,280 minutes × 60 seconds = 3,196,800 seconds` |

## **Expected Output**

| Parameter         | Value |
|------------------|-------------|
| **TimeDifference (Days)** | `37 days` |
| **TimeDifference (Hours)** | `888 hours` |
| **TimeDifference (Minutes)** | `53,280 minutes` |
| **TimeDifference (Seconds)** | `3,196,800 seconds` |

## **Summary**

- Computes the **difference** between the two dates in **Seconds, Minutes, Hours, and Days**.
- Stores the result in the **TimeDifference** variable for further processing.
- Useful for calculating **event durations, deadlines, waiting times, or age differences**.

---
