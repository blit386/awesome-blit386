# Security Policy

This repository is a curated list. It contains Markdown, a license, and nothing that executes – no dependencies, no
build step, no published package. That shapes what a security report here can usefully be about.

## Reporting a vulnerability in BLIT386 itself

Vulnerabilities in the engine, the scaffolder, or `@blit386/kit` do not belong here. Report them privately through
[GitHub's private vulnerability reporting on the engine repository](https://github.com/blit386/blit386/security/advisories/new),
and see [that repository's security policy](https://github.com/blit386/blit386/blob/main/SECURITY.md) for supported
versions and response times.

## Reporting a problem with a link on this list

The real risk in a curated list is a link that was safe when it was added and is not safe now – a domain that expired
and was re-registered, an account that was taken over, a project that started shipping something it did not ship
before.

If a listed resource has become malicious, do not open a public issue. A public report advertises the bad link to
everyone reading the repository before it can be removed. Report it privately through
[the engine repository's advisory form](https://github.com/blit386/blit386/security/advisories/new), naming the entry
and what changed. The link will be removed first and discussed afterward.

Ordinary link rot – a dead domain, a moved page, an abandoned project – is not a security matter. Open a pull request
removing or updating the entry, per [CONTRIBUTING.md](CONTRIBUTING.md).

## Scope

In scope:

- A resource listed here that now distributes malware, phishes, or has been taken over.
- Anything in this repository's own contents that could harm a reader who follows it.

Out of scope:

- Vulnerabilities in the listed projects themselves. Report those to their own maintainers; they are other people's
  work and this list does not vouch for their internals.
- Dead or outdated links, which are handled as normal contributions.
