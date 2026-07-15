# Contibuting documentation

## Explanation of branch strategy

- Below is shown the hierarchy of this repository

Setup looks like
```text
main
  └── central
        ├── feature/alice-task
        ├── feature/bob-task
        └── feature/charlie-task
  └──dev/alice
  └──dev/bob
  └──dev/charlie
```

## Branch Naming Convention
All feature branches must follow the pattern: `feature/[a-z0-9-]+`
Examples:
  ✅ feature/alice-task
  ✅ feature/update-readme
  ❌ feature/Alice_Task
  ❌ feature/MY FEATURE

  
A typical layout format is shown below

# Contributing

## Getting Started
- Clone the repo
- Install dependencies
- Run tests

## Branching Model
- main = stable
- dev = integration
- feature/* = new work

## Commit Messages
- Use Conventional Commits

## Pull Requests
- PRs must pass CI
- Include tests
- Reference issue numbers

## Code Style
- Follow linting rules
- Run pre-commit hooks

## Reporting Issues
- Use issue templates
- Provide reproduction steps
