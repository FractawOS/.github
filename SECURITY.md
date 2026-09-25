# Security Policy

Security issues should not be disclosed publicly before maintainers have had a reasonable opportunity to investigate them.

FractawOS may interact with sensitive operating system capabilities including processes, devices, audio, networking, system resources, application execution, and user files.

Because modules can request access to these capabilities, the module permission model is considered part of the security boundary.

## Reporting vulnerabilities

If you discover a security vulnerability, report it privately to the project maintainers.

Do not open a public issue containing exploit details, credentials, sensitive system information, or instructions that could place users at risk.

A public disclosure may be coordinated after the issue has been investigated and mitigated.

## Module security

Modules must declare the permissions they require.

Modules should request the minimum permissions necessary for their functionality.

The FractawOS Core should mediate access to protected platform capabilities whenever possible.

Modules should not bypass the public security or permission model.

## Trust levels

FractawModuleRegistry may distinguish between Community, Verified, and Official modules.

These classifications describe project review and maintenance status.

They do not guarantee that software is free from defects or vulnerabilities.
