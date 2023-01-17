# CRUD Test UI UX Design

Please read each note very carefully!

Create a simple CRUD application the below model:
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

- Happy flow
- Validation fails flows
- [Gherkins scenario](https://www.cucumber.io/)
- Create Web design for desktop view
- Create Mobile responsive design 

### Validations (Must)

- During Create and Edit; validate the phone number to be a valid *mobile* number only.

- A Valid email and a valid bank account number must be checked before submitting the form.

- Customers must be unique in database: By `Firstname`, `Lastname` and `Date Of Birth`.

- Email must be unique.

### Delivery (Must)
- Please clone this repository in a new github repository in private mode and share with ID: `mason-chase` in private mode on github.com, make sure you do not erase my commits and then create a [pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) (code review).

## Nice to do:
- HTML/CSS output.
