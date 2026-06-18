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

## Portfolio Note

This repository is a cleaned public version of a four-milestone university project. The final code version is used as the main source, while the milestone history is documented in `docs/MILESTONE_HISTORY.md`.
