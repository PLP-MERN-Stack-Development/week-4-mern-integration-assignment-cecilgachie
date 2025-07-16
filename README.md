[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=19945194&assignment_repo_type=AssignmentRepo)
# MERN Stack Integration Assignment

This assignment focuses on building a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application that demonstrates seamless integration between front-end and back-end components.

## Assignment Overview

You will build a blog application with the following features:
1. RESTful API with Express.js and MongoDB
2. React front-end with component architecture
3. Full CRUD functionality for blog posts
4. User authentication and authorization
5. Advanced features like image uploads and comments

## Project Structure

```
mern-blog/
├── client/                 # React front-end
│   ├── public/             # Static files
│   ├── src/                # React source code
│   │   ├── components/     # Reusable components
│   │   ├── pages/          # Page components
│   │   ├── hooks/          # Custom React hooks
│   │   ├── services/       # API services
│   │   ├── context/        # React context providers
│   │   └── App.jsx         # Main application component
│   └── package.json        # Client dependencies
├── server/                 # Express.js back-end
│   ├── config/             # Configuration files
│   ├── controllers/        # Route controllers
│   ├── models/             # Mongoose models
│   ├── routes/             # API routes
│   ├── middleware/         # Custom middleware
│   ├── utils/              # Utility functions
│   ├── server.js           # Main server file
│   └── package.json        # Server dependencies
└── README.md               # Project documentation
```

## Setup Instructions

1. Make sure you have Node.js (v18+) and MongoDB installed.
2. Clone this repository:
   ```
   git clone <your-repo-url>
   cd week-4-mern-integration-assignment-cecilgachie
   ```
3. Install server dependencies:
   ```
   cd server
   npm install
   ```
4. Install client dependencies:
   ```
   cd ../client
   npm install
   ```
5. Set up environment variables as described in the `.env.example` files in both `client` and `server` folders.
6. Start the development servers:
   ```
   # In the server directory
   npm run dev

   # In the client directory (in a new terminal)
   npm run dev
   ```

## API Documentation

### Blog Posts
- `GET /api/posts` - Get all blog posts
- `GET /api/posts/:id` - Get a specific blog post
- `POST /api/posts` - Create a new blog post
- `PUT /api/posts/:id` - Update an existing blog post
- `DELETE /api/posts/:id` - Delete a blog post

### Categories
- `GET /api/categories` - Get all categories
- `POST /api/categories` - Create a new category

> Add details about request/response bodies as you implement them.

## Features Implemented
- [ ] RESTful API for blog posts and categories
- [ ] CRUD operations for blog posts
- [ ] React front-end with routing
- [ ] User authentication (registration, login, protected routes)
- [ ] Image uploads for blog posts
- [ ] Pagination, search, and filtering
- [ ] Comments on blog posts
- [ ] Optimistic UI updates
- [ ] Error and loading state handling

> Mark the features you have completed with an `x`.

## Screenshots

> Add screenshots of your working application here. For example:

![Home Page](screenshots/home.png)
![Post View](screenshots/post.png)

## Resources

- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://react.dev/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [Mongoose Documentation](https://mongoosejs.com/docs/) 