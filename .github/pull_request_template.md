# ⚠️ __IMPORTANT: Please do not create a Pull Request without creating an Issue first.__

All changes need to be discussed before proceeding. Failure to do so may result in the pull request being rejected.

Before submitting a pull request, please be sure to review:
- Our Code of Conduct: https://github.com/COVID-19-electronic-health-system/.github/blob/master/CODE_OF_CONDUCT.md
- Our Contributing Guidelines: https://github.com/COVID-19-electronic-health-system/.github/blob/master/CONTRIBUTING.md
- Our Support documentation: https://github.com/COVID-19-electronic-health-system/.github/blob/master/SUPPORT.md

-----

## Please include the issue number the pull request fixes by replacing YOUR-ISSUE-HERE in the text below.

Fixes #YOUR-ISSUE-HERE

## Summary

<!-- Please provide a basic summary of what this pull request fixes so that others can review it. -->

## Details

<!-- Please explain the details for any changes. What existing problem does this pull request solve? -->

## Test Plan (required)

<!-- Demonstrate the code is solid, e.g. list the exact commands you ran and their output, and screenshots/video if the pull request modifies the UI. -->

## Final Checklist

- [ ] For CoronaTracker, did you bump the version in `package.json`?
    - Update the second decimal for a major change
    - Update the third decimal for a minor change
    - Numbers can go past 9, e.g. `1.0.9` => `1.0.10`
    - For more info, read about [Semantic Versioning](https://semver.org/)
- [ ] Did you add any new tests as necessary?
- [ ] Is your PR rebased off the most current master?
- [ ] Have you squashed all commits? _(can be done at merge)_
- [ ] Did you use `yarn` not `npm`? _(important!)_
- [ ] Did you use Material-UI wherever possible?
- [ ] Did you run `yarn lint` on the code?
- [ ] Did you run all of your most recent changes locally to make sure everything is working?
