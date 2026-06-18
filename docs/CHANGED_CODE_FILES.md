# Changed / Added Code Files

This document highlights the code files that changed across the four milestones. It is useful when showing the project in a portfolio because it points recruiters or reviewers to the parts where the implementation work happened.

The public repository uses the final Milestone 4 code as the main codebase, because it contains the completed version.

## Milestone 1 → Milestone 2

**Changed or added code/config files:** 49

### Backend API and domain/data layer

- `apps/dotnet/src/Api/Features/Articles/ArticlesHandler.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesMapper.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModel.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModule.cs`
- `apps/dotnet/src/Api/Features/Articles/IArticlesHandler.cs`
- `apps/dotnet/src/Api/Features/Users/UserHandler.cs`
- `apps/dotnet/src/Api/Program.cs`
- `apps/dotnet/src/Core/Dto/ArticleDto.cs`
- `apps/dotnet/src/Core/Entities/Article.cs`
- `apps/dotnet/src/Core/Entities/ArticleFavorite.cs`
- `apps/dotnet/src/Core/Entities/SearchCount.cs`
- `apps/dotnet/src/Core/Repositories/IConduitRepository.cs`
- `apps/dotnet/src/Data/Contexts/ConduitContext.cs`
- `apps/dotnet/src/Data/Data.csproj`
- `apps/dotnet/src/Data/Migrations/20250509092357_conductStatisticMigration.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250509092357_conductStatisticMigration.cs`
- `apps/dotnet/src/Data/Migrations/ConduitContextModelSnapshot.cs`
- `apps/dotnet/src/Data/Migrations/conductStatisticMigration.sql`
- `apps/dotnet/src/Data/Services/ConduitRepository.cs`

### Vue frontend

- `apps/vue3/auto-imports.d.ts`
- `apps/vue3/package.json`
- `apps/vue3/src/components/ArticleList.vue`
- `apps/vue3/src/components/AuthPage.vue`
- `apps/vue3/src/layouts/components/TheHeader.vue`
- `apps/vue3/src/pages/article/components/ArticleForm.vue`
- `apps/vue3/src/pages/article/components/CommentList.vue`
- `apps/vue3/src/pages/search.vue`
- `apps/vue3/src/pages/settings/index.vue`
- `apps/vue3/src/stores/useUserStore.ts`
- `apps/vue3/typed-router.d.ts`
- `apps/vue3/vite.config.ts`

### Flutter frontend

- `apps/flutter/lib/bloc/all_articles_bloc/all_articles_bloc.dart`
- `apps/flutter/lib/bloc/profile_bloc/profile_bloc.dart`
- `apps/flutter/lib/bloc/register_bloc/register_bloc.dart`
- `apps/flutter/lib/config/constant.dart`
- `apps/flutter/lib/navigator/route.dart`
- `apps/flutter/lib/repository/all_article_repo.dart`
- `apps/flutter/lib/ui/add_article/add_article_screen.dart`
- `apps/flutter/lib/ui/base/drawer.dart`
- `apps/flutter/lib/ui/comments/comments_screen.dart`
- `apps/flutter/lib/ui/search_screen.dart`

### Tests

- `apps/dotnet/tst/Assignment.Tests/Assignment1.cs`
- `apps/dotnet/tst/Assignment.Tests/Assignment2.cs`

### Build/config/docs

- `.github/classroom/autograding.json`
- `.github/workflows/docs.yml`
- `.github/workflows/dotnet.yml`
- `.github/workflows/sql.yml`
- `.github/workflows/vue3.yml`
- `docs/produced_users.json`

## Milestone 2 → Milestone 3

**Changed or added code/config files:** 82

### Backend API and domain/data layer

- `apps/dotnet/SaltMigration.sql`
- `apps/dotnet/conductStatisticMigration.sql`
- `apps/dotnet/src/Api/Features/Articles/ArticlesHandler.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesMapper.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModel.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModule.cs`
- `apps/dotnet/src/Api/Features/Articles/IArticlesHandler.cs`
- `apps/dotnet/src/Api/Features/Search/ISearchHandler.cs`
- `apps/dotnet/src/Api/Features/Search/SearchHandler.cs`
- `apps/dotnet/src/Api/Features/Search/SearchModel.cs`
- `apps/dotnet/src/Api/Features/Search/SearchModule.cs`
- `apps/dotnet/src/Api/Features/Users/IUserHandler.cs`
- `apps/dotnet/src/Api/Features/Users/UserHandler.cs`
- `apps/dotnet/src/Api/Features/Users/UserModule.cs`
- `apps/dotnet/src/Api/Program.cs`
- `apps/dotnet/src/Api/Utils/PasswordHasher.cs`
- `apps/dotnet/src/Core/Dto/ArticleDto.cs`
- `apps/dotnet/src/Core/Dto/ChangePasswordDto.cs`
- `apps/dotnet/src/Core/Dto/SearchDto.cs`
- `apps/dotnet/src/Core/Dto/UserDto.cs`
- `apps/dotnet/src/Core/Entities/Article.cs`
- `apps/dotnet/src/Core/Entities/ArticleFavorite.cs`
- `apps/dotnet/src/Core/Entities/SearchCount.cs`
- `apps/dotnet/src/Core/Entities/User.cs`
- `apps/dotnet/src/Core/Repositories/IConduitRepository.cs`
- `apps/dotnet/src/Data/Contexts/ConduitContext.cs`
- `apps/dotnet/src/Data/Data.csproj`
- `apps/dotnet/src/Data/Migrations/20250425102547_ConductStatisticMigration.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250425102547_ConductStatisticMigration.cs`
- `apps/dotnet/src/Data/Migrations/20250509092357_conductStatisticMigration.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250509092357_conductStatisticMigration.cs`
- `apps/dotnet/src/Data/Migrations/20250522142954_AddSaltToUser.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250522142954_AddSaltToUser.cs`
- `apps/dotnet/src/Data/Migrations/ConduitContextModelSnapshot.cs`
- `apps/dotnet/src/Data/Migrations/MissingMigration.sql`
- `apps/dotnet/src/Data/Migrations/conductStatisticMigration.sql`
- `apps/dotnet/src/Data/Services/ConduitRepository.cs`

### Vue frontend

- `apps/vue3/cypress.config.ts`
- `apps/vue3/package.json`
- `apps/vue3/src/api/index.ts`
- `apps/vue3/src/components/ArticleList.vue`
- `apps/vue3/src/components/ArticleToggle.vue`
- `apps/vue3/src/layouts/components/TheHeader.vue`
- `apps/vue3/src/pages/index/components/SearchField.vue`
- `apps/vue3/src/pages/index/index.vue`
- `apps/vue3/src/pages/search.vue`
- `apps/vue3/src/pages/settings/index.vue`
- `apps/vue3/src/pages/settings/password.vue`
- `apps/vue3/src/types/index.d.ts`
- `apps/vue3/typed-router.d.ts`

### Flutter frontend

- `apps/flutter/lib/bloc/profile_bloc/profile_bloc.dart`
- `apps/flutter/lib/bloc/register_bloc/register_bloc.dart`
- `apps/flutter/lib/bloc/search_bloc/search_bloc.dart`
- `apps/flutter/lib/bloc/search_bloc/search_event.dart`
- `apps/flutter/lib/bloc/search_bloc/search_state.dart`
- `apps/flutter/lib/config/constant.dart`
- `apps/flutter/lib/main.dart`
- `apps/flutter/lib/model/profile_model.dart`
- `apps/flutter/lib/navigator/route.dart`
- `apps/flutter/lib/repository/all_article_repo.dart`
- `apps/flutter/lib/repository/auth_repo.dart`
- `apps/flutter/lib/services/user_client.dart`
- `apps/flutter/lib/ui/base/drawer.dart`
- `apps/flutter/lib/ui/change_password/change_password_screen.dart`
- `apps/flutter/lib/ui/global/global.dart`
- `apps/flutter/lib/ui/register/register_screen.dart`
- `apps/flutter/lib/ui/search_screen.dart`
- `apps/flutter/lib/ui/search_screen/search_screen.dart`
- `apps/flutter/lib/ui/splash/splash_screen.dart`
- `apps/flutter/pubspec.yaml`

### Tests

- `apps/dotnet/tst/Assignment.Tests/Assignment2.cs`
- `apps/dotnet/tst/Unit.Tests/Assignment_3_Test_Cases/PasswordHashingTest.cs`
- `apps/flutter/test/test_registration.dart`
- `apps/vue3/cypress/support/commands.ts`
- `apps/vue3/cypress/support/e2e.ts`
- `apps/vue3/tests/end2end.cy.ts`

### Build/config/docs

- `.github/workflows/docs.yml`
- `.github/workflows/dotnet.yml`
- `.github/workflows/flutter.yml`
- `.github/workflows/guard.yml`
- `.github/workflows/sql.yml`
- `.github/workflows/vue3.yml`

## Milestone 3 → Milestone 4

**Changed or added code/config files:** 74

### Backend API and domain/data layer

- `apps/dotnet/SaltMigration.sql`
- `apps/dotnet/src/Api/Features/Articles/ArticlesMapper.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModel.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesModule.cs`
- `apps/dotnet/src/Api/Features/Profiles/IProfilesHandler.cs`
- `apps/dotnet/src/Api/Features/Profiles/ProfilesHandler.cs`
- `apps/dotnet/src/Api/Features/Profiles/ProfilesModule.cs`
- `apps/dotnet/src/Api/Features/Users/IUserHandler.cs`
- `apps/dotnet/src/Api/Features/Users/UserHandler.cs`
- `apps/dotnet/src/Api/Features/Users/UserModule.cs`
- `apps/dotnet/src/Api/Program.cs`
- `apps/dotnet/src/Api/Utils/PasswordHasher.cs`
- `apps/dotnet/src/Core/Dto/ChangePasswordDto.cs`
- `apps/dotnet/src/Core/Dto/UserDto.cs`
- `apps/dotnet/src/Core/Entities/Article.cs`
- `apps/dotnet/src/Core/Entities/ArticleImage.cs`
- `apps/dotnet/src/Core/Entities/User.cs`
- `apps/dotnet/src/Data/Contexts/ConduitContext.cs`
- `apps/dotnet/src/Data/Migrations/20250522142954_AddSaltToUser.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250522142954_AddSaltToUser.cs`
- `apps/dotnet/src/Data/Migrations/20250622085717_AddArticleImages.Designer.cs`
- `apps/dotnet/src/Data/Migrations/20250622085717_AddArticleImages.cs`
- `apps/dotnet/src/Data/Migrations/ConduitContextModelSnapshot.cs`
- `apps/dotnet/src/Data/Migrations/MissingMigration.sql`
- `apps/dotnet/src/Data/Services/ConduitRepository.cs`

### Vue frontend

- `apps/vue3/components.d.ts`
- `apps/vue3/cypress.config.ts`
- `apps/vue3/package.json`
- `apps/vue3/src/api/index.ts`
- `apps/vue3/src/components/MarkdownRenderer.vue`
- `apps/vue3/src/pages/article/[[id]].vue`
- `apps/vue3/src/pages/article/components/ArticleForm.vue`
- `apps/vue3/src/pages/index/index.vue`
- `apps/vue3/src/pages/settings/index.vue`
- `apps/vue3/src/pages/settings/password.vue`
- `apps/vue3/src/types/index.d.ts`

### Flutter frontend

- `apps/flutter/lib/bloc/register_bloc/register_bloc.dart`
- `apps/flutter/lib/config/constant.dart`
- `apps/flutter/lib/main.dart`
- `apps/flutter/lib/model/profile_model.dart`
- `apps/flutter/lib/model/user_model.g.dart`
- `apps/flutter/lib/repository/all_article_repo.dart`
- `apps/flutter/lib/repository/auth_repo.dart`
- `apps/flutter/lib/services/user_client.dart`
- `apps/flutter/lib/ui/about_us/about_us_screen.dart`
- `apps/flutter/lib/ui/add_article/add_article_screen.dart`
- `apps/flutter/lib/ui/change_password/change_password_screen.dart`
- `apps/flutter/lib/ui/feed/yourfeed.dart`
- `apps/flutter/lib/ui/global/global.dart`
- `apps/flutter/lib/ui/global/global_item_detail_screen.dart`
- `apps/flutter/lib/ui/global/markdown_preview.dart`
- `apps/flutter/lib/ui/login/login_screen.dart`
- `apps/flutter/lib/ui/profile/profile_screen.dart`
- `apps/flutter/lib/ui/register/register_screen.dart`
- `apps/flutter/lib/widget/all_article_widget.dart`
- `apps/flutter/pubspec.yaml`
- `apps/flutter/web/index.html`

### Tests

- `apps/dotnet/tst/Unit.Tests/ArticleMapperImageTest.cs`
- `apps/dotnet/tst/Unit.Tests/Assignment_3_Test_Cases/PasswordHashingTest.cs`
- `apps/dotnet/tst/Unit.Tests/Test_ProfilBild/ProfilesImageUploadTest.cs`
- `apps/dotnet/tst/Unit.Tests/Unit.Tests.sln`
- `apps/flutter/test/add_article_screen_test.dart`
- `apps/flutter/test/photo-test.dart`
- `apps/flutter/test/test_registration.dart`
- `apps/flutter/test/widget_test.dart`
- `apps/vue3/cypress/e2e/edit_markdown_article.cy.ts`
- `apps/vue3/cypress/e2e/end2end.cy.ts`
- `apps/vue3/cypress/support/e2e.ts`
- `apps/vue3/tests/end2end.cy.ts`
- `apps/vue3/tests/utils.test.ts`

### Build/config/docs

- `.github/workflows/docs.yml`
- `.github/workflows/dotnet.yml`
- `.github/workflows/flutter.yml`
- `.github/workflows/vue3.yml`

## Most Important Final Implementation Files

### Backend

- `apps/dotnet/src/Api/Features/Articles/ArticlesModule.cs`
- `apps/dotnet/src/Api/Features/Articles/ArticlesMapper.cs`
- `apps/dotnet/src/Api/Features/Profiles/ProfilesModule.cs`
- `apps/dotnet/src/Api/Features/Profiles/ProfilesHandler.cs`
- `apps/dotnet/src/Api/Features/Search/SearchModule.cs`
- `apps/dotnet/src/Api/Features/Users/UserModule.cs`
- `apps/dotnet/src/Api/Utils/PasswordHasher.cs`
- `apps/dotnet/src/Core/Entities/ArticleImage.cs`
- `apps/dotnet/src/Data/Contexts/ConduitContext.cs`
- `apps/dotnet/src/Data/Migrations/20250622085717_AddArticleImages.cs`

### Vue

- `apps/vue3/src/components/MarkdownRenderer.vue`
- `apps/vue3/src/pages/article/components/ArticleForm.vue`
- `apps/vue3/src/pages/article/[[id]].vue`
- `apps/vue3/src/pages/settings/index.vue`
- `apps/vue3/src/pages/settings/password.vue`
- `apps/vue3/src/api/index.ts`
- `apps/vue3/cypress/e2e/edit_markdown_article.cy.ts`

### Flutter

- `apps/flutter/lib/ui/profile/profile_screen.dart`
- `apps/flutter/lib/ui/global/markdown_preview.dart`
- `apps/flutter/lib/ui/global/global_item_detail_screen.dart`
- `apps/flutter/lib/ui/add_article/add_article_screen.dart`
- `apps/flutter/lib/ui/change_password/change_password_screen.dart`
- `apps/flutter/lib/repository/auth_repo.dart`
- `apps/flutter/lib/repository/all_article_repo.dart`
- `apps/flutter/test/photo-test.dart`