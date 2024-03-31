# Flask CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application built using Flask, SQLAlchemy, and Bootstrap. It allows users to manage employee data by performing CRUD operations.

## Features

- Add new employees
- View existing employees
- Update employee information
- Delete employees

## Technologies Used

- Python
- Flask
- SQLAlchemy
- Bootstrap
- MySQL (Database)

## Prerequisites

Before running this application, make sure you have the following installed:

- Python 3.x
- Flask
- SQLAlchemy
- MySQL Server

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/flask-crud-app.git

2. Navigate to the project directory:
   ```bash
   cd flask-crud-app

3. Set up the MySQL database:

    Create a MySQL database named `crud`.

4. Update the database connection string in `app.py`:

    ```app.config['SQLALCHEMY_DATABASE_URI'] = 'mysql://username:password@localhost/crud'```

5. Run the application:

    ```python app.py```

6. Open your web browser and go to http://localhost:5000 to access the application.

## Usage

- **Navigate to the home page to view a list of employees.**
- **Click on "Add New Employee" to add a new employee.**
- **Click on "Edit" to update an existing employee's information.**
- **Click on "Delete" to remove an employee from the database.**

## Screenshots

- **Home**

    ![Home Page](./Snapshots/Home.png)
    
    Description: This is the home page where users can view a list of employees.

- **Add Employee Page:**

    ![Add Page](./Snapshots/Add_emp.png)

    Description: Users can add a new employee using this page.

- **Edit Employee Page:**

    ![Edit Page](./Snapshots/Edit_emp.png)

    Description: Users can edit an existing employee's information using this page.

- **Delete Confirmation:**

    ![Delete Page](./Snapshots/Delete_emp.png)

    Description: This confirmation message appears when users try to delete an employee.

- **Database Configuration:**

    ![Database page](./Snapshots/Db.png)

    Description: This is the overall configuration of DB after performing CRUD operations. It shows how many records are in the table.
    

## Contributing

To contribute to this project, follow these steps:

1. **Fork the repository.**
   
2. **Create a new branch (`git checkout -b feature/new-feature`).**
   
3. **Make your changes.**
   
4. **Commit your changes (`git commit -am 'Add new feature'`).**
   
5. **Push to the branch (`git push origin feature/new-feature`).**
   
6. **Create a new Pull Request.**

    

