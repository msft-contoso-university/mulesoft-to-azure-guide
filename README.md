---
title: MuleSoft to Azure Migration Guide
description: A community guide to Microsoft service mappings, backend API migration, low-code integration, costs, and migration readiness.
ms.date: 2026-10-16
---

## Overview

Explore practical mappings from MuleSoft capabilities to Azure Integration
Services and Microsoft low-code tools. Separate gateway migration from
integration execution and backend API modernization.

The guide includes:

* Searchable capability mappings and service comparisons
* Logic Apps, Power Automate, and Power Apps guidance
* Backend API hosting, contracts, dependencies, and cutover planning
* Migration Agent coverage and validation caveats
* Cost drivers and a reader-supplied-rate planning worksheet
* Discovery, acceptance, recovery, and production-readiness checklists
* Primary documentation links and a dated research snapshot

## View the guide

Open the [published migration guide](https://demo.gilbertappiah.com/mulesoft-to-azure-guide/).
GitHub Pages serves the site under the organization's configured custom domain.

You can also open [index.html](./index.html) directly in a browser. No build,
installation, external JavaScript, or stylesheet dependency is required.
Source links require an internet connection.

## Use the cost worksheet

Enter current rates for your region, agreement, and selected hosting model.
Pricing fields intentionally start blank. The worksheet calculates a simplified
monthly recurring total, not a quote or a guaranteed saving.

Include platform baseline, operation/connector metering, telemetry, and other
recurring charges. Account separately for nonlinear meters, free allowances,
taxes, one-time migration effort, and remaining legacy-platform costs.

Worksheet inputs and discovery checkmarks stay in the open page. They are not
stored or transmitted. Search, service, and pattern selections use URL parameters
so you can share those views.

## Publish with GitHub Pages

The site is a static page served from the root of the `main` branch.
In repository settings, select **Pages**, choose **Deploy from a branch**,
then select **main** and **/ (root)**.

The repository contains only public site assets. The local ignore policy is an
allowlist; add new public assets deliberately before tracking them.

## Maintain the content

Update [index.html](./index.html), check the cited documentation, and revise the
research date when verifying product-specific claims. Test navigation, filters,
service selection, cost arithmetic and invalid inputs, mobile layouts, and
print output before publishing.

Use generic examples only. Do not include organization-specific architecture,
discovery notes, identities, credentials, endpoints, or production payloads.

## Scope and attribution

This is an independently authored community reference, not an official product
support statement, automated conversion guarantee, or pricing commitment.
Validate current product features, availability, licensing, and prices.

The [Azure app hosting options guide](https://github.com/msft-contoso-university/azure-app-hosting-options)
inspired the information architecture. Product documentation and source links
are listed within the guide.
