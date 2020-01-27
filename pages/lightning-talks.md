---
layout: page
title: Lightning Talks
author: Maulik R. Kamdar
permalink: lightning-talks
mainnav: false
sidenav: true
sidebartitle: Lightning Talks
published: true
order: 4
---

----------------------------------------------------------------

# A new Biodiversity and Ecology dataset {#biodiversity}

#### Speakers
- [Jen Hammock, Smithsonian Institution](https://orcid.org/0000-0002-9943-2342) 
- [Katja Schulz, Smithsonian Institution](https://orcid.org/0000-0001-7134-3324)

#### Abstract 

The Encyclopedia of Life integrates data connecting organisms, categorical attributes, environments, and geographic entities. This is stored natively as a property graph. A projection of the dataset simplifies the graph to taxa rather than individual organisms, and bundles records supporting the same relationship type between the same two entities. The provenance data in this projection is linked less directly, but the graph supports intuitive triples of the form:

Elkhorn_coral builds_habitat reef
or
mosquito feeds_on human

We are working on translating the projection into an RDF resource. We are in need of feedback on the semantic structure of the current draft.

The graph includes 2 million taxa, 1.2M linked to geographic entities, 800,000 linked to habitats, 600,000 linked to functional or ecological categories, and 200,000 linked to other taxa via ecological interactions. Taxa, geographic entities, attribute categorical values and habitats are hierarchically organized. Entities and relationships are identified using OBO Foundry ontologies, Wikidata, Geonames or specialist biodiversity thesauri wherever possible; where necessary, ad hoc terms are minted.

----------------------------------------------------------------

# Finding Correlation and Causation in Knowledge Graphs {#correlation-causation}

#### Speakers
- [Jans Aasman, Franz Inc.](https://franz.com)

#### Abstract

Franz is involved in a number of Knowledge Graph projects that capture real world events. For fairly obvious business purposes we would like to know in each of the domains the correlation and co-occurrence of certain events so, given an event X, we can predict the chance of event Y. In a healthcare Knowledge Graph we find significant correlations (and co-occurrence) between having HIV and being Bipolar, but what causes what? Why do we see that strange correlation?

In a Knowledge Graph around airplane repairs we find a high correlation between certain types of breakdowns, repairs and purchases that on first sight seem relatively unexplainable. There is no relationship between the part that breaks and the part that we have to purchase in the bill of material for the plane. So what causes what and why?

Finally, in the domain of call center interactions we find high correlations between 'product names' mentioned by the call center agent and 'product names' mentioned by the Customer. How does one trigger the other?

Based on the ideas in the "Book of Why" by Judea Pearl we came up with new techniques that will add the arrow of time to our analysis so that we actually start showing in a visual graph how one event might cause (and thereby predict) the other event.

----------------------------------------------------------------

# Heuristic evaluation of semantic search interfaces in bibliographic systems {#bibliographic}

#### Speakers
- [Jim Hahn, University of Pennsylvania](https://www.library.upenn.edu/people/staff/jim-hahn)

#### Abstract

This lightening talk will present a position statement and research agenda in the areas of user interface evaluation for semantic search interfaces in bibliographic systems. Within the community of bibliographic systems research, there has been growing interest and enthusiasm for connecting traditional library data within the graph structures of the semantic web. Classical library metadata is an expressive and highly specialized vocabulary rooted in descriptive and subject cataloging. Efforts to re-deploy this expressiveness for the semantic web are underway with transformation and enrichment of library data. Bibliographic systems researchers have also prototyped the development of semantic search interfaces that take advantage of graph based data. The Library of Congress is leading the development of the upper level bibliographic ontology BIBFRAME, aimed at supporting the discovery of library linked data on the web. While development of semantic interfaces based on BIBFRAME have been prototyped, there is a need to verify that new semantic search interfaces can meet traditional bibliographic tasks. The research agenda will seek to understand how semantic interfaces support library tasks that classical bibliographic systems support, specifically attributes of finding, identifying, selecting, obtaining and exploring by way of contextual search. A possible outcome of such a research area may include the articulation for best uses of semantic searching with contextual exploration relative to classic library record based (non-graph based) searches of named entity searching.

----------------------------------------------------------------

# Study Data Validation & Submission Conformance {#study-validation}

#### Speakers
- Tim Williams, UCB Biosciences Inc

#### Abstract

Converting study data to Linked Data as Resource Description Framework (RDF) goes a long way toward improving data quality and flexibility. But the unique identifiers, semantic relationships, ontology-based schema, and integral metadata are just part of the equation. When validation rules are included in the data ecosystem, quality control spans the entire data life cycle from data collection all the way through to submission and reporting.

FDA Submission conformance checks can be represented using Shapes Constraint Language (SHACL), with a goal of replacing labor-intensive, manual validation processes performed by both study sponsors and regulatory agencies. Faster approvals will ensure patients receive treatment sooner.
