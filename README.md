# .github

## Workflows

[Shared workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows) used across my repos.

- [dependabot-auto-merge](.github/workflows/dependabot-auto-merge.yml) - Marks pull requests for auto-merge if they're from Dependabot and meet the specified criteria.
- [fixup-commits](.github/workflows/fixup-commits.yml) - Prevents pull requests from being merged if they contain [autosquash commit messages](https://git-scm.com/docs/git-rebase#git-rebase---autosquash).
