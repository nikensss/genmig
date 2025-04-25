# Migration generation tool

Create a `.env` file based on the `.env.example` file and then run:

```bash
bun run genmig
```

It will show a list of the currently available branches. Select the one for
which you want to generate the migration for.

# Requirements

- bun
- fzf
- expect
- git
- zsh
- docker
- pnpm
