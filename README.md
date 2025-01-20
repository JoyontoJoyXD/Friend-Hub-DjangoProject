# Friend Hub - A Social Media Platform

![Project Screenshot](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%20(1491).png)


## Introduction
**Friend Hub** is a social media web application built with Django that allows users to create profiles, share posts, follow other users, and engage with their community. The platform provides a seamless user experience with features like user authentication, profile management, and media uploads.

## Features
- **User Authentication:** Sign up, login, and logout functionality.
- **Profile Management:** Update profile details, including bio and profile picture.
- **Post Creation:** Share images and captions with friends.
- **Follow System:** Follow and unfollow users.
- **Search Users:** Search for users by their username.
- **Like & Comment:** Engage with posts by liking and commenting.
- **Responsive Design:** Fully responsive UI across all devices.

## Technologies Used
- **Backend:** Django, Python
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite (default), can be upgraded to PostgreSQL
- **Authentication:** Django's built-in authentication system
- **Deployment:** Heroku / AWS / DigitalOcean (haven't done yet)

## Installation

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- Django
- Virtual Environment (optional but recommended)

### Steps to Set Up Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Friend-Hub.git
   cd Friend-Hub
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Apply database migrations:
   ```bash
   python manage.py migrate
   ```

5. Create a superuser (admin account):
   ```bash
   python manage.py createsuperuser
   ```

6. Run the development server:
   ```bash
   python manage.py runserver
   ```

7. Open your browser and navigate to:
   ```
   http://127.0.0.1:8000
   ```

## Project Structure
```
Friend-Hub/
│-- media/              # Uploaded media files
│-- static/             # Static files (CSS, JS, images)
│-- templates/          # HTML template files
│-- users/              # User management app
│-- posts/              # Post management app
│-- FriendHub/          # Main project settings
│-- db.sqlite3          # SQLite database
│-- manage.py           # Django management script
│-- requirements.txt    # Project dependencies
│-- README.md           # Project documentation
```

## Screenshots
![Signup Page](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201491.png)
![Login Page](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201492.png)
![User Profile](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201488.png)
![Search Feature](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201494.png)
![Home Feed](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201490.png)
![Settings Page](https://github.com/JoyontoJoyXD/Friend-Hub-DjangoProject/blob/main/Screenshot%201493.png)

## Future Enhancements
- Implement direct messaging between users.
- Add notifications for new followers and likes.
- Improve UI/UX with better design elements.
- Deploy the application to a cloud platform.

## Contributors
- **Joyonto Das**  
- **Jannatul Ferdus Shuchona**  
- **Jarin Tasnim Antara**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any queries or suggestions, please reach out via:
- Email: 20201005@uap-bd.edu/ 20201021@uap-bd.edu/ 19201065@uap-bd.edu

---

Thank you for visiting Friend Hub! Connect and share with your friends today.

