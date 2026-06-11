---
description: "A draft compatibility model for Semarchy's platform tracks, CLIs, extension, and API guidance."
icon: table-cells
---

# Compatibility matrix

This page exists because Semarchy described compatibility drift as a real reader problem.

<table>
  <thead>
    <tr>
      <th>Surface</th>
      <th>Why it can drift</th>
      <th>What the docs should say explicitly</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Platform track</td>
      <td>SaaS evolves continuously while self-hosted customers pin releases.</td>
      <td>Supported platform tracks, deprecations, and upgrade expectations.</td>
    </tr>
    <tr>
      <td>Design CLI</td>
      <td>Local workflows may depend on newer modeling behavior than older platform tracks expose.</td>
      <td>Minimum or recommended platform compatibility.</td>
    </tr>
    <tr>
      <td>Platform CLI</td>
      <td>Operational commands often reflect environment capabilities that change by release.</td>
      <td>Track-specific command differences and rollout guidance.</td>
    </tr>
    <tr>
      <td>VS Code extension</td>
      <td>Editor experiences evolve quickly and may outpace slower customer-managed environments.</td>
      <td>Supported extension ranges and fallback behavior.</td>
    </tr>
    <tr>
      <td>APIs and integrations</td>
      <td>Third-party systems and embedded product surfaces can change independently.</td>
      <td>Version policy, stability level, and where canonical endpoint truth lives.</td>
    </tr>
  </tbody>
</table>

{% hint style="warning" %}
This matrix is more important than yet another nested reference tree. If Semarchy makes compatibility explicit, readers will trust the rest of the docs more.
{% endhint %}
