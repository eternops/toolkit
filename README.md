# ETERN Toolkit

AI-assisted recovery tools for aging software.

ETERN Toolkit helps engineers analyze, revive, and modernize aging software systems with minimal disruption.

It is designed for legacy recovery workflows such as:

- deprecated API detection
- framework migration assistance
- dependency repair
- Docker environment generation
- database compatibility analysis
- configuration reconstruction

The goal is simple:

**Make old software runnable again.**

---

## Philosophy

**Recover first. Replace only when necessary.**

Legacy systems often contain:

- valuable business logic
- undocumented behavior
- irreplaceable operational knowledge

Blind rewrites destroy these.

This toolkit exists to preserve them.

---

## Planned Features

### `scan`

Analyze legacy source code.

Example:

```bash
lrt scan ./legacy-project
```

Detect:

- deprecated PHP functions
- removed framework APIs
- obsolete dependencies
- incompatible runtime assumptions

---

### `doctor`

Generate recovery suggestions.

```bash
lrt doctor
```

Examples:

- replace `mysql_connect()` with PDO
- identify missing extensions
- detect framework upgrade blockers

---

### `dockerize`

Generate isolated runtime environments.

```bash
lrt dockerize
```

Output:

- Dockerfile
- docker-compose.yml
- runtime compatibility notes

---

### `migrate`

Generate minimal modernization patches.

```bash
lrt migrate
```

Goal:

- preserve behavior
- minimize code changes
- keep patches reversible

---

## Target Users

- legacy software consultants
- PHP maintenance engineers
- small technical teams
- digital preservation specialists
- organizations with undocumented systems

---

## Status

Early design phase.

This repository currently defines:

- ideas
- architecture
- specifications

Implementation will begin incrementally.
