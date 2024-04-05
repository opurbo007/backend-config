# Express Backend Config

**Version:** 1.0.0  
**Author:** Opu Pal

## Description

This project provides a professional backend structure using Express.js, MongoDB, and related technologies. It aims to streamline the development process by offering a solid foundation for building scalable and maintainable backend applications.

## Features

- **Express.js**: Fast, unopinionated, minimalist web framework for Node.js.
- **MongoDB**: A leading NoSQL database, providing scalability and flexibility.
- **bcrypt**: Library for hashing passwords securely.
- **cookie-parser**: Middleware for parsing cookies in Express.
- **cors**: Middleware for enabling Cross-Origin Resource Sharing (CORS).
- **dotenv**: Module for loading environment variables from a .env file.
- **jsonwebtoken**: Implementation of JSON Web Tokens (JWT) for user authentication.
- **mongoose**: Elegant MongoDB object modeling for Node.js.
- **mongoose-aggregate-paginate-v2**: Mongoose plugin for pagination and aggregation support.

## Installation

1. Clone the repository: `git clone [repository_url]`
2. Install dependencies: `npm install`

## Usage

### Development

To run the server in development mode with auto-reloading:

```bash
npm run dev
```

This command utilizes nodemon for auto-restarting the server upon file changes.

### Production

To start the server in production mode:

```bash
npm start
```

## Configuration

This project uses the `dotenv` module for managing environment variables. Create a `.env` file in the root directory and define your environment variables there. Here's an example:

```
PORT=3000
MONGODB_URI=mongodb://localhost:27017/my_database
SECRET_KEY=my_secret_key
```

## License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for details.
