# Address Book Project 📇

## Project Overview
This project is a **Command-Line Address Book** application built in C. It allows users to store, search, edit, and delete contact details such as names, phone numbers, and emails. The contact data is stored in a plain text file, making it easy to access and manage.

### Key Features:
- **Create a New Contact**: Add contacts with proper validation for name, phone number, and email.
- **List Contacts**: Display all contacts in a formatted way.
- **Search Contacts**: Find contacts by name or phone number.
- **Edit Contact**: Modify details of existing contacts.
- **Delete Contact**: Remove unwanted contacts from the address book.
- **Data Persistence**: All contacts are stored in a text file (`data.txt`).

### Technology Stack:
- **Language**: C
- **File Handling**: Plain text for contact storage.
- **Data Structures**: Struct for contact management.
  
### Input Validation:
- **Name**: Must contain alphabetic characters only.
- **Phone Number**: Must be a 10-digit number and not previously registered.
- **Email**: Must contain `@` and end with `.com` while ensuring no duplicates.

### How to Run the Project:
1. Clone the repository:  
   ```bash
   git clone https://github.com/AftabEnnus/AddressBook
