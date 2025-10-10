# DTC Middleware vv0.4.0

**Release Date:** 2025-10-10T14:33:03Z

## Release Notes

Functionality:
- If a quote request to CA AutoFinance is not correctly received, the code checks if the message "One or more validation errors occurred." is given. If so, the application will set the proposal on "Extra handeling" instead of "Systeem error"

Fix:
- Logs for HTTP requests and responses will filter out calls to receive access tokens

---

For access to the application, please contact your DTC representative.
