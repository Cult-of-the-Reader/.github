# Cult Of The Reader

A full-stack bookstore application built as a final project for the Professional Certificate in Web Application Development (IFCD0210).

## Live Demo

- **Main Page**: [https://cult-of-the-reader-rueo.onrender.com/](https://cult-of-the-reader-rueo.onrender.com/)
- **API Documentation**: [https://cult-of-the-reader.onrender.com/api-docs](https://cult-of-the-reader.onrender.com/api-docs)

---

*Note: Due to the free tier limitations on Render, the application may take a moment to load initially.*

## Project Overview

Cult Of The Reader is a complete bookstore application with user authentication, product catalog, shopping cart functionality, and user reviews.

## Technology Stack

### Backend
- **Node.js** server with Express
- **Dual Database Architecture**:
  - MongoDB Atlas (books collection)
  - MySQL via Aiven.io (user data, cart items, reviews)
- **Authentication** with JWT
- **API Documentation** using Swagger

### Frontend
- **React** with Vite as build tool
- **Context API** for state management
- **Responsive Design** for all devices
- **Component-based architecture**

## Key Features

- User registration and authentication
- Book catalog browsing
- Detailed book pages with descriptions
- Shopping cart functionality
- User profile management
- Book review system

## Application Structure

The application follows a clear client-server architecture:

### Server Side
- **Controllers**: Handle business logic for authentication, books, cart items, etc.
- **Models**: Define data structures for all entities
- **Routes**: API endpoints for client-server communication
- **Middleware**: Authentication and request processing

### Client Side
- **Pages**: Main application views (Home, Book, Login, Register, Profile)
- **Components**: Reusable UI elements organized by function
- **Contexts**: Global state management for authentication and cart
- **Services**: API communication layer

## Deployment

The application is deployed using Render:
- Backend as a Web Service
- Frontend as a Static Site

## Testing

The project includes:
- Jest tests for backend models
- JMeter templates for performance testing
- Cypress for frontend testing

## Documentation

- [Spanish Documentation (PDF)](./doc/documentacion.pdf)
- UML and ER diagrams available in the docs folder
- API documentation accessible via Swagger

## Acknowledgements

Development supervised by Davinia de La Rosa as part of the Professional Certificate in Web Application Development (IFCD0210).
