---
title: 'ADA Publishing Microservices'
date: 2019-01-24T14:32:00+01:00
draft: false
featuredImg: ""
tags:
  - CI
  - CD
---

{{< figure src="https://upload.wikimedia.org/wikipedia/commons/6/62/Babbage_Difference_Engine_%28the_power-supply_end%29.jpg" alt="Babbage engine" caption="Babbage engine (the power-supply end). CC-BY-2.0 Jitze Couperus. Wikimedia " >}}

## About ADA Research Project (Advanced Document Architecture), Oct '18
— an interoperable framework

The problem space ADA is addressing is research publication production. Research publishing is made up of two main workflow types:

- traditional ‘research paper’ workflows;
- and then ‘research artifacts’ workflows, which is made up of everything else produced in the research cycle.

If you boil down the key barriers to the use of effective computation systems in this space to three factors, they would be:

1. That the basic digital plumbing doesn’t work, i.e., how can I make a validated DOCX and easily, and 100% reliably transform it into validated HTML5 file.
2. Funders can’t afford to fix the problems.
3. Anyone who does try to solve the problems in this space uses unsustainable and outdated platform models.

The ADA is to make an microservices API network, using a twofold approach:

- to enable document interoperability with, transformation, and semantic enrichment, functionality through a ‘microservice’ network, and
- secondly to reduce costs using automation and Infrastructure as Code (IasC) meaning, CI, CD, virtualization, and cryptographic, technologies.

We can do the above by bringing together different areas of expertise:

- Publishing technologies - with Le-tex, Fidus Writer, and Vivliostyle;
- Research life cycle with TIB; and
- CI/CD/ and virtualization with Endocode.

## What would ADA look like?

- ADA Microservices API: There would be an API that providers could offer their services. For example: DataCite with DOIs, ORCiD as authentication IDs, video enrichment via TIB AV portal, PoD via Ingram, ORKG content semantic enrichment, or VIVO research information, etc.

- ADA docs: A real-time web based word processor with multi-format conversion, and all ADA microservices. This would use Fidus Writer, Le-tex, and Vivliostyle technologies.

- All FOSS: cloud deployment GCS, any cloud deploy, baremetal deploy, and institutional white labeling.

## The ADA consortium and business model

A consortium of FOSS businesses, development groups, and research institutions would be formed. Le-tex, Fidus Writer, Vivliostyle, and Endocode are already business and R&D partners. We would carry out public facing development rounds to get multiple institutions and parties to invest in the development cycles. TIB with partners would provide services of different kinds to the academic community. Services metering would be employed as API calls—units would need to be determined, or as Blockchain and cryptographic transactions.
