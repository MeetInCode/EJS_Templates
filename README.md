# EJS_Templates
This is a simple Express.js application that serves static files and uses EJS as the templating engine. The application has three routes: the home page, the about page, and the contact page.
Sure! Here is a small README file for your Express.js application using EJS templates:

---

# Express.js Application with EJS Templates

This is a simple Express.js application that serves static files and uses EJS as the templating engine. The application has three routes: the home page, the about page, and the contact page.

## Installation

1. Clone the repository or download the source code.

2. Navigate to the project directory.

3. Install the dependencies using npm:
   ```sh
   npm install
   ```

## Running the Application

1. Start the server:
   ```sh
   node solution.js
   ```

2. Open your browser and navigate to `http://localhost:3000`.

## Project Structure

- `app.js`: The main application file where the Express server is configured.
- `public/`: Directory to store static files (e.g., CSS, JavaScript, images).
- `views/`: Directory to store EJS template files.

## Routes

- `GET /`: Renders the `index.ejs` template.
- `GET /about`: Renders the `about.ejs` template.
- `GET /contact`: Renders the `contact.ejs` template.

## Dependencies

- `express`: Fast, unopinionated, minimalist web framework for Node.js.
- `ejs`: Embedded JavaScript templating.

## License

This project is licensed under the MIT License.

---

Feel free to customize this README file to fit your specific needs.
