# matrix-walker

Source:
- https://github.com/6851-2021/matrix-walker

## What problem does it solve?

## Key idea

## Build / run notes (Fedora)

```bash
# commands you ran
```

## What I learned (engineering)

### Policy Compliance Setup (2026-01-16)

Applied comprehensive engineering policies to make the project compliant with organizational standards:

**Git & Source Control:**
- Added `.gitattributes` for LF canonical line endings (cross-platform consistency)
- Configured `.pre-commit-config.yaml` with hooks for formatting, linting, security checks
- Created `exception-and-decision-log.md` for tracking policy deviations

**Code Style Enforcement:**
- C++: `.clang-format` (Google style, 4-space indent, 100 char limit)
- Python: `py/pyproject.toml` with ruff configuration
- JavaScript/React: Prettier + ESLint configurations
- `.editorconfig` for cross-editor consistency

**Documentation:**
- Restructured `README.md` per policy (purpose, quickstart, prerequisites, setup, tests, formatting)
- Added `CONTRIBUTING.md` with development workflow
- Created `POLICY_COMPLIANCE.md` summary

**Build Hygiene:**
- Comprehensive `.gitignore` covering all build artifacts, IDE files, cache outputs
- Proper isolation of generated files from source control

**Key Takeaway:** Policy compliance is not just about rules—it's about creating reproducible, maintainable projects. The pre-commit hooks catch issues before CI, saving time and ensuring consistency across the team.

## Relevance to ML/CV systems
- Cache-oblivious data structures are critical for GPU memory access patterns
- Space-filling curves (Hilbert, Z-order) are used in spatial data structures for CV workloads
- Understanding cache behavior helps optimize data loading pipelines for training
