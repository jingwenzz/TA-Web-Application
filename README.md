# TA Web Application

A web-based platform designed to support teaching assistants (TAs), instructors, and students by streamlining classroom management tasks and improving communication.  
This project demonstrates full-stack development, database integration, and deployment-ready structure.



## Features
- **Role-based access control**: Separate permissions for instructors, TAs, and students.  
- **Task management**: Create, assign, and track TA responsibilities.  
- **Announcements & communication**: Simple tools for updates and feedback.  
- **Data persistence**: Reliable backend storage with relational database.  
- **Responsive UI**: Accessible and user-friendly interface.  



## Tech Stack
- **Backend**: Python (Flask/Django)  
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: PostgreSQL / SQLite  
- **Version control**: Git + GitHub  


## Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/jingwenzz/TA-Web-Application.git
   cd TA-Web-Application

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate

3. Install dependencies:
   ```bash
   pip install -r requirements.txt

4. Set up the database (example for SQLite):
   ```bash
   python manage.py migrate

5. Run the application:
   ```bash
   python manage.py runserver

6. Open the application in your browser:
   ```bash
   http://127.0.0.1:8000/

## Repository Structure

   ```bash
   TA-Web-Application/
   │── TAWebApplication.sln # Visual Studio solution file
   │
   ├── TAWebApplication/ # Main Windows Forms application
   │ ├── Forms/ # UI components: LoginForm, TaskViewForm, etc.
   │ ├── Helpers/ # Utility classes for formatting and processing
   │ ├── Models/ # Data models for TAs, tasks, students, etc.
   │ ├── Services/ # Core logic: authentication, task/grade management
   │ ├── Program.cs # Application entry point
   │ └── App.config # Configuration file
   │
   ├── TAWebApplicationTests/ # (Optional) Unit test project
   │ └── (Add test files here)
   │
   └── README.md # Project documentation
   ```

## Testing
To add unit tests, create test classes under the `TAWebApplicationTests/` folder. You can run tests using the built-in Visual Studio Test Explorer or with `dotnet test` if targeting .NET Core.


## Documentation

- Application behavior and form usage are described in source code comments within each `Form.cs` file.  
- Configuration is managed via `App.config`.  
- You may add high-level design notes in a `docs/` folder if needed.


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License

MIT License
