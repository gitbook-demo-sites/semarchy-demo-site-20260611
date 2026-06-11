---
description: "Landing space for a Semarchy documentation hub that stays close to the current public docs structure."
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
Semarchy already has strong product depth. This revised draft stays much closer to the current documentation model: one shared homepage and two deployment tracks, each preserving the familiar `Get started`, `Guides`, `Reference`, and `Releases` framing.

<a class="button primary" href="https://www.semarchy.com/get-started/">Start with Semarchy</a>
<a class="button secondary" href="https://support.semarchy.com/">Contact support</a>

<button type="button" class="button primary" data-action="ask" data-icon="gitbook-assistant">Search the Semarchy docs</button>
<button type="button" class="button secondary" data-action="ask" data-query="Which deployment path should I use: SaaS or self-hosted?" data-icon="cloud">Deployment choice</button> <button type="button" class="button secondary" data-action="ask" data-query="Which Semarchy tools have compatibility constraints?" data-icon="code-branch">Compatibility</button> <button type="button" class="button secondary" data-action="ask" data-query="Where do I find CLI, VS Code, and API guidance?" data-icon="terminal">Tooling</button>
{% endcolumn %}

{% column width="42%" %}
{% hint style="success" icon="circle-info" %}
**Demo thesis**

This version is more literal to the current Semarchy docs, while still showing one additional GitBook value: a private shared-content library for reusable material across SaaS and self-hosted.
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
      <td><a href="https://app.gitbook.com/s/sQVyekheKgc48qS6NC3K/README">README</a></td>
    </tr>
    <tr>
      <td><i class="fa-server" style="color:#003B72;"></i></td>
      <td><strong>Self-hosted platform</strong></td>
      <td>Installation, upgrades, environment operations, and the version-aware path for customer-managed deployments.</td>
      <td><a href="https://app.gitbook.com/s/C2xHo5F5QL4m0UbrhFwu/README">README</a></td>
    </tr>
  </tbody>
</table>

## What changed from the first draft

- The published site is now closer to the current Semarchy docs shape.
- The more opinionated shared-toolchain concept has been moved out of the public navigation.
- Reusable cross-track material is instead modeled in a private shared-content space for authors.

## Suggested first path

1. Read [why this structure](why-this-structure.md).
2. Choose either the [SaaS platform](https://app.gitbook.com/s/sQVyekheKgc48qS6NC3K/README) or [self-hosted platform](https://app.gitbook.com/s/C2xHo5F5QL4m0UbrhFwu/README) path.
3. Review the proposed [versioning strategy](versioning-strategy.md) before modeling long-lived releases.
