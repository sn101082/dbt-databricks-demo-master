DBT Project example

### Setup

- python -m venv dbt-env
- pip install dbt
- pip install "dbt-spark[ODBC]" OR pip install "dbt-spark[PyHive]"

Try running the following commands:
- dbt compile
- dbt debug
- dbt test
- dbt run
- dbt docs generate
- dbt docs serve

### Limitations
- No support for Azure password passthrough
