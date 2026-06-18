# Milestone History

This repository combines the four milestone submissions into one clean GitHub-ready project. The final code is based on Milestone 4, because it contains the most complete version of the application. Earlier milestones are represented here through the development history and changed-code overview.

## Milestone 1 — Foundation and Initial Fixes

Focus areas:

- Understanding the existing RealWorld/Conduit mono-repository
- Setting up backend and frontend projects
- Working with user, article, comment, and profile flows
- First backend/frontend fixes and integration work

Important areas touched:

```text
apps/dotnet/src/Api/Features/Articles/
apps/dotnet/src/Api/Features/Users/
apps/vue3/src/pages/
apps/vue3/src/components/
apps/flutter/lib/ui/
```

## Milestone 2 — Articles, Search, Statistics, and UI Integration

Focus areas:

- Extending article handling
- Adding or improving search-related functionality
- Updating backend data models and migrations
- Improving Vue and Flutter frontend integration
- Adding assignment/unit tests

Important areas touched:

```text
apps/dotnet/src/Api/Features/Articles/
apps/dotnet/src/Core/Entities/SearchCount.cs
apps/dotnet/src/Data/Migrations/
apps/vue3/src/pages/search.vue
apps/flutter/lib/ui/search_screen.dart
```

## Milestone 3 — Security, Password Handling, and Extended Frontend Work

Focus areas:

- Password-change functionality
- Password hashing/salt handling
- Search implementation improvements
- Vue settings/password page
- Flutter password-change screen
- Additional backend and frontend tests

Important areas touched:

```text
apps/dotnet/src/Api/Utils/PasswordHasher.cs
apps/dotnet/src/Core/Dto/ChangePasswordDto.cs
apps/dotnet/src/Data/Migrations/*AddSaltToUser*
apps/vue3/src/pages/settings/password.vue
apps/flutter/lib/ui/change_password/
```

## Milestone 4 — Image Uploads and Markdown Features

Focus areas:

- Profile image upload in backend and frontends
- Article image upload support
- Article-image database model and migration
- Markdown rendering for articles
- Markdown preview while editing
- Cypress/unit/widget tests for new functionality

Important areas touched:

```text
apps/dotnet/src/Api/Features/Profiles/
apps/dotnet/src/Api/Features/Articles/
apps/dotnet/src/Core/Entities/ArticleImage.cs
apps/dotnet/src/Data/Migrations/*AddArticleImages*
apps/vue3/src/components/MarkdownRenderer.vue
apps/vue3/src/pages/article/components/ArticleForm.vue
apps/flutter/lib/ui/global/markdown_preview.dart
apps/flutter/lib/ui/profile/profile_screen.dart
```
