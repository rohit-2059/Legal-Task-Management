# Legal Task Management Application

A Flask-based web application for managing legal tasks and deadlines.

## Features

- Task creation and management
- Deadline tracking
- Priority levels
- Task status updates
- Enhanced user interface with modern styling

## Requirements

- Python 3.7+
- Flask
- Flask-SQLAlchemy

## Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/legal-task-management.git
cd legal-task-management
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
python app.py
```

4. Open your browser and navigate to `http://localhost:5000`

## Project Structure

```
├── app.py              # Main Flask application
├── requirements.txt    # Python dependencies
├── tasks.json         # Task configuration/storage
├── static/            # CSS and JavaScript files
│   ├── style.css
│   ├── script.js
│   └── enhanced.js
├── templates/         # HTML templates
│   ├── index.html
│   └── task_details.html
└── utils/             # Utility functions
    ├── __init__.py
    └── helper.py
```

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is open source and available under the [MIT License](LICENSE).
