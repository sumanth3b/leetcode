# Copilot Instructions for AI Coding Agents

This repository is a minimal Python codebase. Follow these guidelines to be productive and consistent when contributing or generating code:

## Project Structure
- All code is currently in a single file: `Sample.py`.
- There are no additional modules, tests, or configuration files present.

## Main Functionality
- The core function is `two_sum(nums, target)`, which returns indices of two numbers in `nums` that add up to `target`.
- Example usage is provided in the `if __name__ == "__main__":` block.

## Patterns and Conventions
- Use clear, concise function and variable names (e.g., `two_sum`, `seen`, `need`).
- Prefer returning results directly rather than printing inside utility functions.
- Keep logic simple and readable; avoid unnecessary abstractions for small scripts.

## Developer Workflow
- Run the script directly with `python Sample.py` to test functionality.
- No build system, test framework, or external dependencies are present.
- Add new features or functions directly to `Sample.py` unless the project grows.

## Extending the Codebase
- If adding new algorithms, follow the style of `two_sum`:
  - Place new functions at the top level.
  - Add example calls in the `__main__` block for demonstration.
- If the codebase grows, consider splitting into multiple files and adding a `README.md` to document structure and usage.

## Example
```python
# Add new functions above the __main__ block
def my_algorithm(...):
    ...

if __name__ == "__main__":
    print(my_algorithm(...))
```

---

If you add new files or workflows, update this document to reflect changes. For questions or unclear conventions, ask for clarification.