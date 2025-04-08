# Python and FastAPI Best Practices

This rule applies to Python and FastAPI code in this project.

## Python Best Practices

- Use Python 3.10+ syntax and features
- Follow PEP 8 style guidelines with descriptive variable names
- Use type hints for all function parameters and return types
- Prefer list, dict comprehensions over loops when appropriate
- Use pathlib instead of os.path for file operations
- Implement proper error handling with try/except blocks
- Create unit tests for all new functions

## FastAPI Best Practices

- Structure API endpoints in a RESTful manner
- Use Pydantic models for request/response validation
- Implement dependency injection for shared resources
- Document all endpoints with appropriate descriptions
- Include proper status codes in responses
- Use async/await for I/O-bound operations
- Implement proper error handling with exception handlers
- Add appropriate CORS settings for frontend integration
- Use structured logging

## Virtual Environment with UV

- Use UV package manager instead of pip for all dependencies
- Always activate the virtual environment before running commands
- Add new dependencies to pyproject.toml with exact versions
- Run `uv pip sync` after updating dependencies

## Development Process

- Run linters and formatters before committing code
- Use pre-commit hooks for automated checks
- Follow git best practices with descriptive commit messages 