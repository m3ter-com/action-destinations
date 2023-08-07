---
# The end name should be similar to `Slack  Destination`
title: <destination_name>
hide-boilerplate: true
hide-dossier: true
---

<!-- This template is meant for Actions-based destinations that do not have an existing Classic or non-Actions-based version. For Actions Destinations that are a new version of a classic destination, see the doc-template-update.md template. -->

{% include content/plan-grid.md name="actions" %}

<!-- Include a brief description of the destination here, along with a link to your website. -->

[m3ter](https://m3ter.com/) powers every variation of usage-based pricing for software companies at all stages of growth. Ingest and enrich usage data, apply pricing, and generate error-free bills in real-time.

This destination enables you to ingest your usage events from Segment conveniently and efficiently.

<!-- This include describes the requirement of A.js 2.0 or higher for Actions compatibility, and is required if your destination has a web component. -->

{% include content/ajs-upgrade.md %}

<!-- The section below explains how to enable and configure the destination. Include any configuration steps not captured below. For example, obtaining an API key from your platform and any configuration steps required to connect to the destination. -->

## Getting started

1. From the Segment web app, click **Catalog**, then click **Destinations**.
2. Find the Destinations Actions item in the left navigation, and click it.
3. Click **Configure m3ter**.
4. Select an existing Source to connect to m3ter (Actions).

<!-- The line below renders a table of connection settings (if applicable), Pre-built Mappings, and available actions. -->

{% include components/actions-fields.html %}

<!--
Additional Context

Include additional information that you think will be useful to the user here. For information that is specific to an individual mapping, please add that as a comment so that the Segment docs team can include it in the auto-generated content for that mapping.
-->

There are two prerequisites to using this integration with your m3ter organization:

1. A Meter with suitable configuration for your usage events must exist; see [https://www.m3ter.com/docs/guides/setting-up-usage-data-meters-and-aggregations](https://www.m3ter.com/docs/guides/setting-up-usage-data-meters-and-aggregations) for more information.
2. A [Service User](https://www.m3ter.com/docs/guides/authenticating-with-the-platform/service-authentication) with `measurements:upload` [permission](https://www.m3ter.com/docs/guides/organization-and-access-management/creating-and-managing-permissions) must exist, and you should have the API credentials to hand.

<!-- TODO: some step-by-step of the segment config and field mappings here -->