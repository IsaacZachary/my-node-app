# Simple Web Server with Express.js

This Node.js application sets up a simple web server using Express.js. The application sets up a basic web server that listens for requests on a specified port and responds with a simple "Hello, World!" message when accessed through a web browser or API request.

## Application Structure

- **index.js**: 
  - Imports the Express.js framework and the dotenv package for managing environment variables.
  - Creates an instance of the Express application.
  - Specifies the port number to listen on, either from the environment variable or defaulting to port 3000.
  - Defines a route for the root URL ("/") that responds with the message "Hello, World!".
  - Starts the server, listening on the specified port.

- **package.json**: 
  - Contains metadata about the application, including its name, version, and description.
  - Specifies the main entry point of the application (index.js).
  - Defines a script named "start" that runs the application using the `node index.js` command.
  - Lists dependencies required for the application to run, including Express.js and dotenv.

- **.env**: 
  - Stores environment variables for the application, such as the port number. In this case, it sets the port to 3000.

- **.gitignore**: 
  - Specifies files and directories that should be ignored by Git, such as the `node_modules` directory and the `.env` file.

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/IsaacZachary/my-node-app.git
   ```

2. Navigate to the project directory:

   ```bash
   cd my-node-app
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

To start the server, run:

```bash
npm start
```

The server will start listening on the specified port (default: 3000). Open a web browser and navigate to `http://localhost:3000` to see the "Hello, World!" message.
```
