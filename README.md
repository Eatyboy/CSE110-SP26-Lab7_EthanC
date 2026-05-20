# CSE 110 SP26 Lab 7
## Ethan Carter

1) You'd fit an automated test suite in a GitHub action (or other version control CI/CD pipeline) that runs whenever code is pushed to ensure that the tests are always ran when code changes. This ensures that all code changes are correct according to the tests, and it also allows for things like preventing merges when tests fail.

2) No, that's what unit tests are for.

3) Navigation mode only analyzes the page state right after it loads, whereas snapshot mode analyzes the current page state. Navigation mode is good for overall performance information, and snapshot mode is good for finding issues, particularly accessibility issues, isolated to the current page state.

4) We could add a meta description for SEO, a `[lang]` attribute to the `<html>` element for accessibility, and we could optimize the viewport for mobile to improve performance.
