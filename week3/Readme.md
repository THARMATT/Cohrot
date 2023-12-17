# Week 3 

## Fetch API

### Overview
The Fetch API is a modern JavaScript API for making network requests (HTTP), providing a flexible and powerful interface for handling asynchronous data retrieval.

### Async/Await
Introduced as a syntactic sugar for handling asynchronous code with the Fetch API, using `async` and `await` for improved readability.

## Authentication
Certainly! Here's a README.md template covering the topics of hashing, encryption, JSON Web Tokens (JWTs), and local storage:

```markdown
# Web Security Overview

## Hashing

Hashing is a fundamental technique used to secure sensitive information, such as passwords.

- **Definition:**
  - Hashing is the process of converting input data into a fixed-size string of characters, which is typically a hash code.
  - It is a one-way transformation, meaning it should not be reversible.

- **Usage:**
  - Commonly used for password storage in a secure manner.

## Encryption

Encryption is a method of securing data by converting it into a different format that is unreadable without a decryption key.

- **Definition:**
  - Encryption transforms data into a format that is not easily readable.
  - Two main types: symmetric (uses the same key for encryption and decryption) and asymmetric (uses a pair of public and private keys).

- **Usage:**
  - Protecting sensitive information during transmission or storage.

## JSON Web Tokens (JWTs)

JSON Web Tokens (JWTs) provide a compact, URL-safe means of representing claims between two parties.

- **Structure:**
  - Comprised of three parts: header, payload, and signature.
  - Typically used for authentication and authorization.

- **Usage:**
  - Often employed in web development for stateless authentication.

## Local Storage

Local Storage is a web storage solution that allows data to be stored and retrieved across browser sessions.

- **Characteristics:**
  - Stores data with no expiration time.
  - Limited to about 5 MB of data per domain.

- **Usage:**
  - Commonly used for client-side storage of non-sensitive data.


### Token-Based Authentication
Commonly uses JSON Web Tokens (JWTs) for secure authentication, often sent in the Authorization header of HTTP requests.

### Session-Based Authentication
Relies on server-side sessions to manage user authentication.

### Security Considerations
- Use HTTPS for secure communication.
- Set token expiration times for enhanced security.
- Safely store tokens in the browser using options like HTTP-only cookies or secure storage mechanisms.

## Databases

### Relational Databases

#### Examples
- MySQL
- PostgreSQL
- SQLite

#### Key Concepts
- Tables
- Rows
- Columns
- Primary Keys
- Foreign Keys

### NoSQL Databases

#### Examples
- MongoDB
- Redis
- Cassandra

#### Key Concepts
- Documents
- Collections
- Indexing

### MongoDB and Mongoose

#### MongoDB
- Document-oriented NoSQL database.
- Stores data in flexible, JSON-like BSON documents.

#### Mongoose
- Object-Document Mapping (ODM) library for MongoDB with Node.js.
- Simplifies data modeling, validation, and interaction with MongoDB.

#### Key Mongoose Concepts
- Defining Schemas and Models.
- Connecting to MongoDB.
- Creating, Querying, and Updating Documents.
- Middleware and Hooks for advanced functionality.

---
