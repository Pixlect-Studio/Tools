# Security & Code Ownership

## Proprietary project notice

Pixlect Tools and its source code, design, interface, branding, documentation, and associated assets are proprietary works of Pixlect Studio unless a file explicitly states otherwise. **All rights are reserved.**

No permission is granted by making this repository or its website viewable to the public. Without prior written permission from Pixlect Studio, visitors must not:

- Fork, clone, copy, mirror, download for redistribution, or republish this project or substantial portions of its source code.
- Modify, adapt, create derivative works from, or incorporate the code into another product or service.
- Claim authorship or ownership, remove copyright notices, or represent the project as their own.
- Use Pixlect branding, logos, names, or assets in a way that suggests endorsement or ownership.
- Sell, sublicense, distribute, or commercially exploit the project or its components.

Viewing the public website does not grant permission to reuse its source code. Any exception requires explicit written authorization from Pixlect Studio.

## Important GitHub limitation

A public GitHub repository makes source code publicly accessible. A README or security notice cannot technically prevent GitHub users from downloading or forking public source. To restrict GitHub's built-in forking and source access, the repository owner must use a private repository and grant access only to approved collaborators. This notice records the project's intended permissions; it is not a technical access-control mechanism.

## Reporting a security issue

Report suspected vulnerabilities privately to the Pixlect Studio maintainers through a contact channel published by Pixlect Studio. Include the affected page or feature, steps to reproduce, expected behaviour, and impact. Do not publish exploit details or access other users' data.

Please do not include passwords, API keys, access tokens, personal information, or other secrets in public issues.

## Security practices

- The public Updates feed performs read-only requests to the Pixlect news page and public Realtime Database endpoint.
- News content is inserted as text, not trusted HTML. External links are limited to HTTP(S) URLs and open with `noopener noreferrer`.
- Member-only/private news records are filtered from the public Updates interface.
- No login, password collection, account storage, chat, or user-to-user messaging is included in this release.
- Groq API keys entered in workspace settings are stored locally only when the user enables the remember option. Browser storage is not a secure secret vault.

## No licence granted

Unless Pixlect Studio gives written permission, no licence is granted to copy, modify, distribute, sublicense, or create derivative works from this project. All rights are reserved.
