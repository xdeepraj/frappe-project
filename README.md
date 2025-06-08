# To-Do App (Frappe v15)

A simple task management web application built using the Frappe Framework v15.

## 🚀 Features

- Create and manage tasks
- Set task descriptions, priorities, due dates, and status
- Mark tasks as “To-Do”, “In Progress”, or “Done”
- View a summary report of tasks grouped by status
- Clean UI with Frappe's built-in List View & Report Builder

## 📦 Tech Stack

- **Backend**: Python (Frappe Framework)
- **Database**: MariaDB (via Frappe)
- **Frontend**: Auto-generated via Frappe Desk UI
- **Reports**: Built using Frappe’s Report Builder

## 📁 Doctype Structure

The custom `Task` Doctype includes:
- `title`: Task title
- `description`: Short task summary
- `status`: To-Do / In Progress / Done
- `priority`: Low / Medium / High
- `due_date`: Deadline for task

## 📊 Reports

- A `Task Summary` report is included
- Grouped by task status for quick overviews
- Built without custom code using Report Builder

## 🛠 Setup Instructions (Dev)

1. Clone the repo:
   ```bash
   git clone https://github.com/xdeepraj/frappe-project.git
