# Web Blog Project

The project is built using PHP and MySQL, and is designed to demonstrate CRUD operations, authentication, and structured application architecture.

---

## Overview

The application is split into two main sections:

- **Admin Panel** – Enables administrators to manage blog content such as posts, categories, and users.
- **Public Interface** – Allows users to view blog content, perform searches, and register/log in.

---

## Project Structure

### `admin/` – Administrative Backend

Contains logic and views specific to content management by administrators.

- CRUD Operations:
  - Files: `add-*.php`, `edit-*.php`, `delete-*.php`
  - Logic Handlers: `*-logic.php`
- Admin Layout:
  - Shared components in `partials/` (e.g., `header.php`)
- Dashboard & Management:
  - `index.php`, `manage-categories.php`, `manage-users.php`
- Configuration:
  - `admin/config/` – Database and constants files specific to admin panel

### Root Directory – Public-Facing Interface

Files directly accessible to site visitors.

- Core Pages:
  - `index.php`, `blog.php`, `category-posts.php`, `post.php`
  - Static Pages: `about.php`, `contact.php`, `services.php`
  - Search: `search.php`
- Authentication:
  - Forms: `signin.php`, `signup.php`
  - Logic: `signin-logic.php`, `signup-logic.php`, `logout.php`
- Layout:
  - Shared layout components in `partials/` (e.g., `header.php`, `footer.php`)
- Configuration:
  - `config/` – Database connection and constants for public pages

### Static Resources

- `css/` – Stylesheets (`style.css`)
- `js/` – JavaScript files (`main.js`)
- `images/` – Static assets such as icons, banners, etc.

---

## Setup Instructions

Follow the steps below to run the project locally using XAMPP:

1. Ensure **XAMPP** is installed on your system.
2. Extract the project folder into `htdocs` (e.g., `C:/xampp/htdocs/blog`).
3. Launch **phpMyAdmin** and create a new database named `blog`.
4. Import the SQL file `blog-tables.sql` located in the project root to populate the database schema.
5. Open your browser and navigate to `http://localhost/blog`.
6. Use any credentials to sign in and test the functionality.

---

## Development Notes

- Ensure that `display_errors` is enabled in `php.ini` for easier debugging during development.
- Code follows a modular pattern with reusable components.
- Database interactions use procedural MySQLi; can be extended with PDO or ORM (e.g., Eloquent).
- Admin and public areas are logically separated for clarity and maintainability.

---

## Author

**Roman Zostenko**  
GitHub: [wwtanji](https://github.com/wwtanji)

---

## References

- [PHP Documentation](https://www.php.net/docs.php)
- [MySQL Documentation](https://dev.mysql.com/doc/)
- [XAMPP](https://www.apachefriends.org/index.html)
- [phpMyAdmin](https://www.phpmyadmin.net/)
- [MDN: HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN: CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN: JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)