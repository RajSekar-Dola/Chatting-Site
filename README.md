# Chatting Site

This is a simple real-time chatting site built using Node.js and Socket.IO. The project includes a server file (`app.js`), configuration files (`package.json` and `package-lock.json`), and a `public` folder that contains the necessary frontend files.

## Features

- Real-time messaging
- Sound notification for new messages

## Project Structure

.
├── app.js
├── package.json
├── package-lock.json
└── public
├── ding.mp3
├── index.html
├── main.js
└── style.css

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) (v14.x or later)
- npm (Node Package Manager, comes with Node.js)

### Installation

1. Clone the repository:
    ```sh
    git clone <repository_url>
    ```
2. Navigate into the project directory:
    ```sh
    cd chatting-site
    ```
3. Install the dependencies:
    ```sh
    npm install
    ```

### Running the Application

To start the server, run:
```sh
node app.js
The server will start on http://localhost:4000.

Using the Chatting Site
Open your web browser and navigate to http://localhost:4000.
Enter your name and start chatting.
You will hear a sound notification (ding.mp3) whenever a new message is received.
File Descriptions
app.js: The main server file that sets up the server using Express and Socket.IO.
package.json: Lists the project dependencies and scripts.
package-lock.json: Contains the exact versions of dependencies installed.
public/index.html: The main HTML file that contains the structure of the chat interface.
public/main.js: The JavaScript file that handles the frontend logic and Socket.IO client-side code.
public/style.css: The CSS file for styling the chat interface.
public/ding.mp3: The sound file for new message notifications.
Built With
Node.js
Express
Socket.IO
