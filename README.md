This repository consists of two main components: the backend API and the frontend UI, structured into two separate directories:

MoviesAPI (Backend APIs)
This folder contains the backend APIs developed in C#. To run these APIs, please ensure you have the following installed:

.NET SDK: Required to run the code on IIS Express. You can download it from the official .NET website.

NuGet Packages: The following packages are necessary for the project. You can add them using the dotnet CLI:

Microsoft.EntityFrameworkCore
Microsoft.EntityFrameworkCore.Design
Npgsql.EntityFrameworkCore.PostgreSQL

dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Npgsql.EntityFrameworkCore.PostgreSQL


movie-dataset-ui (Frontend UI)
This folder contains the UI files and a backend folder named movie-api-proxy for the frontend.

Running the Frontend:

Navigate to the movie-dataset-ui directory.
Run the following command in the terminal to start the frontend server:

npm start

Running the Backend Proxy:

Navigate to the movie-api-proxy directory within movie-dataset-ui:

cd movie-api-proxy

Start the API server with:

node apiserver.js
