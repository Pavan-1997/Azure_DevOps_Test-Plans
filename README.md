# Azure DevOps Test Plans  
   
## Manual and Exploratory Testing  

### Planned Manual Testing
Designated testers and test leads organize tests into plans and suites.

### User Acceptance Testing
User acceptance testers ensure the delivered product meets customer requirements.

### Exploratory Testing
Developers, testers, UX teams, and others explore the software without predefined test plans.

### Stakeholder Feedback
Testing by external stakeholders, like marketing and sales teams, using the browser-based extension Azure Test Feedback.

## Automated Testing   

### Integration with Azure Pipelines 
Azure Test Plans works seamlessly with Azure Pipelines for continuous integration and deployment (CI/CD).

### Result Capture and Review 
Pipeline tasks capture and publish test results, which can be reviewed using progress and pipeline reports.

## Traceability  

### Linking to User Stories/Requirements
Test cases and suites are linked to user stories, features, or requirements for end-to-end traceability.
It helps in tracking the quality of requirements.

## Reporting and Analysis  

### Configurable Tracking
Progress can be tracked through configurable charts and test-specific widgets on dashboards.

### Built-in Reports
Various built-in reports, such as Progress reports, pipeline test result reports, and Analytics services, aid in result tracking and progress monitoring.

# Running Tests

## Options
- Test Runner: for web and desktop
- Mark test passed or failed
- Capture the results

## Test and Feedback Extension  

Gather results in the form of screen recording and capture.

## Access level 
- You should have Basic + test plan access to execute, create, and publish test cases
- To execute the test cases using Test Runner, you should have at least basic access
- To run exploratory testing with the Feedback extension, you should have stakeholder access

  ![image](https://github.com/piyushsachdeva/AzureDevOps-Zero-to-Hero/assets/40286378/de46dd53-3d44-4208-93e1-2497ed422877)

### Test Plan  

- Group of test suites and test cases

### Test Suites  

- Group of test cases into separate test scenarios

### Test Cases  

- Actual steps to test an application

### Shared Steps  

- Steps that can be shared across test cases

![image](https://github.com/Pavan-1997/Azure_DevOps_Test-Plans/assets/32020205/49fdf875-5707-4d60-9b1a-090ebdc700cd)

---
## Steps to Perform

- Go to Azure DevOps Organization settings -> Billing -> Activate the Basic + Test Plans 

- Now go to User in same settings page click on the default user 

- Now click on more option on th default user -> Change Access level to Basic + Test Plans -> Click on Save

- Now go to the Test Plans in the Project created earlier -> Click on + New Test Plan -> Give it a nane -> Click on Create

- Now click on more options in the Test Plan created -> Click on New Suite -> Click on Requirement based suite

- Now go to Boards -> Work items -> New Work Item -> Epic -> Give a title name -> Save it

- Go to Step 5. change the Value of Work Item Type to Microsoft.EpicCategory -> Click on Run query -> You will see the epic created -> Click on Create suites

- Click on New Test Case -> Give a title name -> Give Steps -> Give also Expected results -> Click on Save and Close -> Similary add another Test Case

- By clicking on the Test Case we can assign to any person from the Testing team

- Go to Step 6. in the Boards you will be seeing test cases attached to the epic created

- Go to Test Plans select all the Test cases -> Click on Execute -> Click on Run for web application -> It gives you a Runner with more options
