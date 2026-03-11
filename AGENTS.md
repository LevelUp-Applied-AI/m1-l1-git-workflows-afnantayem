# AGENTS.md

## Testing Requirements

Before committing any AI-assisted change, the environment test must pass:

`python test_environment.py`

Any additional Python scripts added to the project should run without errors locally before being committed.

---

## Secrets Policy

Do not include API keys, passwords, personal file paths, or raw datasets in prompts or commits.

Files that must never be committed include:

* `.env`
* `*.key`
* any file containing credentials or private data.

---

## Scope Boundaries

AI agents may edit documentation files such as `README.md` and simple Python scripts related to the project.

Changes to the following files require human review:

* `requirements.txt`
* `setup.sh`
* `.gitignore`

These files affect the project environment and repository behavior.

---

## Reproducibility Standard

Any AI-assisted change must be tested locally before committing.

The code must run successfully and produce the expected result on the local machine.
AI-generated code should always be reviewed and verified before being pushed to the repository.
