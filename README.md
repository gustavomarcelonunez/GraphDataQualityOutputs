This repository contains exported artifacts used in the evaluation of LLM-based
Text→graph→QA pipelines over historical scientific literature.

The materials include:
- Samples of 30 randomly extracted triples (entity–relationship–entity) per model,
  exported from the generated graph structures in GraphML format. These samples
  are provided for qualitative inspection and manual assessment of relational
  coherence and factual plausibility.
- A set of domain-specific competency questions authored by a marine biology
  domain expert, together with the corresponding answers produced by each LLM
  using the generated graph representations.

The generated structures correspond to RDF-style data graphs (KG-like graphs)
constructed without an explicit ontology or T-Box. As such, they are not intended
to support ontology-based reasoning, but to enable comparative analysis of graph
structure, extracted relations, and downstream question answering behavior across
different LLMs under identical conditions.

These artifacts support reproducibility and transparency of the evaluation
presented in the associated paper, particularly in settings where no reference
knowledge graph or gold standard is available.
