# Frontend, Backend on LocalHost 

## Code Resource Instructions

### Steps to Open Resources

#### 1. Set Up Required Software
- Install and configure **Visual Studio Code (VS Code)**.
- Download and install **Node.js**, then set it up in VS Code.

#### 2. Extract the GitHub Repository
- Download the ZIP file from GitHub and extract its contents.
- Open **VS Code** and navigate to the extracted folder named **"Dem-bigeo1-main"**.

#### 3. Run the Backend Server
- Open the **"Dem-bigeo1-main"** folder in **VS Code**.
- Launch a **new terminal** and execute the following commands:  
  ```sh
  cd bigeo-backend
  node server.js
  ```
- This will start the backend server.

#### 4. Verify Backend API
- Open a web browser and visit:  
  ```
  http://localhost:5000/api/shipments
  ```
- This will confirm that the backend is running correctly.

#### 5. Install Dependencies and Start the Frontend
- Open a **new terminal** in **VS Code** and run:  
  ```sh
  Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

  npm install
  ```
- You may see warnings like:  
  ```
  npm WARN deprecated
  npm WARN deprecated
  npm WARN deprecated
  npm WARN deprecated
  ```
  *(These warnings can be ignored.)*
- Once the installation is complete, start the application by running:  
  ```sh
  npm start
  ```
- The project will open automatically in your default web browser.

### Note
This is a **demo version**. Additional features will be implemented in the future. However, at this stage, further development is not possible. We appreciate your understanding.

And, To manually create a database on a local PostgreSQL instance using the guidance provided in the 'PostgreSQL-Database.pdf' file, execute the **CREATE DATABASE** command.






