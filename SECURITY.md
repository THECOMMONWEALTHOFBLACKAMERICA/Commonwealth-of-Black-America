# Commonwealth of Black America — Security Policy

## Scope

This policy covers security issues affecting the public CBA repository, future CBA websites or software stored here, public registries, and any technical systems later developed from this repository.

## Never report secrets publicly

Do not open a public Issue containing passwords, API keys, private keys, authentication tokens, banking credentials, personal identity data, raw DNA data, or exploitable security details involving a live system.

Until a dedicated security contact is established, repository maintainers should handle potentially sensitive reports privately through GitHub-supported private reporting channels where available.

## Priority risks

Security planning should prioritize:

- protection of citizenship and genealogy evidence
- account takeover prevention
- repository-administrator security
- election-system integrity
- Treasury and payment-system security
- protection of private member information
- integrity of the public citizen registry
- prevention of unauthorized document alteration

## Repository administrator requirements

Maintainers should use strong unique passwords and multi-factor authentication. High-impact changes should increasingly move through reviewed pull requests rather than direct edits to the default branch as the institution grows.

## Sensitive-data incident response

If protected data or a credential is exposed:

1. Revoke or rotate the exposed credential immediately.
2. Remove the data from the current repository state.
3. Determine whether Git history also contains the sensitive information.
4. Use appropriate history-removal procedures if required.
5. Review access logs and affected systems where available.
6. Record a non-sensitive incident summary after containment when transparency is appropriate.

## Election and financial software

Future election, identity, wallet, payment, stablecoin, or Treasury software should not be treated as production-ready merely because it is published here. Such systems require professional security review, testing, legal/compliance review where applicable, access controls, audit logging, backups, and incident-response procedures before live use.
