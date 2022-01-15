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

How to name a commit?
* build: fuji updated
* feat: upgrade of user listing
* fix: user filtering
* 1.0.156
* chore: README.md

Code comments:
* You can and should write code, not comments
* If you find a case to write a comment make sure that:
  1. Every file, class, function and variable is well named
  2. Class, function, variable makes one thing
  3. Function is not to long and confusing
  4. Link to documentation you can write as a private, static, final, readonly string in class
  5. Not implemented element? Throw runtime exception
  6. You comment explains WHY something is done, but not HOW
