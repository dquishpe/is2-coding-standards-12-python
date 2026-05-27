# loan-eligibility-python

Loan eligibility calculator for a cooperativa de ahorro y crédito. Computes whether a member is eligible for a loan and at what rate, based on income, debt, employment, and savings history.

## Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the tests

```bash
pytest
```

## Use it from the CLI

```bash
python -m loan.cli --income 1200 --debt 320 --tenure-months 18 --age 34 --savings-balance 850
```

## Linter / Static Analysis Tool

| Field | Details |
|-------|---------|
| **Tool** | SonarQube for IDE (formerly SonarLint) |
| **Version** | v5.2.3 |
| **Publisher** | SonarSource |
| **Identifier** | sonarsource.sonarlint-vscode |
| **Marketplace** | [SonarQube for IDE on VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode) |

> **Note:** SonarQube for IDE was rebranded from SonarLint in 2025. It is the same tool listed in the allowed tools for this workshop under the name **SonarLint**.

---
