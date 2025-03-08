# Criminal Case Management System

## Overview
The **Criminal Case Management System** is a Java-based application designed to manage and track criminal records, emergency contacts, and complaint statuses. It facilitates law enforcement by maintaining a structured database of criminals, allowing users to file complaints, and enabling police officers to update case statuses.

## Features
- **User Management**:
  - Separate portals for **police officers** and **public users**.
  - Public users can register and log in to file complaints.
  - Police officers can log in and manage criminal records.

- **Criminal Record Management**:
  - Add, delete, and update criminal records in the system.
  - Store criminal details including **name, CNIC, age, and crime details**.

- **Complaint Management**:
  - Public users can file complaints and track their status.
  - Police officers can **view, update, and resolve complaints**.

- **Emergency Contacts**:
  - Allows police officers to add and manage emergency contacts.
  - Public users can access emergency services.

- **Wanted List**:
  - Police officers can maintain a **wanted list**.
  - Criminals can be **added, removed, and updated** in the wanted list.

## Technologies Used
- **Programming Language**: Java (Swing for UI)
- **Database**: MySQL
- **Libraries**: JDBC for database connectivity

## File Structure
### **Source Files**
- `Main.java` - The core file containing the logic for user authentication, criminal records, complaints, and emergency contact management.
- `Main.form` - The GUI layout file for Swing components.

### **Database Tables**
The system uses a MySQL database with the following tables:
- `criminal` - Stores details of criminals.
- `complaint` - Stores complaints filed by public users.
- `emergencycontacts` - Stores emergency service contacts.
- `public_user` - Stores registered public users.
- `admin` - Stores police officer login credentials.

## Setup Instructions
1. Clone the repository or download the source code.
2. Set up MySQL and create a database named **`CriminalCase`**.
3. Import the provided database schema (`CriminalCase.sql`).
4. Update database connection details in `Main.java`.
5. Compile and run the project using a Java IDE (NetBeans or Eclipse).


If you encounter any issues or have questions, please feel free to reach out for assistance. Happy coding!
