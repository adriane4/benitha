# GitHub Agent Demo

A safe demo showing how a GitHub agent can be structured.

It does not store passwords, tokens, or secrets. Authentication must be supplied by a GitHub App or OAuth integration outside this repository.

Flow: UI -> Agent -> GitHub authentication -> GitHub API -> Result.

Capabilities depend on the permissions granted to the GitHub App/integration.
