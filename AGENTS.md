# AGENTS.md - GitAgent

## Tech Stack
- **Language**: TypeScript
- **Runtime**: Node.js
- **Standard**: Git-native AI Agent Standard
- **Protocols**: MCP (Model Context Protocol), A2A (Agent-to-Agent)
- **Framework**: Framework-agnostic (works with Claude, OpenAI, CrewAI, LangChain)
- **Registry**: Git-based agent registry
- **CLI**: GitAgent CLI

## Project Structure
```
src/                  # Core source code
registry/             # Agent registry
registry-landing/     # Registry landing page
docs/                 # Documentation
spec/                 # Specification files
patterns/             # Agent patterns
examples/             # Usage examples
```

## Key Dependencies
- TypeScript compiler
- Git (system)
- Various AI framework adapters

## Commands
```bash
npm run build         # TypeScript compilation
npm test              # Run tests
gitagent <command>    # Use the CLI
```

## Conventions
- Git-native agent definitions
- Framework-agnostic design
- MCP/A2A protocol support
- FINRA compliance ready

## Environment Variables
- `GITAGENT_HOME` - Agent home directory
- Git provider tokens as needed
