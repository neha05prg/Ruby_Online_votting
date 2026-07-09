# Online Voting System

## Overview

The Online Voting System is a web-based application developed using Ruby on Rails that provides a secure and user-friendly platform for conducting elections digitally. The system allows registered users to participate in elections by casting their votes online while enabling administrators to manage candidates, elections, and voting records efficiently.

The application is designed to simplify the election process, reduce manual effort, improve transparency, and ensure that each registered voter can cast only one vote per election.

---

## Features

- User registration and secure authentication
- Admin and voter roles
- Candidate management
- Election creation and management
- Secure online voting
- One vote per registered voter
- Real-time vote counting
- Election result display
- Responsive and user-friendly interface

---

## Technologies Used

- Ruby
- Ruby on Rails
- HTML5
- CSS3
- JavaScript
- SQLite3 (Development Database)
- Bootstrap (if used)

---

## Project Structure

```
app/                # MVC components (Models, Views, Controllers)
config/             # Application configuration
db/                 # Database migrations and schema
public/             # Static files
lib/                # Custom libraries
test/               # Test cases
Gemfile             # Project dependencies
README.md           # Project documentation
```

---

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/online-voting-system.git
```

2. Navigate to the project directory

```bash
cd online-voting-system
```

3. Install dependencies

```bash
bundle install
```

4. Set up the database

```bash
rails db:create
rails db:migrate
```

5. Start the server

```bash
rails server
```

6. Open your browser and visit

```
http://localhost:3000
```

---

## Usage

- Register as a voter or log in with existing credentials.
- View the list of available elections.
- Select a candidate and cast your vote.
- View election results after voting ends.
- Administrators can manage elections, candidates, and users through the admin interface.

---

## Security Features

- Secure user authentication
- Role-based authorization
- One vote per voter
- Server-side validation
- Protection against duplicate voting

---

## Future Enhancements

- Email verification
- OTP-based authentication
- Live election dashboard
- Vote receipt generation
- Graphical analytics and reports
- Multi-language support


---

## License

This project is developed for educational purposes and can be modified or extended for learning and research.
