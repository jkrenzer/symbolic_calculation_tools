# symbolic_calculation_tools

## Development quick start

1. Install Poetry (latest recommended).
2. Install dependencies:
   ```bash
   poetry install --with dev
   ```
3. Install hooks with prek:
   ```bash
   poetry run prek install
   poetry run prek install --hook-type commit-msg
   ```

Conventional commits are enforced through Commitizen (`cz check`) on the `commit-msg` hook.
