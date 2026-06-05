# Contributing to dummy-node-devops

Thank you for your interest in contributing! We welcome contributions from the community.

## Prerequisites

- Node.js (LTS version recommended)
- npm (comes with Node.js)
- Git

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

## Contribution Workflow

1. **Fork** the repository on GitHub
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/dummy-node-devops.git`
3. **Create a branch**: `git checkout -b feature/your-feature-name`
4. **Make your changes** and commit: `git commit -am "Add your message"`
5. **Push** to your fork: `git push origin feature/your-feature-name`
6. **Open a Pull Request** against the `master` branch

## Continuous Integration

All pull requests are automatically built and tested via Jenkins CI. The pipeline is defined in the `Jenkinsfile` and includes build, test, and deployment stages.

## Code Quality

- Write clean, maintainable code
- Add tests when implementing new features (run with `npm test`)
- Follow existing code style and conventions

## Questions or Issues?

Feel free to open an issue on GitHub if you have questions or encounter problems.
