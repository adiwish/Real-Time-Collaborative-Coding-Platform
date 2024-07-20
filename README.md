# Online Compiler

## Overview
The Online Compiler is a web application built using the MERN stack (MongoDB, Express.js, React, Node.js). It allows users to write, compile, and execute code in multiple programming languages directly in their web browser. The application supports real-time error detection and syntax highlighting, providing a seamless and interactive coding experience.

## Features
- **Multi-Language Support**: Write and compile code in various programming languages including C, C++, Java, Python, and JavaScript.
- **Real-Time Error Detection**: Identify and highlight syntax errors in real-time as you write code.
- **Syntax Highlighting**: Enjoy a visually rich coding environment with syntax highlighting for different programming languages.
- **User Authentication**: Secure login and registration system to save and manage user sessions.
- **Code Management**: Save, edit, and delete code snippets with ease.
- **Responsive Design**: Fully responsive user interface for optimal performance on desktop and mobile devices.

## Technologies Used
- **Frontend**: React, HTML, CSS, Bootstrap
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Code Execution Engine**: Docker, various language compilers/interpreters

## Installation

### Prerequisites
- Node.js
- MongoDB
- Docker

### Steps
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/online-compiler.git
   cd online-compiler
   ```

2. **Install dependencies**
   ```bash
   npm install
   cd client
   npm install
   cd ..
   ```

3. **Set up environment variables**
   Create a `.env` file in the root directory and add the following variables:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```

4. **Start MongoDB**
   Make sure your MongoDB server is running. You can start MongoDB using:
   ```bash
   mongod
   ```

5. **Start the Docker service**
   Ensure Docker is running on your machine. You can start Docker using:
   ```bash
   sudo systemctl start docker
   ```

6. **Start the application**
   ```bash
   npm run dev
   ```

   The frontend will run on `http://localhost:3000` and the backend on `http://localhost:5000`.

## Usage

### Create a New Code Snippet
1. Navigate to the homepage.
2. Click on the "New Code" button.
3. Select the programming language from the dropdown menu.
4. Enter your code in the editor.
5. Click "Run" to compile and execute the code.
6. View the output in the terminal window below the editor.
7. Click "Save" to store the code snippet in your account.

### Edit an Existing Code Snippet
1. Go to the "My Codes" section.
2. Select the code snippet you want to edit.
3. Make the necessary changes in the editor.
4. Click "Save Changes" to update the code snippet.

### Delete a Code Snippet
1. Go to the "My Codes" section.
2. Click on the "Delete" button next to the code snippet you want to remove.
3. Confirm the deletion in the popup dialog.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact
For any questions or suggestions, please contact [adityabarnwal16@example.com].

---
