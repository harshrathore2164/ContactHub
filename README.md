# Contacts-Management-App

This project is a contacts management application built with Node.js and Express. It provides APIs for managing contacts and users, allowing users to perform CRUD (Create, Read, Update, Delete) operations on contacts.

# Features
Create Contact: Users can add new contacts with details such as name, email, and phone number.
Read Contact: Users can view a list of all contacts or retrieve details of a specific contact.
Update Contact: Users can update the details of existing contacts.
Delete Contact: Users can delete contacts from the database.
User Authentication: Users can sign up and log in to manage their contacts securely.
Error Handling: Comprehensive error handling middleware to handle exceptions and errors gracefully.


Set up environment variables:
Create a .env file in the root directory and add the following variables:

```plaintext
PORT=5001
MONGODB_URI=<your_mongodb_connection_string>
ACCESS_TOKEN_SECERT=<your access token>
