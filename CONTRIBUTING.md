# Contributing to dummy-node-devops

Thanks for your interest in contributing! We welcome contributions from the community.

## Development Setup

1. **Fork** this repository to your GitHub account
2. **Clone** your fork: `git clone https://github.com/YOUR_USERNAME/dummy-node-devops.git`
3. **Install dependencies**: `npm install`
4. **Verify** your setup by running the test suite

## Submitting Changes

1. Create a new branch: `git checkout -b feature/your-feature-name`
2. Make your changes and commit: `git commit -am "Description of changes"`
3. Push to your fork: `git push origin feature/your-feature-name`
4. Open a **Pull Request** against the `master` branch

## Code Quality

- Write clean, maintainable code with clear commit messages
- All changes go through our CI pipeline (see `Jenkinsfile`) with stages: Pull → Build → Test → Deploy
- Ensure your code passes all stages before submitting

## Running Tests

Run the test suite with: `npm test`

Feel free to open an issue for questions or suggestions. Happy contributing! 🎉
