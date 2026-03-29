# ChorePal

A gamified chore management application that transforms mundane tasks into engaging gameplay experiences through combat systems, randomization mechanics, and gacha-style rewards.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Team & Contributing](#team--contributing)
- [License](#license)
- [Notes](#notes)

## Overview

ChorePal is a Java-based chore management application designed to gamify household and personal task management. By incorporating game mechanics like combat systems, random number generation (RNG), and gacha-style rewards, ChorePal makes completing chores more engaging and fun.

This project is currently in **beta**, meaning core features are still being refined and expanded. We're actively developing and iterating based on team feedback and user experience.

## Features

- **Gamified Task Management**: Complete chores and earn rewards through various game mechanics
- **Combat System**: Engage in turn-based or real-time combat challenges tied to task completion
- **RNG & Gacha Mechanics**: Unlock rewards and items through randomized drops and gacha systems
- **Clean File Organization**: Repository organized by category with clear, readable folder names
- **Team Collaboration**: Built by a dedicated team of programmers

## Prerequisites

Before installing ChorePal, ensure you have the following installed on your system:

- **Java** (latest version) - [Download Java](https://www.oracle.com/java/technologies/downloads/)

To verify your Java installation, run:
```bash
java -version
```

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/e-qep/ChorePal.git
   cd ChorePal
   ```

2. **Build the project**:
   ```bash
   javac -d bin src/**/*.java
   ```
   *(Or use your project's build tool if applicable)*

3. **Run ChorePal**:
   ```bash
   java -cp bin Main
   ```
   *(Adjust the main class name as needed)*

## Project Structure

The repository is organized into clean, category-based folders for easy navigation and collaboration:

```
ChorePal/
├── src/                    # Source code
├── gui/                    # GUI components
├── assets/                 # Game assets (sprites, sounds, etc.)
├── docs/                   # Documentation
├── tests/                  # Test files
└── README.md               # This file
```

**Note**: Files are named clearly and logically. We avoid naming conventions like "TEST_V1.0_REAL_ACTUAL_VERSION3" to maintain code clarity and team sanity.

## Getting Started

1. Install Java (latest version)
2. Clone this repository
3. Follow the [Installation](#installation) section above
4. Start managing chores with gamification!

*For detailed setup instructions or troubleshooting, check the docs folder or reach out to the team.*

## Team & Contributing

ChorePal is developed by a small, dedicated team:

- **Backend Developer**: Alex
- **GUI Developer**: Luca
- **Ideas and Management**: Mihai

### Contributing

At this stage, contributions are primarily handled by our core team. If you're interested in contributing:

1. Reach out to the team to discuss your ideas
2. Fork the repository
3. Create a feature branch (`git checkout -b feature/your-feature`)
4. Commit your changes (`git commit -m 'Add your feature'`)
5. Push to the branch (`git push origin feature/your-feature`)
6. Open a Pull Request for team review

### Reporting Issues

Found a bug or have a feature request? Please open an issue on the [GitHub Issues page](https://github.com/e-qep/ChorePal/issues).

## License

ChorePal is currently unlicensed. A license will be added in a future release.

## Notes

- This project is in **beta** and is actively being developed
- Expect changes, new features, and refinements as we iterate
- For project milestones, development roadmap, and team discussions, please refer to our project management tools (Issues, Discussions, or project board)
- Java version requirement: Latest stable release recommended
