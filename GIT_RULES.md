## Commit Rules:

This commits rules is set to ensure all the developers follows a uniform way of writing commits so that it is easy to read the changes made and also automate versioning.
The commits are based on [conventional commit](https://www.conventionalcommits.org/en/v1.0.0/) which is a widely followed convention for commits. While writing a commit message to any changes made to code base, make sure it reflects the changes and follows the conventions i.e:

```
change_type(package_name): short description/subject line...

Long Description...
```

Here,

change_type means the type of changes like `feat`,`fix` and so on.

package_name means which packages this changes is for. This is optional.

short discription/subject line means about the changes

Long Description are optional. Add it if its required to reflect the changes in more detail.

For eg:

Lets say the changes is about implementing a new feature which is about new social login mechanism in `deriv_auth` package.

```
feat(deriv_auth): add ability to sign in with google

- create UI for login pages
- add state functionality
- add google services for authentication
```

More changes types:

| Changes Types | Meaning                    | Description                                                                                                   |
| ------------- | -------------------------- | ------------------------------------------------------------------------------------------------------------- |
| feat          | Features                   | A new feature                                                                                                 |
| fix           | Bug Fixes                  | A bug fix                                                                                                     |
| chore         | Chores                     | Other changes that don’t modify src or test files                                                             |
| docs          | Docume­ntation             | Docume­ntation only changes                                                                                   |
| revert        | Reverts                    | Reverts a previous commit                                                                                     |
| refactor      | Code Refact­oring          | A code change that neither fixes a bug nor adds a feature                                                     |
| test          | Tests                      | Adding missing tests or correcting existing tests                                                             |
| style         | Styles                     | Changes that do not affect the meaning of the code (white­ -space, format­ting, missing semi-c­olons, etc)    |
| perf          | Perfor­mance Improv­ements | A code change that improves perfor­mance                                                                      |
| build         | Builds                     | Changes that affect the build system or external depend­encies (example scopes: gulp, broccoli, npm)          |
| ci            | Continuous Integr­ations   | Changes to our CI config­uration files and scripts (example scopes: Travis, Circle, Browse­rStack, SauceLabs) |

## PR Rules:
