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

\```
TA-Web-Application/
│── app/              # Main application code
│── templates/        # HTML templates
│── static/           # CSS, JS, images
│── requirements.txt  # Python dependencies
│── manage.py         # Application runner
└── README.md         # Project documentation
\```


## Testing

Run the test suite:

\```
pytest
\```


## Documentation

- API endpoints and usage examples can be added to the `docs/` directory.  
- Configuration files and environment variables should be documented in `config/`.


## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License

MIT License
