# Hotel Booking Cancellation Analysis

## Overview
Exploratory data analysis on hotel booking demand to understand cancellation patterns and identify key drivers behind high cancellations in **City Hotel**.

## Key Findings
* **Hotel Type Comparison:** **City Hotel** has a higher cancellation rate (~41.73%) compared to **Resort Hotel** (~27.76%).
* **Lead Time Impact:** In **City Hotel**, canceled bookings have a noticeably higher average `lead_time` (~150.28 days) than non-canceled bookings (~80.70 days).
* **Deposit Type Pattern:** In **City Hotel**, **Non Refund** bookings show a very high cancellation rate (~99.81%) compared to **Refundable** (~70.00%) and **No Deposit** (~30.47%).

## Tools & Workflow
* Python (`pandas`, `matplotlib`, `seaborn`) in Jupyter Notebook
* Data cleaning, column standardization, and root-cause exploration
