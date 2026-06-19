# World Capitals Quiz

A full-stack web application that tests users' knowledge of world capitals. The application presents random countries, accepts user answers for their capitals, and keeps track of the user's score throughout the quiz.

## Features

* Random country-based quiz questions
* Capital city answer validation
* Real-time score tracking
* Immediate feedback on answers
* Data retrieved from PostgreSQL database
* Clean and responsive user interface
* Server-side rendering using EJS

## Tech Stack

### Frontend

* HTML
* CSS
* EJS

### Backend

* Node.js
* Express.js

### Database

* PostgreSQL

## How It Works

1. A random country is selected from the database.
2. The user enters the capital city of that country.
3. The application checks whether the answer is correct.
4. If correct, the score increases.
5. The next question is displayed automatically.
6. The process continues until the user enters the wrong answer.
7. User can restart the quiz.

## Database Structure

### capitals

| Column  | Type    |
| ------- | ------- |
| id      | SERIAL  |
| country | VARCHAR |
| capital | VARCHAR |

## Installation

### Clone the repository

```bash
git clone https://github.com/aditichaudhary05/world-capitals-quiz.git
```

### Navigate to the project directory

```bash
cd world-capitals-quiz
```

### Install dependencies

```bash
npm install
```

### Configure PostgreSQL

Create a PostgreSQL database and import the required table.

Update your database credentials in the project configuration file.

### Start the application

```bash
node index.js
```

### Open in browser

```text
http://localhost:3000
```

## Screenshots

Add screenshots of:
![World Capital Quiz](screenshot.png)

## Learning Outcomes

This project helped me practice:

* Express.js routing
* PostgreSQL queries
* Database integration with Node.js
* Form handling
* Server-side rendering with EJS
* Application state management
* Full-stack web development fundamentals

## Future Improvements

* Multiple difficulty levels
* Timer-based quiz mode
* Leaderboard system
* User authentication
* High score tracking
* Category-based quizzes

## Author

Aditi Chaudhary

GitHub: https://github.com/aditichaudhary05
