# Windows

Windows is common, but local development can be more complicated because many programming tools were originally designed around Unix/Linux-style terminals.

## Pros

- Most students are familiar with it
- Works well with browser-based AI tools
- Works well with [VS Code](https://code.visualstudio.com)
- Can use Windows Subsystem for Linux
- Good compatibility with general software

## Cons

- Terminal differences can be confusing
- PowerShell commands are different from Bash commands
- Some tutorials assume macOS or Linux
- Path issues can happen
- Native package installation can be harder

## [Windows Subsystem for Linux (WSL)](https://learn.microsoft.com/en-us/windows/wsl/)

Windows Subsystem for Linux, often called WSL, lets you run a Linux environment inside Windows.

This is useful because many developer tools assume a Linux-like system.

### Why Use WSL?

- Easier [Node.js](https://nodejs.org), [Python](https://python.org), [Rust](https://rust-lang.org), and [Git](https://git-scm.com) workflows
- Better compatibility with many coding tutorials
- More similar to production servers
- Works well with [VS Code](https://code.visualstudio.com)

### Common WSL Gotchas

- Files can live in Windows or inside Linux
- Terminal commands may differ depending on where you are
- [Docker](https://docker.com) integration can be confusing
- Permissions can be confusing
- Some tools installed in Windows are not available inside WSL, and vice versa

## Recommendation for Students

If you are using Windows:

- Browser-based tools are the easiest starting point
- Use [VS Code](https://code.visualstudio.com)
- Consider WSL if you are doing serious coding
- **Do not wait until the hackathon to test your setup**
