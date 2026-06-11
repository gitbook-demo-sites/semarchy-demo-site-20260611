---
description: "A concrete catalog of reusable GitBook snippets for Semarchy's shared docs layer."
icon: boxes-stacked
---

# Snippet catalog

This page is the clearest proof that the private shared library is more than a conceptual holding area.

## Included today

<table>
  <thead>
    <tr>
      <th>Snippet</th>
      <th>Use case</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>.gitbook/includes/shared-sso-prereqs.md</code></td>
      <td>Shared SSO and cutover prerequisites across cloud and self-hosted admin docs.</td>
    </tr>
    <tr>
      <td><code>.gitbook/includes/shared-api-client-checklist.md</code></td>
      <td>Reusable API client setup checklist across both deployment tracks.</td>
    </tr>
    <tr>
      <td><code>.gitbook/includes/compatibility-note.md</code></td>
      <td>Standard warning block for version-sensitive workflows.</td>
    </tr>
    <tr>
      <td><code>.gitbook/includes/release-note-warning.md</code></td>
      <td>Shared release-note framing and rollout guidance.</td>
    </tr>
  </tbody>
</table>

## Live render examples

{% include ".gitbook/includes/shared-sso-prereqs.md" %}

{% include ".gitbook/includes/shared-api-client-checklist.md" %}

{% include ".gitbook/includes/compatibility-note.md" %}

{% include ".gitbook/includes/release-note-warning.md" %}

## Shared variables

- Product: <code class="expression">space.vars.product_name</code>
- Public docs: <code class="expression">space.vars.docs_url</code>
- Support: <code class="expression">space.vars.support_url</code>
- Suggested owner: <code class="expression">space.vars.compatibility_owner</code>
