QuickChat is a Java-based messaging system that allows users to:Register and log in securelySend, store, or disregard messagesGenerate message IDs and hashesStore messages using parallel arraysSearch, delete, and display message reports
The system demonstrates the use of:
- Object-Oriented Programming (OOP)
- Parallel arrays
- Input validation
- File handling
- Menu-driven console application
The system contains the following classes:
MainApp→ Main menu and program entry point
MessageTest→ Handles registration, login, and message creation
LoginForm→ Validates user credentials
Message→ Handles message creation, validation, and storage
MessageManager→ Stores messages using parallel arrays
MessageProcessor  Handles searching, reporting, and deletion
Users must log in using registered credentials
-Displays success or failure messages.Users can:
Send messages
Store messages Disregard messages
Each message:
- Gets a unique 10-digit ID
- Generates a message hash
- Can be stored in a JSON file
