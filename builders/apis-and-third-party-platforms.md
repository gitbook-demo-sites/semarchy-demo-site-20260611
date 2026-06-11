---
description: "A pragmatic recommendation for how Semarchy can document APIs and external integrations."
icon: plug-circle-bolt
---

# APIs and third-party platforms

Semarchy's open question about API docs is the right one. The choice is not between *all in product* and *all in GitBook*. The better split is usually:

- keep endpoint truth close to the product or generated spec
- use GitBook for onboarding, lifecycle guidance, conventions, authentication narratives, and integration scenarios

## What belongs here

- API overview and architecture
- authentication and environment conventions
- lifecycle and versioning policy
- third-party platform interaction patterns
- integration tutorials and troubleshooting

## What may stay elsewhere

- mechanically generated endpoint reference
- highly product-embedded try-it consoles

{% hint style="success" %}
The OpenAPI-backed section in this demo is intentionally lightweight. It shows how Semarchy could keep a spec-driven endpoint reference in GitBook without hand-authoring every operation page.
{% endhint %}
