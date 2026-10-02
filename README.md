# dirdust

Go CLI that organizes a messy folder by file extension

## Examples

```bash
./bin/dirdust ~/Downloads --dry-run
./bin/dirdust ~/Downloads
```

## Features

- Skips hidden files and folders by default
- Dry-run prints the plan before moving anything
- Single static binary, no runtime deps
- Groups files into folders by extension

## Getting started

```bash
go build -o bin/ ./...
```

## Project structure

```text
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── SECURITY.md
├── go.mod
└── main.go
```

## License

MIT. Do whatever you want.
