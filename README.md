# Movies_ETL

Assumption 1: JSON file must be used for wiki_movies_raw. This will require a json module import.

Assumption 2: Requirement for postgres to be downloaded in order for sqlalchemy to import create_engine

Assumption 3: Protect private information by storing db_password on separate text file. File can either be included in gitignore or not committed.

Assumption 4: Ensure Database is created in sql prior to data being uploadted using Data.to_sql fuction

Assumption 5: After data load, confirm all columns converted correctly.
