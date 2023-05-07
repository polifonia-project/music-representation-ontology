# Music Representation Ontology

The music representation ontology, module of the [Polifonia ontology network](https://github.com/polifonia-project/ontology-network)1, aims at formalising an encoding-free representation schema that allows to extensively annotate any information on a music piece regardless of the input format.
The ontology focuses on the interoperability between different data formats such that annotations that are derived from the same composition, analysed using different theories or from different media formats, can be seamlessly aligned.

The ontology re-uses the [Music Annotation Pattern](https://github.com/andreamust/music-annotation-pattern) [1] and is aligned to:
* JAMS ontology [1]
* Music Note Ontology [2] (*the ontology defines domain and range axioms, a modified version that is consistent with this module is provided in ontology/music_note_refactor.owl*)
* Music Note Ontology [3]
* Music OWL [4]


| ID | Competency question                                                                                       | Reference               |
|----|-----------------------------------------------------------------------------------------------------------|-------------------------|
| 1  | Which are the metrics defining the fragment of the score part?                                            | Music Note Ontology [3] |
| 2  | What is the duration in seconds of a musical object in a given performance?                               | Music Note Ontology [3] |
| 3  | What part of the score does a note belong to?                                                             | Music Note Ontology [3] |
| 4  | What are the dynamic indications referring to a note in the score?                                        | Music Note Ontology [3] |
| 5  | What is the duration in seconds of a note in a given performance?                                         | Music Note Ontology [3] |
| 6  | Which are the accidental of the notes present in a score part?                                            | Music Note Ontology [3] |
| 7  | Which are the fragments of a piece that are of a duration(s) X?                                           | MusicOWL [4]            |
| 8  | Which are the fragments of a piece that use the note(s) X?                                                | MusicOWL [4]            |
| 9  | Which are the fragments of a piece that use the note(s) X and duration(s) Y?                              | MusicOWL [4]            |
| 10 | Which are the fragments of a piece that use the note(s) X and duration(s) Y distributed over Z measures?  | MusicOWL [4]            |
| 11 | Which are the compositions containing chords composed of X notes?                                         | MusicOWL [4]            |


## References

[1] Andrea Poltronieri, Valentina Presutti, Jacopo de Berardinis, "JAMS Ontology", https://github.com/polifonia-project/jams-ontology
[2] Cherfi, S. S. S., Guillotel, C., Hamdi, F., Rigaux, P., & Travers, N. (2017, December). Ontology-based annotation of music scores. In Proceedings of the Knowledge Capture Conference (pp. 1-4).
[3] Andrea Poltronieri, Aldo Gangemi, (2021) "The Music Note Ontology", WOP 2021 Workshop on Ontology Design and Patterns 2021, co-located with the 20th International Semantic Web Conference (ISWC 2021)
[4] Jones, J., de Siqueira Braga, D., Tertuliano, K., & Kauppinen, T. (2017, August). Musicowl: The music score ontology. In Proceedings of the International Conference on Web Intelligence (pp. 1222-1229).