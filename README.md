

# Capital City Quiz

Capital City Quiz is an interactive web application where users can test their knowledge of capital cities around the world. Built with Node.js, Express, and PostgreSQL, this quiz challenges users to identify the capital city for each country presented.

## Features

- Interactive quiz to guess the capital cities of different countries.
- Score tracking for correct answers.
- Simple and user-friendly web interface.

## Getting Started

These instructions will guide you through setting up the project on your local machine for development and testing purposes.

### Prerequisites

- Node.js
- npm (Node Package Manager)
- PostgreSQL

### Installation

1. **Clone the repository:**
  
   - git clone https://github.com/rajpanjabi/capital-city-quiz.git
   - cd capital-city-quiz
### Install dependencies:

- npm install

### Set up PostgreSQL:

- Ensure PostgreSQL is installed and running.
- Create a database and initialize it with the required tables and data.

### Environment Variables:

- Create a .env file in the project root.
- Add the following content, adjusting values for your database setup:
  
.env

- DB_USER=your_username
- DB_HOST=localhost
- DB_DATABASE=your_database
- DB_PASSWORD=your_password
- DB_PORT=5432


### Start the application:

- npm start
- Open http://localhost:3000 in your browser to use the app.

### Usage

- The home page displays a country name.
- Enter the corresponding capital city and submit your answer.
- Your score updates based on correct answers.
- The quiz ends with a wrong answer, displaying your final score and an option to restart.
