# Book Library Frontend

A React-based frontend application for managing your personal book collection. This application provides a user-friendly interface to track, organize, and manage your books.

## Features

- View your entire book collection
- Add new books with title, author, genre, and reading status
- Edit existing book information
- Delete books from your collection
- Track reading status (Read/Unread)
- Search and filter books
- Responsive design for all devices

## Tech Stack

- React 19.2.3
- React Router DOM for navigation
- CSS for styling
- RESTful API integration

## Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/bilalwebs/book-library-frontend.git
   ```

2. Navigate to the project directory:
   ```bash
   cd book-library-frontend
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Start the development server:
   ```bash
   npm start
   ```

5. Open your browser and visit `http://localhost:3000`

## Backend Integration

This frontend connects to a backend service running on `http://localhost:3001`. Make sure the backend server is running before starting the frontend.

## Project Structure

- `src/App.js` - Main application component
- `src/components/` - Reusable UI components
- `src/index.js` - Application entry point

## API Endpoints Used

- `GET /books` - Retrieve all books
- `POST /books` - Add a new book
- `PUT /books/:id` - Update a book
- `DELETE /books/:id` - Delete a book

## Contributing

Feel free to submit issues and enhancement requests!
