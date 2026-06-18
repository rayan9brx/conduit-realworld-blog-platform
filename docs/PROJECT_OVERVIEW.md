# Project Overview

## Idea

This project is a full-stack blog platform similar to Medium. Users can create accounts, write articles, edit articles, follow article feeds, comment on posts, favorite posts, search for content, and manage their profile.

The goal was not only to build features, but also to practice a realistic software-development workflow: backend API work, frontend integration, testing, debugging, database migrations, and iterative development across multiple milestones.

## Architecture

The project is structured as a mono-repository with three applications:

```text
apps/dotnet   -> Backend REST API
apps/vue3     -> Web frontend
apps/flutter  -> Flutter frontend
```

The backend is responsible for authentication, persistence, domain logic, image uploads, article management, user management, comments, favorites, search, and statistics. The frontends consume the backend API and provide the user interface.

## Key Learning Outcomes

- Working with a larger existing codebase
- Understanding and extending a layered backend architecture
- Implementing REST API endpoints in .NET
- Working with Entity Framework Core migrations
- Connecting Vue and Flutter frontends to a backend API
- Adding tests for new functionality
- Debugging cross-stack issues between backend and frontend
- Presenting a university milestone project as a professional portfolio project

## Important Implemented Areas

### Authentication and User Management

The project includes registration, login, JWT-based authentication, profile loading, profile updates, and password-change logic.

### Articles and Comments

Users can create, edit, view, comment on, and favorite articles. Article data is mapped between backend entities and API models.

### Search and Statistics

Search functionality and search-count/statistic handling were added during the milestone development.

### Image Uploads

The backend supports image upload endpoints. The frontends include UI logic for selecting and uploading profile images and article images.

### Markdown Support

Markdown rendering was added so article content can be displayed in a formatted way. Editing screens include preview functionality.
