# Monitor

A free compute + scheduling shell for a private project. This repo holds
no application logic of its own -- it exists solely because GitHub
Actions minutes are billed on whichever repo a workflow runs in, and
public repos get unlimited free minutes on GitHub-hosted runners.

`.github/workflows/pumpfun-runner.yml` checks out a private repo's code
on a schedule, runs it, and pushes the results straight back. See that
workflow file's own header for the full setup and reasoning.
