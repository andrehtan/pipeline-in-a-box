# Pipeline in a box

## What this is
Portfolio project: load a public dataset with dlt into DuckDB,
model and test it with dbt, run it daily on GitHub Actions,
and show results in a small dashboard.

## Stack
Python, dlt, DuckDB, dbt Core (dbt-duckdb), GitHub Actions,
Streamlit or Evidence. Windows + Git Bash.

## Layout
- ingest/      dlt pipeline code
- transform/   dbt project
- app/         dashboard
- docs/        data profile, AI review log, design notes

## How to work with me
- I'm learning. Explain your plan before writing code, and
  keep changes small: one step at a time.
- Never commit, push or merge without asking me.
- If you're unsure a library function or flag exists, say so
  and point me to the doc page. Don't guess.

## Rules
- Never read, print or commit .env or any secret.
- Work on a branch, never directly on main.
