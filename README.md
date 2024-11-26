# Infinite Courses

[Live Link](https://infinite-courses-server.vercel.app/)

## Overview
This is the backend server for the Infinite Courses application, built with Express.js.

## Prerequisites
- Node.js (v14 or later)
- npm

## Installation

1. Clone the repository
```bash
git clone https://github.com/rakibul58/infinite-courses-server.git
cd infinite-courses-server
```

2. Install dependencies
```bash
npm install
```

## Running the Server

### Development Mode
```bash
npm start
```

## API Endpoints

- `GET /`: Basic server health check
- `GET /courses`: Retrieve all courses
- `GET /course/:id`: Retrieve a specific course by ID

## Dependencies
- Express.js
- CORS

## Configuration
- Default Port: 5000 (can be configured via environment variable PORT)

## Project Structure
- `index.js`: Main server file
- `data/courses.json`: Course data file

## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is open source. Please check the LICENSE file for details.
