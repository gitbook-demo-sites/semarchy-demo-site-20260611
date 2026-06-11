---
description: "Landing space for a Semarchy documentation hub built around deployment model, shared toolchains, and compatibility."
icon: house
layout:
  width: wide
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: false
  outline:
    visible: false
  pagination:
    visible: true
  metadata:
    visible: true
---

# Semarchy Documentation Hub

{% columns %}
{% column width="58%" %}
Semarchy already has strong product depth. The issue is not lack of material, it is that versioning, deployment model, and toolchain compatibility are doing too much of the navigation work. This draft reorganizes the experience around one entrypoint, two deployment paths, and one shared builder surface for CLI, VS Code, APIs, and third-party integrations.

<a class="button primary" href="https://www.semarchy.com/get-started/">Start with Semarchy</a>
<a class="button secondary" href="https://support.semarchy.com/">Contact support</a>

<button type="button" class="button primary" data-action="ask" data-icon="gitbook-assistant">Search the Semarchy docs</button>
<button type="button" class="button secondary" data-action="ask" data-query="Which deployment path should I use: SaaS or self-hosted?" data-icon="cloud">Deployment choice</button> <button type="button" class="button secondary" data-action="ask" data-query="Which Semarchy tools have compatibility constraints?" data-icon="code-branch">Compatibility</button> <button type="button" class="button secondary" data-action="ask" data-query="Where do I find CLI, VS Code, and API guidance?" data-icon="terminal">Tooling</button>
{% endcolumn %}

{% column width="42%" %}
{% hint style="success" icon="circle-info" %}
**Demo thesis**

This version deliberately separates *deployment-specific* content from *shared builder surfaces*. That gives Semarchy a cleaner story for SaaS vs self-hosted readers without duplicating every CLI, API, and integration explanation.
{% endhint %}
{% endcolumn %}
{% endcolumns %}

***

<table data-view="cards">
  <thead>
    <tr>
      <th width="48"></th>
      <th></th>
      <th></th>
      <th data-hidden data-card-target data-type="content-ref"></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><i class="fa-cloud" style="color:#003B72;"></i></td>
      <td><strong>SaaS platform</strong></td>
      <td>Cloud-first onboarding, administration, design workflows, and release guidance for Semarchy-hosted deployments.</td>
      <td><a href="https://app.gitbook.com/s/XSPACE_SAAS/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-server" style="color:#003B72;"></i></td>
      <td><strong>Self-hosted platform</strong></td>
      <td>Installation, upgrades, environment operations, and the version-aware path for customer-managed deployments.</td>
      <td><a href="https://app.gitbook.com/s/XSPACE_SELF_HOSTED/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-code-branch" style="color:#003B72;"></i></td>
      <td><strong>Builders and integrations</strong></td>
      <td>VS Code, Design CLI, Platform CLI, APIs, and third-party integration surfaces organized as one compatibility-aware toolchain.</td>
      <td><a href="https://app.gitbook.com/s/XSPACE_BUILDERS/README">README</a></td>
    </tr>
  </tbody>
</table>

## What this draft is trying to prove

{% columns %}
{% column %}
### For Semarchy readers

- One clear choice between SaaS and self-hosted
- Shared tooling explained once instead of repeated everywhere
- Better discoverability for compatibility and release decisions
- A cleaner path to decide where API docs should live
{% endcolumn %}

{% column %}
### For Semarchy authors

- Product teams can own shared surfaces without duplicating deployment content
- Release notes and compatibility can become first-class content, not footnotes
- CLI and extension docs can evolve independently without fragmenting navigation
- Legacy content has a defined landing zone instead of lingering as parallel navigation
{% endcolumn %}
{% endcolumns %}

## Suggested first path

1. Read [why this structure](why-this-structure.md).
2. Choose either the [SaaS platform](https://app.gitbook.com/s/XSPACE_SAAS/README) or [self-hosted platform](https://app.gitbook.com/s/XSPACE_SELF_HOSTED/README) path.
3. Use [builders and integrations](https://app.gitbook.com/s/XSPACE_BUILDERS/README) for shared toolchain, API, and compatibility questions.
4. Review the proposed [versioning strategy](versioning-strategy.md) before modeling long-lived releases.
