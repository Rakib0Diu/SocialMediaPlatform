**Social Media Platform**

**Overview**
A lightweight, Java-based social media application that allows users to connect, 
share content, and interact with friends. This desktop-based platform is built using Java Swing for GUI, 
JDBC for database operations, and MySQL for persistent storage.

**Features**
 - User Registration and Login
 -  Create, Read, Update, Delete (CRUD) posts
 - Like / Dislike Posts
 - Comment on Posts
 - Add / Remove Friends
 - View Profiles and Friends Lists
 - Personalized Timeline from Friends' Posts

**Technologies Used**
- Java (JDK 23)
- Swing – GUI Development
- MySQL – Relational Database
- JDBC – Java Database Connectivity

**Project Structure**
src/
├── controller/    # Business logic and database handling
├── model/         # Data models (User, Post, Comment, etc.)
├── view/          # GUI interfaces and user interactions
└── Database.java  # Database connection configuration

**Getting Started**
1. Clone the Repository

   git clone https://github.com/yourusername/social-media-platform.git
   cd social-media-platform

2. Database Setup

   - Create a MySQL database named `socialmedia`.
   - Import the `schema.sql` file if available (or manually create tables).
   - Update the DB connection credentials in `Database.java`:
     String url = "jdbc:mysql://localhost:3306/socialmedia";
     String user = "your_username";
     String password = "your_password";

3. Run the Application

   - Open the project in IntelliJ/Eclipse or compile from terminal:
     javac -d bin src/**/*.java
     java -cp bin view.Main

**License**
MIT License

Copyright (c) 2025 [Md. Rakibul Islam]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
