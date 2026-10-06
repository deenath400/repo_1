# repo_1 — release mirror test (source)

Development and tagging happen here. Pushing a semver tag `vX.Y.Z` triggers
`.github/workflows/release-mirror.yml`, which pushes the tag and a
`release/X.Y` branch to `deenath400/repo_2` over SSH using a deploy key.
