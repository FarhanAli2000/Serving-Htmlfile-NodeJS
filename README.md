🌐 Simple Node.js HTML Server

This project is a basic HTTP server built using Node.js. The server reads an HTML file and serves it to the client upon request. This example demonstrates the fundamental use of Node.js's http and fs modules for serving static HTML content.

📌 Features

HTML File Serving:

Serves a single HTML file (server.html) as the default response.

Efficient File Handling: 

Reads the HTML file once and reuses it for every incoming request.

Basic HTTP Server Setup:

Includes a custom server configuration with Node.js.

🛠 Technologies Used

Node.js -

JavaScript runtime environment

HTTP Module - 

For creating the server and handling requests

File System (FS) Module - For reading the HTML file

📒 Usage

How It Works

The server:

Reads server.html once when starting.

Serves this file content for all incoming requests with a 200 OK status.

Accessing the Server

Open your browser and navigate to http://127.0.0.1:80.

The HTML content from server.html will be displayed.

🔍 Example Response

The server will respond with the content of server.html. Ensure server.html contains valid HTML to display in the browser.

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request to improve this server.

Created with ❤️ using Node.js. If you found this project helpful, please give it a ⭐!
