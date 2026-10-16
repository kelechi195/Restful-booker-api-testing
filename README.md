# Restful Booker API Testing Project

## Project Overview

This project demonstrates API testing of the Restful Booker practice API using Postman and Newman.

## Objectives

- Validate API endpoints and HTTP response status codes.
- Test positive and negative scenarios.
- Verify response data and field validation.
- Document unexpected API behaviour.
- Generate HTML test execution reports.

## Tools and Technologies

- Postman
- Newman
- Newman HTML Extra Reporter
- JavaScript
- Microsoft Excel
- GitHub
- Visual Studio Code

## Test Scope

### POST /booking

- Valid booking creation
- Missing and empty fields
- Invalid data types
- Boundary and negative values

### GET /booking

- Retrieve booking details by ID
- Verify returned booking fields
- Test invalid booking IDs
- Retrieve the booking list

## Test Execution and Reporting

Newman executes the Postman collection from the command line. HTML reports document request execution, assertions, and test outcomes.

### Live Newman HTML Report

[**View the Newman Test Execution Dashboard**](https://kelechi195.github.io/Restful-booker-api-testing/reports/restful-booker-report.html)

The report presents the Postman collection execution results, request details, assertion outcomes, and response information.

### Test Results and Analysis

The execution report is used to review passed and failed assertions and identify unexpected API behaviour.

- **Passed assertions:** Validations that met their expected results.
- **Failed assertions:** Validations where actual behaviour differed from the expected result.
- **Execution errors:** Request or script execution problems, which should be distinguished from failed assertions.

Failed assertions are reviewed against documented expectations and test assumptions before being classified as defects. Because formal business requirements are not provided for this practice API, findings are assessed carefully before being confirmed as bugs.

### Test Documentation

[**View the Excel Test Documentation**](<Test case documentation/Booking Api Project.xlsx>)

The workbook contains test cases, bug reports, and the Requirements Traceability Matrix (RTM).

## Disclaimer

This portfolio project uses the publicly accessible Restful Booker practice API. Findings are evaluated against documented expectations and assumptions.

## Author

**Kelechi Solomon Ukwajiuba**

QA Engineer | Manual API Testing | Postman | Newman | Test Documentation

- **LinkedIn:** [Kelechi Solomon Ukwajiuba](https://linkedin.com/in/kelechi-ukwajiuba-56aba528a/)
- **GitHub:** [kelechi195](https://github.com/kelechi195)
