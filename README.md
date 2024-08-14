# Sample Snowflake Notebook for Data Transformation

1. Create a Database called "testing_db" and create a table called "users" in "public" schema.
2. Load the table by using the "username-or-email.csv".
3. Add the notebook and execute all.

## What does the notebook does

1. Connect and create a session with the snowflake database.
2. Filters the users table for records with username matching "johnson81".
3. Generate a new email using a UUID.
4. Upsert the formatted record in to the table.