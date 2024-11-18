# Standard requirements
To consider an backlog item "done", you must check the required items that apply:

- [ ] Test data is available for testing;
- [ ] Input data is validated and filtered;
- [ ] The code does not contain credentials;
- [ ] Passwords are validated based on the Programic password policy;
- [ ] Strictly confidential information is stored encrypted;
- [ ] The direct URL of strictly confidential information contains an authorization token which expires after a maximum of 24 hours;
- [ ] Exceptions are handled properly and not kept quiet unless really necessary.
- [ ] Logs are generated based on emergency, alert, critical, error, warning, notice, info, and debug levels, according to the [RFC 5424 specification](https://datatracker.ietf.org/doc/html/rfc5424).