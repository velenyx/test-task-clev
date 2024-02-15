# Project Initialization

Install deps:

```bash
npm install
```

To start the project, run the following command in your terminal:

```bash
npm run dev
```

## Test Task

### Objective

The task involves refactoring the application to eliminate direct dependencies among the following modules: `user`, `tasks`, `lib`.

### Key Requirement

It's crucial to ensure that there are **no transitive dependencies** through a third module as well. The modules `user`, `tasks`, `lib` should act as leaves in the dependency tree, implying they do not directly depend on each other or indirectly through another module.

Good luck with your task! We look forward to seeing your innovative solutions to this challenge.
