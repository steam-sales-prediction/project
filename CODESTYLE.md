# Code Style

We should aim to follow the famous python [PEP 8](https://peps.python.org/pep-0008/) conventions.

## 1. Naming Conventions

- **Variables**: Use `snake_case` (e.g., `my_variable`).
- **Functions**: Use `snake_case` (e.g., `my_function`).
- **Classes**: Use `PascalCase` (e.g., `MyClass`).
- **Constants**: Use `UPPER_CASE` (e.g., `HYPER_PARAMETER`)
- **Jupyter Notebooks**: Use `snake_case` (e.g., `clean_dlcs.ipynb`). 

## 2. Indentation and Spacing

- Indentation 4 spaces wide.
- Use a single space before and after operators (e.g., `a = b + c`).
- Do not add a space after function names before the opening parenthesis (e.g., `functionName(args)`).
- No trailing whitespace

## 3. Git and Collaboration Practices

### Main branch

The main branch is the primary development branch and shouldn't be pushed into directly, you should always prefer creating a pull request (PR).

### Feature Branch Names

Create a branch per task.

Branch names should be in lowercase and separated by dashes ('-') if they contain multiple words. Example:
```
git branch preprocess-text-features
```

### Commit Messages

Use conventional commit types, which can be found [here](https://github.com/pvdlg/conventional-changelog-metahub?tab=readme-ov-file#commit-types).

Example:
```
feat: cleaned and transformed the genres column
fix: removed numeric features scaling on the test data
```

Always remember to make commit messages descriptive and don't forget to add a description if needed:
```bash
git commit -m "conventional_type: message" -m "description"
```

## 4. Jupyter Notebook

Try to write clean markdown inside notebooks. A good notebook tells a story, not just runs code.

Before submitting a notebook in a PR, make sure to:

- **Restart & Run All:** Restart and run all cells from top to bottom to ensure there are no issues or errors.
- **Clean Cell Outputs:** Make sure that the remaining cell outputs are useful ones and remove any unnecessary cell outputs.