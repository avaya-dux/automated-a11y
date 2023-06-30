# Automated Accessibility (a11y)

This is an example repository detailing how to automate a11y and add unit testing for it as well.

## Why should I use this?

- reduce [cognitive load](https://github.com/zakirullin/cognitive-load) by automating
- have fewer bugs opened
- set standards that all devs can easily follow and thus reduce code complexity

## Setup Instructions

- add github action ([see example files](./.github/workflows/))
  - see the [official plugin docs](https://github.com/treosh/lighthouse-ci-action) for more info
- optionally add configuration for plugin ([see example file](./lighthouserc.json))
  - note that this file is optional, but highly recommended so that you have control on your own requirements
  - [this is where I got some of my config values](https://github.com/GoogleChrome/lighthouse-ci/blob/main/docs/configuration.md#categories), and you can [view many more options here](https://github.com/GoogleChrome/lighthouse/blob/v5.5.0/lighthouse-core/config/default-config.js#L375-L407)
- add a branch protection rule so that PRs cannot go through unless they pass these checks

## Notes on how to use this repository

Note that all of these projects are simply instantiated with defaults and little to no work has been done on them. You should use the test files as a _general_ guide, but note that they are minimal examples. You can contact anyone on the Neo team for assistance if you have questions.

### quick notes

- [Angular Site](https://automated-a11y-angular.netlify.app)
- [React Site](https://automated-a11y-react.netlify.app)
- [Svelte Site](https://automated-a11y-svelte.netlify.app)
- [plugin github repo](https://github.com/treosh/lighthouse-ci-action)
