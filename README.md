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
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
