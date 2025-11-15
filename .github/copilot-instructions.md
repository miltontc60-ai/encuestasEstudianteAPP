# Copilot Instructions for encuestasEstudianteAPP

## Project Overview
**encuestasEstudianteAPP** is a student survey application in early development. The project is designed as a multi-file PHP/HTML application managed in a VS Code workspace with multiple folder contexts.

### Key Files
- `Sql/xd.php` - PHP backend logic (currently placeholder)
- `Sql/hola.html` - HTML frontend (currently placeholder)
- `README.md` - Project documentation (minimal, under development)

## Architecture & Structure
This is a **front-end/back-end separated architecture**:
- **Frontend**: HTML files in `Sql/` directory (user interface)
- **Backend**: PHP files in `Sql/` directory (server-side logic)
- **Database**: SQL-based (future implementation - check for migrations/schema files as project expands)

The workspace includes a secondary folder for related systems (`../../Escritorio/New folder (3)/sistema_gestion`), suggesting this may be part of a larger ecosystem.

## Development Workflow
- **Editor**: VS Code with workspace configuration in `encuestasEstudianteAPP.code-workspace`
- **Source Control**: Git repository (ignore main branch for PRs - see `.vscode/settings.json`)
- **Branching**: Use feature branches; PRs against main are controlled

## Key Conventions & Patterns
1. **Directory Organization**: Code organized in `Sql/` directory (mix of frontend HTML and backend PHP)
2. **File Naming**: Simple naming pattern (e.g., `xd.php`, `hola.html`) - may need formalization as project grows
3. **PHP Entry Points**: PHP files in `Sql/` serve as backend handlers

## Important Notes
- Project is in **early development stages** with placeholder content
- **No external dependencies** visible yet (future composer.json for PHP packages expected)
- **No build/test framework** currently configured
- As features are added, establish: database schema patterns, form handling conventions, API response formats, and error handling standards

## Guidance for Agents
When contributing to this project:
1. **Expand from placeholders** - `xd.php` and `hola.html` need real implementation
2. **Establish conventions early** - Define PHP coding standards, form submission patterns, and response formats before significant growth
3. **Plan database schema** - Prepare SQL structure for storing survey data, student info, and responses
4. **Document as you go** - Keep README.md updated with setup instructions, API endpoints, and data models
