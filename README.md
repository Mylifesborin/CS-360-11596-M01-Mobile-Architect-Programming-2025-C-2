# CS-360-11596-M01-Mobile-Architect-Programming-2025-C-2

This mobile app project is a weight-tracking tool that lets users log entries, view data, and receive SMS alerts for reaching goals. It focuses on clean design, user-friendly navigation, and strong backend integration with an SQLite database.

App Summary
The app was designed to help users track their daily weight changes and stay motivated by receiving SMS notifications when they reach goals. It focuses on simple, intuitive interactions and visual clarity.

Screens and Features
Login Screen: For user authentication and account creation.

Dashboard Screen: Displays weight entries in a readable grid layout.

SMS Notification Screen: Prompts for SMS permissions and sends alerts.

The design kept users in mind by making sure screens were simple, direct, and easy to navigate without extra clutter.

Coding Approach
I started by building the basic UI layouts and then coded the database connection and functionality step-by-step. I heavily used testing in the Android Emulator and kept my code modular, with each class serving a specific purpose.

Testing Process
Testing was done on the Android Emulator, covering login flows, database functions (create, read, update, delete), and SMS permissions. Testing helped catch minor UI bugs and permission handling issues early.

Overcoming Challenges
One major challenge was handling permissions smoothly so that if the user denied SMS permissions, the app would still function normally. I used condition checks and fallback messages to solve this.

Strengths Demonstrated
I am particularly proud of how the database and UI came together. The app consistently reads and updates user data, and the SMS feature makes it feel dynamic and responsive.

