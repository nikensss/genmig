# Migration generation tool

Create a `.env` file based on the `.env.example` file and then run:

```bash
bun install
```

After that, you can run the migration generation script with:

```bash
bun run genmig
```

It will generate the migration based on the current branch you are on in the
specified `$REPO_DIR`, using the state in the `$DEV_BRANCH` as the baseline.

# Requirements

- bun
- fzf
- expect
- git
- zsh
- docker
- pnpm
