# Master AI Engineering - Python Project - ContactEase Solutions


ContactEase Solutions is a command-line application for managing contacts, developed in Python using Object-Oriented Programming principles. It provides a simple and intuitive interface to add, view, edit, delete, and search contacts, as well as the ability to save and load data to JSON files.

## Project Requirements

- **OOP in Python**: Implementation of OOP concepts for a solid and scalable structure.
- **Data Structure**: Creation of an efficient data structure to store contacts.
- **User Interface**: Development of an interactive and easy-to-use command-line interface.
- **Features**:
    - Add a Contact
    - View Contacts
    - Edit a Contact
    - Delete a Contact
    - Search for a Contact by first or last name
    - Save and Load contacts to a file

## How to Use

1.  **Run the Code**: Execute all the cells in the notebook in order.
2.  **Main Menu**: Once the program starts, a main menu will be displayed with the following options:
    -   `1. Add new Contacts`: Add new contacts to the address book.
    -   `2. Show all the Contacts`: Display all contacts in the address book.
    -   `3. Edit a Contact`: Modify the details of an existing contact.
    -   `4. Delete a Contact`: Remove a contact from the address book.
    -   `5. Search a Contact using first name and/or last name`: Search for contacts by first and/or last name.
    -   `6. Save the Contacts in a file`: Save the address book to a JSON file.
    -   `7. Load Contacts from a file`: Load an address book from a JSON file.
    -   `8. Clear output`: Clear the console output.
    -   `0. EXIT`: Exit the application.
3.  **Interaction**: Follow the on-screen instructions to interact with the application.

## Code Structure

The code is organized into the following classes and functions:

-   **`Contact` Class**: Represents a single contact with first name, last name, phone number, and email. Includes methods to access and modify contact data.
-   **`Address_book` Class**: Manages a collection of `Contact` objects. Includes methods to add, search, edit, and delete contacts, as well as saving and loading the address book.
-   **Main Functionalities**: Separate functions (`main_add_contact`, `main_show_all_contacts`, etc.) implement the different main menu options, interacting with the user and utilizing the `Address_book` class.
-   **`Main`**: The main section of the code that initializes the address book and handles the interactive menu loop.

## Data Validation

The `_validate_contact_data` function is used to validate the data entered for a contact, ensuring that the first and last names are not empty, the phone number is 10 digits, and the email, if provided, has a valid format.

## Saving and Loading

The saving and loading functionalities use the JSON format to store contact data, allowing the address book to be persisted between different sessions.
