# BookList Razor — CRUD Application

An **ASP.NET Core Razor Pages** application for managing a book list — demonstrating full Create, Read, Update, and Delete operations using Razor Pages and Entity Framework Core.

## What it does

A simple book management web app. Users can view all books, add new entries, edit existing ones, and delete them. Each book has a title, author, and ISBN.

## Tech Stack

- **ASP.NET Core Razor Pages** (.NET)
- **Entity Framework Core** — Code-First with SQL Server

## Key Features

- Razor Pages for all CRUD operations (Index, Create, Edit)
- Book model with Title, Author, and ISBN fields
- EF Core migrations for database creation
- Separate `BookController` API endpoint

## Getting Started

1. Update the connection string in `appsettings.json`.
2. Apply migrations: `dotnet ef database update`
3. Run: `dotnet run --project BookListRazor`
