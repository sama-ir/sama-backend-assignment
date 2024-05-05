
# Table of Contents

1.  [Objective](#orga8390c8)
2.  [Scenario](#org6a5ba99)
3.  [Requirements](#org8b0b9d4)
    1.  [Model/Database Design](#orgd1d68cd)
    2.  [Testing](#orgce79eaf)
    3.  [Database](#orge02bec1)
    4.  [Source Version Control](#orgaa89909)
4.  [Submission](#orgcf38993)
5.  [Note](#orgf6107a1)
6.  [Evaluation Criteria](#org4676356)

# Assignment: Sama Django Backend Assignment Project

## Objective

Demonstrate your proficiency in Django/Python backend development by building a simplified wallet system. The system should allow users to create wallets, transfer funds between wallets, and view transaction history, all through REST APIs, while showcasing efficient database design, adherence to SOLID principles, and good code quality.


## Scenario

You are tasked with developing a simple wallet system for a financial application. The system should enable users to perform basic operations through REST API calls, such as:

-   Creating wallets
-   Transferring funds between wallets
-   Viewing transaction history


## Requirements

### Model/Database Design

Design required django models ensuring:

-   A User can have multiple wallets
-   Daily transfers between different users are limited (Total count and total value of transfers)

Implement the following transaction types:

-   Deposits
-   Withdrawals
-   Refunds

Include (at least) the following transaction statuses:

-   Pending
-   Completed
-   Failed


### Testing

Write at least 3 tests that demonstrate your understanding of a test framework and testing principles.


### Database

Use SQLite as the database for this project.


### Source Version Control

Use git for version control throughout the development process.


## Submission

Share a link to your git repository containing the project, along with a very brief README.md file that includes:

-   Setup instructions
-   Any additional information you deem necessary


## Note

This assignment should take no more than a day to complete (hopefully less). If you&rsquo;re facing issues or need more time, feel free to contact us to discuss.

Focus on demonstrating your proficiency in Django/Python backend development, efficient database design, code quality, design patterns, SOLID principles, tests, and git usage.

Make assumptions where necessary and document them in your code or README.


## Evaluation Criteria

The code will be evaluated based on:

-   Completeness of the implementation
-   Adherence to best practices
-   Code quality
-   Efficiency of the solution in meeting the specified requirements

