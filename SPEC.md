# SPEC

Technical specification for Legacy Revival Toolkit.

---

## CLI Name

```bash
lrt
```

---

## Command Structure

### scan

```bash
lrt scan <path>
```

Purpose:

Analyze source tree.

Outputs:

- detected language
- framework
- dependency risks
- deprecated APIs

---

### doctor

```bash
lrt doctor <path>
```

Purpose:

Produce actionable recovery recommendations.

Outputs:

- warnings
- suggested fixes
- compatibility notes

---

### dockerize

```bash
lrt dockerize <path>
```

Outputs:

- Dockerfile
- docker-compose.yml
- env template

---

### migrate

```bash
lrt migrate <path>
```

Outputs:

- patch files
- migration notes

---

## Core Components

### Analyzer Engine

Responsibilities:

- AST parsing
- dependency graphing
- config extraction

---

### Rule Engine

Rule examples:

- deprecated PHP API mappings
- framework upgrade paths
- extension requirements

---

### Suggestion Engine

LLM-assisted explanations.

Inputs:

- source snippets
- analyzer findings

Outputs:

- human-readable guidance
- patch suggestions

---

### Output Renderer

Formats:

- terminal
- markdown report
- JSON

---

## Safety Requirements

Must never:

- overwrite original code
- auto-apply destructive changes

Must always:

- preserve source
- generate diffs
- explain modifications
