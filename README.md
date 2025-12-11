# Rust CLI Template

> [!TIP]
> Use `cargo generate` to create a new project from this template!

## What's included?

- Complete Cargo.toml with metadata for packaging (deb, rpm, binstall)
- GitHub Actions workflows (CI, CD, security audit)
- Dependabot configuration
- Standard project files (LICENSE, CODE_OF_CONDUCT.md, CONTRIBUTING.md, FUNDING.yml)
- Ready-to-use README template with badges and installation instructions
- Renovate configuration for dependency updates
- Basic Rust project structure (lib.rs and main.rs)

## How to use?

### Prerequisites
Install cargo-generate:
```bash
cargo install cargo-generate
```

### Generate new project
```bash
cargo generate ErenayDev/rust-cli-template
```

The template will prompt you for:
- **Project name**: Your crate name
- **Long description**: Detailed project description
- **Short description**: Brief project summary  
- **GitHub username**: Your GitHub username or organization

### After generation

1. **Update cliff.toml**: The file is excluded from generation due to liquid syntax conflicts. You need to manually update the repository URLs in `cliff.toml` from `example/example_repo` to your actual repository.

2. **Configure GitHub repository**: Set up your repository and enable:
   - Renovate bot: https://github.com/apps/renovate/installations/select_target
   - GitHub Actions (should work automatically)

3. **Install development tools**:
```bash
# For changelog generation (optional, excluded from template)
cargo install git-cliff

# For pre-commit hooks
pip install pre-commit
pre-commit install
```

4. **Update project metadata**: Review and customize:
   - `Cargo.toml` dependencies and metadata
   - `README.md` content
   - License and funding information
   - Keywords and categories

## Template structure

The generated project includes:
- Cross-platform build configurations
- Package metadata for Linux distributions (deb, rpm)
- Binary installation support via cargo-binstall
- Complete CI/CD pipeline for releases
- Security audit workflow
- Contribution guidelines and code of conduct

## Development workflow

Create feature branches:
```bash
git checkout -b feat/awesome-feature
```

The CI will automatically:
- Run tests and linting
- Build for multiple platforms
- Create releases when you push tags
- Audit dependencies for security issues

---

Created with 🩵 by [ErenayDev](https://erenaydev.com.tr)
