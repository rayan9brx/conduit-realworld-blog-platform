# Full-Stack Blog Platform — RealWorld Conduit

A full-stack blogging platform based on the RealWorld **Conduit** specification. The project was developed as a university software-development project in four milestones and cleaned into one portfolio-ready repository.

The application contains a **.NET 7 backend**, a **Vue 3 / TypeScript web frontend**, and a **Flutter frontend**. It demonstrates authentication, user profiles, article management, comments, favorites, search/statistics, password updates, profile image uploads, article image uploads, and Markdown rendering/preview.

## Tech Stack

| Area | Technologies |
|---|---|
| Backend | .NET 7, C#, Minimal APIs, Carter, Entity Framework Core, SQLite, JWT authentication |
| Web frontend | Vue 3, TypeScript, Vite, Pinia, Axios, Cypress/Vitest |
| Mobile/Web frontend | Flutter, Dart, BLoC-style state management |
| Testing | .NET unit tests, Vue tests/Cypress, Flutter widget tests |

## Repository Structure

```text
apps/
  dotnet/    # Backend API, domain entities, EF Core data layer, tests
  vue3/      # Vue 3 TypeScript frontend
  flutter/   # Flutter frontend
docs/
  PROJECT_OVERVIEW.md       # Clear explanation of the project idea and features
  MILESTONE_HISTORY.md      # How the project evolved across the 4 milestones
  CHANGED_CODE_FILES.md     # Important code files edited/added during the milestones
```

## Main Features

- User registration, login, JWT authentication, and profile management
- Article creation, editing, listing, favorites, comments, and tags
- Search functionality and article statistics
- Secure password update flow with password hashing/salt handling
- Profile image upload through a dedicated backend endpoint
- Article image upload and image URL handling
- Markdown rendering for articles
- Markdown preview while editing articles
- Vue and Flutter frontend integration with the backend API
- Unit and end-to-end tests for important features

## Implementation Highlights

### Backend

Important backend work is located in:

```text
apps/dotnet/src/Api/Features/Articles/
apps/dotnet/src/Api/Features/Profiles/
apps/dotnet/src/Api/Features/Search/
apps/dotnet/src/Api/Features/Users/
apps/dotnet/src/Core/Entities/
apps/dotnet/src/Data/
apps/dotnet/tst/
```

The backend includes endpoints for article operations, comments, favorites, profile image upload, article image upload, user management, password changes, and search/statistics. Entity Framework migrations extend the data model for search counts, password salt handling, and article images.

### Vue Frontend

Important Vue work is located in:

```text
apps/vue3/src/pages/
apps/vue3/src/components/
apps/vue3/src/api/
apps/vue3/src/stores/
apps/vue3/cypress/
```

The Vue frontend includes article rendering, editing forms, Markdown preview, settings/profile image support, search, password settings, API integration, and end-to-end tests.

### Flutter Frontend

Important Flutter work is located in:

```text
apps/flutter/lib/ui/
apps/flutter/lib/bloc/
apps/flutter/lib/repository/
apps/flutter/lib/services/
apps/flutter/test/
```

The Flutter frontend includes registration/login flows, profile updates, profile image upload, article UI, Markdown rendering, search, password update screens, and widget tests.

## Running the Project

### Backend

```bash
cd apps/dotnet
dotnet restore
dotnet build
dotnet run --project src/Api/Api.csproj
```

The API is expected to run locally on the configured backend port, commonly `http://localhost:8081` depending on the launch configuration.

### Vue Frontend

```bash
cd apps/vue3
npm install
npm run dev
```

### Flutter Frontend

```bash
cd apps/flutter
flutter pub get
flutter run -d chrome
```

## Tests

### Backend tests

```bash
cd apps/dotnet
dotnet test
```

### Vue tests

```bash
cd apps/vue3
npm install
npm run test
```

### Flutter tests

```bash
cd apps/flutter
flutter test
```

## What I Learned

Through this project, I gained practical experience in building a full-stack web application with a structured backend, modern frontend, and clear API communication between both parts.

Some of the main things I learned include:

- Designing and implementing RESTful APIs with ASP.NET Core
- Structuring a backend project using clean architecture principles
- Working with authentication and JWT-based user sessions
- Connecting a frontend application with backend API endpoints
- Managing user-related features such as profiles, articles, comments, and favorites
- Using TypeScript and Vue.js to build a modern user interface
- Understanding how frontend, backend, database, and mobile clients can work together in one larger software system
- Working with Git and GitHub during a multi-step development process
- Improving code organization, documentation, and project presentation for a professional portfolio

## Challenges and Improvements

During the project, one of the main challenges was understanding how the different parts of a full-stack application interact with each other. The backend, frontend, authentication system, and database all needed to work together correctly.

Another challenge was keeping the project organized while it was developed through multiple milestones. This helped me understand the importance of clean project structure, readable code, and good documentation.

In the future, I would like to improve this project by adding more automated tests, improving the UI/UX, adding better error handling, and deploying the application online so it can be tested directly in a browser.

## Why This Project Is Important to Me

This project was important for me because it gave me practical experience beyond theoretical university exercises. It helped me understand how real software projects are structured and how different technologies are combined to build a complete application.

It also strengthened my interest in full-stack development, backend APIs, clean architecture, and modern software engineering practices.
