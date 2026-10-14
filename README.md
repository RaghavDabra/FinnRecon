# FinnRecon

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Python](https://img.shields.io/badge/Python-3.10%2B-3776ab.svg)

A **financial data reconciliation system** — it ingests financial datasets,
reconciles records across sources, and produces reports on the matches, breaks and
discrepancies it finds.

The full project lives in
[`financial-data-reconcillation-system-main/`](./financial-data-reconcillation-system-main),
which has its own detailed README. This top-level README is an overview and entry
point.

## Repository layout

```
financial-data-reconcillation-system-main/
  src/            core reconciliation engine
  scripts/        command-line entry points / runners
  data/           input datasets
  examples/       sample inputs and worked examples
  reports/        generated reconciliation reports
  results/        run outputs
  tests/          test suite
  requirements.txt
  README.md       detailed project documentation
```

## Getting started

```bash
cd financial-data-reconcillation-system-main

# install dependencies
pip install -r requirements.txt

# run the reconciliation (see scripts/ and the project README for exact commands)
python scripts/<runner>.py
```

See the
[project README](./financial-data-reconcillation-system-main/README.md) for the
full setup, configuration and usage instructions, including the reconciliation
inputs and report formats.

## License

Released under the [MIT License](./LICENSE). © 2026 Raghav Dabra.

## Author

Built by [Raghav Dabra](https://github.com/RaghavDabra).
