# dotnet-framework-projects

Curated collection of desktop applications developed in C# with .NET Framework and Windows Forms.

## Description

dotnet-framework-projects showcases practical desktop applications built on .NET Framework. The collection spans interactive desktop games with image comparisons, school productivity systems with user authentication, role-based dashboards, and media integration, demonstrating user interface engineering, event handling, and Entity Framework data persistence.

## Technologies

- **Language:** C#
- **Platform:** .NET Framework 4.7.2
- **UI Framework:** Windows Forms (WinForms)
- **Data Persistence:** Entity Framework (Database First / EDMX)
- **Database:** SQL Server / LocalDB
- **IDE:** Visual Studio

## Project Structure

```text
dotnet-framework-projects/
├── ListarNofiticacoes/      # Notification feed and alerts display
├── LoginCadastro/           # User authentication and registration module
├── LoginHomeUsuario/        # User session entry and home screen navigation
├── ProvaFutebol2.0/         # Soccer tournament and match management system
├── QualOPikomon/            # Interactive image-comparison guessing game with EF persistence
├── Taskool/                 # Student task organizer with color theming and authentication
├── TesteVideo1/             # Desktop multimedia and video playback integration
└── homeAdminUser/           # Role-based dashboard separating admin and user views
```

## Key Applications

- **QualOPikomon:** Interactive desktop game comparing user input against database-persisted entities using Entity Framework (`Model1.Context.cs`) and custom models (`Pikomon.cs`).
- **Taskool:** School task and productivity manager featuring authenticated user logins (`FormAutentica`), custom UI theming (`FormConfgColor`), and task scheduling.
- **homeAdminUser:** Demonstrates role-based interface access control, rendering customized dashboard actions based on administrative privileges.
- **ProvaFutebol2.0:** Tournament scheduling and statistics tracker for soccer matches.

## Setup & Execution

### Prerequisites
- Windows operating system (required for Windows Forms runtime)
- [Visual Studio 2022](https://visualstudio.microsoft.com/) with the **.NET desktop development** workload installed

### Running an Application
1. Clone the repository:
```bash
git clone https://github.com/EuKaueCMP/dotnet-framework-projects.git
```

2. Open the solution file of the target project in Visual Studio (e.g. `Taskool/Taskool final.sln` or `QualOPikomon/qualOPikomon.sln`) and press `F5` to build and execute.

## Developer

**Kauê Sérgio Campos**  
GitHub: [@EuKaueCMP](https://github.com/EuKaueCMP)
