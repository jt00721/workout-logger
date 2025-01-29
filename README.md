# workout-logger
A simple web app using Go that allows users to log, view, and analyze workouts. Integrate a database (SQLite or PostgreSQL) for backend storage and create a basic user interface using HTML/CSS.

## Plan of the Week:

Day 1: Define Scope and Setup

    Goals
        Define the features of the web app and decide on its tech stack.
        Set up the project structure for a web-based application.

    Tasks
        Define core web app features:
            Add workouts (e.g., exercise name, sets, reps, weight, duration).
            View workout logs in a table or dashboard.
            Update or delete workouts.
        Install necessary Go packages (e.g., net/http, gorilla/mux, gorm for database handling).
        Set up the project folder structure:

        /workout-logger
        ├── /static (for CSS)
        ├── /templates (for HTML)
        ├── main.go
        ├── database.go
        └── routes.go

        Design the database schema with a table for workouts.
        Initialize your project with go mod init workout-logger.

Day 2: Create the Database and Backend Logic

    Goals
        Set up the database connection and backend logic for CRUD operations.

    Tasks
        Initialize the SQLite or PostgreSQL database with a table for workouts.
        Write backend functions to:
            Add a workout (INSERT).
            Retrieve all workouts (SELECT).
            Update a workout (UPDATE).
            Delete a workout (DELETE).
        Test the backend functions with dummy data.

Day 3: Build the HTML Templates

    Goals
        Create HTML templates for the main pages of the web app.

    Tasks
        Build a simple homepage (index.html) with:
            A table to display workout logs.
            Buttons/links for adding, editing, and deleting workouts.
        Create a form page (add-workout.html) for logging a new workout.
        Add a basic layout for consistency (e.g., header, footer, and a navigation bar).
        Style the app with basic CSS (optional: include a popular framework like TailwindCSS or Bootstrap).

Day 4: Connect the Backend and Frontend

    Goals
        Set up HTTP routes to serve pages and handle user actions.

    Tasks
        Use a router (e.g., gorilla/mux) to define routes:
            /: Display all workouts.
            /add: Render the form to add a workout.
            /add/submit: Handle form submission to log a workout.
            /edit/{id}: Render a form to update a workout.
            /delete/{id}: Delete a specific workout.
        Connect the backend CRUD functions to these routes.
        Test the app by adding and viewing workouts through the web interface.

Day 5: Add Analytics and Polishing

    Goals
        Implement basic analytics and refine the user experience.

    Tasks
        Add a stats section to the homepage:
            Total workouts logged.
            Progress tracking (e.g., heaviest weight for a specific exercise).
            Weekly or monthly summaries.
        Improve the UI:
            Add table styling for better readability.
            Display success/error messages after user actions.
        Optimize database queries for analytics.

Day 6: Testing, Debugging, and Final Touches

    Goals
        Ensure the web app works smoothly and fix any issues.
        Finalize all features.

    Tasks
        Test all routes and features:
            Logging, viewing, editing, and deleting workouts.
            Edge cases, like invalid inputs or missing data.
        Debug any issues with database queries or page rendering.
        Finalize CSS styling and overall app design.

Day 7: Wrap-Up and Content Creation

    Goals
        Finalize the project and share your progress online.

    Tasks
        Record a short demo showing the web app’s features.
        Write a blog-style README.md explaining the app and its functionality.
        Share your progress on social media, highlighting what you learned and the challenges you overcame.


## Core Features

1. Add workouts
    - Exercise name
    - Sets
    - Reps
    - Weight
    - Duration

2. View workout logs in a table or dashboard.

3. Update workouts

4. Delete workouts

