# REST-PERSISTENT-DATA-API

# Reflection

During this project, I recreated a clinical patient data API using Flask, SQLAlchemy, SQLite, and JSON Lines file storage. The process involved creating a database connection, defining a data model, building schemas for data validation, and creating API endpoints to add and retrieve patient records. I also implemented data persistence in both a SQLite database (clinical_data.db) and a JSON Lines file (clinical_data.jsonl).

One of the primary challenges I encountered occurred when adding three new clinical data fields to the application. While I was able to update the model, schema, and API code, I received database errors indicating that the new columns did not exist in the database table. I attempted several troubleshooting steps, including deleting the database file, recreating the database, reviewing the model definitions, and verifying that the code was properly updated. Despite these efforts, I was unable to fully resolve the issue before completing the assignment.

Although the application did not function exactly as intended, the project helped me better understand how Flask, SQLAlchemy, and SQLite work together. I gained experience debugging database-related issues and learned that changes to application models do not always automatically update an existing database schema. In the future, I would like to learn more about database migrations, schema management tools such as Alembic, and advanced troubleshooting techniques for web applications and databases. Overall, the assignment provided valuable hands-on experience with API development and data persistence concepts.
