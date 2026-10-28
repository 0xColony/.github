# Contributing to 0xColony

First off: thanks for being here. Colony exists so anyone, from first-time contributors to seasoned engineers, can build, learn and ship together. You don't need permission or a perfect resume to contribute.

## Ways to Contribute

You don't have to write code to help:

- **Code:** fix bugs, add features, improve performance
- **Docs:** fix typos, clarify the README, write guides
- **Issues:** report bugs, suggest ideas, reproduce other people's bugs
- **Review:** read open PRs and leave constructive feedback
- **Community:** help others in the [Discord](<your-discord-invite>)
- **Start something new:** have an idea for a project? Pitch it in Discord and we'll help you set it up under the org

## Before You Start

1. Read our [Code of Conduct](CODE_OF_CONDUCT.md). It applies on GitHub and Discord.
2. Join the [Discord](https://discord.gg/TR2cenyzx) and say hi. It's the fastest way to get help.
3. Check existing issues and PRs so you don't duplicate work.

## Finding Something to Work On

- Look for issues labeled **`good first issue`** (beginner-friendly) or **`help wanted`**.
- Comment on the issue to claim it, so two people don't build the same thing.
- If nothing fits, open an issue describing what you'd like to do **before** writing a big PR.

## Rules for Contribution(IMPORTANT)

1. **Use AI as a tool, not a substitute.** AI assistants are welcome for brainstorming, debugging, and drafting. But you are responsible for every line you submit. If you can't explain what your code does and why, don't open the PR. Low-effort, unreviewed AI dumps will be closed.
2. **Be upfront about it.** If a significant part of your PR was AI-assisted, mention it in the description. No shame in it, it just helps reviewers know what to look at closely.
3. **Join the conversation.** Discuss issues, ideas and improvements in the official [Colony Discord](https://discord.gg/hB42EX8p2) before building anything big. It saves everyone from wasted work.
4. **Beginners are welcome.** If you're new, start with issues labeled `good first issue`. Asking questions is encouraged, and nobody here expects you to already know everything.
5. **Claim before you build.** Comment on an issue and wait for a maintainer to acknowledge before you start, so two people don't do the same work.
6. **One PR, one purpose.** Keep changes small and focused. A PR that fixes a bug, reformats three files and adds a feature will get sent back.
7. **Be kind in review.** Critique the code, never the person, and take feedback in the same spirit. Our [Code of Conduct](CODE_OF_CONDUCT.md) applies everywhere.

## Making a Contribution

1. **Fork** the repository.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/<repo>.git
   cd <repo>
   ```
3. **Create a branch** with a descriptive name:
   ```bash
   git checkout -b fix/short-description
   ```
4. **Make your changes.** Keep them focused: one fix or feature per PR.
5. **Test your changes** and follow the project's setup instructions in its README.
6. **Commit** with a clear message:
   ```bash
   git commit -m "fix: handle empty input in parser"
   ```
7. **Push** to your fork and **open a Pull Request** against `main`.

## Commit Messages

We loosely follow [Conventional Commits](https://www.conventionalcommits.org/):

- `feat:` new feature
- `fix:` bug fix
- `docs:` documentation only
- `refactor:` code change that isn't a fix or feature
- `test:` adding or fixing tests
- `chore:` tooling, config, housekeeping

## Pull Request Guidelines

- Link the issue your PR addresses (e.g. `Closes #12`).
- Describe **what** changed and **why**.
- Keep PRs small and reviewable. Big PRs are hard to review and slow to merge.
- Make sure checks pass, if the repo has any.
- Be open to feedback. Review is how we all get better, not a judgment on you.

## What to Expect from Review

Colony is volunteer-run. We'll try to respond within a few days, but it may take longer. If your PR has been quiet for a week, a friendly ping in the PR or on Discord is welcome. Reviews are about the code, never the person, and "request changes" is a normal part of the process, not a rejection.

## Reporting Bugs

Open an issue and include:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Your environment (OS, language/tool versions)

## Security Issues

**Please don't open public issues for vulnerabilities.** See our [Security Policy](SECURITY.md) for how to report them privately.

## Questions?

Ask in the [Discord](<your-discord-invite>) or see [SUPPORT.md](SUPPORT.md).

## License

By contributing, you agree that your contributions will be licensed under the same license as the project you're contributing to (see each repository's `LICENSE` file).

Thanks for building with us. 🤝
