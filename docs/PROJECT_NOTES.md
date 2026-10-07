# Subscription Analysis — Project Notes

## Analysis flow

Subscription records → date preparation → cancellation/active-duration calculations → signup cohorts → retention calculations → cohort comparison.

## Main fields

- `created_date`: subscription start date
- `canceled_date`: cancellation date when available
- `subscription_cost`: subscription price
- `subscription_interval`: subscription frequency
- `was_subscription_paid`: payment status
- `Active_months`: calculated active duration
- `is_5_months`: indicator for reaching the five-month point
- `retained_month`: retention indicator used in the workbook

## Interpretation

The large number of cancellations and relatively short calculated active duration point to an early-retention problem worth investigating. Cohort analysis helps identify whether that pattern is consistent across signup periods or concentrated in specific cohorts.
