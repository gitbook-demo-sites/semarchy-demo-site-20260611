---
description: "A phased migration path from the current Semarchy docs toward the demo structure."
icon: road
---

# Migration roadmap

This draft assumes Semarchy would not rewrite everything at once.

{% stepper %}
{% step %}
### Phase 1: establish the new shell

Launch the new homepage, SaaS landing, self-hosted landing, and builder landing pages first. Use them as routing and explanation layers over the current body of content.
{% endstep %}

{% step %}
### Phase 2: centralize shared builder content

Move Design CLI, Platform CLI, VS Code, API strategy, and third-party integration overviews into the shared builder space.
{% endstep %}

{% step %}
### Phase 3: formalize compatibility

Add a maintained matrix for platform version, CLI, extension, and API guidance. This is the content Semarchy readers are currently inferring informally.
{% endstep %}

{% step %}
### Phase 4: decide the API-reference split

Use traffic and support data to decide whether in-product API docs remain the canonical endpoint reference, while GitBook carries onboarding, conventions, and integration narratives.
{% endstep %}
{% endstepper %}

{% hint style="warning" %}
The riskiest move would be a bulk migration that preserves today's structural ambiguity. The shell should become clearer before the long-tail reference inventory moves.
{% endhint %}
