# Book Review App

A simple Ruby on Rails application where users can sign up, add books, and write reviews. Each book can have multiple reviews, and users must be signed in to contribute.

---
  <p align="center">
    <img width="732" height="745" src="https://github.com/user-attachments/assets/167f1124-59a9-4f45-9e22-e63c5a4934a2">
  </p>

## Features

- User authentication via Devise
- Add, edit, and delete books
- Leave reviews on books
- View all books and their details
- Responsive UI with custom CSS
- Cover image support via image URL

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/book-review-app.git
cd book-review-app
```

### 2. Install dependencies

Make sure you have Ruby, Rails, and PostgreSQL (or SQLite) set up.

```bash
bundle install
```

### 3. Set up the database

```bash
rails db:create
rails db:migrate
```

### 4. Start the Rails server

```bash
rails server
```

Open your browser and go to `http://localhost:3000`.

---

## Testing the App

- Register or sign in via `/users/sign_up` or `/users/sign_in`
- Navigate to `/books` to view and add books
- Click a book to view its details and leave a review

---

## Adding a Book

When adding a book:
- **Title**: Name of the book
- **Author**: Name of the author
- **Description**: Short summary
- **Cover Image**: A URL pointing to a book cover image (example: `https://example.com/image.jpg`)

---

## Tech Stack

- Ruby on Rails
- Devise for authentication
- PostgreSQL or SQLite
- HTML, ERB, CSS

---

## License

MIT License

---
