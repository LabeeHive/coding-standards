# Standards

## Purpose

This repository contains shared standards for Labee LLC projects. Add it as a Git submodule to maintain consistency across repositories.

---

## Getting started

**Setting up a new repository?** Start here: [repository/setup.md](repository/setup.md)

---

## Standards

| Directory | Description |
|-----------|-------------|
| [automation/](automation/) | Automation standards (Renovate, etc.) |
| [culture/](culture/) | Culture and behavioral principles |
| [docusaurus/](docusaurus/) | Docusaurus public site standards |
| [documentation/](documentation/) | Documentation writing standards |
| [github/](github/) | GitHub collaboration standards (Issues, PRs) |
| [repository/](repository/) | Repository setup standards |
| [swift/](swift/) | Swift and SwiftUI coding standards |

---

## Priority levels

Each standard uses priority levels to indicate importance:

- **P1 (Required)**: Must be followed
- **P2 (Recommended)**: Should be followed when possible
- **P3 (Optional)**: Nice-to-have

---

## Installation

```bash
# Add as submodule
git submodule add https://github.com/labee/coding-standards.git docs/05_standards

# Clone with submodules
git clone --recurse-submodules <your-project-url>

# Initialize submodules in existing clone
git submodule update --init --recursive
```

---

## Updates

```bash
git submodule update --remote docs/05_standards
```

