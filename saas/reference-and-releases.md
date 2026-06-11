---
description: "How SaaS reference and release material should be organized without over-versioning the hosted experience."
icon: clock-rotate-left
---

# Reference and releases

SaaS should stay a living track. Readers still need release visibility, but the navigation should not force them to choose a product version for every question.

## Recommended split

- Keep detailed reference grouped by API, CLI, and design surfaces.
- Use release notes and deprecation callouts to explain hosted change over time.
- Put shared compatibility material in [Builders and integrations](https://app.gitbook.com/s/iQlvI6ojNKxdNRbfueTa/compatibility-matrix).

{% hint style="warning" %}
If the API endpoint details remain embedded in the product, GitBook can still carry the decision-support layer around auth patterns, conventions, lifecycle, and integration scenarios. The docs surface does not need to duplicate every endpoint to be useful.
{% endhint %}
