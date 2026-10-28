# BookIt

BookIt is a full-stack booking application for small businesses, such as salons and tutors. It is being developed as a learning project using C#, ASP.NET Core, SQL Server, React, and TypeScript.

## Current progress

- ASP.NET Core Web API created using .NET 10.
- Health endpoint implemented at `GET /api/health`.
- Starter weather endpoint retained from the project template.

## Getting started

### Prerequisites

- .NET 10 SDK

### Run the API

From the repository root, run:

```powershell
dotnet run --project BookIt.Api
```

Use the local URL shown in the terminal and append `/api/health` to test the health endpoint.

## Planned features

- Business service listings
- Customer registration and authentication
- Appointment booking
- Availability management and prevention of double-booking
- SQL Server persistence
- React and TypeScript front end

## Status

Work in progress. This project is being built incrementally as part of a structured full-stack development learning path.