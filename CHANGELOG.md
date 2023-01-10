# Change Log

## [1.0.8] 2023-01-10
### Changes

- Move to theme-based pattern
  - [Django Theme Pixel](https://github.com/app-generator/django-theme-pixel)
- 🚀 `Deployment` 
  - `CI/CD` flow via `Render`

## [1.0.7] 2022-05-30
### Improvements

- Built with [Pixel Lite Generator](https://appseed.us/generator/pixel-bootstrap/)
  - Timestamp: `2022-05-31 08:05`

## [1.0.6] 2022-01-17
### Improvements

- Bump Django Codebase to [v2.0.0](https://github.com/app-generator/boilerplate-code-django/releases)
- Dependencies update (all packages) 
  - Django==4.0.1
- Settings update for Django 4.x
  - `New Parameter`: CSRF_TRUSTED_ORIGINS
    - [Origin header checking isn`t performed in older versions](https://docs.djangoproject.com/en/4.0/ref/settings/#csrf-trusted-origins)  

## [1.0.5] 2021-12-08
### Improvements 

- Bump Django Codebase to [v1.0.7](https://github.com/app-generator/boilerplate-code-django/releases)

## [1.0.4] 2021-09-07
### Improvements & Fixes

- Bump Django Codebase to [v1.0.5](https://github.com/app-generator/boilerplate-code-django/releases)
  - Dependencies update (all packages)
  - Use Django==3.2.6 (latest stable version)
  - Better Code formatting
  - Improved Files organization
  - Optimize imports
  - Docker Scripts Update 
- Fixes: 
  - Patch 500 Error when authenticated users access `admin` path (no slash at the end)
  - Patch [#16](https://github.com/app-generator/boilerplate-code-django-dashboard/issues/16): Minor issue in Docker 

## [1.0.3] 2021-07-18
### Tooling

- Added scripts to recompile the SCSS files
    - `core/static/assets/` - gulpfile.js
    - `core/static/assets/` - package.json
- `Update README` - [Recompile SCSS](https://github.com/app-generator/django-pixel-lite#recompile-css) (new section)

## [1.0.2] 2021-05-21
### Improvements

- Bump UI: [Jinja Pixel Lite](https://github.com/app-generator/jinja-pixel-lite) v1.0.2 / Pixel Lite v4.0.0
- Codebase: [Django Boilerplate](https://github.com/app-generator/boilerplate-code-django) v1.0.4

## [1.0.1] 2021-01-12
### Improvements

- Bump UI: [Pixel Lite](https://github.com/themesberg/pixel-bootstrap-ui-kit) v3.1.2
- Codebase: [Django Boilerplate](https://github.com/app-generator/boilerplate-code-django) v1.0.4

## [1.0.0] 2020-09-20
### Initial Release

