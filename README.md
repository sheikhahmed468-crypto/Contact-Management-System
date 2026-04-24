Contact Management System (C++)

A robust terminal-based Contact Management System built using C++. This application utilizes a **Doubly Linked List** to manage contacts efficiently and supports persistent data storage through file handling.

Features
Add Contacts: Store names, phone numbers, and email addresses.
Search: Locate contacts quickly by searching for a Name or a Phone Number.
Edit: Update existing contact details without needing to delete them first.
Delete: Remove specific contacts individually or clear the entire directory.
Display: List all saved contacts in an organized, alphabetical view.
Persistent Storage: Automatically saves your contact list to a text file and reloads it every time the program runs.

 Data Structures & Logic

The project is built on core computer science principles:
Doubly Linked List**: Utilized for dynamic memory allocation and easy bidirectional navigation through the contact list.
Bubble Sort Logic**: Automatically sorts entries alphabetically to keep the directory organized.
File I/O**: Uses the `fstream` library to read from and write to `contactbook.txt`.

 How to Use

1. Admin Login: Upon starting, enter your name to access the system.
2. Add Contact (Press 1): Follow the prompts to enter the contact's name, phone number, and email.
3.  Edit Contact (Press 2): Search for a contact and update their information.
4.  Delete Contact (Press 3): Search for a specific contact and confirm its removal.
5.  Search (Press 4): Look up a contact by their name or phone number.
6.  Display (Press 5): View the entire contact list and the total contact count.
7.  Delete All (Press 6): Remove all entries from the contact book.

 Installation

1.  Clone this repository:
    ```bash
    git clone [https://github.com/yourusername/contact-management-system.git](https://github.com/yourusername/contact-management-system.git)
    ```
2.  Navigate to the directory:
    ```bash
    cd contact-management-system
    ```
3.  Compile the source code:
    ```bash
    g++ Contact_book.cpp -o ContactBook
    ```
4.  Run the executable:
    ```bash
    ./ContactBook
    ```

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
