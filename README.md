# Basilisk-101: High-Fidelity Simulations Using Basilisk C

[![Issues](https://img.shields.io/github/issues/comphy-lab/Basilisk-101)](https://github.com/comphy-lab/Basilisk-101/issues)
[![License](https://img.shields.io/github/license/comphy-lab/Basilisk-101)](https://github.com/comphy-lab/Basilisk-101/blob/main/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/comphy-lab/Basilisk-101)](https://github.com/comphy-lab/Basilisk-101/commits/main)
[![Course](https://img.shields.io/badge/Course-March%202025-blue)](https://comphy-lab.org/teaching/2025-Basilisk101-Madrid)
[![Basilisk](https://img.shields.io/badge/Basilisk-Compatible-green)](http://basilisk.fr/)
![CodeRabbit Pull Request Reviews](https://img.shields.io/coderabbit/prs/github/comphy-lab/Basilisk-101?utm_source=oss&utm_medium=github&utm_campaign=comphy-lab%2FBasilisk-101&labelColor=171717&color=FF570A&link=https%3A%2F%2Fcoderabbit.ai&label=CodeRabbit+Reviews)

Repository for the Basilisk C course at Universidad Carlos III de Madrid (March 10-13, 2025).

## Course Description

This intensive course provides a comprehensive introduction to high-fidelity simulations using Basilisk C, a powerful computational framework for fluid dynamics. Participants will learn to implement and solve complex fluid mechanics problems with an emphasis on multiphase flows, interface dynamics, and non-Newtonian rheology.

### What You'll Learn

- **Think before you compute!** Understanding the physics before implementation
- **Writing the first code in Basilisk C** Getting comfortable with the framework
- **Solving conservation equations** Numerical approaches to fluid dynamics
- **Interface tracking methods** Capturing multiphase phenomena accurately
- **Non-Newtonian flows** Modeling complex rheological behaviors

### Course Details

- **Dates**: March 10-13, 2025
- **Location**: Universidad Carlos III de Madrid, Spain
- **Duration**: 4 days, full-time
- **Prerequisites**:
  - Basic knowledge of fluid mechanics
  - Experience with programming (any language, C preferred)
  - Understanding of partial differential equations
  - Laptop with ability to compile C code

For complete course schedule and registration information, visit: [Course Website](https://comphy-lab.org/teaching/2025-Basilisk101-Madrid)

## Repository Structure

```
├-- basilisk/src/: Core Basilisk CFD library (reference only)
├── postProcess/: Project-specific post-processing tools
├── src-local/: Custom header files extending Basilisk functionality
├── testCases/: Test cases with their own Makefile
```

## Installation

Use a C99 compiler and GNU make to build the checked-in Basilisk source:
```bash
bash reset_install_requirements.sh
source .project_config
```

Use the case Makefile or `qcc` without defining `DISPLAY`. For visualization,
write files and render them offline. The legacy network viewer is disabled in
this checkout; previously installed binaries and running processes are not
modified by this change.

## Reporting Issues and Feature Requests

We use GitHub Issues to track bugs, feature requests, and example requests for this course. When creating an issue, please select the appropriate template to help us address your needs efficiently.

### Issue Templates

#### Bug Report:
[Report here](https://github.com/comphy-lab/Basilisk-101/issues/new?template=bug_report.md)

- For problems with installation, compilation, or running code. 
Please include:
- Detailed description of the issue
- Your environment (OS, compiler version)
- Steps to reproduce
- Expected vs. actual behavior
- Error messages and logs
- Code snippets or files that demonstrate the issue

#### Feature/Topic Request:
[Report here](https://github.com/comphy-lab/Basilisk-101/issues/new?template=feature_request.md)
- For requesting specific topics or functionality
- Coverage of specific topics in the course
- New examples or tutorials
- Additional functionality in the codebase
- Improvements to existing materials

#### Example Request:
[Report here](https://github.com/comphy-lab/Basilisk-101/issues/new?template=example_request.md)
- For requesting specific examples that demonstrate:
- Particular Basilisk features
- Solutions to common problems
- Implementation of specific physics or numerical methods

#### General Question:
[Report here](https://github.com/comphy-lab/Basilisk-101/issues/new?template=general_question.md)
- For any other questions

### How to Create an Issue

1. Go to the ["Issues" tab](https://github.com/comphy-lab/Basilisk-101/issues) in the GitHub repository
2. Click the ["New Issue"](https://github.com/comphy-lab/Basilisk-101/issues/new/choose) button
3. Select the appropriate template from the options
4. Fill in the required information according to the template
5. Add relevant labels if available
6. Submit the issue