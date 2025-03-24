# Basic CRUD Operations

A simple CRUD (Create, Read, Update, Delete) application built with Node.js, Express, and MongoDB.

## Prerequisites

- Node.js installed on your system
- MongoDB installed and running locally
- npm (Node Package Manager)

## Setup Instructions

1. Clone the repository or download the files

2. Install dependencies:
```bash
npm install
```

3. Make sure MongoDB is running on your system
   - If MongoDB is not running, start it using your system's method
   - The application expects MongoDB to be running on `mongodb://localhost:27017`

4. Start the application:
```bash
node index.js
```

5. Open your browser and navigate to:
```
http://localhost:3000
```

## Available API Endpoints

- `GET /items` - Retrieve all items
- `POST /items` - Create a new item
- `POST /items/update/:id` - Update an existing item
- `POST /items/delete/:id` - Delete an item

## Database Configuration

The application connects to a MongoDB database named `crud_demo`. If you need to change the database connection settings, modify the MongoDB connection URL in `index.js`.

## Project Structure

```
basic-crud-operations/
├── index.js          # Main application file
├── package.json      # Project dependencies
└── public/          
    └── index.html    # Frontend interface
```

## Contributing

Feel free to submit issues and enhancement requests.