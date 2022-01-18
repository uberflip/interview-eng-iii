# Uberflip Engineer III Technical Challenge

## Abstract: Create a REST API for a basic employee time clock

Your task is to create a RESTful API for a time clock system.  All required endpoints are listed below. You may use your choice of language or framework to accomplish this task.

## Definitions

*Employee*: An employee record should contain at minimum the following list of fields.  Additional fields may be included as desired.  All field data should be validated according to type.

- First name
- Last name
- Email address
- Hourly wage rate
- Social Insurance Number

*Timesheet*: A timesheet is a pair of clock in/out timestamps with the number of hours and gross pay calculated.  

*Social Insurance Number (SIN)*: Use this document as a guide for implementing your own validation for SINs. [https://www.straightlineinternational.com/docs/vaildating_canadian_sin.pdf](https://www.straightlineinternational.com/docs/vaildating_canadian_sin.pdf)

## Requirements

### Endpoints

- Create an employee
- Edit an employee
- Delete an employee
- Retrieve an employee
- Retrieve a list of employees
- Clock in an employee
- Clock out an employee
- Retrieve a timesheet
- Retrieve a list of timesheets

### Constraints

- Employees must have a unique, valid SIN

## Deliverables

Provide a Github repository with your code, database schema and/or migrations, tests, and API documentation.  Include any setup steps necessary for your interviewer to be able to run your project.  Be prepared to review and explain any design decisions that you made.

## Bonus Task

Create a frontend that uses your API.  This is not a requirement.
