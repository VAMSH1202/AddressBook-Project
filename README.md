# Address Book Application 📒

## Overview

The Address Book Application is a console-based program built in C that allows users to store, manage, and retrieve personal contact information in an organized manner. Users can add, update, delete, and search for contacts based on various criteria such as name, phone number, and address. The application ensures data persistence through CSV file storage, so contacts are retained between sessions.

## Features

- **Add Contacts** — Add new contacts with name, phone number, and address
- **Search Contacts** — Search contacts by name, phone number, or address
- **Update Contacts** — Modify existing contact details
- **Delete Contacts** — Remove a contact from the address book
- **Data Persistence** — Contacts saved in a file, retained between sessions
- **Display Contacts** — View all saved contacts in a user-friendly format
- **Sort Contacts** — Sort contacts by name or phone number

## Project Structure

The project is organized into the following key files:

- `address_book.c` — Contains main functionality for managing contacts (add, update, delete, search)
- `contact.h` — Header file defining the `Contact` structure and function prototypes
- `file_operations.c` — Functions for saving and loading contacts to/from a file
- `Makefile` — Build instructions for compiling the application

## Data Structures

The application uses the following structure to store contact information:

### `Contact` Structure
```c
typedef struct {
    char name[100];    // Contact's name
    char phone[15];    // Contact's phone number
    char address[200]; // Contact's physical address
} Contact;
```

## How to Compile & Run
```bash
make
./address_book
```

## What I Learned

- File handling in C using fopen, fread, fwrite, fclose
- Struct-based data organization and CRUD operations
- Modular programming with header files
- Edge case handling and data integrity in C

## Author

**Miryala Vamshi**  
Embedded Systems Engineer  
📧 vamshimiryala2@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/vamshi-miryala-a7b71a347)
