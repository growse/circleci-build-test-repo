# README file

Reqs for this:

- There are a number of CI jobs. Build, test, integration-test, smoke-test
- Integration tests are heavy, so let's not run them all the time.
- Commits to main should run build / test / integration-test / release only if the source changes.
- Int tests should only be triggered when there's a GHA label trigger on a PR
- Smoke tests should only be triggered when there's a GHA label trigger on a PR
