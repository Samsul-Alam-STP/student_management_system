# Student Management System (React + Django)

Welcome to the Student Management System project! This repository contains the source code for a web application developed using React for the frontend and Django with Django REST Framework for the backend. 

## Cloning the Repository

To clone this repository and set up the project on your local machine, follow these steps:

1. Open your terminal or command prompt.

2. Navigate to the directory where you want to clone the repository.

3. Run the following command to clone the repository:

```shell
git clone https://github.com/your-username/student-management-system.git
```

4. Once the cloning process is complete, navigate to the project's root directory:

```shell
cd student-management-system
```

## Backend Setup

To set up the backend Django server and install the required dependencies, follow these steps:

1. Create a virtual environment (optional but recommended) to isolate project dependencies:

```shell
python3 -m venv myenv
```

2. Activate the virtual environment:

   - For Windows:

   ```shell
   myenv\Scripts\activate
   ```

   - For macOS/Linux:

   ```shell
   source myenv/bin/activate
   ```

3. Install the project dependencies using the `pip` package manager:

```shell
pip install -r requirements.txt
```

4. Set up the database by applying migrations:

```shell
python manage.py migrate
```

5. Start the Django development server:

```shell
python manage.py runserver
```

The backend server should now be running at [http://localhost:8000](http://localhost:8000).

## Frontend Setup

To set up the React frontend and install the required dependencies, follow these steps:

1. Open a new terminal or command prompt (while keeping the backend server running).

2. Navigate to the `frontend` directory:

```shell
cd frontend
```

3. Install the project dependencies using npm:

```shell
npm install
```

4. Start the React development server:

```shell
npm start
```

The frontend server should now be running at [http://localhost:3000](http://localhost:3000), and you can access the Student Management System in your web browser.

## Contributing

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue on the repository.
