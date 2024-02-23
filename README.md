# Author-Energy: Weekly Report App

Author-Energy is a Django REST Framework project designed to generate weekly reports for authors based on their energy levels. This application helps authors track their productivity and energy levels throughout the week, enabling them to optimize their work schedules for peak performance.

## Features

- **User Authentication**: Secure user authentication system allowing authors to register, login, and manage their accounts.
- **Weekly Report Generation**: Automatically generate comprehensive weekly reports based on user input regarding their daily energy levels and productivity.
- **Customizable Reports**: Users can customize their reports by adding additional notes or insights for each day.
- **RESTful API**: Provides a RESTful API for seamless integration with other applications or services.
- **Admin Dashboard**: Admin dashboard for managing users, reports, and system settings.

## Installation

1. Clone the repository:

```
git clone https://github.com/archbong/author-energy.git
```

2. Navigate into the project directory:

```
cd author-energy
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Apply database migrations:

```
python manage.py migrate
```

5. Run the development server:

```
python manage.py runserver
```

6. Access the application at `http://localhost:8000/`.

## API Endpoints

- `/api/create-reports/` : Create new report
- `/api/list-reports/`: List all weekly reports or create a new one.
- `/api/detail-reports/<report_id>/`: Retrieve, update, or delete a specific weekly report.

## Usage

1. Register a new account or log in with existing credentials.
2. Submit daily energy levels and productivity data throughout the week.
3. View and customize the generated weekly reports.
4. Optionally integrate the RESTful API with other applications or services.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Django REST Framework
- Python
- PostgreSQL (or any other database backend)
- And all other dependencies used in this project.