# Contributing to Hands-on R Code in Data Analysis

Thank you for your interest in contributing to this project! This document provides guidelines and instructions for contributing.

## Code of Conduct

Please be respectful and inclusive in all interactions. We're committed to providing a welcoming environment for everyone.

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- A clear, descriptive title
- Description of the problem
- Steps to reproduce the issue
- Expected behavior vs. actual behavior
- OS and R version information

### Suggesting Enhancements

Enhancement suggestions are welcome! Please include:
- Clear description of the enhancement
- Use cases and benefits
- Possible implementation approaches

### Pull Requests

1. **Fork the repository** and create a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes** following the code style guidelines

3. **Test your changes** thoroughly

4. **Commit with clear messages**:
   ```bash
   git commit -m "Add: Description of your changes"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request** with:
   - Clear description of changes
   - Reference to any related issues
   - Explanation of what problem it solves

## Code Style Guidelines

### R Code
- Use meaningful variable names
- Add comments for complex logic
- Follow base R style conventions
- Use 2-space indentation
- Keep line length under 80 characters where possible
- Add docstring comments for functions

Example:
```r
# Function to calculate mean absolute deviation
calculate_mad <- function(x) {
  # Calculate median
  median_val <- median(x, na.rm = TRUE)
  
  # Calculate mean absolute deviation
  mad <- mean(abs(x - median_val), na.rm = TRUE)
  
  return(mad)
}
```

### File Naming
- Use descriptive names
- Use lowercase with underscores: `analysis_palmer_penguins.R`
- For reports: `report_YYYYMMDD_description.pdf`

## Documentation

- Document new functions with comments
- Update README.md if adding new major features
- Include examples for complex functionality

## Commit Message Guidelines

Use clear, descriptive commit messages:
- `Add: New feature description`
- `Fix: Bug description`
- `Docs: Documentation updates`
- `Refactor: Code structure improvements`
- `Test: Testing improvements`

Example:
```
Add: Statistical analysis functions for Palmer Penguins dataset

- Added descriptive statistics function
- Added hypothesis testing utilities
- Added visualization helpers
```

## Review Process

1. Your PR will be reviewed by maintainers
2. Please be open to feedback and suggestions
3. Make requested changes in commits with clear messages
4. Your PR will be merged once approved

## Questions?

Feel free to:
- Open an issue for questions
- Reach out through the repository
- Check existing documentation first

## Recognition

Contributors will be recognized in the project README and commit history. Thank you for improving this project!

---

**Last Updated**: February 15, 2026
