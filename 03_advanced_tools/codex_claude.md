# [Claude Code](https://docs.anthropic.com/en/docs/claude-code/overview)

Claude Code is an agentic coding tool from [Anthropic](https://anthropic.com).

It can work with your project files and run commands depending on your permission settings.

## Good For

* Existing codebases
* Debugging
* Refactoring
* Writing tests
* Understanding unfamiliar projects
* Multi-file changes

## Watch Out For

* It may ask to run terminal commands
* It may edit many files
* It may add dependencies you do not need
* It may fix one bug while creating another
* It needs clear instructions

## Safe Prompt Example

```md
Inspect this project.

Do not edit files yet.

Tell me:

1. What framework this project uses
2. How to run it locally
3. Where the main pages are
4. Where the API routes are
5. What files you would change to add a simple dashboard
```

## Better Editing Prompt

```md
Make only the smallest change needed to add a dashboard page.

Rules:

- Do not add a new dependency
- Do not change unrelated files
- Explain each file you changed
- After editing, tell me how to run and test it
```