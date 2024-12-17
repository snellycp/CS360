# CS360
# Inventory Manager Mobile App

## Summary of Requirements and Goals
The goal of this project was to develop a functional mobile app that allows users to manage inventory efficiently. The app was designed to address user needs such as tracking inventory items, updating item quantities, and deleting items when they are no longer needed. It also includes a secure login system and SMS notifications to alert users when inventory levels are low. The app focuses on simplicity and accessibility for small businesses or individuals who need a straightforward inventory management solution.

## User-Centered Design: Screens and Features
To create a user-centered UI, I designed the following screens and features:
- **Login Screen**: Allows users to securely log in or create an account.  
- **Home Screen (Grid View)**: Displays inventory data in a grid format, making it easy for users to add, update, or delete items.  
- **SMS Notifications**: Sends alerts when certain conditions are met (e.g., low inventory).  

The UI was designed with simplicity in mind. Buttons, text fields, and error messages are clear and easy to navigate. I also ensured that users who denied SMS permissions could still access all other features. These designs were successful because they prioritize ease of use and a clean layout, reducing the learning curve for users.

## My Coding Approach
When coding the app, I broke the process into smaller, manageable steps. I started by implementing the **SQLite database** to store user accounts and inventory data. From there, I built the login system, followed by the CRUD (Create, Read, Update, Delete) functionality for managing inventory. Finally, I added SMS notification permissions and handling. I used modular code with clear naming conventions and inline comments to improve readability.

This step-by-step strategy helped me stay organized and tackle challenges efficiently. In the future, I can apply this approach to any development process, ensuring that I complete small pieces of functionality before moving on to the next step.

## Testing and Debugging Process
To ensure the app was functional, I used the **Android Emulator** to test each feature:
1. Tested the login functionality with both valid and invalid credentials.  
2. Verified the CRUD operations by adding, updating, and deleting items from the database.  
3. Tested the SMS feature with both granted and denied permissions.  

Testing is critical because it helps identify and fix issues early in the development process. For example, testing revealed that I needed to handle edge cases where users denied permissions or entered incorrect data.

## Overcoming Challenges
One challenge I faced was managing database persistence and ensuring the app continued to function without SMS permissions. I overcame this by adding clear error handling and fallback options so the app would still run smoothly. I also had to troubleshoot issues with the grid layout and database queries, which taught me the importance of methodical debugging and testing.

## My Successes
I am particularly proud of implementing the SQLite database and CRUD functionality. This component demonstrates my ability to connect a user-friendly UI with a persistent data structure, ensuring users can manage their inventory without losing data. Successfully integrating these features while keeping the app simple and functional highlights the knowledge and skills I’ve gained in mobile app development.

## Reflection
This project taught me how to combine user-centered design principles with strong coding practices to create a fully functional app. I learned how to use tools like **SQLite** for data management, handle permissions, and design clean, responsive UIs. Moving forward, I will build on this experience to create even more advanced mobile applications that solve real-world problems.

---
