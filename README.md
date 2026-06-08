PROJECT TITLE:
   AI Powered Smart Chatbot System 

PROBLEM STATEMENT:
      Many organizations and websites face difficulties in providing instant responses to user queries all the time. Human support
systems require more time, cost, and manpower. Users expect quick and accurate answers, but traditional customer support cannot always
respond immediately. To overcome these issues, an AI Powered Smart Chatbot System is developed to provide automatic, intelligent, and 
real-time responses to users using Artificial Intelligence and Natural Language Processing (NLP).

PROJECT OBJECTIVES :
     * Advanced application - Artificial Intelligence , natural language processing
     * chatbot- answer question,provide information .
     * System - customer service ,education and healthcare .

FEATURES :
     * User-friendly interface 
     * AI-based response generation 
     * User query handling 
     * Time-saving communication
     * Easy information access

PROJECT STATUS :
       Objective  Definition  and Problem Statement Completed 

User :
     The user can interact with the AI chatbot ,ask queries and receive quick responses .
        * User Module 
        * User Panel
        * User Interaction 
        * User Features 

MODULE :
        * User Module 
        * Chatbot Module 
        * Database Module 
        * Authentication Module
        * Admin Module 
        * Interface Module 
      👤 User Module
            * User Registration
            * User Login
            * Ask Questions
            * View Chat Responses
            * Chat History
       🤖 Chatbot Module
            * AI Response Generation
            * NLP Processing
            * FAQ Handling
            * Smart Reply System
      🗄️ Database Module
            * Store User Data
            * Save Chat History
            * Manage Information
      🔐 Authentication Module
            * Secure Login
            * Password Validation
            * User Verification
      ⚙️ Admin Module
            * Manage Users
            * Update FAQ Data
            * Monitor System
     🌐 Interface Module
            * User-Friendly Design
            * Mobile/Desktop Support
            * Easy Navigation


USE CASE DIAGRAM :
     ACTORS :
           * Student 
           * Admin 
     Diagram : 
               # Use Case Diagram ///
             +----------------+
             |      USER      |
             +----------------+
                    |
      +-------------+-------------+
      |                           |
      v                           v
+---------------+         +---------------+
| Ask Question  |         | View Response |
+---------------+         +---------------+
      |
      v
+---------------+
| View FAQ      |
+---------------+
             +----------------+
             |     ADMIN      |
             +----------------+
                    |
      +-------------+-------------+
      |                           |
      v                           v
+---------------+         +---------------+
| Manage FAQ    |         | Manage Users  |
+---------------+         +---------------+
///
                        
DATABASE REQUIREMENTS :
      User Table
         * user_id
         * name
         * email
         * password
      Chat Table
         * chat_id
         * user_id
         * question
         * response
      Admin Table
         * admin_id
         * admin_name
         * password
     FAQ Table
         * faq_id
         * question
         * answer

Relationship :
    All tables are connected with the AI Powered Smart Chatbot System for user interaction, data storage, and response 
management using MySQL database.

Purpose :
    * Store user information
    * Store chatbot questions and responses
    * Manage admin and chatbot data
    * Maintain chat history in MySQL database.


ER DIAGRAM :
   # AI Powered Smart Chatbot System ///
+------------------+
|       USER       |
+------------------+
| user_id (PK)     |
| name             |
| email            |
| password         |
+------------------+
         |
         | 1
         |
         | M
+------------------+
|       CHAT       |
+------------------+
| chat_id (PK)     |
| user_id (FK)     |
| question         |
| response         |
| timestamp        |
+------------------+

+------------------+
|      ADMIN       |
+------------------+
| admin_id (PK)    |
| admin_name       |
| password         |
+------------------+
         |
         | Manages
         |
+------------------+
|       FAQ        |
+------------------+
| faq_id (PK)      |
| question         |
| answer           |
+------------------+ ///

Relationships :
      * One User can have many Chats
      * Chat Table is connected to User Table using user_id
      * Admin manages Users and Chatbot data
      * FAQ Table provides answers to the chatbot system
