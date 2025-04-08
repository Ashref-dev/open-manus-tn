# LangGraph Development Rules

This rule applies to all LangGraph-related code in the project.

## LangGraph Graph Building

- Define clear node functions with explicit input/output typing
- Use proper state management patterns with typed state classes
- Add concise docstrings describing each node's purpose
- Implement proper error handling for LLM calls
- Structure graphs with logical flow and clear edge definitions
- Use conditional edges with explicit conditions
- Follow the ReAct pattern for agent-based interactions
- Include debugging and visualization capabilities

## Tool Integration

- Create well-documented tools with clear input/output contracts
- Implement proper error handling in all tools
- Use consistent naming patterns for tools and their parameters
- Return structured responses from tools for better agent parsing
- Validate tool inputs before execution
- Implement rate limiting for API-based tools
- Add telemetry for tool usage

## LLM Interaction

- Use structured prompts with clear instructions
- Keep system messages concise and focused
- Implement proper prompt templating for consistency
- Include examples in prompts when appropriate
- Use appropriate temperature settings for each use case
- Implement fallback mechanisms for model failures
- Add token usage monitoring

## Testing and Deployment

- Create unit tests for individual nodes
- Implement integration tests for complete graph flows
- Add prompt and model regression tests
- Use environment variables for configuration
- Document deployment requirements clearly 