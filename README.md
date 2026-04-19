# Library Management System - MVC Project

A comprehensive library management system built with ASP.NET Core MVC, featuring book management, author tracking, publisher management, hierarchical shelving (Floor → Shelf), and user role management.

## Tech Stack

- **.NET 9.0** - Core framework
- **ASP.NET Core MVC** - Web application framework
- **Entity Framework Core** - ORM for SQL Server
- **SQL Server** - Database
- **ASP.NET Core Identity** - Authentication & authorization
- **Bootstrap** - Frontend styling
- **Razor Views** - Server-side rendering

## Project Structure

## Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download)
- [SQL Server](https://www.microsoft.com/en-us/sql-server) (2019 or later)
- [SQL Server Management Studio](https://docs.microsoft.com/en-us/sql/ssms) (optional)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) or later (recommended)

## Installation

### 1. Clone the repository
```bash
git clone <your-repository-url>
cd MvcITIProject

Core Entities
Entity	Description
Book	Books with title, ISBN, publication date, price, quantity
Author	Authors with name, biography
Publisher	Publishers with name, address, contact
Category	Book categories/genres
Floor	Library floors (Ground, First, Second, etc.)
Shelf	Shelves belonging to floors
Borrowing	Book borrowing records with due dates
ApplicationUser	ASP.NET Core Identity users
UserPhone	Multiple phone numbers per user

Features
Book Management
Add, edit, delete, view books

Search and filter books

Assign multiple authors per book

Assign publisher and category

Track available quantity

View book details with location (Floor → Shelf)

Author Management
CRUD operations for authors

View all books by an author

Author search

Publisher Management
CRUD operations for publishers

View all books by publisher

Category Management
CRUD operations for categories

Organize books by genre

Location Management (Floor & Shelf)
Hierarchical location structure

Floors (Ground Floor, First Floor, etc.)

Shelves per floor

Assign books to specific shelf locations

Borrowing System
Borrow books with due dates

Return books

Track borrowing history

Overdue notifications

Maximum borrowing limits

User Management
User registration and login

Role-based access control

User profile management

Multiple phone numbers per user

Role Management
Create/delete roles

Assign roles to users

Role-based authorization

Admin/Staff/Member roles
