pnpm
# Performant Node Package Manager (PNPM)

Based on "PNPM: What is it and why should you use it? - LinkedIn" at https://www.linkedin.com/pulse/what-pnpm-why-you-should-use-ahsan-sheikh#:~:text=In%20simple%20terms%2C%20PNPM%20(Performant,are%20managed%20in%20JavaScript%20projects.

## 100 - Introduction

### What is PNPM?

In simple terms, **PNPM (Performant NPM)** is a forward-thinking package management solution designed to address the challenges posed by traditional package managers. At its core, PNPM employs a centralized storage system combined with hard links to streamline the way dependencies are managed in JavaScript projects. Unlike NPM and Yarn, which tend to duplicate packages for each project, PNPM utilizes a content-addressable store to create hard links to packages from the virtual store, drastically reducing redundancy and disk space consumption. 5 Oct 2023

### How Does PNPM Differ from NPM?

PNPM introduces a unique approach to package management that sets it apart from its predecessors.

### Dependency Management:

- **PNPM**: Utilizes a shared dependency mechanism that allows different projects to use the same copy of a package. This efficient approach minimizes duplication and reduces disk space usage.
- **NPM**: Employs a flat dependency architecture where each project has its own copy of all dependencies, potentially leading to higher disk space consumption.

### Disk Space:

- **PNPM**: Requires less disk space due to shared dependencies.
- **NPM**: Consumes more disk space due to separate copies of dependencies.

### Installation Speed:

- **PNPM**: Faster installation due to shared dependencies.
- **NPM**: Installation times might be longer.

### Workflow Integration:

- **PNPM**: Works well with common workflows but may have compatibility issues with some tools.
- **NPM**: Extensive tooling integrations and community support.

### Community and Ecosystem:

- **PNPM**: Smaller community and package registry.
- **NPM**: Larger and established community with extensive package availability.

### PNPM Features:

- **Workspace Support**: Simplifies managing interconnected projects in a mono repo.
- **Aliases**: Allows custom shortcuts for packages and modules.
- **Tab-Completion**: Offers command-line tab completion for better developer experience.

### Why Choose PNPM:

- **Efficient Disk Space**: Saves space with shared dependencies.
- **Faster Installation**: Speeds up installations and updates.
- **Resource Optimization**: Optimizes CPU and memory usage.
- **Use Cases**: Suitable for monorepos, microservices, and projects with limited space.

## 200 - Requirements

- Node.js and NPM

## 300 - Building Our Application

### How to Install PNPM:

Install with Node.js and NPM -> ```npm install -g pnpm```

### Basic PNPM commands

- ```pnpm add <package_name>```: Installs packages and their dependencies.
- ```pnpm install (or pnpm i)```: Installs project dependencies.
- ```pnpm remove <package_name>```: Uninstalls and removes dependencies.
- ```pnpm update <package_name>```: Updates packages.

## 400 - Conclusion

If you work with multiple projects or have limited storage, consider using PNPM. It's a faster and more efficient package manager that saves disk space.

Use PNPM instead of NPM or YARN where possible.
