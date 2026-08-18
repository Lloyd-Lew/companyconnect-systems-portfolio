# Lightweight GitHub Engineering Standard

This standard applies when CompanyConnect.Tech creates or takes ownership of an active technical repository. Its purpose is consistent engineering discipline without adding process for its own sake.

## Repository naming and ownership

Use a concise, descriptive, lowercase-hyphenated repository name. Every active repository needs a named technical owner, a named commercial owner where client impact exists, and an explicit visibility decision. Configure `CODEOWNERS` once more than one maintainer can merge changes.

## Documentation before growth

Every active repository should explain the problem, intended users, system boundaries, safe setup path, configuration requirements, tests, security considerations, release status, and the appropriate support route. Portfolio repositories should document client-safe capability; runnable repositories should document installation and operation.

## Branches, changes, and review

Use short-lived branches for material changes, descriptive commits that explain intent, and pull requests for reviewed work. Enable a protected default branch and at least one review requirement before collaborators receive write access. Do not create artificial pull requests, commits, releases, or activity merely to make GitHub appear active.

## Security and sensitive configuration

Never commit credentials, tokens, customer data, production URLs, or raw customer workflow exports. Use environment variables and GitHub Secrets for CI values. Enable secret scanning and push protection where available. Add a `SECURITY.md` file to any public repository and ensure that sensitive reports have a private route.

## Testing and CI

For runnable code, automate the highest-value confidence checks: formatting or linting, type checks, unit or integration tests for business-critical behavior, and production builds where appropriate. CI must reflect real risk; documentation-only repositories do not need ceremonial code workflows.

## Dependencies and releases

Review dependencies when code is added or updated. Enable dependency alerts and updates when a repository has package manifests. Use releases, tags, and changelogs only for software that is shipped or consumed as a defined versioned artefact.

## Visibility, archiving, and retention

Client and operational repositories remain private by default. Archive a repository only after confirming that it has no active operational purpose, retention requirement, contractual requirement, or intended future use. Never delete repositories, history, or production material without explicit owner approval and a recovery plan.
