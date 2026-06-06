## Swag Labs Manual Testing Project

## Overview

This repository contains a comprehensive manual testing project conducted on the Swag Labs web application. The project covers test planning, test design, test execution, defect management, and reporting activities using TestRail, Jira, Zephyr Scale, and GitHub.

The objective of this project was to validate core application functionality, identify defects, assess system quality, and demonstrate practical software testing skills throughout the Software Testing Life Cycle (STLC).

## Application Under Test

Application: Swag Labs

Type: E-Commerce Web Application

Testing Approach: Manual Functional Testing

## Project Objectives

* Validate critical business workflows
* Verify application functionality against expected behavior
* Identify functional, usability, and data consistency defects
* Execute positive and negative test scenarios
* Document and track defects through Jira
* Generate test execution and coverage reports
* Maintain complete test documentation and traceability

## Scope of Testing

### Login Module

* Valid login verification
* Invalid login validation
* Error message verification
* User specific behavior testing
* Login performance observation

### Inventory Module

* Product display validation
* Product information verification
* Product image validation
* Product details verification
* Product sorting functionality

### Cart Module

* Add to Cart functionality
* Remove from Cart functionality
* Cart badge updates
* Multiple product handling

### Checkout Module

* Checkout information validation
* Input field validation
* Negative test scenarios
* Checkout overview verification
* Order completion workflow

## Test Management Tools

| Tool         | Purpose                                        |
| ------------ | ---------------------------------------------- |
| TestRail     | Test Case Management and Execution             |
| Jira         | Defect Tracking                                |
| Zephyr Scale | Test Management and Traceability               |
| GitHub       | Project Documentation and Portfolio Management |

## Test Deliverables

The following testing artifacts were created during the project:

* Test Scenarios
* Detailed Test Cases
* Test Execution Reports
* Test Summary Reports
* Defect Reports
* Traceability Reports

## Test Execution Summary

### Inventory Module

| Metric           | Result |
| ---------------- | ------ |
| Total Test Cases | 20     |
| Passed           | 17     |
| Failed           | 3      |
| Pass Rate        | 85%    |

### Checkout Module

| Metric           | Result |
| ---------------- | ------ |
| Total Test Cases | 27     |
| Passed           | 20     |
| Failed           | 7      |
| Pass Rate        | 74%    |

### Login Module

Login scenarios were executed using Zephyr Scale and linked with associated defects through Jira issue tracking. Traceability between test cases and defects was maintained throughout execution.

## Defect Summary

A total of six defects were identified, documented, and reported during testing.

| Defect ID | Summary                                                   | Priority |
| --------- | --------------------------------------------------------- | -------- |
| MP-1      | Mismatched Product Images Displayed                       | High     |
| MP-2      | Slow Response Time After Successful Login                 | Low      |
| MP-3      | Incorrect Product Image Displayed for Sauce Labs Backpack | Medium   |
| MP-4      | Product Description Does Not Match Displayed Product      | Medium   |
| MP-5      | User Automatically Logged Out During Navigation           | Medium   |
| MP-6      | Product Name Does Not Match Displayed Product Image       | Medium   |

## Key Findings

### Inventory Defects

* Product information inconsistencies were identified.
* Product images did not always correspond with displayed products.
* Product details pages contained mismatched content.

### Checkout Defects

* Input validation controls were insufficient.
* First Name and Last Name fields accepted invalid numeric and special character input.
* Postal Code field accepted invalid alphabetic and special character values.

### Session Management Defects

* Unexpected user logout occurred during navigation after inactivity.
* Error messages were displayed when accessing the Cart page after session expiration.

## Repository Structure

### Test-Cases

Exported test cases from TestRail and Zephyr Scale.

### Test-Scenarios

High level testing scenarios created during test design.

### Test-Summary-Reports

Execution summaries, coverage reports, and testing metrics.

### Bug-Reports

Detailed Jira defect reports with reproduction steps, expected results, actual results, severity, priority, and evidence.

### Projects

Project specific documentation and supporting testing artifacts.

## Skills Demonstrated

* Manual Testing
* Functional Testing
* Exploratory Testing
* Negative Testing
* Regression Testing
* Defect Reporting
* Test Case Design
* Test Execution
* Test Documentation
* Test Management
* Jira
* TestRail
* Zephyr Scale
* GitHub

## Conclusion

The Swag Labs testing project successfully validated key application workflows across Login, Inventory, Cart, and Checkout modules. Test execution identified multiple functional and data consistency defects, demonstrating the effectiveness of structured manual testing practices and defect management processes.


Author: Muskan Habib

Role: Manual QA Engineer

Tools: TestRail, Jira, Zephyr Scale, GitHub
