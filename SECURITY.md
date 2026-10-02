# Security policy

This policy covers every public repository in the Outcomes Insights organization that does
not carry its own `SECURITY.md`, including the published gems (`conceptql`, `sequelizer`,
`sequel-duckdb`, `sequel-hexspace`).

## Reporting a vulnerability

Please do not open a public issue for a security problem.

Use GitHub's private vulnerability reporting: on the repository's **Security** tab, choose
**Report a vulnerability**. That opens a private advisory only the maintainers can see, and
it is where we will coordinate a fix with you.

If that is not available to you, email the maintainer listed in the gem's gemspec
(`gem specification --remote <name> email`) with "SECURITY" in the subject line.

Include what you can of: the affected repository and version, how to reproduce the problem,
and what you believe the impact is. A proof of concept is welcome; a working exploit against
anyone else's systems is not.

## What to expect

- An acknowledgement within 7 days.
- An assessment, and if the report is confirmed, a fix and a release. We will keep you
  informed through the advisory and credit you in the release notes unless you ask us not to.
- Coordinated disclosure: we ask that you give us the chance to ship a fix before publishing
  details. We will publish a GitHub security advisory when the fix is released.

## Supported versions

These projects are small and maintained by a small team. Security fixes go into the **latest
release** of each gem; we do not backport to earlier versions. Problems in a dependency
should be reported to that project; where a fix requires us to raise a version constraint,
we will do so in the next release.

## Scope

In scope: the code in these repositories and the gems published from them to rubygems.org.
Out of scope: third-party dependencies (report upstream), the hosted services of Outcomes
Insights or its clients, and findings that require physical access or social engineering.
