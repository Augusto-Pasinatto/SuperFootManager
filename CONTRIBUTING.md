# Contributing Guide

Thank you for your interest in contributing to **SuperfootManager**!  
To maintain quality and organization, please follow the conventions below.

---

# 🧱 Branch Strategy

We use a simple branching model:

- **main** → Stable, release-ready code  
- **dev** → Active development branch  
- **feature/< feature-name >** → New features  
- **fix/< issue-fixed >** → Bug fixes  
- **hotfix/< critical-issue >** → Urgent fixes on production  
- **refactor/< improvement >** → Structural improvements (no behavior change)

**Example:**
feature/match-simulation
fix/json-loading-error

---

# 📝 Commit Messages (Conventional Commits)

All commits must follow the **Conventional Commits** specification.

## Format:
< type >: < short message >

[optional extended description]

## Allowed Types:
- **feat:** new feature
- **fix:** bug fix
- **docs:** documentation changes
- **style:** formatting (no logic changes)
- **refactor:** code refactoring (no behavior change)
- **perf:** performance improvements
- **test:** add or update tests
- **build:** changes in dependencies or build scripts
- **ci:** continuous integration/config changes
- **chore:** maintenance tasks

## Examples:

### Feature
feat: implement player training system

Added weekly training cycles, XP progression logic and fatigue
management. Updated JSON schema to support new attributes.

### Bugfix
fix: correct null reference in match simulation

The crash occurred when player stats loaded after lineup creation.
Fixed initialization order.

### Refactor
refactor: reorganize UI controllers into separate modules

---

# 🔄 Pull Requests

Before submitting a PR:

1. Update your branch with the latest from **dev**:
2. Ensure the project builds without errors in Unity.
3. Test your changes.
4. Follow commit conventions.
5. Include a description of:
- What was changed  
- Why it was changed  
- Any side effects  
- Steps to test  

---

# 🧪 Code Style Guidelines

- Use **C# conventions** (PascalCase for classes, camelCase for variables).
- Keep Unity scripts organized inside `/Scripts/`.
- Avoid large monolithic scripts — prefer modular design.
- Use summary comments for public methods and classes.

---

# 📦 Folder Structure (recommended & maybe will change)
/Assets
/Scripts
/Managers
/UI
/Simulation
/Data
/Resources
/Scenes
/Prefabs


---

# ✔ Accepted Contributions

- Gameplay improvements
- UI enhancements
- Bug fixes
- Balance adjustments
- New features
- Performance improvements
- Documentation

---

# ❌ Not Accepted

- Code without clear purpose
- Features without discussion (major redesigns)
- Commits not following the conventions
- Unsolicited asset packs (models, textures etc.)

---

Thank you for contributing to **SuperfootManager**!  


