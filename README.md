# corerun skills

Skills that teach a coding agent to drive [corerun](https://corerun.ai) through
its CLI.

```
/plugin marketplace add corerunai/skills
/plugin install corerun@corerun
```

They drive the `corerun` CLI, so they are useful anywhere it is installed and
logged in:

```bash
uv tool install "git+https://github.com/corerunai/corerun-sdk.git"
corerun login
```

Installing the CLI ships the same skills, and `corerun skills install` copies
them into an agent's skills directory — this repository exists so that neither
is required.

## This repository is generated

Do not edit it. The skills live in `corerun-sdk/src/corerun/skills/` in the
corerun repository, beside the CLI they describe, because a skill and the
commands it documents have to change together. Anything committed here by hand
is overwritten on the next publish.
