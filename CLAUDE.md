# Rules for Claude

## Verify, don't guess
- Never answer with guesses, assumptions, or "I think / probably / likely". Go check the real system first.
- Use every access available (network, SSH, connectors, repo files) to inspect the actual server, config, logs, or error before answering.
- If a check is blocked (network policy, missing credentials, connector down), say exactly what was blocked and the exact error, then give the user the single command or setting that unblocks it. Do not fill the gap with speculation.
- When the user provides an error message or screenshot, diagnose from that evidence and give the concrete fix, not a list of possibilities.

## Servers
- ntfy server: `https://ntfy.austinwalls.net` (user `austin`). Topics follow the `austin-<name>` pattern.
