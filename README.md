Women Safety Alert System
Overview
The Women Safety Alert System is a Java-based project designed to enhance women's safety by allowing users to store emergency contacts and trigger an SOS alert. In an emergency, the system sends notifications to predefined contacts.

Features

Store & Manage Contacts – Users can add, view, and delete emergency contacts.

SOS Alert System – Sends emergency alerts to stored contacts.

Multithreading – Ensures smooth operation without blocking the main application.

Data Persistence – Stores contacts securely in a file.

Error Handling – Prevents common issues like deleting non-existing contacts or triggering alerts without contacts.

Technologies Used

Programming Language: Java
Concepts: OOP (Encapsulation, Inheritance, Polymorphism, Abstraction), Multithreading, File Handling, Exception Handling
Data Storage: File handling using Java I/O

Installation & Setup
Clone the Repository
git clone https://github.com/your-username/women-safety-alert-system.git
cd women-safety-alert-system
Compile the Code
javac WomenSafetyAlertSystem.java
Run the Application
java WomenSafetyAlertSystem
How It Works
Add Emergency Contacts – Users can store emergency contacts.
View Contacts – Display the list of stored contacts.
Trigger an SOS Alert – Sends an emergency notification to contacts.
Handle Edge Cases – Prevents errors like missing contacts.

Code Structure
📂 women-safety-alert-system  
 ├── 📄 WomenSafetyAlertSystem.java  # Main class  
 ├── 📄 Contact.java                 # Contact class (Encapsulation)  
 ├── 📄 Alert.java                   # Abstract class for alerts (Abstraction & Polymorphism)  
 ├── 📄 SOSAlert.java                 # Extends Alert to send notifications  
 ├── 📄 DataHandler.java              # Manages file operations  
 ├── 📄 README.md                     # Documentation  
 
Future Enhancements
GPS Integration – Share live location in alerts.
SMS & WhatsApp Alerts – Notify contacts via messaging services.
Mobile App Interface – Build a user-friendly app.
Demo & Usage
Run the application.
Add emergency contacts.
Trigger an SOS alert.
View the logs of sent alerts.
