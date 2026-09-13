# corerun skills

Skills that teach a coding agent to drive [corerun](https://github.com/corerunai/corerun)
through its CLI.

```
/plugin marketplace add corerunai/skills
/plugin install corerun@corerun
```

They drive the `corerun` CLI, so they are useful anywhere it is
installed and logged in. `pip install corerun-sdk` ships the same
skills, and `corerun skills install` copies them into an agent's
skills directory — this repository exists so that neither is required.

## This repository is generated

Do not edit it. The skills live in
[corerunai/corerun](https://github.com/corerunai/corerun) under
`corerun-sdk/src/corerun/skills/`, beside the CLI they describe,
because a skill and the commands it documents have to change together.
Anything committed here by hand is overwritten on the next publish.
