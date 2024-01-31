# Daft Automated Testing Assessment

## Overview

This repository contains submission for the Daft Automated Testing Assessment. The assessment aimed to specifically addressing recent keyword filtering issues on the Daft website for production regression testing.

## Technical Challenge

1. 
### Scenario

The end-to-end test scenario includes:

1. Opening the Daft homepage (www.daft.ie).
2. Searching for a Sale Ad in county Dublin.
3. Verifying that there are results for this location.
4. Applying the "garage" keyword filter.
5. Checking that there are results for that filter.
6. Opening one search result to ensure the filter was applied correctly (checking for the presence of the "garage" keyword in that advert).

My submission includes:
- Source code for automated tests.
- Setup instructions.

## Instructions for Running the Tests

To run the automated tests, follow these steps:

1. Clone Repository:
   - Clone this repository to your local machine using the command:
     git clone https://github.com/your-username/daft-automated-testing.git

3. Install Dependencies under Pom.xml:
    -Selenium Java
    - TestNg

4. **Run Tests:**
   - Execute the automated tests under FilterTestClass or from Testing Suite

DistilledAssessmentFramework/src/test/java/daftIeTests/FilterTest.java

5. I have followed page object Model thus all the locators and Methods are under
DistilledAssessmentFramework/src/main/java/daft/pageobjects
 
## Technology Stack

- Testing Framework: [ Selenium, TestNG ]
- Programming Language: [Java ]

## Notes
Feel free to reach out if you have any questions or need further clarification.
