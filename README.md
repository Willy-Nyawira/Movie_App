# MvcMovie Application

MvcMovie is a simple ASP.NET Core MVC web application that demonstrates the core concepts of the Model-View-Controller pattern in the .NET framework. This project is part of the official Microsoft tutorials for learning ASP.NET Core MVC.

## Features

- **Movie Management**: Add, edit, delete, and list movies.
- **Search**: Search movies by title or genre.
- **Validation**: Form validation for movie details.
- **Responsive Design**: A simple, responsive UI.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 5.0 or later)
- [Visual Studio](https://visualstudio.microsoft.com/) (2022 recommended) or Visual Studio Code
- SQL Server or SQLite for database

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/YourUsername/MvcMovie.git
cd MvcMovie
```

### 2. Set Up the Database

By default, the project uses SQLite. To use SQL Server or another database, update the connection string in `appsettings.json`.

```json
"ConnectionStrings": {
  "MvcMovieContext": "Data Source=MvcMovie.db"
}
```

### 3. Run the Application

#### Using Visual Studio

1. Open the solution file (`MvcMovie.sln`) in Visual Studio.
2. Set the MvcMovie project as the startup project.
3. Press `F5` to run the application.

#### Using .NET CLI

```bash
dotnet restore
dotnet build
dotnet run
```

### 4. Access the Application

Open your web browser and navigate to `http://localhost:5000`.

## Project Structure

- **Controllers**: Contains the application's controllers.
- **Models**: Contains the data models and data access logic.
- **Views**: Contains the Razor views for the application's UI.
- **wwwroot**: Contains static files like CSS, JavaScript, and images.

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.


You can adapt this README to fit the specifics of your implementation or additional features you may have added to the project.
