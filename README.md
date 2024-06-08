# User and Admin Panel Project

## Table of Contents
- [Project Description](#project-description)
- [Technologies Used](#technologies-used)
- [Features](#features)
  - [Admin Panel](#admin-panel)
  - [User Panel](#user-panel)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Description

This project is a web application that features separate panels for users and admins. The admin panel allows administrators to manage users, missions, skills, mission themes, and approve mission applications. The user panel enables users to view available missions, apply for missions, and update their personal details.

## Technologies Used
- **Frontend:** Angular
- **Backend:** .NET Core
- **Database:** PostgreSQL Server

## Features

### Admin Panel
- **Add User:** Admins can create new user accounts.
- **Add New Mission:** Admins can create and manage missions.
- **Add Mission Skills:** Admins can add new Mission skills that can be linked to missions and users.
- **Add Mission Theme:** Admins can add themes to categorize missions.
- **Approve Mission Applications:** Admins can view and approve/reject mission applications submitted by users.

### User Panel
- **View Available Missions:** Users can browse and view details of all available missions.
- **Apply for Missions:** Users can apply to participate in missions.
- **Update User Details:** Users can update their personal information and profile.

## Installation

### Prerequisites
- Node.js and npm
- Angular CLI
- .NET SDK
- SQL Server

### Backend Setup
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yourproject.git
    ```
2. Navigate to the backend directory:
    ```sh
    cd yourproject/backend
    ```
3. Restore the .NET dependencies:
    ```sh
    dotnet restore
    ```
4. Update the database connection string in `appsettings.json`.
5. Run the migrations to set up the database:
    ```sh
    dotnet ef database update
    ```
6. Start the backend server:
    ```sh
    dotnet run
    ```

### Frontend Setup
1. Navigate to the frontend directory:
    ```sh
    cd yourproject/frontend
    ```
2. Install the Angular dependencies:
    ```sh
    npm install
    ```
3. Start the Angular development server:
    ```sh
    ng serve
    ```

## Usage
- Access the application by navigating to `http://localhost:4200` in your web browser.
- Admins can log in to the admin panel to manage users and missions.
- Users can log in to the user panel to view and apply for missions and update their profile.

## Contributing
We welcome contributions from the community! If you're interested in contributing to this project, please follow these steps:

1. **Fork the Repository:**
   - Click the "Fork" button at the top right corner of this repository page to create a copy of the repository under your own GitHub account.

2. **Clone the Forked Repository:**
   - Clone your forked repository to your local machine:
     ```sh
     git clone https://github.com/yourusername/yourforkedrepository.git
     ```

3. **Create a New Branch:**
   - Create a new branch for your feature or bug fix:
     ```sh
     git checkout -b feature/your-feature-name
     ```

4. **Make Your Changes:**
   - Make your changes to the codebase.

5. **Commit Your Changes:**
   - Commit your changes with a descriptive commit message:
     ```sh
     git add .
     git commit -m "Add description of your changes"
     ```

6. **Push Your Changes:**
   - Push your changes to your forked repository:
     ```sh
     git push origin feature/your-feature-name
     ```

7. **Submit a Pull Request:**
   - Go to the original repository and click the "New Pull Request" button.
   - Select your branch from the head repository and the base repository.
   - Provide a clear description of your changes and submit the pull request.


### Issues
If you find a bug or have a feature request, please open an issue on GitHub. Be sure to include a clear title and description, as well as any relevant information or screenshots.

### Contact
If you have any questions or need further assistance, feel free to contact the project maintainers:
- **Project Maintainer:** [Saurav Gheewala](mailto:sg.saurav@gmail.com)

We appreciate your interest in contributing and look forward to your involvement in improving this project!

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
