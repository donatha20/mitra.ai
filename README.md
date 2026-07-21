# mitra.ai

An AI-powered web application that assesses mental health risk and identifies the key factors associated with each prediction. The system combines machine learning with an intuitive web interface to support mental health risk assessment and provide interpretable results.

## Features

- Mental health risk assessment
- Interpretable prediction results
- Identification of key risk factors
- User-friendly React frontend
- Django REST API backend
- PostgreSQL database
- Secure data management
- Research and administrative dashboards

## Technology Stack

### Frontend
- React
- Vite
- TypeScript
- Tailwind CSS

### Backend
- Django
- Django REST Framework

### Database
- PostgreSQL

### Machine Learning
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy

## Project Structure

```
project-root/
│
├── frontend/          # React application
├── backend/           # Django application
├── ml/                # Machine learning models and pipelines
├── docs/              # Project documentation
└── README.md
```

## Installation

### Clone the repository

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

### Backend Setup

```bash
cd backend

python -m venv venv

# Windows
venv\Scripts\activate

# Linux/macOS
source venv/bin/activate

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

## Environment Variables

Create a `.env` file for both the frontend and backend and configure the required environment variables.

Example backend configuration:

```
SECRET_KEY=your-secret-key
DEBUG=True

DB_NAME=database_name
DB_USER=database_user
DB_PASSWORD=database_password
DB_HOST=localhost
DB_PORT=5432
```

## Technologies Used

- React
- Django
- Django REST Framework
- PostgreSQL
- Scikit-learn
- XGBoost
- SHAP
- Pandas
- NumPy

## Future Improvements

- User authentication and authorization
- Enhanced analytics dashboard
- Expanded explainable AI visualizations
- Mobile responsiveness improvements
- Model version management

## License

This project is intended for academic and research purposes.
