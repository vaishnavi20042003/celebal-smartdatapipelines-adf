# Trigger on Last Saturday of Every Month

Steps:
1. Use Custom Schedule Expression:
   ```
   0 0 10 ? * 7L *
   ```
   This means: 10 AM on the last Saturday of each month.
2. Link the trigger to a pipeline in ADF