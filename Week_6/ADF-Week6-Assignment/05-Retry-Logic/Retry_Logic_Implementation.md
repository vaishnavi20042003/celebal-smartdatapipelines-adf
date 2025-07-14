# Retry Logic in ADF

To handle transient failures:
1. Open your activity (e.g., Copy)
2. Set the following under Retry:
   - Retry: `3`
   - Retry interval: `00:00:10` (10 seconds)
3. For critical failures, use "If Condition" or "Until" loop
4. Use alerts and logging for failures