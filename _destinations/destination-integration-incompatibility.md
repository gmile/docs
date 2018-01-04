---
title: Destination & Integration Compatibility
tags: [destinations]
keywords: destinations, integrations, incompatible, mixed data types, multiple data types, compatibility, compatible
permalink: /destinations/destination-integration-compatibility
summary: "Verify your integrations' compatibility with your data warehouse."

toc: true
layout: destination
type: "all"
destination: false
---
{% include misc/data-files.html %}
{% include misc/support-icons.html %}

When selecting a destination, it's important to first verify that all the data sources you want to connect to Stitch will be compatible. 

**As Stitch currently allows only one destination per account,** we recommend verifying your integrations' compatibility before connecting a destination. This will ensure that you can successfully connect and replicate data from all your sources.

---

## Degrees of Incompatibility

The compatibility of any integration/destination combination falls into one of three categories: **always** compatible, **sometimes** compatible, and **never** compatible.

The matrices below use the following icons to indicate the degree of incompatibility for an integration/destination combo:

- {{ supported | replace:"TOOLTIP","" }} indicates that, as far as we know, this combo is **always** compatible.
- {{ sometimes-supported | replace:"TOOLTIP","" }} indicates that this combo is **sometimes** compatible - there may be compatibility issues, but they're infrequent or parts of the integration may still be usable.
- {{ not-supported | replace:"TOOLTIP","" }} indicates that this combo is **never** compatible. It's unlikely that Stitch will be able to load data from this integration into the given destination.

---

## Incompatible Integrations by Destination Type

Below you'll find a list of integrations that may have full or partial incompatibility with any of Stitch's destination offerings.

{% include destinations/destination-level-incompatibility.html %}

{% include destinations/full-incompatibility-matrix.html %}