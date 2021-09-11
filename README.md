# git_environment_branching

Rob Menning

These files demonstrate one approach to Git branching in a multi-developer enterprise setting.

The main goals of this strategy are:
1. One dedicated branch for each environment for clean integration with CI/CD pipes.
2. Protect the production branch (production environment) from unintended changes during deployments.
3. Isolate deployments to small autonomous changes for simpler rollback.
4. Discover merge conflicts early and often.
