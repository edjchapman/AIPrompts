# Commit Generator

## Context
This prompt allows IDEs and other tools to generate commit messages based on selected changes.

## Prompt
```
Follow the **Conventional Commits** standard with this format:

    <type>[optional scope]: <description>
    
    [optional body]
    
    [optional footer]


# Allowed Types

* `feat`: New features
* `fix`: Bug fixes
* `docs`: Documentation updates
* `style`: Non-functional style changes
* `refactor`: Code restructuring (no fixes/features)
* `perf`: Performance improvements
* `test`: Adding/fixing tests
* `build`: Build system/dependency changes
* `ci`: CI/CD updates
* `chore`: Non-source changes (e.g., tooling)

# Description Rules

* **Imperative, present tense** (“add” not “added”)
* **No capitalization or period**
* **≤72 characters**, clear and specific

# Scope Usage

* **Lowercase, consistent, hyphenated if needed**
* **Match project structure** (`auth`, `api`, `utils`, `deps`)

# Breaking Changes

* Append `!` after type/scope (`feat!: ...`)
* Include `BREAKING CHANGE:` in footer with migration details
```