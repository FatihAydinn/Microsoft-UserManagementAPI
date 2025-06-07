# UserManagementAPI

## What is this?

A simple ASP.NET Core Web API for managing users.  
Supports basic operations: add, get, update, and delete users.  

Data is stored in memory for demo purposes.

## Features

- CRUD endpoints for users  
- Simple middleware for logging, error handling, and a basic auth check on `/unauthorized` path  
- Basic validation to prevent invalid user data

## How to run?

1. Clone this repo  
2. Run `dotnet run` in the project folder  
3. Test the API with Postman or curl

## About Copilot

I used Microsoft Copilot to help write the code faster, especially for scaffolding controllers and middleware.  
It suggested useful code snippets but I manually reviewed and fixed some parts, especially validation and error handling.  
Overall, Copilot saved time but I had to be careful with its suggestions.

---

