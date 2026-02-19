# Architecture: {Project Name}

> Last updated: {YYYY-MM-DD}

## Overview

{1–2 paragraph summary of the system architecture and its primary design goals.}

## System Diagram

```
{High-level ASCII or Mermaid diagram showing major components and data flow.}
```

## Components

### {Component 1}

- **Responsibility:** {What this component does.}
- **Interface:** {How other components interact with it (API, events, shared state).}
- **Key files:** `{path/to/main-file}`

### {Component 2}

- **Responsibility:** {What this component does.}
- **Interface:** {How other components interact with it.}
- **Key files:** `{path/to/main-file}`

## Data Flow

1. {Step 1: User/system triggers X.}
2. {Step 2: Component A processes and forwards to B.}
3. {Step 3: Component B returns result.}

## Key Design Decisions

| Decision | Choice | Alternatives Considered | Rationale |
|----------|--------|------------------------|-----------|
| {Decision} | {What was chosen} | {What else was considered} | {Why this choice} |

## Infrastructure

- **Deployment:** {How and where it runs (Docker, K8s, Vercel, etc.)}
- **CI/CD:** {Pipeline description}
- **Monitoring:** {How health is tracked}

## Dependencies

| Dependency | Purpose | Version |
|-----------|---------|---------|
| {dep} | {why} | {ver} |

## Future Considerations

- {Planned improvement or known technical debt item.}
