# Makework

**One project. One command. Everything ready to work.**

Makework is a lightweight, local-first CLI written in Rust that orchestrates development workspaces.

Define your project's working environment once, then launch all your terminal processes with a single command.

Instead of maintaining custom shell scripts for every project, describe your workspace in a `Workfile.yaml` and let Makework handle the setup and terminal orchestration.

### Example

```bash
makework api
```

Makework is designed to bring together the tools you need to work: AI coding agents, development servers, Git interfaces, logs, test watchers, and interactive shells.

### Principles

- **Declarative:** define your workspace once in YAML.
- **Simple:** one command to launch your environment.
- **Local-first:** no accounts, cloud services, or mandatory daemon.
- **Terminal-native:** real interactive processes, not simulated terminal sessions.
- **Extensible:** a clean architecture that separates workspace definitions from terminal backends.
- **Built with Rust:** a native CLI designed for reliability and maintainability.

### Status

Makework is under active development. The initial release targets Kitty as its terminal backend.

Features, configuration format, and CLI behavior may change before the first stable release.

### License

License to be determined.
