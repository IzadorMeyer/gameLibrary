### Releasing

To release your library to `bower` initially:

1. Save your changes to the `index.js` file.
2. `git add -A`
3. `git commit -m "* add makeBody method"`
4. `git tag -a v1.0.0 -m "init"`
5. `git push origin main --tags`.  **DON'T FORGET --tags**

<hr>

### Updating 

To re-release your library to `bower`:

1. Save your changes to the `index.js` file.
2. Open up the `bower.json` file, and increment the version number, from `1.0.0` to `1.1.0` (or from its previous version to the next version). Save the file.
3. `git add -A`
4. `git commit -m "<message that describes changes>"`
5. `git tag -a v1.1.0 -m "<message that describes changes>"`
6. `git push origin main --tags`.  **DON'T FORGET --tags

References:

* <a href="https://git-scm.com/book/en/v2/Git-Basics-Tagging" target="_blank">Git Tagging</a>
* <a href="https://docs.npmjs.com/about-semantic-versioning" target="_blank">Semantic Versioning</a>
