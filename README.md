# Lab-13: ASP.NET Core Web Application (VS Code)

## Project Overview

This project demonstrates how to build simple web applications using **ASP.NET Core, C#, and Visual Studio Code**. It includes basic Razor Pages examples such as forms, calculator, login validation, and dynamic content rendering.


## Objective

* Set up ASP.NET Core environment in VS Code
* Create and run web applications using C#
* Work with Razor Pages
* Handle user input using forms
* Build simple interactive web features

## Technologies Used

* ASP.NET Core (Razor Pages)
* C# Programming Language
* Visual Studio Code
* .NET SDK
* HTML/CSS (Basic Frontend)

## Requirements

Install the following before running the project:

* Visual Studio Code
* .NET SDK
* C# Extension (Microsoft)
* C# Dev Kit
* .NET Install Tool Extension
* Web Browser (Chrome/Edge)

## Setup Instructions

### 1. Check .NET Installation

```bash id="h3kq9d"
dotnet --version

### 2. Create Project

```bash id="p9xk2l"
dotnet new webapp -n MyFirstWebApp
cd MyFirstWebApp
code .

### 3. Run Project

```bash id="q1m8vz"
dotnet run

Open in browser:

https://localhost:5001


## Lab Activities

### 1. First Web Page

Modify `Pages/Index.cshtml`:

```html id="a1b2c3"
<h1>Welcome to ASP.NET Core in VS Code</h1>
<p>This is my first web application.</p>
```

### 2. Simple Form Input

Accept username and display greeting.

### 3. Simple Calculator

Add two numbers using Razor Pages and display result.

### 4. Login Validation

Validate username and password:

* Username: `admin`
* Password: `123`

## Student Tasks

* Student registration form (name + course)
* Find largest of two numbers
* Grade calculator (A, B, C, Fail)
* Feedback form (name + message)
* Digital clock using C#

## Features

* Simple Razor Pages examples
* Form handling in ASP.NET Core
* Beginner-friendly C# web development
* Real-time output in browser

## Output Preview

> Run the project and open browser at `https://localhost:5001` to view output pages.

## Author
Imad Khan

