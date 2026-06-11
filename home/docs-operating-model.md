---
description: "A practical ownership model for Semarchy's docs if the site is reorganized around deployment plus shared builder surfaces."
icon: people-arrows
---

# Docs operating model

The structure only works if ownership lines are equally clear.

## Proposed ownership

<table>
  <thead>
    <tr>
      <th>Surface</th>
      <th>Primary owner</th>
      <th>Why</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>SaaS platform</td>
      <td>Cloud platform and admin teams</td>
      <td>They control environment behavior, login, access, and hosted release expectations.</td>
    </tr>
    <tr>
      <td>Self-hosted platform</td>
      <td>Deployment and support engineering</td>
      <td>They own install, upgrade, sizing, dependencies, and break-fix operations.</td>
    </tr>
    <tr>
      <td>Builders and integrations</td>
      <td>Developer experience or product engineering</td>
      <td>CLI, extension, API, and compatibility content should evolve together.</td>
    </tr>
  </tbody>
</table>

## Publishing workflow

{% stepper %}
{% step %}
### Shared builder changes publish independently

A Design CLI change should not wait for self-hosted release notes unless there is a real compatibility dependency.
{% endstep %}

{% step %}
### Compatibility notes are attached to the change, not retrofitted later

If a CLI or extension release depends on platform version thresholds, capture that in the same pull request or review workflow.
{% endstep %}

{% step %}
### Legacy content gets mapped, not copied

When older docs still matter, route readers through a clear archive or migration note instead of cloning pages into the new IA.
{% endstep %}
{% endstepper %}
