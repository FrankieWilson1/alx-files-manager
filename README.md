# Files Manager

## Description
Files Manager is a collaborative file management application built as an ALX backend project. It provides a platform for users to upload, manage, and view files with advanced features like user authentication via tokens, image thumbnail generation, and background job processing. The application demonstrates core concepts of modern web development including RESTful API design, database management, and asynchronous job processing.

## Features
- User authentication and token-based access control
- File upload and management functionality
- File listing and retrieval capabilities
- Image thumbnail generation for uploaded images
- Background job processing for asynchronous operations
- File permission and access control management

## Technologies Used
- **Backend Runtime**: Node.js with Express.js framework
- **Database**: MongoDB (NoSQL database for file data storage)
- **Caching**: Redis (in-memory data structure store)
- **Background Processing**: Bull (queue library for job handling)
- **Testing**: Mocha testing framework
- **Development Tools**: Nodemon (auto-restart), ESLint (code linting)
- **Utilities**: Image-thumbnail (thumbnail generation), Mime-types (MIME type handling).

## Installation
1. Clone the repository:
```bash
  git clone <repository-url>
```
2. Navigate to the project directory:
```bash
  cd files_manager
```
3. Install dependecies:
```bash
  npm install
```

## Usage

##### Start the server
To start the server, run:
```bash
  npm run startt-server
```

#### Start the worker
To start the background worker, run:
```bash
  npm run start-worker
```

#### Run Tests
To run tests, use:
```bash
  npm test
```

## API Endpoints
* #### POST /auth/login
  Authenticate user and recieve a token
* #### GET/files
  Retrieve a list of all files
* #### POST/files/upload
  Upload a new file
* #### GET/files/:id
  Permissions of specific file.
* #### GET/files/:id/thumbnail
  Generate and retrieve thumbnail for an image

## Requirements
* Ubuntu 18.04 LTS
* Node.js version 12.x.x
* Code is linted using ESLint.

## Linting
To check for linting issues, run:
```bash
npm run lint
```

## Authors

| Name             | GitHub Profile                                       | X Profile                                 |
|------------------|------------------------------------------------------|-------------------------------------------|
| Frank W.     Ugwu| [Frank Ugwu Williams](https://github.com/frankiewilson1) |  [@frankwilies](https://x.com/frankwilies)|
| Loubna           | [Loubna](https://github.com/Loubnaa1)      |  [@loubna](loubnaaddress)                 |

### Note
Migrated from early ALX backend specialization (2023–2024). Collaborative project with @Loubnaa1. Demonstrates full-stack JS skills: authentication, file handling, queuing with Bull, and NoSQL/Redis integration.

