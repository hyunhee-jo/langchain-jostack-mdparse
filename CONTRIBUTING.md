# Contributing

## Development Setup

```bash
git clone https://github.com/hyunhee-jo/langchain-jostack-mdparse.git
cd langchain-jostack-mdparse
pip install -e .
pip install pytest pytest-socket ruff mypy
```

## Important: SYNCED Markers

Code between `# --- BEGIN SYNCED ... ---` and `# --- END SYNCED ... ---` markers
is auto-generated from upstream jostack-mdparse. **Do not edit these blocks manually.**

## Running Tests

```bash
make test
```

## Pull Requests

- One PR per feature/fix
- All tests must pass
- Do not modify SYNCED blocks (they are auto-generated)
