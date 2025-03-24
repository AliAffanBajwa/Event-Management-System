# Event Management System

A simple Django-based event management system that allows users to create, update, delete, and view events and categories.

## Features
- Create, update, and delete events
- Manage categories with event associations
- View category-wise event listings
- Event statistics via charts

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/AliAffanBajwa/Event-Management-System.git
   cd event_management_system
   ```
2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Apply migrations:
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```
5. Run the development server:
   ```sh
   python manage.py runserver
   ```

## Usage
- Access the web application at `http://127.0.0.1:8000/`
- Navigate through categories and events
- Use the admin panel for additional management



