# Sample Snowflake Notebook for Data Transformation

## Transform From Table Notebook (transform-from-table-notebook.ipynb)

Load data to a table by using snowsight load data option and the "username-or-email.csv".

1. Connect and create a session with the snowflake.
2. Filters the users table for records with username matching "johnson81".
3. Generate a new email using a UUID.
4. Upsert the formatted record in to the table.

## Transform From Stage CSV Notebook (transform-from-stage-csv-notebook.ipynb)

Create a stage in the database and upload the CSV to the created stage.

1. Connect and create a session with the snowflake.
2. Read the file from the stage.
3. Generate a new email using a UUID.
4. Upsert the formatted record in to the table.