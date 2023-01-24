# Standard requirements
To consider an backlog item "done", you must check the required items that apply:


- [ ] Test data is available for testing;
- [ ] Input data is validated and filtered;
- [ ] The code does not contain credentials;
- [ ] Passwords are validated based on the Programic password policy;
- [ ] Strictly confidential information is stored encrypted;
- [ ] The direct URL of strictly confidential information contains an authorization token which expires after a maximum of 24 hours;
- [ ] Significant user interaction is logged with reference to user and action;
- [ ] Exceptions are handled properly and not kept quiet unless really necessary.