# Maybell Fashion – Manual Testing Test Plan

## 1. Project Overview

This project involves independent manual functional testing of the Maybell Fashion e-commerce website.

The purpose of this project is to evaluate the website's functionality, navigation, product browsing, filtering, stock availability, shopping cart operations, and pricing calculations from an end-user perspective.

**Website:** https://maybell.in/

**Project Type:** Independent QA Portfolio Project

**Testing Type:** Manual Functional Testing

## 2. Testing Objectives

The objectives of this testing project are:

- Verify the functionality of main menu and footer navigation.
- Validate product listing and product detail page functionality.
- Verify product filtering and sorting behaviour.
- Check product stock availability and quantity restrictions.
- Validate shopping cart operations, including adding and removing products.
- Verify cart quantity updates and price calculations.
- Validate discount code application and removal.
- Check whether the final payable amount is calculated correctly.
- Identify and document functional defects.
- Evaluate the overall shopping experience through end-to-end testing.

## 3. Scope of Testing

### 3.1 In-Scope Features

The following features are included in the testing scope.

#### A. Navigation

- Main menu navigation
- Footer navigation
- Navigation between website sections
- Navigation from product listing pages to product detail pages
- Browser Back and Forward navigation
- Navigation throughout the shopping journey

#### B. Product Listing Page (PLP)

- Product listing and display
- Product selection
- Product filtering
- Filter selection and result updates
- Sorting functionality
- Behaviour when multiple filters are applied
- Clearing and resetting filters

#### C. Product Detail Page (PDP)

- Product information display
- Product image and variant display
- Color and size selection
- Product-related interactions
- Product availability information
- Navigation between product listing and detail pages

#### D. Product Stock and Availability

- Verification of product stock availability
- In-stock and out-of-stock product behaviour
- Quantity selection based on available stock
- Stock-related messages displayed to the user
- Validation when requested quantity exceeds available stock
- Stock availability behaviour during cart operations

#### E. Shopping Cart

- Adding products to the cart
- Removing products from the cart
- Updating product quantities
- Cart item count updates
- Cart item and quantity validation
- Cart behaviour when stock limits are reached
- Cart total calculation

#### F. Pricing and Discount Functionality

- Product price verification
- Subtotal calculation
- Discount amount calculation
- Applying discount codes
- Removing discount codes
- Valid and invalid discount code behaviour, where applicable
- Price updates after quantity changes
- Price updates after adding or removing products
- Final payable amount verification

#### G. General Functional Testing

- End-to-end shopping journey
- Basic UI behaviour
- Error messages and user feedback
- Functional consistency across related pages
- Identification of unexpected behaviour

### 3.2 Out-of-Scope Features

The following areas are excluded from this project:

- Actual payment processing
- Backend and database testing
- API testing
- Automation testing
- Performance and load testing
- Security and penetration testing
- Testing across multiple browsers and operating systems beyond the selected environment

## 4. Test Approach

Testing is performed manually using the following approaches:

**Functional Testing:** Verify that website features behave according to their intended functionality.

**Exploratory Testing:** Explore website features and user journeys to identify unexpected behaviour.

**Positive Testing:** Validate functionality using valid inputs and expected user actions.

**Negative Testing:** Validate behaviour using invalid or unexpected inputs where applicable.

**Boundary Value Testing:** Check quantity limits and relevant input boundaries.

**End-to-End Testing:** Validate complete shopping journeys across multiple website sections.

**Regression Testing:** Recheck affected functionality after a defect is fixed, where applicable.

## 5. Test Environment

| Environment | Details |
|---|---|
| Website | https://maybell.in/ |
| Testing Type | Manual Testing |
| Operating System | Windows 11 |
| Browser | Google Chrome |
| Testing Tool | Web Browser |
| Documentation Tool | GitHub Markdown |
| Evidence | Screenshots and screen recordings, where applicable |

## 6. Test Deliverables

The following deliverables will be maintained in this GitHub portfolio:

- Test Plan
- Test Scenarios
- Test Cases
- Test Execution Report
- Defect Reports
- Test Evidence
- Test Summary Report

## 7. Entry Criteria

Testing can begin when:

- The website is accessible.
- The required pages and features are available.
- The testing environment is ready.
- The testing scope has been defined.

## 8. Exit Criteria

Testing will be considered complete when:

- All planned test cases have been executed.
- Test execution results have been documented.
- Identified defects have been recorded.
- Relevant test evidence has been collected.
- A test summary report has been prepared.

## 9. Defect Reporting

Unexpected behaviour identified during testing will be documented with the following details:

- Defect ID
- Defect Title
- Environment
- Preconditions
- Steps to Reproduce
- Expected Result
- Actual Result
- Severity
- Priority
- Supporting Evidence

Only reproducible and sufficiently verified defects will be included in the final defect report.

## 10. Project Disclaimer

This is an independent manual QA portfolio project conducted for learning and professional demonstration purposes.

The testing does not represent an official QA engagement or endorsement by Maybell Fashion.
