---
description: "How Platform CLI and the VS Code extension should be explained as companion interfaces, not isolated add-ons."
icon: laptop
---

# Platform CLI and VS Code

These two surfaces often get read as convenience tooling. For Semarchy, they are part of the operational contract of the platform.

## Why group them

- They support overlapping builder workflows.
- They are likely to share compatibility constraints with platform versions.
- They benefit from consistent examples, auth guidance, and release callouts.

## Recommended split

{% tabs %}
{% tab title="Platform CLI" %}
Focus on automation, environment interaction, and admin-friendly flows.
{% endtab %}

{% tab title="VS Code extension" %}
Focus on in-editor authoring, validation, and the day-to-day developer loop.
{% endtab %}
{% endtabs %}
