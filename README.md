Objective

The primary objectives of this project are:
●	To design and implement a contact management system using C++.
●	To efficiently store, search, update, and delete contact information using a binary search tree.
●	To provide persistent storage using a text file to save and retrieve contact details.
●	To enable case-insensitive searches by name or phone number.
●	To ensure data integrity by validating inputs like phone numbers.
●	To provide a user-friendly interface for managing contacts.


Functional Requirements

The system should provide the following functionalities:
●	Add a Contact: Allows users to insert new contacts into the BST and save them in a text file.
●	Search Contacts:
o	By Name: Search for a contact by its name (case-insensitive).
o	By State: Search for contacts based on their state (case-insensitive).
●	Update a Contact: Enables updating the details of an existing contact (name, phone number, address, or state).
●	Delete a Contact: Provides functionality to delete a contact from both the BST and the text file.
●	Bulk Insert: Insert multiple contacts from a file.
●	Persistent Storage: All contact entries should be saved in a text file (phonebook.txt) and retrieved upon system startup.
●	Admin and User Interfaces: Separate interfaces for administrators and general users, with authentication for admin access.
