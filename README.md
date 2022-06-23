# QA Testing Challenge
As the next step in the hiring process, we’d like you to complete a testing challenge.

## The Project

Your task is to create test cases for [Twala Sign (Staging Environment)](https://sign-staging.twala.io) regarding the following processes:

* Registration
* Login
* Document Signing

Basic Auth credentials will be sent to you on a separate email.

## Requirements

Test cases must have a few integral parts that should always be present in fields.

**Test Case ID**
Test cases should all bear unique IDs to represent them. In most cases, following a convention for this naming ID helps with organization, clarity, and understanding.

**Test Description**
This description should detail what unit, feature, or function is being tested or what is being verified.

**Assumptions and Pre-Conditions**
This entails any conditions to be met before test case execution. One example would be requiring a valid account for a login.

**Test Data**
This relates to the variables and their values in the test case. In the example of a login, it would be the username and password for the account.

**Steps to be Executed**
These should be easily repeatable steps as executed from the end user’s perspective. For instance, a test case for logging into an email server might include these steps:

Open email server web page.
Enter username.
Enter password.
Click “Enter” or “Login” button.
Step 6: Expected Result

This indicates the result expected after the test case step execution. Upon entering the right login information, the expected result would be a successful login.

**Actual Result and Post-Conditions**
As compared to the expected result, we can determine the status of the test case. In the case of the email login, the user would either be successfully logged in or not. The post-condition is what happens as a result of the step execution such as being redirected to the email inbox.

**Pass/Fail**
Determining the pass/fail status depends on how the expected result and the actual result compare to each other.
Same result = Pass
Different results = Fail

## Additional Information
* You are free to use any test case template or standard you are most familiar with.
* Have fun and be as creative as you like!
* Please feel free to reach out to ask any questions.

## How to Submit This Challenge
1. Work on your solution.
2. **If you are applying for a mid-level or senior-level role,** aside from creating the test cases, you are required to create automation tests on the same three processes. You can use any framework of your choice.
3. Send us an email at charlie.coroza@twala.io and CC paul.twala.io and stephanie.amurao@twala.io when you're ready to have it reviewed and schedule the tech interview.

## Timeframe

We would like the take home challenge to be completed within 5 days. If you need more time, please reach out to us. You will not be judged on how quickly you complete the challenge.
