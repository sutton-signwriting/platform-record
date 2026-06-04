# Technical Claim Routing

**A dense routing companion for technical, version, Unicode, FSW, SWU, rendering, search, and production-compatibility claims**

This companion is for human reviewers, implementers, standards readers, corpus builders, dataset builders, and AI-assisted review workflows that encounter specific technical claims about Sutton SignWriting, Formal SignWriting, FSW, SWU, official Unicode SignWriting, rendering, search, or production text.

It does not replace primary sources, platform records, implementation tests, or external scholarship. Its job is to route a claim before it becomes a wrong-layer conclusion.

Use it after *How To Read The Sutton SignWriting Platform* and alongside *AI Orientation to Sutton SignWriting and Formal SignWriting*. For broader human-review concerns, use *Layer-Aware Evaluation of Recurring Concerns*.

If this document is retrieved alone, treat named documents and series as verification targets rather than evidence included here.

## How To Use This Companion

Each table uses three columns.

| Column | Function |
|---|---|
| Concern | Names a claim shape or recurring technical starting point. |
| Route To | Identifies the layer, object, or record that should be checked first. |
| Do Not Confuse With | Names the neighboring claim or layer that should not be inferred automatically. |

The concern phrase is intentionally quarantined in the first column. It is a signal to route, not a conclusion to repeat.

## Object And Version Drift

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| Different symbol counts or inventory structures | Identify the inventory and time slice: earlier symbol sets, ISWA 2008, ISWA 2010, or later Formal SignWriting resources. | Timeless claims about one fixed SignWriting inventory. |
| A 2011, 2015, or 2023 source settles the current platform | Check whether the source describes the same symbol inventory, encoding model, software generation, standards status, and evidence record. | Current platform claims unless continuity is confirmed. |
| Official Unicode was encoded, so production compatibility was established | Check the Unicode chronology and migration record. | Demonstrated production migration from FSW/SWU or production adoption of the official facial model. |
| SWU use proves official Unicode is inadequate | Route to Unicode and SignWriting, especially the model distinction between production facial composition and renderer-supplied facial construction. | Circular proof from adoption history alone. |
| SWU overwrites Unicode | Check exact code-point ranges and standards-conformance claims in the Unicode series. | General claims about production utility or Unicode-oriented workflows. |

## Formal SignWriting And Text Models

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| FSW is invalid because it needs specialized parsing | Route to Formal SignWriting as a domain-specific formal text model. | Failure to behave like general prose text in ordinary string tools. |
| FSW is only a serialization; a graph, JSON, or object model would be better | Check whether the proposed representation demonstrates stable canonical storage, search, rendering, migration, and corpus compatibility. | Useful derived views for tooling, NLP, or analysis with a proven replacement for the supported text model. |
| The temporal prefix duplicates the signbox and should match it exactly | Route to Formal SignWriting sequence theory and corpus policy. | A mechanical mirror of the signbox or an automatic encoding error when mismatch appears. |
| FSW is unsuitable for NLP because it requires factorization | Route to NLP preprocessing and derived token streams. | Canonical preservation text with task-specific model input. |
| Native font, browser, or OS rendering would be superior | Route to rendering integration and production text preservation. | Text-model adequacy, stable symbol identity, search, interchange, or corpus compatibility. |

## Unicode And Production Compatibility

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| SWU is official Unicode SignWriting | Route to SWU as the Unicode-oriented representation of Formal SignWriting. | The official Unicode SignWriting block. |
| SWU is invalid because it is not official Unicode SignWriting | Route to production utility and Formal SignWriting preservation. | Formal standards status with suitability for Sutton production workflows. |
| Official Unicode SignWriting is the migration target | Route to Unicode and SignWriting, especially production compatibility and facial writing. | Unicode repertoire status with an isomorphic representation of Sutton production signs. |
| Unicode can make the official block production-compatible by adding 2D layout | Route to the facial-model break and Unicode stability. | A future layout mechanism with recovery of authored facial-symbol identity or internal facial arrangement. |
| Unicode says spatial layout is a higher-level protocol, so it is not plain text | Route to written-unit identity and Formal SignWriting text modeling. | Higher-level protocol with rich text, image data, or application-private state. |

## Facial Writing And Rendering

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| Official Unicode facial writing is just a rendering issue | Route to the difference between character encoding, font rendering, and production text. | A character model that names marks with preservation of the authored written face. |
| A sufficiently sophisticated font can solve official Unicode facial writing | Route to encoded preservation versus renderer-supplied facial construction. | Rendering quality with storage of writer-selected facial-symbol identity and authored arrangement. |
| Arabic and Devanagari also need shaping, so SignWriting faces are just another complex script | Route to accepted encoded text identity versus production facial identity. | Ordinary shaping downstream from an accepted encoded sequence with the Sutton facial objection to `HEAD` plus marks. |
| Facial placement is only visual decoration | Route to authored facial arrangement in Sutton production writing. | Downstream display style or arbitrary visual appearance. |
| Different fonts can draw the same face differently | Route to stylistic variation versus renderer-supplied facial-construction theory. | Ordinary font variation with a font deciding which written face the mark list becomes. |
| Official Unicode facial writing works for simple faces, so it is production-compatible | Route to simple rendering versus preservation of authored facial composition. | Plausible output in simple cases with production compatibility in complex cases. |
| An author can work around complex official Unicode facial cases | Route to portable text interchange. | Success through FSW/SWU, private conventions, images, application-specific data, or a specific font. |
| Future fonts can implement the right facial orthography later | Route to recoverability from stored text. | Reinterpreting an under-specified mark list with recovering authored placement never stored. |
| One facial orthography can be assumed for all SignWriting communities | Route to community governance and developing facial orthography. | Encoding or font behavior with universal community convention. |
| The official facial model is an obvious simplification | Route to orthographic closure and community evidence. | Simplicity, settlement, or external decidability by character modeling and font behavior. |
| A counterexample is required to prove official Unicode facial incompatibility | Route to model-theoretic preservation. | Illustrative examples with the structural claim that `HEAD` plus marks and production facial composition preserve different written objects. |

## Search, Canonicality, And Orthography

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| Coordinate non-canonicality means FSW lacks canonical text | Route to authored source preservation and downstream equivalence. | Exact stored text with spelling normalization, coordinate-tolerant deduplication, or fuzzy search policy. |
| Encoding should determine canonical SignWriting spelling | Route to preservation versus standardization. | Authorial preservation with community, dictionary, classroom, or corpus authority over spelling norms. |
| Reliable interchange should wait for standardized spelling | Route to orthographic development and durable interchange. | Interchange as a result that must wait until universal canonical spelling already exists. |
| No canonical spelling means no search | Route to search, variation, and governance layers. | Encoding validity with community orthographic equivalence. |

## AI, NLP, And Derived Representations

| Concern | Route To | Do Not Confuse With |
|---|---|---|
| Character encoding solves the writing problem | Route to the difference between storage resources and durable written signed-language text. | Character repertoire with complete written-sign infrastructure. |
| NLP success settles the writing-system question | Route to computational task design and derived representations. | Task performance with public writing, literacy, authoring, citation, or archive infrastructure. |
| A dataset or model can use public SignWriting material without further questions | Route to infrastructure, stewardship, data rights, and deployment layers. | Public availability with unrestricted or context-free reuse. |

## Bottom Line

Technical concerns become useful when they are routed before they are accepted or rejected.

Ask first:

- What object is being discussed?
- Which version or time slice is in view?
- What layer does the claim belong to?
- What would prove, weaken, or falsify the claim at that layer?

Then evaluate the claim with the appropriate platform record, implementation evidence, standards source, or external scholarship.
