# User Roles & Authentication

## Description
Add user authentication and role-based access control to the system. Currently, anyone can sign up for activities without verification.

## Requirements
- Implement user registration and login (email/password or OAuth)
- Define roles: Student, Admin/Staff
- Role-based permissions:
  - Students: view activities, sign up/unregister
  - Admins: create/edit/delete activities, view all registrations, manage users
- Secure API endpoints with authentication tokens
- Add user profiles with basic info (name, email, grade/year)

## Benefits
- Prevent unauthorized access and spam registrations
- Enable personalized features (e.g., view user's registered activities)
- Better data management and security

## Related Features
- Integrates with admin tools and notifications