# Runbook: Adding or Updating a Token

1) Copy the template:
   /metadata/_templates/token.example.json → /metadata/<token-symbol>.json

2) Fill required fields. If mainnet is unknown, leave "" and note "PILOT".

3) Submit a PR with a short note:
   - what changed
   - links (explorers, images)
   - where the token is used (e.g., staking bot)

4) CI will sanity-check JSON structure.
