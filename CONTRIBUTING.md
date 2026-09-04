# Contributing

The definition is versioned. Anyone can propose a change.

## Propose a change to the definition

1. Open a pull request that edits the current version file in `definition/` (or adds a new version file if the change is large enough to warrant one).
2. In the PR description, say in plain language: what you changed, why the current wording fails in a real case you have hit, and what you would use the revised definition for.
3. The co-organizers review. Changes merge when at least two co-organizers approve. Contested changes are recorded in `definition/CONTESTED.md` rather than dropped.

## Versioning

- `v0.1`: drafted in the room on 15 October 2026.
- Patch versions (`v0.1.1`) fix wording without changing meaning.
- Minor versions (`v0.2`) change or add a dimension of the definition.
- Every version is a git tag. The file for a version is never rewritten after it is tagged; changes go into the next version.

## Add yourself as an adopter

If your team, office, or lab uses the definition for something real (a benchmark, a policy draft, a product principle, a review criterion), open a PR adding one line to the "Adopters" section of `CONTRIBUTORS.md`: name, organization, what you use it for, and a link if there is one.

## Submit a position statement

Position statements for the October session are submitted through the site, not by PR. Statements are published here in `position-statements/` with the author's consent after the session.

## Code of conduct

This is a conversation, not a debate. Assume the other person's definition is doing real work for them. Disagree with wording, not with people.
