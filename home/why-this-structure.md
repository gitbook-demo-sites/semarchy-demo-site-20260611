---
description: "Why this demo reorganizes Semarchy around deployment paths plus a shared builder surface."
icon: sitemap
---

# Why this structure

Semarchy's current documentation already contains the right raw building blocks: `Get started`, `Guides`, `Reference`, and `Releases`, with distinct SaaS and self-hosted entrypoints. The harder problem is that the same taxonomy has to carry very different reader jobs:

- a cloud admin trying to configure access
- a self-hosted team planning upgrades
- a designer moving between the platform and the Design CLI
- a developer deciding whether to use in-product API docs, external reference docs, or both

This draft changes the outer shell without throwing away that investment.

## Design principles

{% stepper %}
{% step %}
### Split by deployment only where the experience is genuinely different

SaaS and self-hosted deserve different landing pages because setup, hosting responsibility, and release expectations differ. They should not each have to explain the full builder toolchain from scratch.
{% endstep %}

{% step %}
### Explain shared tools once

The VS Code extension, Design CLI, Platform CLI, APIs, and third-party platform integrations are a single ecosystem. Readers should be able to understand compatibility across those surfaces without bouncing between parallel reference trees.
{% endstep %}

{% step %}
### Elevate compatibility and release behavior

Compatibility is not a buried note. It is a top-level concern for Semarchy because product, CLI, extension, and hosted or self-hosted versions can drift independently.
{% endstep %}
{% endstepper %}

## What changed from the current shape

<table data-view="cards">
  <thead>
    <tr>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Before</strong></td>
      <td>Two deployment portals share the same structure, which is clear but makes shared toolchain and compatibility stories harder to discover.</td>
    </tr>
    <tr>
      <td><strong>After</strong></td>
      <td>Deployment-specific content stays separate, while shared builder and integration content lives in one cross-cutting space.</td>
    </tr>
  </tbody>
</table>

## Cross-space reading model

- Use [SaaS platform](https://app.gitbook.com/s/XSPACE_SAAS/README) for cloud-first tasks.
- Use [Self-hosted platform](https://app.gitbook.com/s/XSPACE_SELF_HOSTED/README) for install, upgrade, and operated-environment tasks.
- Use [Builders and integrations](https://app.gitbook.com/s/XSPACE_BUILDERS/README) for CLI, VS Code, APIs, and compatibility.

{% hint style="info" %}
This is intentionally a sales demo structure, not a line-by-line migration plan. The point is to show how GitBook can turn Semarchy's current content depth into a clearer reader journey.
{% endhint %}
