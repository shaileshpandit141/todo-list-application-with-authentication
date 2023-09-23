# Todo List Application with Authentication
---
This is a simple web-based Todo List application built using Django that includes user authentication. With this application, users can create, update, delete, and manage their tasks in an organized manner. User authentication ensures that each user has their own private todo list.

### Features
- User Authentication: Users can register, log in, and log out to access their personalized todo lists.
- Todo List Management: Users can create, update, and delete tasks on their todo list.
- Task Status: Users can mark tasks as completed or uncompleted.

### Getting Started
To get this project up and running on your local machine, follow these steps:

1. Clone the Repository
   ```shell
   git clone https://github.com/shaileshpandit141/Todo-List-Application-with-Authentication.git
   ```
2. Create a Virtual Environment (Optional but Recommended)

   Create a virtual environment to isolate project dependencies:
   ```shell
   python -m venv env
   ```
   Activate the virtual environment:

    * On Windows:
        ```shell
        env\Scripts\activate
        ```
    * On macOS and Linux:
        ```shell
        source env/bin/activate
        ``` 
3. Install Dependencies
   
    Install the project dependencies using pip:
    ```shell
    pip install -r requirements.txt
    ```
4. Apply Migrations

    Run makemigrations command to create the necessary python instance for sql quaries:
    ```shell
    python manage.py makemigrations
    ```

    and also Run migrate command to create the necessary tables in the database:
    ```shell
    python manage.py migrate
    ```
5. Create a Superuser

    Create a superuser account to access the Django admin interface:
    ```shell
    python manage.py createsuperuser
    ```
    Follow the prompts to create a superuser account with a username and password.

6. Run the Development Server

    Start the Django development server:
    ```shell
    python manage.py runserver
    ```
    The application should now be running locally at ``http://127.0.0.1:8000/``.
    
7. Access the Admin Panel

    You can access the all django templates UI by visiting ``http://127.0.0.1:8000/admin/`` and logging in with the superuser credentials created earlier. Here, you can manage users and tasks.

    Also You can access the admin panel by visiting ``http://127.0.0.1:8000/admin/`` and logging in with the superuser credentials created earlier. Here, you can manage users and tasks.

8. Create a User Account

    Visit ``http://127.0.0.1:8000/register/`` to create a new user account. Once registered, you can log in and start using the todo list application.

### Usage
* og in using your registered account or create a new account if you haven't already.
* Once logged in, you can add, edit, and delete tasks from your todo list.
* You can set the priority and status of each task.


### Contributing
If you'd like to contribute to this project, please follow these guidelines:

* Fork the repository on GitHub.
* Create a new branch with a descriptive name for your feature or bug fix.
* Make your changes and commit them with clear commit messages.
* Push your branch to your fork.
* Create a pull request with a clear title and description.

### Acknowledgments
* This project was inspired by the need for a simple and organized way to manage tasks.
* Thank you to the Django community for providing excellent documentation and resources.

Feel free to customize and expand upon this Todo List application to suit your needs. Happy coding!