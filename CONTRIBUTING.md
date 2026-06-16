# Contributing to SRAO Framework

Thank you for your interest in contributing! Here's how you can help:

## Ways to Contribute

### 1. New Industry Models
Add a new industry domain model to SRAO-Domain-Modeler:
- Create a new file in eferences/ following the existing format
- Include: concept dictionary, entity relationships, at least 2 workflow templates
- Submit a PR to [SRAO-Domain-Modeler](https://github.com/beixuan577/SRAO-Domain-Modeler)

### 2. New Orchestration Templates
Add DAG code templates for additional engines:
- Create template in SRAO-Workflow-Orchestrator eferences/
- Follow the existing naming convention: engine-template.ext
- Include: parallel execution, conditional branching, error handling
- Submit a PR to [SRAO-Workflow-Orchestrator](https://github.com/beixuan577/SRAO-Workflow-Orchestrator)

### 3. Bug Reports
- Open an issue in the relevant repository
- Include: expected behavior, actual behavior, steps to reproduce

### 4. Feature Requests
- Open an issue with the label enhancement
- Describe the use case and proposed solution

## Development Process

1. Fork the repository
2. Create a feature branch (git checkout -b feature/amazing-feature)
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Code Style

- YAML: 2-space indentation
- Python: PEP 8
- TypeScript: ESLint recommended
- Markdown: ATX headers, no trailing whitespace

## License

By contributing, you agree that your contributions will be licensed under the MIT License.