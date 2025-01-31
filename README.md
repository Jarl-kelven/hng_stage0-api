# HNG Stage 0 Backend Task

This is a simple public API that returns basic information in JSON format.

## Setup Instructions

Follow these steps to set up and run the project locally on your machine.

Prerequisites
Before you begin, ensure you have the following installed:

Node.js (v16 or higher recommended)

npm (usually comes with Node.js)

Git (optional, for cloning the repository)

Step 1: Clone the Repository
Open your terminal or command prompt.

Run the following command to clone the repository:
```node
git clone https://github.com/yourusername/your-repo.git

```
Navigate to the project directory:

```node
cd your-repo
```
Step 2: Install Dependencies
Install the required dependencies by running:

```node
    npm install
```

Step 3: Set Up Environment Variables
Create a .env file in the root directory of the project.

Add the following environment variables to the .env file:

EMAIL=your-email@example.com
GITHUB_URL=https://github.com/yourusername/your-repo
PORT=3000
Replace your-email@example.com and https://github.com/yourusername/your-repo with your actual email and GitHub repository URL.

Step 4: Run the Project
Start the server by running:

```node 
    node index.js
```

The server will start on http://localhost:3000. You can test the API by visiting this URL in your browser or using a tool like curl or Postman.



---

## API Documentation

### Endpoint
- **GET** `/`

### Response Format
```json
{
  "email": "your-email@example.com",
  "current_datetime": "2025-01-30T09:30:00Z",
  "github_url": "https://github.com/yourusername/your-repo"
}
```

## Backlink
Here is the backlink related to the chosen programming language/stack:
- [HNG Node.js Developers Hiring Page](https://hng.tech/hire/nodejs-developers)
