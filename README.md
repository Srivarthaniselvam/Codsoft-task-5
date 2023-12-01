# Codsoft-task-5

# Contact Management System

# Program Explanation:

The Python program is a Contact Management System that allows users to manage a list of contacts. It consists of two classes: `Contact` and `ContactManager`.

# Classes:

1. **Contact Class:**
   - Attributes:
     - `name`: Name of the contact.
     - `phone_number`: Phone number of the contact.
     - `email`: Email address of the contact.
     - `address`: Address of the contact.

2. **ContactManager Class:**
   - Attributes:
     - `contacts`: List to store `Contact` objects.

   - Methods:
     - `add_contact`: Adds a new contact to the contact list.
     - `view_contacts`: Displays all contacts with their names and phone numbers.
     - `search_contacts`: Searches for contacts based on a query (name or phone number).
     - `update_contact`: Updates the information of an existing contact.
     - `delete_contact`: Deletes a contact from the contact list.

# Execution:

1. The program starts by creating an instance of the `ContactManager` class.

2. Users are presented with a menu to perform various actions:
   - Add a new contact.
   - View all contacts.
   - Search for contacts based on a name or phone number.
   - Update the information of an existing contact.
   - Delete a contact.
   - Exit the Contact Management System.

3. Users can interact with the system by choosing options from the menu.

4. Contacts are added, viewed, searched, updated, or deleted based on user input.

5. The program continues to run until the user chooses to exit.


# Features:

- Users can add, view, search, update, and delete contacts.
- Contacts are stored in a list and managed by the `ContactManager` class.
- The program provides a simple command-line interface for interaction.
- Error handling is implemented for invalid input or index.

# Sample Interaction:

Welcome to Contact Management System
1. Add Contact
2. View Contacts
3. Search Contacts
4. Update Contact
5. Delete Contact
Type 'exit' to Exit
Enter your choice: 1
Ex: 
Name: John Doe
Phone number: 123-456-7890
Email: john@example.com
Address: 123 Main Street
Contact added successfully!

...

Enter your choice: 2
1. John Doe - 123-456-7890
2. Jane Smith - 987-654-3210

...

Enter your choice: 4
1. John Doe - 123-456-7890
2. Jane Smith - 987-654-3210
Enter index of the contact to update: 1
New Name: Jane Doe
New Phone number: 555-555-5555
New Email: jane@example.com
New Address: 456 Oak Street
Contact updated successfully!

...

Enter your choice: exit
.............Closing Contact Management System............

# Sample video

https://github.com/Srivarthaniselvam/Codsoft-task-5/assets/151417502/eb05c649-9416-4154-a5e0-3a55c067192e

