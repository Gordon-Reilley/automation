# Lab 18 - Automation

## Project Name - Automation

### Author - Gordon P Reilley Jr

### Feature Tasks and Requirements:

- Given a document `potential-contacts`, find and collect all email addresses and phone numbers.
- Phone numbers may be in various formats.
  - (xxx) yyy-zzzz, yyy-zzzz, xxx-yyy-zzzz, etc.
  - phone numbers with missing area code should presume 206
  - phone numbers should be stored in xxx-yyy-zzzz format.
- Once emails and phone numbers are found they should be stored in two separate documents.
- The information should be sorted in ascending order.
- Duplicate entries are not allowed.

### Implementation Notes

- Find potential-contacts.txt and existing-contacts.txt in folder assets for today’s class in course repo.

#### User Acceptance Tests

The application must:

- The ‘phone_numbers.txt’ and ‘emails.txt’ files will be verified by an automated system. So make sure to match the naming/formatting requirements exactly.