# Automated Security and Dependancy Updates

The [renovatebot](https://github.com/renovatebot/renovate) is a completely free plugin for [most platforms](https://github.com/renovatebot/renovate#supported-platforms) (including github, bitbucket, and more). The Neo team uses it in all of their products and have created this repository to show that it can manage any type of project that is NPM based.

## Setup Instructions

Simply install [the plugin](https://github.com/apps/renovate) (github link) to your istance. We recommend _also_ setting up a config file ([see ours here](./.github/renovate.json5)), but that is optional. You can contact anyone on the Neo team for assistance if you have questions.

## Not Shown, non-js languages

The renovatebot works with non-js languages such as Java.

## Notes on how to use this repository

Note that all of these projects are simply instantiated with defaults and little to no work has been done on them. You should _not_ be using any of the code in this repository. The only files you should use as guides are the [renovate config file](./.github/renovate.json5) and the [root level `package.json`](./package.json).
