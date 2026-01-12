## Debugging Philosophy

When a customer integration breaks, I start from what is observable.

1. Check if the request was sent in the Network tab
2. Verify the status code and response
3. Inspect the payload for missing or incorrect fields
4. Compare expected user actions with actual events sent
5. Decide whether the issue is client-side or server-side

This keeps debugging focused on facts instead of assumptions.
