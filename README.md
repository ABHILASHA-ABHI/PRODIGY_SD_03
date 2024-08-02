# PRODIGY_SD_03

Task 3 - Allow users to store and manage contact information.

### Project Overview

The Contact Manager program is a simple Java application designed to help users manage their contacts efficiently. It allows users to add, view, edit, and delete contact information, including names, phone numbers, and email addresses. The program stores this information in a file to ensure that contacts are saved between sessions, providing a persistent storage solution.

### Features

1. **Add Contact**:
    - Users can add new contacts by entering the contact's name, phone number, and email address.
    
2. **View Contacts**:
    - Users can view a list of all their contacts. Each contact is displayed with its name, phone number, and email address.
    
3. **Edit Contact**:
    - Users can edit the details of an existing contact by selecting the contact from the list and updating its information.
    
4. **Delete Contact**:
    - Users can delete a contact by selecting it from the list, removing it from the storage.
    
5. **Persistent Storage**:
    - Contacts are stored in a file (`contacts.txt`), ensuring that all contact information is preserved even after the program is closed and reopened.

### Results

The Contact Manager program provides a straightforward and efficient way to manage personal contact information. Users can easily add new contacts, view their contact list, update existing contacts, and delete contacts they no longer need. The use of persistent storage ensures that contact information is not lost between sessions, making the program reliable and practical for everyday use.

### Examples

#### Adding a Contact

1. The user selects the option to add a contact.
2. The user inputs the contact's name, phone number, and email address.
3. The program confirms that the contact has been added successfully.

Example:
```
Enter name: John Doe
Enter phone number: 123-456-7890
Enter email: johndoe@example.com
Contact added successfully.
```

#### Viewing Contacts

1. The user selects the option to view contacts.
2. The program displays a list of all contacts.

Example:
```
1. Name: John Doe, Phone: 123-456-7890, Email: johndoe@example.com
```

#### Editing a Contact

1. The user selects the option to edit a contact.
2. The user selects the contact to edit by its number.
3. The user updates the contact's information.
4. The program confirms that the contact has been updated successfully.

Example:
```
Enter the contact number to edit: 1
Enter new name (leave blank to keep current): John A. Doe
Enter new phone number (leave blank to keep current): 
Enter new email (leave blank to keep current): johnadoe@example.com
Contact updated successfully.
```

#### Deleting a Contact

1. The user selects the option to delete a contact.
2. The user selects the contact to delete by its number.
3. The program confirms that the contact has been deleted successfully.

Example:
```
Enter the contact number to delete: 1
Contact deleted successfully.
```

### Conclusion

The Contact Manager program is an effective tool for managing contact information. Its user-friendly interface and essential features make it easy to add, view, edit, and delete contacts. The use of persistent storage ensures that contact information is reliably saved between sessions. This simple yet functional program is suitable for anyone needing an organized way to manage their personal or professional contacts.
