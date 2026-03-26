# Rails Task Manager

A task management application built with Ruby on Rails, allowing users to create, view, update, and delete tasks.

## Features

- List all tasks
- View task details
- Create new tasks
- Edit existing tasks (including completion status)
- Delete tasks

## Tech Stack

- Ruby on Rails
- Active Record (ORM)
- ERB (Embedded Ruby)

## How It Works

The application follows the MVC architecture:

- **Model**: Task model with title, details, and completion status
- **Controller**: Handles CRUD operations and user interactions
- **View**: Renders forms and task data dynamically

Tasks are stored in a database and managed using Active Record.

## Setup

```bash
git clone https://github.com/sp1aca9fa/rails-task-manager.git
cd rails-task-manager
bundle install
rails db:create db:migrate
rails server
```

Open in your browser: http://localhost:3000

## Learnings

- Building full CRUD functionality from scratch
- Working with Active Record and database migrations
- Handling REST-like routes and controller actions
- Managing forms and user input in Rails
- Structuring a complete Rails application

## Notes

This project was built to practice core Rails concepts, including database-backed applications and CRUD workflows.
