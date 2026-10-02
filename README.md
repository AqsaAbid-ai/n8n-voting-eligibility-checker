# Voting Eligibility Checker (n8n)

An n8n workflow that takes an age from a form and tells the user whether they are eligible to vote.

## How it works
1. A form collects the user's age
2. The workflow checks the age and shows one of four results:
   - Below 0: invalid age
   - Below 18: not eligible
   - 18 to 119: eligible
   - 120 or more: beyond the normal human age range

## How to use
1. Download the `.json` file from this repository
2. In n8n, open the workflow menu and choose Import
3. Select the file and run the workflow

## Limitations
- It only checks the age entered, not any identity or citizenship details
- The form only works while n8n is running

## Next steps
- Save each submission to a Google Sheet
