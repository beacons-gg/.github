# Security policy

This policy covers every repository in the Beacon organization. A repository's own `SECURITY.md`
can add to the policy but never replaces the policy.

## Report a vulnerability

Report a vulnerability through GitHub's private vulnerability reporting. Open the repository's
**Security** tab and choose **Report a vulnerability**. Only the maintainers can read the report.

Don't open a public issue, discussion or pull request for a vulnerability. Keep the details private
until the maintainers publish an advisory.

If you can't use GitHub, email `security@beacons.gg`. Reports about Beacon's hosted service go to the
same address. `https://beacons.gg/.well-known/security.txt` lists the same channels.

## Supported versions

Only the latest release gets security fixes:

- the latest version of each `@beaconsgg/*` package on npm;
- the latest server image, `ghcr.io/beacons-gg/beacon-server`;
- the latest console image, `ghcr.io/beacons-gg/beacon-admin`.

An older release gets no fix. Upgrade to the latest release to get one.

## What to include

- the repository, and the release or commit you tested;
- what an attacker can do, and what the attacker needs first;
- the steps that reproduce the issue, or a proof of concept;
- the requests, logs or screenshots that show the issue;
- the name to credit in the advisory, or a request for no credit.

Test against a server you run yourself. Don't test against servers other people run, and don't
access data that isn't yours.

## What happens next

The maintainers acknowledge a report within 3 business days. They then confirm the issue and tell
you what they found. A confirmed issue is fixed in a private fork. The fix ships in a new release
with a GitHub security advisory, and the advisory credits you unless you asked for no credit.
