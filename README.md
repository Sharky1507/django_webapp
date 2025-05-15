# Django Web Application
## Setup Instructions

### 1. Install Dependencies
```
pip install django pillow
```

### 2. Database Setup
```
python manage.py migrate
```

### 3. Create Admin User
```
python manage.py createsuperuser
```

### 4. Run the Application
```
python manage.py runserver
```

### 5. Access the Application
- Application URL: http://127.0.0.1:8000/
- Admin Interface: http://127.0.0.1:8000/admin/

## User Types
- **Patient**: Regular user with patient-specific dashboard
- **Doctor**: Medical professional with doctor-specific dashboard

## Signup Requirements
- First Name and Last Name
- Username and Email
- Password (with confirmation)
- Address details (line1, city, state, pincode)
- Profile picture (optional)
- User type selection

## Notes
- Images are stored in the media/profile_pics directory
- Both user types share similar signup forms but have different dashboards
- Passwords must match for successful registration
