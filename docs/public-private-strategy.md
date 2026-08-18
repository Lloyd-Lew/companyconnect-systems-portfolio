# Public and Private Repository Strategy

CompanyConnect.Tech uses GitHub in two distinct ways: public repositories establish credible, client-safe proof; private repositories protect customer information, business infrastructure, and reusable implementation detail.

## Public repository criteria

A repository may be public when it has a clear audience and it can safely demonstrate an approved capability, reusable product foundation, sanitized technical pattern, documentation, or open-source utility. It must not contain customer information, credentials, live access routes, client-specific configuration, proprietary logic that should remain internal, or claims that cannot be supported.

## Private repository criteria

A repository must remain private when it contains workflow exports, client systems, customer data, production integrations, credentials, deployment configuration, internal operations, early commercial IP, or incomplete work that could misrepresent the business. Private does not mean unimportant; it often means the work is valuable enough to protect.

## Current portfolio application

| Repository class | Current account use | Visibility stance |
| --- | --- | --- |
| Profile infrastructure | Personal profile README and account metadata | Public |
| Client-safe systems portfolio | Portfolio narrative, delivery patterns, diagrams, sales resources, standards | Public and pinned |
| Client workflow archives | Raw automation exports and operational configuration | Private indefinitely |
| Empty or deferred repositories | No active technical content | Private; archive only after owner confirmation |
| Future product or showcase code | A genuine, sanitized, independently useful demonstrator | Public only after security, documentation, and support review |

## Publishing gate

Before changing a private repository to public or adding an asset to the portfolio, confirm all of the following.

1. The asset has a clear public purpose and a named audience.
2. All claims are accurate, current, and supportable.
3. Client data, customer names, credentials, secrets, private URLs, and live configuration have been removed or written permission to publish has been obtained.
4. The material does not reveal reusable commercial IP that the business intends to protect.
5. The README, security posture, licence, ownership, and contact route are appropriate for the repository type.
6. A technical and commercial owner has approved the release.

If any answer is “no,” keep the asset private and create a client-safe summary instead.
