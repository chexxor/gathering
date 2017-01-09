Gathering is a self hosted website for announcing group events.

Since this is a learning project for now I will not address issues and will not merge pull requests.

> Status: Design phase

> License: Apache License 2.0

## Deps

This package requires:

- `stack`
- `postgresql-9.5+`

## Setup

Here are the different make options:

- `setup`: Install GHC and deps for the package using stack
- `initdb`: Create the `gather` role and database and the relevant tables
- `build`: Build the haskell package
- `dev`: Continuously build on file changes - good for development
- `run`: Execute the server with the default settings
- `clean_all`: Delete the package build and the database
- `clean_db`: Drop the tables, the database and the 'gather' role

