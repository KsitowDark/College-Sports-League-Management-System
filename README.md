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

## Installation

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/Mouriyavk/College-Sports-League-Management-System.git
   cd College-Sports-League-Management-System
   
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
 
## Usage

1. **Register Teams**:
  - Navigate to the registration page.
  - Departments can register their teams and players for different sports.

3. **Schedule Matches**:
  - Admin can schedule matches between different departments.

3.**Update Scores**:
  - Enter and update match scores after each game.
  
4.**View Leaderboard**:
  - Check the leaderboard to see department rankings.
  
5.**Post Announcements**:
  - Admin can post announcements about winners and upcoming events.




  
    
   



   

   



