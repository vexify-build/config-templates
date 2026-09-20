# Config Templates

A collection of configuration file templates for common tools and workflows.

## Structure

```
config-templates/
├── git/           # Git configuration
├── eslint/        # ESLint rules
├── prettier/      # Prettier formatting
├── github/        # GitHub Actions workflows
├── vscode/        # VS Code settings
└── tmux/          # Tmux configuration
```

## Usage

### Git Configuration

Copy to your home directory:

```bash
cp git/.gitconfig ~/.gitconfig
cp git/.gitignore-global ~/.gitignore-global
git config --global core.excludesFile ~/.gitignore-global
```

### ESLint

```bash
cp eslint/.eslintrc.js your-project/
cd your-project && npm install --save-dev eslint
```

### Prettier

```bash
cp prettier/.prettierrc your-project/
npm install --save-dev prettier
```

### GitHub Actions

Copy workflow files to `.github/workflows/` in your repository.

### VS Code

Copy settings to `.vscode/settings.json` or use VS Code Settings Sync.

### Tmux

```bash
cp tmux/.tmux.conf ~/.tmux.conf
```

## License

MIT
