#python-backend-systems

This repository contains a collection of Python backend projects and exercises, focusing on practical concepts and real-world skills for backend development. Each subdirectory covers a specific topic, ranging from generators and decorators to database operations, asynchronous programming, and comprehensive testing.

---

## Project Structure

- **`python-generators-0x00/`**

  - Learn how to use Python generators for efficient data streaming and batch processing, especially with databases.
  - Includes scripts for streaming users, batch processing, lazy pagination, and seeding a MySQL database.

- **`python-decorators-0x01/`**

  - Explore Python decorators for logging, database connection management, transactions, retries, and caching.
  - Practice writing reusable and composable decorator functions for backend tasks.

- **`python-context-async-perations-0x02/`**

  - Dive into context managers and asynchronous operations in Python.
  - Work with database connections, execute queries asynchronously, and handle concurrent operations.

- **`0x03-Unittests_and_integration_tests/`**

  - Master unit and integration testing using `unittest`, `parameterized`, and `mock`.
  - This project provides a client for the GitHub API and includes extensive tests to demonstrate best practices for mocking and test parameterization. You'll learn to write robust tests for utility functions (`access_nested_map`), API clients (`GithubOrgClient`), and memoized properties.

- **`Django-Middleware-0x03/` & `messaging_app/`**
  - These directories contain a complete messaging API built with the Django REST Framework.
  - The project features JWT-based authentication, conversation and message management (`ConversationViewSet`, `MessageViewSet`), and custom middleware for logging API requests (`RequestLoggingMiddleware`). It serves as a practical example of building a full-fledged RESTful service.

---

## Key Concepts Covered

- Python generators and iterators
- Decorators and higher-order functions
- Database operations (MySQL, SQLite)
- Context managers and async programming
- Unit testing, integration testing, and mocking with `unittest` and `mock`
- API development with Django REST Framework
- Authentication with JWT
- Custom Django middleware
- Code style compliance (PEP8/pycodestyle)

---

## How to Use

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/alx-backend-python.git
   cd alx-backend-python
   ```

2. **Explore a project:**
   Navigate into any project directory to see the code and run the examples. Each project is self-contained. For example, to run the tests for the unit testing project:
   ```bash
   cd 0x03-Unittests_and_integration_tests/
   python -m unittest test_utils.py
   ```
