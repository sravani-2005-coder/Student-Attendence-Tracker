# Student-Attendence-Tracker
The Student Attendance Tracker is a dynamic, student-centric web application developed using Java. It allows students to track their attendance percentage by entering the number of classes conducted and the number of classes attended. The application stores attendance data persistently and updates it only when the user modifies the values.
This project focuses on simplicity, usability, and real-life relevance for students.

# Features
- Subject-wise attendance tracking
- Dynamic Calculation of attendance tracking
- Persistent storage of attendance data until updated
- Attendance Status Indicator:
    * Safe (≥ 75%)
    * Warning (65% – 74%)
    * Shortage (< 65%)
-Clean and user-friendly web interface


# Technologies
  - Frontend: HTML, CSS
  - Backend: Java (Servlets)
  - Server: Apache Tomcat
  - Storage: File Handling (Text File)

# How It Works
1. User enters subject name, total classes conducted, and classes attended.
2. Data is sent to the Java Servlet.
3. Servlet calculates attendance percentage and status.
4. Attendance data is stored persistently using file handling.
5. Stored data is displayed on the webpage until the user updates it.



# Project Structure
 
AttendanceTrackerWeb/

   |── src/com/attendance/AttendanceServlet.java

   |── WebContent/index.html

   |── WebContent/result.jsp

   |── WebContent/style.css

   |── WebContent/WEB-INF/web.xml

    
# How to Run the Project
- Install JDK and Apache Tomcat
- Import the project into Eclipse as a Dynamic Web Project
- Configure Tomcat server in Eclipse
- Run the project on the server
- Open the browser and access the application
