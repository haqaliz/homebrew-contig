# homebrew-contig

Homebrew tap for the [contig](https://github.com/haqaliz/contig) CLI: the
Layer-2 run, self-heal, verify, reproduce engine for bioinformatics pipelines.

## Install

```bash
brew install haqaliz/contig/contig
```

This installs the standalone release binary (no Python needed). A real pipeline
run still needs Nextflow, a Java runtime, and a container runtime; the
self-contained commands work without them.

## Upgrade

```bash
brew update
brew upgrade contig
```

The formula lives at `Formula/contig.rb`. It is generated from the source of
truth at [`homebrew/contig.rb`](https://github.com/haqaliz/contig/blob/master/homebrew/contig.rb)
in the main repo; see its `RELEASING.md` for how releases are cut.
