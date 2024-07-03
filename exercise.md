# Ops Developer Exercise

The purpose of this exercise is to create a simple automated workflow that simulates onboarding of a new temporary project team member for a fictional company called Redhill Ltd.

## Goals
- Design and develop a form to accept user input
- Using the input data, populate a document template
- Email the document to the new user
- Save results to a database

## Concepts
- Project - A project has a fixed duration, with a start and end date
- Initiator - The person from Redhill Ltd initiating the onboarding of a new member
- New member - Person joining a project at Redhill Ltd

## Prelude

These resources may be helpful.

- Form handling and database tables - https://www.youtube.com/watch?v=GSXLPLzu1RI
- Sending email from Buildship - https://www.youtube.com/watch?v=soczzk2D5UE
- Free SMTP mail server - https://resend.com/

## M1 - Form Design

Use a SaaS form building tool to design an input form. For this exercise use Tally.io for the form. Pay special attention to the choice of form fields and whether or not they are mandatory.

## M2 - Offer Letter Template

We need to send an offer letter defining the terms of work agreement to the new member. Design an offer letter template in Google Docs that displays key information such as person's name, their email address, start date, end date, salary, etc. 

This template will be used in Milestone 3.

## M3 - Automation

Using Buildship.io, create an automation that will perform the following steps

1. Accept the form submission data
2. Populate the offer letter template with the submitted data
3. Email the offer letter to the new member

## R4 - Persisting Data

Using either the built-in Buildship database or Supabase.io, design a database table to save all of the key data.

Then alter your automation flow to save the sumbitted form data to this new database table.


## Bonus Points

Your solution will gain extra points if you include some or all of these items.

1. Use of Supabase for persistence
2. Add password protection to the form
3. Prevent sending multiple offers to the same email address

## Deadline

Your solution is due within 48 hours. Please follow submission instructions from the email.



