# SecureChat Project Setup

Welcome to SecureChat! Follow these steps to install the required dependencies, configure the project, and start the server.

---

## Prerequisites

Before starting, ensure you have the following installed:

1. **Node.js**: Download and install from [nodejs.org](https://nodejs.org/).
2. **Git**: Install Git for version control from [git-scm.com](https://git-scm.com/).  (Optional)

Once you have Node.js installed, you can proceed to install the required packages.

---

## Installation

### 1. Install Dependencies

In the project directory, install the required packages with the following commands:

#### npm install express
#### npm install socket.io
#### npm install crypto-js

These dependencies are essential for running the server and handling secure, real-time chat functionality.

---

### Running the Server

To start the server, use the following command in the terminal within the project directory:

#### node server.js

node server.js

This will launch the SecureChat server, making it accessible locally at -> http://localhost:3000

---

## Using the `Active Server.bat` File

For convenience, you can use the `Active Server.bat` file to start the server with a double-click. This batch file includes the command to run the server, but first, you’ll need to set up the correct path:

### Edit `Active Server.bat`:

1. Open `Active Server.bat` in a text editor.
2. Replace `<-----Current path----->` with the full path to your project directory. For example:

   ```bat
   cd C:\Users\YourUsername\Path\To\SecureChat
   node server.js
   ```

### Save and Execute
After editing and saving the file, double-click Active Server.bat to start the server automatically.

Now, the server will run without needing to open a terminal every time.
