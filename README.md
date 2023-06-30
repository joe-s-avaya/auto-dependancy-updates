# Automated Security and Dependancy Updates

The [renovatebot](https://github.com/renovatebot/renovate) is a completely free plugin for [most platforms](https://github.com/renovatebot/renovate#supported-platforms) (including github, bitbucket, and more). The Neo team uses it in all of their products and have created this repository to show that it can manage any type of project that is NPM based.

## Why should I use this?

The renovatebot automatically creates PRs to:

- update all of your repository dependancies
- resolve security risks in those dependancies
- gives you data in every PR it generates on age, adoption, and [merge confidence](https://docs.renovatebot.com/merge-confidence/)

See the [official docs](https://docs.renovatebot.com) for even more reasons. See [this PR from June 26th 2023](https://github.com/avaya-dux/neo-react-library/pull/217) for an example of what these PRs look like.

## Setup Instructions

Simply install [the plugin](https://github.com/apps/renovate) (github link) to your instance. We recommend _also_ setting up a config file ([see ours here](./.github/renovate.json5)), but that is optional. You can contact anyone on the Neo team for assistance if you have questions.

## Notes on how to use this repository

Note that all of these projects are simply instantiated with defaults and little to no work has been done on them. You should _not_ be using any of the code in this repository. The only files you should use as guides are the [renovate config file](./.github/renovate.json5) and the [root level `package.json`](./package.json).

Note that renovate creates [an "issue"](https://github.com/joe-s-avaya/auto-dependancy-updates/issues/3) that you can use to run and rerun checks for it. You should leave this open.

## Not Shown, non-js languages

The renovatebot also works with non-js languages such as Java. I will not be demonstrating that in this repository.
