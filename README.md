# Infotute: Revolutionizing Educational Management

## Overview

**Infotute** is an advanced platform aimed at revolutionizing the management of educational institutions. It provides a comprehensive solution for handling various academic activities, ensuring smooth communication between students, trainers, and administrators. Built with robust technologies like Java, MySQL, and NetBeans, Infotute is designed to be scalable and user-friendly.

## Features

- **Comprehensive Information Delivery:** Stay updated with the latest notices, timetables, exams, and more.
- **User-Friendly Interface:** Designed for ease of use by students, trainers, and administrators.
- **Modular Architecture:** Includes distinct modules for Admin, Student, Trainer, Institution, Login, and Registration.

## Technology Stack

- **Backend:** Java
- **Database:** MySQL
- **IDE:** NetBeans
- **Version Control:** Git

## Installation

### Prerequisites

- Java Development Kit (JDK) 8 or later
- MySQL Database
- NetBeans IDE
- Git

### Step-by-Step Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/infotute.git
   cd infotute
   ```

2. **Install MySQL:**
   - Download and install MySQL from the [official MySQL website](https://dev.mysql.com/downloads/).
   - Create a new database for Infotute.

3. **Set Up the Database:**
   - Create a database and user for Infotute.
   - Import the SQL schema located in the `database` folder:
     ```bash
     mysql -u username -p infotute_db < database/schema.sql
     ```

4. **Configure the Database Connection:**
   - Open the `config.properties` file in the `src` directory.
   - Update the database URL, username, and password as per your MySQL setup.

5. **Build the Project:**
   - Open NetBeans IDE and import the project.
   - Build the project to compile the source code.

6. **Run the Application:**
   - From NetBeans, run the project directly or use the terminal:
     ```bash
     java -jar Infotute.jar
     ```

7. **Access the Application:**
   - Open your web browser and go to `http://localhost:8080/infotute`.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Make sure to follow the coding standards and include detailed commit messages.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any queries or support, feel free to contact:

- **Madhu Priya**  
  GitHub: [MadhuPriya1004](https://github.com/MadhuPriya1004)
