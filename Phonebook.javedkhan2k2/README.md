# Phonebook Console Application

## Project Description

This Application is Part of Console Application Project
at [CSharpAcademy](https://thecsharpacademy.com/project/15/drinks).

## The Application Requirements

* This is an application where you should record contacts
with their phone numbers.
* Users should be able to Add, Delete, Update and Read from a
database, using the console.
* You need to use Entity Framework, raw SQL isn't allowed.
* Your code should contain a base Contact class with AT LEAST
{Id INT, Name STRING, Email STRING and Phone Number(STRING)}
* You should validate e-mails and phone numbers and let the
user know what formats are expected
* You should use Code-First Approach, which means EF will
create the database schema for you.
* You should use SQL Server, not SQLite

## The Application Challenges

* Create a functionality that allows users to add the contact's e-mail
address and send an e-mail message from the app.
* Expand the app by creating categories of contacts (i.e. Family,
Friends, Work, etc).
* What if you want to send not only e-mails but SMS?

## How to run the Application

Microsoft [Secret Manager](https://learn.microsoft.com/en-us/aspnet/core/security/app-secrets?view=aspnetcore-8.0&tabs=windows) is used to store
and retrieve Database, Email and SMS ([Twilio](https://www.twilio.com/en-us) is used for testing purpose) credentials.
To run the application set the below secrets.

* DatabaseUserID
* DatabasePassword
* twilioAccountSid
* twilioAuthToken
* twilioNumber
* senderEmail
* senderPassword
* smtpHost (for outlook smtp.office365.com
and for google use smtp.gmail.com)
* smtpPort (in most cases it is 587)

If any of the above secrets are not set, the program will not run.

## Application Usage

Users can add/delete/edit/update contacts and contacts categories using the Main menu.
