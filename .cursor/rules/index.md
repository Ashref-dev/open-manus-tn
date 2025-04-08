# LangGraph ReAct Agent Project Rules

This is the main entry point for Cursor AI Rules for this LangGraph ReAct Agent project.

## File Types and Rules

- **Python and FastAPI**: @file:.cursor/rules/python_fastapi.md
  - Applies to: `**/*.py`
  - Python best practices, FastAPI implementation, UV package management

- **LangGraph**: @file:.cursor/rules/langgraph.md
  - Applies to: `src/react_agent/*.py`
  - LangGraph development, node functions, tool integration

- **Azure DevOps Agent**: @file:.cursor/rules/azure_devops.md
  - Applies to: `src/react_agent/*.py`
  - Azure DevOps integration, security, deployment

## Environment

- This project uses UV package manager in a virtual environment
- Python 3.10+ is required
- FastAPI is used for API development
- LangGraph is used for agent development
- Azure DevOps integration is a key component

## Development Process

- Follow test-driven development principles
- Document code changes
- Run linters before committing
- Use proper git workflow with feature branches 