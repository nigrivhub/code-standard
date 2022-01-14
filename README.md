# Nigriv Code Standard

Main idea about project is: what should I do to make biggest change in production?
Use this everytime you need to decide what to do next.

What you should put into project:
* source code
* preparation scripts for databases
* client libraries
* deployment template
* minimal requirements in README.md

What you musn't put into project:
* compiling outputs
* credentials, passwords or tokens
* media assets (in 95%)

What you should use:
* company libraries if possible
* linter
* (suggestion) digital sketch over task list

How you should test:
* use unit tests to cover own data structures and no data, crucial elements
* use e2e to test scenarios and business logic using database
* don't use mockups
