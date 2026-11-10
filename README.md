# BicycleMushroomApp

A simple Windows Forms application built with C# and .NET. It combines two small educational tools:

- a login page
- a bicycle rental cost calculator
- a mushroom identification decision tree

## Features

### Login screen
- Secure-looking desktop login form
- Default credentials:
  - Username: `admin`
  - Password: `1234`

### Bicycle rental calculator
- Enter a start hour and end hour
- Validate input for range and format
- Calculate cost in RWF based on the selected time interval

### Mushroom identifier
- Ask a series of yes/no questions
- Narrow down the type of mushroom
- Show the final result as a message box

## Project structure

```text
BicycleMushroomApp/
├── Program.cs
├── LoginForm.cs
├── LoginForm.Designer.cs
├── ChooseForm.cs
├── ChooseForm.Designer.cs
├── BicycleForm.cs
├── BicycleForm.Designer.cs
├── MushroomForm.cs
├── MushroomForm.Designer.cs
├── BicycleMushroomApp.csproj
├── BicycleMushroomApp.slnx
├── .gitignore
└── README.md
```

## Requirements

- Windows operating system
- .NET 10 SDK
- Visual Studio 2022 or later recommended

## Run the app

From the project folder:

```powershell
cd "C:\Users\gad\Downloads\BicycleMushroomApp\BicycleMushroomApp"
dotnet run
```

Or from the repository root:

```powershell
dotnet run --project "C:\Users\gad\Downloads\BicycleMushroomApp\BicycleMushroomApp\BicycleMushroomApp.csproj"
```

## Build

```powershell
cd "C:\Users\gad\Downloads\BicycleMushroomApp\BicycleMushroomApp"
dotnet build
```

## Notes

This project is a beginner-friendly WinForms example and is intended for learning and demonstration purposes. It has a simple architecture with multiple forms and basic validation logic.
