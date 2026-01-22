# Project Instructions for Claude

## Overview
This is a [web application/API/library/tool] built with [technology stack]. The project follows [architecture pattern] and is designed to [main purpose].

## Code Style Guidelines

### General Principles
- Write clear, self-documenting code
- Prefer readability over cleverness
- Keep functions small and focused
- Use meaningful variable and function names

### Language-Specific Guidelines
- **Python**: Follow PEP 8, use type hints, prefer f-strings
- **JavaScript/TypeScript**: Use ES6+ features, prefer const/let over var
- **[Your Language]**: [Your specific guidelines]

## Architecture and Patterns

### Project Structure
```
src/
  ├── components/     # Reusable UI components
  ├── services/       # Business logic and API calls
  ├── utils/          # Helper functions
  └── tests/          # Test files
```

### Key Patterns
- Use dependency injection for services
- Implement error boundaries for React components
- Follow RESTful conventions for API endpoints
- Use async/await for asynchronous operations

## Testing Requirements

- Write unit tests for all business logic
- Aim for 80%+ code coverage
- Use descriptive test names following the pattern: `test_[function]_[scenario]_[expected_result]`
- Mock external dependencies in tests

## Documentation Standards

- Add docstrings to all public functions and classes
- Include examples in docstrings for complex functions
- Update README.md when adding new features
- Document API endpoints in OpenAPI/Swagger format

## Common Tasks and Commands

### Development
```bash
npm start          # Start development server
npm test           # Run tests
npm run lint       # Run linter
```

### Deployment
- Use semantic versioning (MAJOR.MINOR.PATCH)
- Always update CHANGELOG.md
- Tag releases in git

## Specific Preferences

### Error Handling
- Always handle errors explicitly, never use empty catch blocks
- Log errors with appropriate context
- Return user-friendly error messages

### Performance
- Avoid N+1 queries in database operations
- Use caching where appropriate
- Lazy load components and data when possible

### Security
- Never commit secrets or API keys
- Validate all user inputs
- Use parameterized queries to prevent SQL injection
- Implement proper authentication and authorization

## Things to Avoid

- Don't use deprecated APIs or libraries
- Avoid global state when possible
- Don't commit commented-out code (use git history instead)
- Avoid deep nesting (max 3 levels)

## Questions to Ask Before Making Changes

1. Does this change break existing functionality?
2. Are there existing patterns in the codebase I should follow?
3. Do I need to update tests?
4. Should this be documented?
5. Are there security or performance implications?
