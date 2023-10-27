---
component-id: https://w3id.org/polifonia/ontology/music-representation/
type: Ontology
name: Music Representation Ontology
description: An ontology to achieve interoperability of annotation made on musical content.
image: https://github.com/polifonia-project/music-representation-ontology/raw/main/diagrams/music_representation.png
logo: https://github.com/polifonia-project/music-representation-ontology/raw/main/assets/logo.png
work-package:
- WP2
pilot:
- INTERLINK
project: polifonia-project
resource: ontology/music-representation.owl
release-date: 27/06/2023
release-number: v1.0
release-link: https://github.com/polifonia-project/ontology-network/releases/tag/v1.0
doi: 10.5281/zenodo.7919970
changelog: https://github.com/polifonia-project/ontology-network/releases/tag/v1.0
licence:
- CC-BY_v4
copyright: "Copyright (c) 2023 Andrea Poltronieri, Nicolas Lazzari, Jacopo de Berardinis"
contributors:
- Andrea Poltronieri <https://github.com/andreamust>
- Nicolas Lazzari <https://github.com/n28div>
- Jacopo de Berardinis <https://github.com/jonnybluesman>
related-components:
- informed-by:
  - polifoniacq-dataset
- reuses:  
  - https://w3id.org/polifonia/ontology/core/
---

# Music Representation Ontology
The [Music Representation Ontology](https://github.com/polifonia-project/music-representation-ontology) provides a comprehensive schema to describe the analysis of musical objects (a score, an audio track, etc.) interpreted in the context of an existing theory.
Fragments of a musical object -- elements of a musical object whose temporal location is uniquely identifiable -- are described by an annotation provided by an agent, that ranges from an expert annotator to an algorithm.
An annotation is either the subjective result of an analysis (e.g. the chord played in a specific section) or objective (e.g. a note in a digital score).
Each annotation describes some observation (e.g. notes, chords, etc.), whose content we refer to as a musical projection, and can be composed hierarchically.
