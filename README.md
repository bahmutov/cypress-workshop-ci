# cypress-workshop-ci
> A workshop that teaches you how to run Cypress on major CI providers

**Warning: ⚠️** this is not an introduction to Cypress testing workshop, only how to successfully run Cypress on CI. If you need to refresh your Cypress skills, check out the [bahmutov/cypress-workshop-basics](https://github.com/bahmutov/cypress-workshop-basics)

## Requirements

You will need:

- `git` to clone the repository
- Node v12+ to install and run locally
- 👉 fork the [bahmutov/cypress-workshop-ci-example](https://github.com/bahmutov/cypress-workshop-ci-example) now 👈

### Create free accounts

- GitHub [https://github.com/](https://github.com/)
- CircleCI [https://circleci.com/](https://circleci.com/)
- Netlify [https://www.netlify.com/](https://www.netlify.com/)
- Cypress Dashboard [https://dashboard.cypress.io/](https://dashboard.cypress.io/)

## Slides 🖥

See the presentation at [https://cypress-workshop-ci.netlify.app/][presentation]. Every section of the presentation has a subfolder in the [slides](./slides) folder with a Markdown file. The Markdown is rendered into HTML using [Vite and Reveal.js combination](https://glebbahmutov.com/blog/reveal-vite/). You can open the presentation by clicking on "view slides" links in the table below.

[presentation]: https://cypress-workshop-ci.netlify.app/

## Content 🗂

topic | Markdown | view slides
---|---|---
Introduction | [intro](./slides/intro/README.md) | [intro slides](https://cypress-workshop-ci.netlify.app/?p=intro)
Generic CI | [generic-ci](./slides/generic-ci/README.md) | [generic ci slides](https://cypress-workshop-ci.netlify.app/?p=generic-ci)
GitHub Action | [github-action](./slides/github-action/README.md) | [github action slides](https://cypress-workshop-ci.netlify.app/?p=github-action)
Circle CI Orb | [circleci](./slides/circleci/README.md) | [circleci slides](https://cypress-workshop-ci.netlify.app/?p=circleci)
Netlify Build plugin | [netlify-build](./slides/netlify-build/README.md) | [netlify build slides](https://cypress-workshop-ci.netlify.app/?p=netlify-build)

## Self-paced workshop

This workshop should have all the content necessary to learn how to run Cypress on continuous integration service. Use the example application and follow the written steps above. I suggest starting with the introduction and then picking one of the topics matching your situation. If you get stuck, or something is unclear, do not hesitate to open a GitHub issue in this repository to improve this workshop.

## Content index

1. Introduction [slides](https://cypress-workshop-ci.netlify.app/?p=intro)
   1. requirements
   2. example repo [bahmutov/cypress-workshop-ci-example](https://github.com/bahmutov/cypress-workshop-ci-example)
   3. NPM scripts and commands
   4. Cypress binary and info
2. Running Cypress on generic CI [slides](https://cypress-workshop-ci.netlify.app/?p=generic-ci)
   1. GitHub CI workflow
   2. caching dependencies
   3. waiting for the server to start
   4. storing test artifacts on CI
   5. recording tests on Cypress Dashboard
3. Cypress GitHub Action [slides](https://cypress-workshop-ci.netlify.app/?p=github-action)
   1. installing and running Cypress using action
   2. building the application
   3. action versions
   4. run tests in parallel
   5. split workflow into jobs
4. Cypress CircleCI Orb [slides](https://cypress-workshop-ci.netlify.app/?p=circleci)
   1. running the tests
   2. recording the test artifacts
   3. saving the workspace
   4. separate the install job from the test job
   5. testing in parallel
5. Cypress Netlify plug [slides](https://cypress-workshop-ci.netlify.app/?p=netlify-build)
   1. deploy project on Netlify
   2. run E2E tests after deploy
   3. recording test results
   4. run E2E tests before build
   5. set up Cypress GitHub Integration
   6. set up GitHub status checks

## Example application

We will test the example application from the repo [bahmutov/cypress-workshop-ci-example](https://github.com/bahmutov/cypress-workshop-ci-example). You should fork that repo under your GitHub account and use with each CI provider.

## Attribution

I have created this repo originally while working at Cypress.io, see [cypress-io/cypress-workshop-ci](https://github.com/cypress-io/cypress-workshop-ci)

## Author

Gleb Bahmutov has PhD in Computer Science and has worked at Cypress.io for four years as VP of Engineering and Distinguished Engineer, and was heavily involved in all areas of the Test Runner development, as well as Cypress Dashboard features, plugin writing, and CI integration. He has spoken about Cypress approximately a hundred times at meetups and conferences, wrote 100s of blog posts about testing, and has recorded more than 150 Cypress videos available for free on his YouTube channel. Today, Gleb is still heavily using Cypress at a large company making sure its web applications are always working correctly.

## Other workshops

If your organization is interested in learning about Cypress in depth, please contact me. Besides this "Cypress Basics" workshop, I also regularly teach the following workshop.

- https://github.com/bahmutov/cypress-workshop-basics
- https://github.com/bahmutov/cypress-workshop-socketio-chat

Of course, I can customize a workshop to your needs, if necessary. Please let me know by getting in touch; you can email me at gleb.bahmutov at gmail.com.

## Additional information

- https://www.cypress.io/
- https://docs.cypress.io/
- https://glebbahmutov.com/cypress-examples/
- https://cypress.tips/
- https://www.youtube.com/glebbahmutov
- https://slides.com/bahmutov
