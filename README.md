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

*Social Insurance Number (SIN)*: Use the following method to validate a SIN.

>Let's use this fictitious SIN to demonstrate: `130 692 544`
>
>Always multiply the SIN Number by this number: `121 212 121`
>
>(Multiply each digit of the top number by each digit of the bottom number)
>
>`130 692 544`
>
>`121 212 121`
>
>`160 394 584`
>
>If you get a 2 digit product, add the digits together. Notice here that 6 * 2 = 12, add 1 and 2 together and get 3.
>
>Then add all of these digits together: 1 + 6 + 0 + 3 + 9 + 4 + 5 + 8 + 4 = 40
>
>If the SIN is valid this sum will be evenly divisible by 10. This is a 'valid' SIN.

## Requirements

### Endpoints

- Create an employee
- Edit an employee
- Delete an employee
- Retrieve an employee
- Retrieve a list of employees
- Clock in an employee
- Clock out an employee
- Retrieve a list of timesheets

### Constraints

- Employees must have a unique, valid SIN
- An employee must be clocked in to be able to be clocked out

### Search Criteria

The list employees endpoint should support searching by first or last name. The timesheet list endpoint should support searching by employee ID and date range.

## Deliverables

Provide a Github repository with your code, data schema, unit and feature tests, and API documentation.  Include a README with any setup steps necessary for your interviewer to be able to run your project.  Be prepared to screen share a working copy of your API with your interviewer and review and explain the design decisions that you made.  

## Bonus Task

Create a frontend that uses your API.  This is not a requirement.
