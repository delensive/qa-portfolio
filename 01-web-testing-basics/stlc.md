# STLC Notes

## 1. What is STLC?

STLC means Software Testing Life Cycle.
It describes the testing process from requirement analysis to test closure.

## 2. Main STLC stages

1. Requirement Analysis
2. Test Planning
3. Test Case Design
4. Test Environment Setup
5. Test Execution
6. Bug Reporting
7. Retesting
8. Regression Testing
9. Test Closure

## 3. Requirement Analysis

At this stage QA reviews requirements and looks for unclear logic, missing scenarios and possible risks.

Example:
If the requirement says "User can log in", QA should ask what happens with invalid password, empty fields, blocked account and successful logout.

## 4. Test Planning

At this stage QA decides what should be tested, what should not be tested now, what risks exist and what resources are needed.

## 5. Test Case Design

At this stage QA creates checklists, test cases and test data.

Example:
For login functionality, QA can prepare checks for valid login, invalid password, empty username, empty password and logout.

## 6. Test Environment Setup

At this stage QA makes sure that the test environment is ready.

Examples:

* test website is available
* test account exists
* required test data is prepared
* correct build/version is deployed

## 7. Test Execution

At this stage QA runs test cases or checklists and compares actual results with expected results.

## 8. Bug Reporting

If actual result is different from expected result, QA creates a bug report.

A good bug report should include:

* title
* environment
* steps to reproduce
* expected result
* actual result
* severity
* attachments if needed

## 9. Retesting

Retesting means checking whether a specific bug was fixed.

Example:
If the bug was about an incorrect error message for empty password, QA repeats the same steps after the fix.

## 10. Regression Testing

Regression testing means checking that existing functionality still works after changes.

Example:
After fixing login validation, QA should also check successful login, invalid login and logout.

## 11. Test Closure

At this stage QA summarizes testing results.

The summary may include:

* what was tested
* how many bugs were found
* which bugs were fixed
* which risks remain
* whether the feature is ready for release

## 12. Retesting vs Regression Testing

Retesting checks a specific fixed bug.
Regression testing checks that other existing functionality was not broken by the changes.

## My understanding

SDLC describes how the product is developed.  
STLC describes how the testing process is organized.

QA should participate in requirement analysis because many problems can be found before development starts. QA checks requirements for unclear logic, missing scenarios, contradictions and risks.

A checklist is a short list of checks.  
A test case is a detailed test scenario with steps, test data and expected result.

Retesting means checking whether a specific fixed bug was actually fixed.  
Regression testing means checking that existing functionality was not broken after changes.

After a login form bug fix, I would check:
- successful login with valid credentials
- login with empty username
- login with empty password
- login with both fields empty
- invalid username and invalid password
- very long input values
- special characters
- logout
- password recovery, if it is required
