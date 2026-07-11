# lucos_architecture_models

Generated architectural models of the lucOS estate.

**This repository is generated — do not hand-edit.**

The `lucos_repos` audit sweep regenerates `model.dsl`, `landscape.md`, and
`divergences.md` here on every sweep (~every 6 hours), sourced from configy,
loganne, and each system's `/_info` endpoint. Hand edits will be silently
overwritten on the next sweep.

See [ADR-0006](https://github.com/lucas42/lucos_repos/blob/main/docs/adr/0006-c4-estate-model.md)
and [ADR-0008](https://github.com/lucas42/lucos_repos/blob/main/docs/adr/0008-c4-output-relocation.md)
in `lucos_repos` for the generation model and the decision to relocate output here.