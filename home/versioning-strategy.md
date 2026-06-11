---
description: "A GitBook-friendly versioning strategy for Semarchy's SaaS, self-hosted, and shared toolchain docs."
icon: code-compare
---

# Versioning strategy

Semarchy's versioning challenge is not just product versioning. It is coordination across:

- SaaS behavior that changes continuously
- self-hosted platform releases that customers pin and upgrade on their own schedule
- tools like the Design CLI, Platform CLI, and VS Code extension that may release independently

## Recommended model

{% tabs %}
{% tab title="SaaS" %}
Treat SaaS as a living track with release notes, deprecation notices, and compatibility callouts. Do not burden it with hard version selectors unless the feature behavior truly forks.
{% endtab %}

{% tab title="Self-hosted" %}
Treat self-hosted as versioned documentation with clearly named supported tracks, such as `latest`, `1.1`, and `1.0`. Each track should expose upgrade notes and compatibility rules up front.
{% endtab %}

{% tab title="Shared tools" %}
Keep tool pages canonical, then attach compatibility matrices and version callouts when a tool behaves differently across platform tracks.
{% endtab %}
{% endtabs %}

## Where GitBook helps

- Section-level navigation lets Semarchy keep separate deployment paths without hiding shared tooling.
- Reusable content blocks can keep recurring support policy or compatibility notes consistent.
- Audience-specific or authenticated overlays can keep internal rollout notes near public docs without forking a whole second site.
- AI search performs better when compatibility guidance is explicit and centralized.

## Suggested first iteration

1. Keep the SaaS space unversioned.
2. Model self-hosted as real versioned tracks.
3. Keep toolchain pages canonical in [Builders and integrations](https://app.gitbook.com/s/XSPACE_BUILDERS/README).
4. Add a visible compatibility matrix before expanding more release permutations.
