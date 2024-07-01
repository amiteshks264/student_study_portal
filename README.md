# Student Study Portal

This is a Django project aimed at making studying easier for students by providing various tools on one platform.

## Features

- **Dashboard**: Centralized area for accessing all study tools.
- **User Authentication**: Secure login and registration system.
- **Study Tools**: Access to a variety of tools designed to aid in studying.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/amiteshks264/student_study_portal.git
   ```
2. Navigate to the project directory:
   ```bash
   cd student_study_portal
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Apply the migrations:
   ```bash
   python manage.py migrate
   ```
5. Run the development server:
   ```bash
   python manage.py runserver
   ```

## Usage

1. Open your web browser and go to `http://127.0.0.1:8000/`.
2. Register a new account or log in with existing credentials.
3. Access the dashboard to utilize the available study tools.

## Project Structure

### 1. **Project Structure**

- **manage.py**: A command-line utility that lets you interact with this Django project.
- **settings.py**: Configuration settings for the Django project.
- **urls.py**: URL declarations for the project; a "table of contents" of your Django-powered site.
- **wsgi.py**: An entry-point for WSGI-compatible web servers to serve your project.

### 2. **Applications**

The project contains multiple Django applications, each handling different functionalities:

- **Authentication App**:
  - Manages user registration, login, and logout.
  - Handles password reset and profile management.

- **Dashboard App**:
  - Provides an overview of available study tools and resources.
  - Customizable interface based on user preferences.

- **Study Tools App**:
  - Includes various tools like flashcards, note-taking, scheduling, etc.
  - Each tool is implemented as a separate module within the app.

### 3. **Templates**

- **HTML Templates**: These are stored in a `templates` directory within each app.
  - **base.html**: The base template that other templates extend.
  - **dashboard.html**: Template for the dashboard view.
  - **login.html**: Template for the login page.
  - **register.html**: Template for the registration page.

### 4. **Static Files**

- **CSS**: Styling for the web pages.
- **JavaScript**: Client-side functionality.
- **Images**: Icons, logos, and other images.

### 5. **Models**

- **User Model**: Represents user information and authentication details.
- **Tool Models**: Represents data structures for various study tools (e.g., flashcards, notes).

### 6. **Views**

- **Function-based views or Class-based views**: Handle requests and return responses.
  - **DashboardView**: Renders the dashboard page.
  - **LoginView**: Handles user login.
  - **RegisterView**: Manages user registration.

### 7. **Forms**

- **AuthenticationForm**: Handles user authentication.
- **RegistrationForm**: Manages user registration details.
- **ToolForms**: Forms for various study tools (e.g., creating flashcards, notes).

### 8. **URLs**

- **project-level urls.py**: Includes app-level URLs.
- **app-level urls.py**: Manages URL routing for specific applications.

### 9. **Admin**

- **Admin Configurations**: Allows administrators to manage the site through the Django admin interface.
  - **UserAdmin**: Configuration for managing users.
  - **ToolAdmin**: Configuration for managing study tools.

### 10. **Migrations**

- **Database Migrations**: Tracks changes to the models and applies them to the database.

### 11. **Settings**

- **Development Settings**: Configuration for development environment.
- **Production Settings**: Configuration for production environment.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-branch
   ```
5. Open a pull request.

## Contact

For any questions or suggestions, please contact [Amitesh](https://github.com/amiteshks264).

---
