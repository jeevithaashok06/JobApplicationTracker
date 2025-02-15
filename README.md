# JobApplicationTracker

Job Application Tracker

Overview

This project is a simple Job Application Tracker built using ASP.NET Core Web API for the backend and Angular for the frontend. It allows users to add, update, and view job applications they have submitted.

Features

Backend (ASP.NET Core Web API)

Endpoints:

GET /applications - Retrieve all job applications.

GET /applications/{id} - Retrieve a specific application.

POST /applications - Add a new application.

PUT /applications/{id} - Update an application.

Uses Entity Framework Core (Code First) with an SQLite or In-Memory Database.

Implements Repository Pattern and Dependency Injection.

FluentValidation for request validation.

Swagger UI for API documentation.

CORS configured to allow frontend communication.

Frontend (Angular)

Features:

Display a list of job applications.

Add a new application.

Update application status (e.g., Interview/Offer/Rejected).

Uses HttpClient for API calls.

Reactive Forms for data entry.

Routing and Navigation for UI flow.

Basic Styling with Bootstrap.

Installation & Setup

Prerequisites

.NET 8 SDK

Node.js & Angular CLI

Backend Setup

Download the project
Install dependencies:

dotnet restore

Run the API:

dotnet run

Open Swagger UI at: localhost:8450

For front end

download node modules
