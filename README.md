Project Description
The Flask Blog Application is a simple blog app where the main user (admin) can add blog content. Registered users can create an account, log in, view the blog posts, and leave comments. It’s designed to offer a basic but functional blogging platform with an interactive user experience.

Features
User registration and login

Add, edit, and delete blog posts (Admin)

Comment on blog posts (Registered users)

View blog posts and their comments

Basic user authentication and authorization

Technologies Used
Python: The programming language used for the backend logic.

Flask: A lightweight web framework used to build the application.

SQLAlchemy: An ORM (Object Relational Mapping) tool used for database interactions.

Bootstrap: For responsive design (if included).

Flask-WTF: For form handling in Flask (if used).

Installation
To run this project locally, follow these steps:

Clone the repository:

bash
Copy
Edit
git clone https://github.com/ochiengrichie/flask-blog.git
Navigate to the project directory:

bash
Copy
Edit
cd flask-blog
Create a virtual environment:

bash
Copy
Edit
python3 -m venv venv
Activate the virtual environment:

On Windows:

bash
Copy
Edit
venv\Scripts\activate
On MacOS/Linux:

bash
Copy
Edit
source venv/bin/activate
Install the required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Set environment variables (e.g., for database URL, secret key):

You can create a .env file in the project root and add necessary configuration like:

bash
Copy
Edit
FLASK_APP=app.py
FLASK_ENV=development
DATABASE_URL=sqlite:///your_database.db
Run the application:

bash
Copy
Edit
flask run
Open a browser and visit http://127.0.0.1:5000/ to access the application.

Usage
Once the app is running, you can:

Sign up and log in as a user.

The admin can add new blog posts, which will be visible to all users.

Users can comment on posts, and the admin can manage the posts.

Contact
If you have any questions or feedback, feel free to reach out at:
Email: ochiengrichie24@gmail.com

