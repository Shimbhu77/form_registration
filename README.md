## Registration Form Documentation

This documentation provides an overview of the registration form application, its fields, validations, and functionality. The form is developed using Node.js and MongoDB for data storage and retrieval.

### Fields

The registration form consists of the following fields:

1. First Name: Textbox field that accepts alphabets only.
2. Last Name: Textbox field that accepts alphabets only.
3. E-Mail: Textbox field that accepts a valid email format.
4. Country: Dropdown field that displays a list of countries stored in the database. It is a required field.
5. State: Dropdown field that displays a list of states stored in the database based on the selected country. It is a required field.
6. City: Dropdown field that displays a list of cities stored in the database based on the selected state. It is a required field.
7. Gender: Radio button field that allows the user to select their gender. It is a required field.
8. Date of Birth: Date field that allows the user to enter their date of birth. It must be older than 14 years.
9. Age: Text field that is calculated automatically based on the entered date of birth.
10. Save Button: Clicking this button will store the entered information in the database.

### Validation

The registration form applies the following validations:

- First Name: Accepts alphabets only.
- Last Name: Accepts alphabets only.
- E-Mail: Accepts a valid email format.
- Country: Must be selected from the list of countries stored in the database.
- State: Must be selected from the list of states stored in the database based on the selected country.
- City: Must be selected from the list of cities stored in the database based on the selected state.
- Gender: Must be selected (either male or female).
- Date of Birth: Must be older than 14 years.

### Functionality

Upon filling in the registration form and clicking the Save button, the entered information will be stored in the database. The data will be associated with a unique identifier and can be retrieved for future use.

To view the stored information, a separate page is available that displays the registered user's details. This page fetches the data from the database and presents it in a user-friendly format.

The application leverages Node.js as the server-side runtime environment and MongoDB as the database management system for data storage and retrieval.
### Contributor
[Shimbhu Kumawat](https://github.com/Shimbhu77)
