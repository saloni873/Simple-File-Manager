# Simple Node.js File Manager
This is a basic web-based file manager built with **Node.js** and the **Express.js** framework. It uses Node's built-in **`fs` (File System)** module to perform file operations directly on the server. The application allows users to view, create, and rename text files through a simple web interface.

### Features
**View Files**: Lists all text files in the `files` directory.
**Read Content**: Displays the content of a selected file.
**Create New Files**: Allows users to create new `.txt` files with content.
**Rename Files**: Renames existing files.

### Technologies Used

**Node.js**: The JavaScript runtime environment.
**Express.js**: The web framework for handling routes and server logic.
**EJS**: The template engine used for rendering dynamic HTML pages.
**fs Module**: Node's native File System module.

### Getting Started

Follow these steps to get the project up and running on your local machine.

#### Prerequisites

Make sure you have Node.js and npm installed.

#### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

#### Running the Application

1.  **Start the server:**
    ```bash
    node app.js
    ```
    (Note: Change `app.js` to whatever your main server file is called, like `index.js` or `server.js`).

2.  **View the application:**
    Open your web browser and go to `http://localhost:3000`.
