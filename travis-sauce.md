## Setting Up Travis and Sauce Labs for CI

On many projects you'll want to ensure that when someone else updates/adds code that it will not break the existing code base.

This is where continuous integration comes in. CI ensures that code cannot be merged into a particular repo until all unit tests are passing.

1. Write unit tests
2. Create a `.travis.yml` file
3. `npm i zuul --save-dev`
4. Create a `.zuul.yml` file
5. Create Sauce Labs Account if an OSS Project
6. Encrypt Sauce Labs Credentials and add to `.travis.yml`
7. Ensure that Travis is setup for the repo
