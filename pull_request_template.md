**Add silly text to see git flow in action**:

**Ticket:** http://www.exaple.com/task2/

**Checklist for the author of the Pull-Request**

- [ ]  The commit message follows guidelines

- [ ]   I tested the changes in this pull-request myself

- [ ]  I have performed a self-review of my own code and all items from Checklist for the Reviewers was passed

**Checklist for the Reviewers**

- [ ]  The code follows the style guidelines

- [ ] All the linters are passed

- [ ] The implementation corresponds to the use case which described in the task

- [ ] All the gems and libraries are used correctly

- [ ] Design patterns are used correctly

- [ ] All the new features have documentation and an additional information for README.md was provided

- [ ]  There is no redundant or commented code

- [ ] The code is readable and understandable

**The code follows these principles**

- [ ] DRY (Don't Repeat Yourself)

- [ ] KISS (Keep It Short and Simple)

- [ ] YAGNI (You Ain't Gonna Need It)

- [ ] SOLID (SRP, OCP, LSP, ISP, DIP)

**Database**

- The database structure corresponds to normal forms

- The migrations have DDL (Data Definition Language) and no DML (Data Manipulation Language)

**Automation Testing**

- There are Unit tests

- There are Acceptance or Request tests

- All the tests have test-cases for positive and negative cases

- Test Coverage is greater than 90% in general and 100% for the critical functionality

- All the tests are passed successfully

**Security**

- There is verification of the data entered by the user regarding to use case

- There is user authentication for the feature

- There is user authorization for the feature

- The passwords are encrypted

- The tokens extracted to the environment variables or encrypted file

- There are no SQL-injections

- The controllers use only allowed parameters
