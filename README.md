# Notflix

<p align="center">
  <img src=".github/images/notflix-logo.png" alt="Notflix Logo" width="300">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white" alt="Blazor">
  <img src="https://img.shields.io/badge/Entity%20Framework%20Core-512BD4?style=for-the-badge&logo=.net&logoColor=white" alt="Entity Framework Core">
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite">
  <img src="https://img.shields.io/badge/TMDb%20API-01D277?style=for-the-badge&logo=themoviedatabase&logoColor=white" alt="TMDb API">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge" alt="C#">
</p>

## About

Notflix is a movie browsing application built with Blazor and Entity Framework Core. This project was developed during a two-week college assignment by Juwan Jouma and Joulian Alsuliman.

**Disclaimer:** This project has no affiliation with Netflix and was created solely for educational purposes.

## Features

- Browse popular and trending movies
- Search for movies by title
- View detailed movie information
- User authentication system
- Favorite movies functionality
- Responsive design

## Technologies

- **Blazor**: Web framework for building interactive web UIs using C#
- **Bootstrap**: Front-end framework for responsive design
- **Entity Framework Core**: ORM for database operations
- **TMDb API**: The Movie Database API for fetching movie data
- **SQLite**: Lightweight database for storing user information
- **Blazored.LocalStorage/SessionStorage**: For client-side storage
- **EmailService**: For handling email communications including verification and password reset
- **BCrypt.Net**: For secure password hashing

## Getting Started

### Prerequisites

- .NET 6.0 SDK or later
- Visual Studio 2022 or Visual Studio Code

### Installation

1. Clone the repository
2. Open the solution in Visual Studio
3. Restore NuGet packages
4. Run the application

## See It In Action

<p align="center">
  <img src=".github/images/notflix-main-page.png" alt="Main Page" width="800">
  <br>
  <em>Main Page - Browse trending movies</em>
</p>

<p align="center">
  <img src=".github/images/notflix-main-page-genres.png" alt="Movie Genres" width="800">
  <br>
  <em>Browse movies by genres</em>
</p>

<p align="center">
  <img src=".github/images/notflix-main-page-genres-horror.png" alt="Horror Genre" width="800">
  <br>
  <em>Horror genre selection</em>
</p>

<p align="center">
  <img src=".github/images/notflix-main-page-search.png" alt="Search Functionality" width="800">
  <br>
  <em>Search for movies by title</em>
</p>

<p align="center">
  <img src=".github/images/notflix-main-page-trailer.png" alt="Movie Trailer" width="800">
  <br>
  <em>Watch movie trailers</em>
</p>

<p align="center">
  <img src=".github/images/notflix-registration.png" alt="Registration Page" width="800">
  <br>
  <em>User registration</em>
</p>

<p align="center">
  <img src=".github/images/notflix-settings.png" alt="Settings Page" width="800">
  <br>
  <em>User settings</em>
</p>

## Project Structure

- **BlazorApp**: Main Blazor Server application
  - **DB**: Database context and models
  - **Models**: Data transfer objects
  - **Pages**: Razor pages for the application
  - **Services**: Business logic and API services
  - **Shared**: Reusable Razor components

- **NotflixApp**: Desktop wrapper application

## Contributors

<p align="center">
  <a href="https://github.com/The5TiM"><img src="https://img.shields.io/badge/The5TiM%20|%20Juwan%20Jouma-181717?style=for-the-badge&logo=github" alt="The5TiM | Juwan Jouma" /></a>
  <a href="https://github.com/JoulianALS"><img src="https://img.shields.io/badge/JoulianALS%20|%20Joulian%20Alsuliman-181717?style=for-the-badge&logo=github" alt="JoulianALS | Joulian Alsuliman" /></a>
</p>
