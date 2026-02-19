# README Badge Strategy

Add these badges at the top of each flagship repository README.

## Badge Templates

### CI Status
```markdown
![CI](https://github.com/HungYangChang/{repo}/actions/workflows/ci.yml/badge.svg)
```

### Coverage (if using Codecov)
```markdown
[![codecov](https://codecov.io/gh/HungYangChang/{repo}/branch/main/graph/badge.svg)](https://codecov.io/gh/HungYangChang/{repo})
```

### Coverage (static badge — use when Codecov not configured)
```markdown
![Coverage](https://img.shields.io/badge/coverage-95%25-brightgreen)
```

### License
```markdown
![License](https://img.shields.io/badge/license-MIT-blue)
```

### Python Version
```markdown
![Python](https://img.shields.io/badge/python-3.10%2B-blue)
```

### Node Version
```markdown
![Node](https://img.shields.io/badge/node-18%2B-green)
```

## Recommended Badge Order

```markdown
![CI](badge-url) ![Coverage](badge-url) ![License](badge-url) ![Python](badge-url)
```

## Per-Repo Exceptions

For repos where tests are not yet feasible, omit the CI/coverage badges and add a note:

```markdown
> **Note:** This project is a research prototype. Automated tests are planned for the next iteration.
```
