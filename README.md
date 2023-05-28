# CRUD Test UI UX Design

Please read each note very carefully!

Create a UI/UX design for a simple CRUD application in your desired tool (Figma, Adobe XD or any toher) 

Application implements the below model:
```
Customer {
	Firstname
	Lastname
	Date Of Birth
	Phone Number
	Email
	Bank Account Number
}
```
## Practices and patterns (Must):

- Happy flows with prototype for following scenario:
	
	S1. User creates a customer from a list of zero entries and arrives to list of 1 customer
	
	S2. User update an existing customer and values are updated
	
	S3. User delete a customer from a list of one customer and arrives to an empty list of customers
	
- Validation fails flows within create or update

	V1. Duplicate error (by firstname, lastname and date-of-birth)
	
	V2. Duplicate error (by email)
	
	V3. Invalid Email, Mobile or Bank Account
	
- Create Web design for desktop view
- Create Mobile responsive design 
- [Gherkins scenario](https://www.cucumber.io/)

### Validations (Must)

- During Create and Edit; validate the phone number format that user can only provide a valid *mobile* number only.

- A Valid email and a valid bank account number must be checked before submitting the form.

- Customers must be unique in database: By `Firstname`, `Lastname` and `Date Of Birth`.

- Email must be unique.

### Delivery (Must)
- Please create a Figma design and share the link with us.
- Make sure your design have marking for Scenarios in S1, S2, S3 and V1, V2, V3
- To prevent any prejudice, do not write your personal name, email or phone in the test result.
