# College Sports League Management System

## Overview

This project is a web-based application to manage a sports league where different departments of a college compete against each other in various sports. The application allows departments to register teams, schedule matches, update scores, and post announcements about winners and upcoming events.

## Features

1. **Registration System**:
   - Departments can register teams for different sports.
   - Players can register and be assigned to teams.

2. **Match Scheduling and Results**:
   - Schedule matches between departments.
   - Enter and update scores.
   - Display match results.

3. **Leaderboard and Announcements**:
   - Maintain a leaderboard to track department rankings.
   - Post announcements about winners and upcoming events.

## Technologies Used

- **Backend**: Python, Flask
- **Database**: SQLite (using SQLAlchemy)
- **Frontend**: HTML, CSS 
- **Version Control**: Git

## Project Structure

college_sports_league/
├── app.py # Main application file
├── config.py # Configuration settings
├── models.py # Database models
├── routes.py # Application routes and view functions
├── templates/ # HTML templates
│ ├── base.html # Base template
│ ├── index.html # Homepage template
│ ├── register.html # Registration page template
│ ├── schedule.html # Match schedule template
│ ├── results.html # Match results template
│ ├── leaderboard.html# Leaderboard template
│ └── announcements.html # Announcements template
├── static/ # Static files (CSS, JS, images)
└── README.md # Project README file

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/your-username/college_sports_league.git
   cd college_sports_league
   
2. **Create a Virtual Environment**:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   
3. **Install Dependencies**:
    ```sh
    pip install -r requirements.txt

4. **Set Up the Database**:
   ```sh
   flask db init
   flask db migrate -m "Initial migration."
   flask db upgrade
5. **Run the Application**:
    ```sh
    flask run
 
##Usage
1. **Register Teams**:
  Navigate to the registration page.
  Departments can register their teams and players for different sports.
2. **Schedule Matches**:
  Admin can schedule matches between different departments.
3.**Update Scores**:
  Enter and update match scores after each game.
4.**View Leaderboard**:
  Check the leaderboard to see department rankings.
5.**Post Announcements**:
  Admin can post announcements about winners and upcoming events.




  
    
   



   

   



