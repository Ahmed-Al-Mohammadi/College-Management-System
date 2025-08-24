# College Management System

## Description

This project is a desktop-based College Management System developed in Java, likely using Swing for the graphical user interface, and designed to manage various aspects of a college or university. It provides functionalities for managing students, instructors, courses, departments, and enrollments. The system interacts with a SQL Server database to store and retrieve data.

## Features

-   **Student Management**: Add, view, update, and delete student records.
-   **Instructor Management**: Manage instructor information, including their assigned departments.
-   **Course Management**: Handle course details, such as course names, codes, and associated departments.
-   **Department Management**: Organize and manage different academic departments within the college.
-   **Enrollment Management**: Facilitate student enrollment in courses and track their academic progress.
-   **User Interface**: Intuitive graphical user interface for easy interaction.
-   **Database Integration**: Persistent data storage using SQL Server.

## Project Structure

```
College-Management-System/
├── Database/                       # Contains database-related files (ERD, SQL scripts, Schema)
│   ├── ERD.pdf                     # Entity-Relationship Diagram of the database
│   ├── SQLQuery1.sql               # SQL script for database creation or queries
│   └── Schema.pdf                  # Database schema documentation
├── modern_tech_collage/            # Main Java project directory
│   ├── modern_tech_collage/        # Source code and build artifacts
│   │   ├── build/                  # Compiled Java classes
│   │   ├── dist/                   # Distribution files (JAR, libraries)
│   │   ├── nbproject/              # NetBeans project configuration
│   │   └── src/                    # Java source code files
│   │       └── modern_tech_collage/# Java packages and classes
│   │           ├── Course.java
│   │           ├── Department.java
│   │           ├── Enrollment.java
│   │           ├── Instructor.java
│   │           ├── Main_Page.java
│   │           ├── Modern_tech_collage.java # Main entry point
│   │           ├── Student.java
│   │           └── Welcome_Page.java
├── README.md                       # This README file
└── uml/                            # UML diagrams for system design
    ├── UML Activity.pdf
    ├── UML use case.pdf
    ├── case scenario 2.pdf
    ├── case senario .pdf
    └── class diagram.pdf
```

## Getting Started

### Prerequisites

-   Java Development Kit (JDK) 8 or higher.
-   SQL Server (or compatible database) for data storage.
-   NetBeans IDE (recommended for opening and running the project).

### Installation

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/Ahmed-Al-Mohammadi/College-Management-System.git
    cd College-Management-System
    ```

2.  **Database Setup**:
    -   Locate the `Database` folder within the cloned repository.
    -   Use the `SQLQuery1.sql` file to create the necessary database and tables in your SQL Server instance.
    -   Ensure the database connection details in the Java source code (if any, typically in a configuration file or directly in the code) are updated to match your SQL Server setup.

3.  **Open Project in NetBeans (Recommended)**:
    -   Open NetBeans IDE.
    -   Go to `File` -> `Open Project...`.
    -   Navigate to the `College-Management-System/modern_tech_collage` directory and select the project.

### Running the Application

1.  **From NetBeans IDE**:
    -   Once the project is opened in NetBeans, you can run it directly by clicking the `Run Project` button (green play icon) or by pressing `F6`.

2.  **From Command Line (after building)**:
    -   Navigate to the `College-Management-System/modern_tech_collage/modern_tech_collage/dist` directory.
    -   Run the JAR file:
        ```bash
        java -jar modern_tech_collage.jar
        ```

## Usage

Upon launching the application, you will be presented with a welcome page. Navigate through the system using the provided graphical interface to manage college data. The main functionalities include adding, viewing, updating, and deleting records for students, instructors, courses, and departments.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, please:

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/YourFeature`).
3.  Make your changes.
4.  Commit your changes (`git commit -m 'Add some feature'`).
5.  Push to the branch (`git push origin feature/YourFeature`).
6.  Open a Pull Request.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details.

## Contact

For any questions or suggestions, please open an issue in the GitHub repository.
