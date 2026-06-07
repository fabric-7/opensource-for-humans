# Security

Security in OpenSource for Humans is both technical and human. A failure can expose vulnerable people, organizations, or volunteers.

## Report Vulnerabilities

If you find a vulnerability, do not open a public issue with exploitable details.

Use a private channel defined by the maintainer team. Until that channel exists, report directly to the project maintainers.

## Sensitive Scope

The following are considered sensitive:

- exposure of personal data;
- authentication failures;
- unauthorized access to the admin panel;
- unauthorized changes to services;
- injection of malicious links;
- abusive scraping;
- log leaks;
- AI prompts or logs containing personal data;
- failures that make scams or fake organizations easier.

## Incident Response

When an incident is confirmed:

1. Contain the problem.
2. Preserve evidence.
3. Assess affected data and people.
4. Fix the root cause.
5. Notify data subjects and authorities when necessary.
6. Publish a post-incident summary when it is safe to do so.

## Secure Development

Critical changes should consider:

- input validation;
- access control;
- logs without sensitive data;
- rate limiting;
- dependency review;
- backups;
- auditing;
- protection against spam and scams.
