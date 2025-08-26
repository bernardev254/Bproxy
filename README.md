# Bproxy

**Bproxy** is a lightweight, high-performance load balancer written in Rust. It supports multiple load balancing algorithms (starting with round-robin) and can be controlled via a CLI or REST API. Bproxy is designed to be modular, efficient, and easy to extend.

---

## Features

- **Round-Robin Load Balancing**: Distribute requests evenly across backend servers.
- **CLI and API Support**: Manage the load balancer via command-line or HTTP API.
- **Async Runtime**: Built on Tokio for high concurrency and performance.
- **Modular Design**: Easy to extend with new algorithms and features.
- **Configuration**: Load backend servers from a configuration file.

---

## Installation

### Prerequisites

- Rust (latest stable version)
- Cargo (Rust package manager)

### Build from Source

1. Clone the repository:

   ```sh
   git clone https://github.com/bernardev254/Bproxy.git
   cd Bproxy
   ```
### Contribution Workflow
1. ### Github Setup
```
# Install GitHub CLI (if not already installed)
# Visit: https://cli.github.com/ for installation instructions

# Verify installation
gh --version
```

2. ### Fork and clone
```
gh repo fork bernardev254/Bproxy --clone --remote
cd Bproxy
```

3. ### Create Branch & Make Changes
### Create and switch to a new branch
```
git checkout -b fix-98-<branch>
```

### Stage and commit your changes
```
git add .
git commit -m "[Insert meaningful commit message here]"
```
4. ### Push & Create Pull Request
## Push your branch to your fork
```
git push origin <branch>
```

## Create a Pull Request
```
gh pr create --title "Fix: <pr name>" --body "Closes #[issue number]"
```
## Tips & Resources
```
Best Practices:
✓
Read the project's CONTRIBUTING.md and README files
✓
Follow the project's coding standards and conventions
✓
Write clear, descriptive commit messages
✓
Test your changes thoroughly before submitting
✓
Keep your PR focused on solving the specific issue
✓
Respond promptly to feedback from maintainers

```