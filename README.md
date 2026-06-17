PROJECT TITLE:
   AI Powered Smart System Assistant Chatbot System 

PROBLEM STATEMENT:
         Students often face difficulties in accessing academic information such as class schedules, course details, attendance records, examination information, and study materials. Traditional methods of obtaining this information can be time-consuming and may require manual assistance from faculty or administrative staff. Therefore, there is a need for an AI-powered student assistant chatbot that can provide instant, accurate, and personalized academic support, improving accessibility, communication, and efficiency for students.

PROJECT OBJECTIVES :
   1. To develop an AI-powered chatbot that provides instant responses to student queries.
   2. To provide easy access to academic information such as courses, timetables, attendance, and examination details.
   3. To assist students in accessing study materials and important announcements.
   4. To reduce the time and effort required to obtain academic information.
   5. To improve communication between students and the educational institution.
   6. To provide a user-friendly and efficient platform for academic support.
   7. To enhance the overall learning experience through smart and automated assistance.

FEATURES :
   1. Student Login and Authentication – Secure access for students and administrators.
   2. AI-Based Chatbot Assistance – Provides instant responses to student queries.
   3. Academic Information Access – Displays course details, syllabus, and timetable information.
   4. Attendance Information – Allows students to check attendance records.
   5. Examination Details – Provides exam schedules, results, and related updates.
   6. Study Material Access – Shares notes, documents, and learning resources.
   7. Announcements and Notifications – Delivers important academic updates and notices.
   8. 24/7 Availability – Offers support anytime and anywhere.
   9. User-Friendly Interface – Easy-to-use chatbot interface for students.
   10. Admin Management – Enables administrators to update and manage academic information.
PROJECT STATUS :
      Current Status: In Progress
Completed Tasks:

- Project title finalized.
- Problem statement prepared.
- Project objectives defined.
- Requirements gathered and analyzed.
- GitHub repository created and configured.
- Basic project documentation prepared.

Ongoing Tasks:

- System design and architecture planning.
- Database design and ER diagram creation.
- User interface design.
- Chatbot development and integration.

Upcoming Tasks:

- System implementation.
- Testing and debugging.
- Performance evaluation.
- Final documentation and project deployment.
User :
1. Student

- Access academic information.
- Check timetable, attendance, and exam details.
- View study materials and announcements.
- Interact with the chatbot for instant assistance.

2. Administrator (Admin)

- Manage student information.
- Update academic details, notices, and study materials.
- Monitor chatbot activities and system usage.
- Maintain and manage the overall system.
MODULE :
       1. User Authentication Module
         - Student and Admin login.
         - Secure user authentication.
       2. Student Management Module
         - Manage student profiles and details.
         - View academic information.
       3. Chatbot Interaction Module
         - AI-powered chatbot for answering student queries.
         - Provides instant academic assistance.
       4. Academic Information Module
         - Manage course details, timetable, and syllabus.
         - Display academic information to students.
       5. Attendance Management Module
         - Store and view attendance records.
         - Allow students to check attendance status.
       6. Study Materials Module
         - Upload and access notes, documents, and learning resources.
       7. Notification and Announcement Module
         - Share important notices, updates, and announcements.
       8. Admin Management Module
         - Manage users, academic data, and system settings.
         - Monitor and maintain the chatbot system.
USE CASE DIAGRAM :
     ACTORS :
           * Student 
           * Admin 
    
DATABASE REQUIREMENTS :
      The system requires a database to store and manage student information, chatbot interactions, academic details, and user accounts. The database ensures secure storage, quick retrieval, and efficient management of data.
      Main Tables
         * Users
         * User ID
         * Name
         * Email
         * Password
         * Role (Student/Admin)
                   Students
                        * Student ID
                        * Name
                        * Department
                        * Year
                        * Semester
                        * Contact Information
                   Chat History
                        * Chat ID
                        * User ID
                        * Query
                        * Response
                        * Date & Time
                   Academic Information
                        * Academic ID
                        * Student ID
                        * Subject Name
                        * Marks
                        * Attendance
                        * Semester
                  Announcements
                        * Announcement ID
                        * Title
                        * Description
                        * Date
                  Admin
                        * Admin ID
                        * Username
                        * Password
    Database Software
           Database: MySQL
           Language: SQL
    Purpose
         The database stores student records, academic details, chatbot conversations, announcements, and user login information, enabling the chatbot to provide accurate and quick responses to students.
         
      

   
ER DIAGRAM :
      * Student  
      * Admin
      * Chatbot System 
Relationships :
      * Student has Chat History
      * Student has Academic Information
      * Admin creates Announcements
      * Chatbot stores Chat History
      * Chatbot retrieves Academic Information

Database Schema Creation
         Database schema creation is the process of designing the structure of a database by defining tables, attributes, primary keys, foreign keys, and relationships between entities. It helps organize data efficiently and ensures data integrity, consistency, and security.
         In the AI Powered Smart Student Assistant Chatbot System, the database schema is designed to store and manage student information, user accounts, academic records, chatbot conversations, announcements, and administrator details. Each table represents a specific entity, and relationships are established using primary and foreign keys.
         The schema enables the chatbot to retrieve student-related information quickly, store chat history, manage academic data, and provide accurate responses to users. A well-designed database schema improves system performance, reduces data redundancy, and supports efficient data management.

UI Wireframe Design
     UI Wireframe Design is a visual blueprint of the application that shows the layout, structure, and placement of interface elements before actual development. It helps designers and developers understand how users will interact with the system.
     For the AI Powered Smart Student Assistant Chatbot System, the wireframe includes the following screens:
           1. Login Page 
           2. Student Dashboard 
           3. Chatbot Interface
           4. Admin Dashboard 

Login UI Design :
     The Login UI allows students and administrators to securely access the system using their username/email and password. It provides authentication and ensures that only authorized users can access the chatbot and academic information.
     
Student Dashboard UI Design :
      The Student Dashboard serves as the main interface for students. It provides quick access to academic information, attendance, marks, announcements, and the AI chatbot for answering student queries.
Admin Dashboard UI Design :
      The Admin Dashboard enables administrators to manage student records, academic information, announcements, and chatbot activities. It provides centralized control over the entire system.

Navigation & Form Design :
   Navigation Design:
         Navigation design helps users move easily between different pages and features of a system. It includes menus, buttons, links, and navigation bars that provide a clear path for accessing information and completing tasks.
   Form Design:
         Form design focuses on collecting user information efficiently through input fields, dropdowns, checkboxes, and buttons. A good form design is simple, user-friendly, and easy to complete with clear labels and validation messages.
   Purpose:
         To improve user experience by making the system easy to navigate and ensuring accurate data entry.
Design Review :
      Design Review is the process of evaluating the user interface (UI) and user experience (UX) of a system to ensure it is user-friendly, visually appealing, and meets project requirements.
      Purpose:
         Identify design issues and usability problems.
         Check consistency in layout, colors, fonts, and navigation.
         Improve user experience and accessibility.
         Gather feedback for further improvements.
      Outcome: 
         A refined and effective design that is easy for users to understand and use.
Frontend Environment Setup :
         Frontend Environment Setup is the process of preparing the tools and technologies required for frontend development.
         Activities:
            Install a code editor (e.g., Visual Studio Code).
            Install runtime and package manager (e.g., Node.js and npm).
            Create the frontend project structure.
            Install required libraries and dependencies.
            Configure folders, files, and development settings.
            Test the setup by running the application locally.
         Purpose: 
            To create a development environment where the user interface can be designed, developed, and tested efficiently.

Login Page Development :
         Login Page Development involves creating a secure and user-friendly page that allows users to access the system using their credentials.
         Activities:
               Design the login interface.
               Create input fields for username/email and password.
               Add a login button and validation messages.
               Implement password visibility option (optional).
               Connect the login form with the backend database for authentication.
               Test the login functionality and error handling.
         Purpose:
               To provide secure access to the system and ensure that only authorized users can log in and use the application.

Registration Page Development :
         Registration Page Development involves creating a page where new users can create an account by providing their details.
         Activities:
               Design the registration form.
               Add input fields such as Name, Email, Password, and Confirm Password.
               Implement form validation for required fields.
               Display error and success messages.
               Store user information securely in the database.
               Test the registration process and data submission.
         Purpose: 
               To allow new users to create an account and access the system's features securely.

Dashboard Development :
      Dashboard Development involves creating the main interface that users see after logging into the system. It provides quick access to important features, information, and activities.
      Activities:
            Design the dashboard layout.
            Add navigation menus and shortcuts.
            Display user information and key data.
            Integrate chatbot access and system features.
            Ensure responsive design for different devices.
            Test dashboard functionality and usability.
      Purpose: 
            To provide users with a centralized and user-friendly interface for accessing all major functions of the system efficiently.

CRUD Form Development :
         CRUD Form Development involves creating forms that allow users to Create, Read, Update, and Delete data within the system.
         Activities:
               Design data entry forms.
               Implement Create functionality to add new records.
               Implement Read functionality to view records.
               Implement Update functionality to edit existing records.
               Implement Delete functionality to remove records.
               Add form validation and error handling.
               Connect forms with the database.
         Purpose: 
               To enable users to manage system data efficiently and maintain accurate records within the application.
