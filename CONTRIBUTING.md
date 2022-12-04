# Contribution guide

- [Contribution guide](#contribution-guide)
  - [Ways to contribute](#ways-to-contribute)
  - [Finding an issue](#finding-an-issue)
  - [Ask for help](#ask-for-help)
  - [Pull request lifecycle](#pull-request-lifecycle)
  - [Setting up the development environment](#setting-up-the-development-environment)
    - [Forking and cloning the project](#forking-and-cloning-the-project)
      - [Prerequisites](#prerequisites)
  - [Signing commits](#signing-commits)

Welcome 👋 Thank you for your interest in contributing to our project. We are happy to have you join us! 💖

As you get started, you are in the best position to give us feedback on project areas we might have forgotten about or assumed to work well. These include, but are not limited to, the following:

- Problems found while setting up a new developer environment
- Gaps in our documentation
- Bugs in our automation scripts

If anything doesn't make sense or doesn't work as expected, please open an issue and let us know!

## Ways to contribute

We welcome many different types of contributions including:

<!-- TODO: These are not set in stone and should be reconsidered per project based on needs. -->

- New features and content suggestions.
- Identify and filing issues.
- Providing feedback on existing issues.
- [Engaging with the community](https://discord.gg/XzT3ww5tef) and answering questions.
- Contributing documentation or code.
- Design.
- Promoting the project in personal circles and social media.
- Helping to improve process.
- Attending meetings and events.

## Finding an issue

We have good first issues for new contributors and help wanted issues suitable for any contributor. Good first issues have extra information to help you make your first contribution a success. Help wanted issues are ideal when you feel a bit more comfortable with the project details.

Sometimes there won’t be any issues with these labels. That’s ok! There is likely still something for you to work on. If you want to contribute but don’t know where to start or can’t find a suitable issue, speak to us on [Discord](https://discord.gg/XzT3ww5tef), and we will be happy to help.

Once you find an issue you’d like to work on, please post a comment saying you want to work on it. Something like “I want to work on this” is fine. Also, mention the core team using the `@The-Mycelium-Network/mycelium-network-maintainers` handle to ensure someone will get back to you.

## Ask for help

The best way to reach us with a question when contributing is to use the following channels in the following order of precedence:

- [Start a discussion](https://github.com/orgs/The-Mycelium-Network/discussions).
- Ask your question or highlight your discussion on [Discord](https://discord.gg/XzT3ww5tef).
- File an issue and tag the core team using the `@The-Mycelium-Network/mycelium-network-maintainers` handle.

## Pull request lifecycle

For guidance on how to approach pull requests and what you can expect from maintainers and other contributors, please see our [detailed documentation here](TODO: add link when https://github.com/The-Mycelium-Network/the-mycelium-network/pull/3 is merged).

<!-- TODO: This will be project specific. Sometimes changes might be live instantly or within a few minutes. Update accordingly. -->

Once a pull request is merged, the changes will be live within 24 hours.

## Setting up the development environment

<!-- This is very project specific. The below is merely some guidance that might be applicable for most projects. -->

### Forking and cloning the project

The first step in setting up your development environment is to [fork the repository](https://docs.github.com/en/get-started/quickstart/fork-a-repo) and [clone](https://docs.github.com/en/get-started/quickstart/fork-a-repo#cloning-your-forked-repository) the repository to your local machine.

#### Prerequisites

- [NVM](https://github.com/nvm-sh/nvm) or [NVM for Windows](https://github.com/coreybutler/nvm-windows).
- [Nodejs](https://nodejs.org/en/) (Latest stable release or up to two versions back).

Once you have the above installed and have the repository cloned, it is time to install the project dependencies.

```bash
npm i
```

With the dependencies installed you can start the project with the following command:

```bash
npm start
```

Open `http://localhost:3000` in your browser.

To run the test suite, use the following command:

```bash
npm test
```

<!-- This section is project dependent. For some projects this can be an unnecessary stumbling block. -->

## Signing commits

We require all commits to be signed. GitHub has a detailed guide on [setting up signed commits](https://docs.github.com/en/authentication/managing-commit-signature-verification/signing-commits). If you get stuck, please [ask for help](#ask-for-help).
