# About Aibel
Aibel is a leading service company within the oil, gas and offshore wind industries. We provide our customers with optimal and innovative solutions within engineering, construction, modifications and maintenance throughout a project's entire life cycle.

https://aibel.com/

# Aibel's Material Master Data (MMD) Ontology
Aibel's Material Master Data (MMD) ontology defines the vocabulary Aibel uses for product classification and description. MMD is Master Data source for downstream engineering authoring tools, like 3D CAD and ERP systems. By using the ontology, Aibel has improved the data quality in project execution and reduced the time and cost associated with generating project product catalogs.

# License and Versions
This repository contains the MMD ontology published under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. The ontology has been obscured to protect sensitive information, which is largely done by re-minting IRIs and literals, while still preserving the logical content of the ontology.

The ontology is written in <a href="https://www.w3.org/TR/owl2-overview/">OWL 2</a>, and it is provided in three different versions, all in serialized in <a href="https://www.w3.org/TR/turtle/">Turtle syntax</a>.

| Version       | Description |
|---------------|-------------|
| mmd-all       | All of MMD. *Not* suitable for use with OWL 2 reasoners; use <a href="https://www.w3.org/TR/rdf-sparql-query/">SPARQL</a> instead. |
| mmd-prod      | All of MMD, minus deprecated items. *Not* suitable for use with OWL 2 reasoners; use <a href="https://www.w3.org/TR/rdf-sparql-query/">SPARQL</a> instead. |
| mmd-ereasoner | A limited version suitable for use with an OWL 2 reasoner. Aibel uses <a href="http://www.hermit-reasoner.com/">HermiT</a>. Classified with HermiT in ~2.5 hours. |
| mmd-reasoner  | Even more stripped-down version. Classified with HermiT in ~34 minutes. |

# Keep Us Informed!
Aibel publishes the ontology with the primary intent of providing researchers and software developers with free access to a large-scale real industrial ontology and will therefore appreciate to be given access to or be made aware of any developments or new insights that result from the use of the ontology.

Questions or comments may be posted as issues to this repository.

# Ontology Metrics

|                                     | mmd-reasoner | mmd-ereasoner |  mmd-prod |   mmd-all |
|-------------------------------------|-------------:|--------------:|----------:|----------:|
| **Metrics**                         |              |               |           |           |
| **Axiom**                           |    1,757,061 |     3,049,219 | 4,340,601 | 4,373,312 |
| **Logical axiom count**             |      617,836 |       993,812 | 1,226,452 | 1,234,803 |
| **Declaration axioms count**        |      110,399 |       189,839 |   228,615 |   230,052 |
| **Class count**                     |       97,605 |       181,067 |   200,085 |   201,541 |
| **Object property count**           |          170 |           169 |       212 |       212 |
| **Data property count**             |          819 |           818 |       826 |       826 |
| **Individual count**                |       15,625 |        15,537 |    44,561 |    44,561 |
| **Annotation Property count**       |          387 |           402 |       472 |       475 |
| **Class axioms**                    |              |               |           |           |
| **SubClassOf**                      |      583,662 |       959,731 | 1,112,348 | 1,120,699 |
| **EquivalentClasses**               |        1,035 |         1,004 |     1,039 |     1,039 |
| **DisjointClasses**                 |           25 |            25 |        29 |        29 |
| **GCI count**                       |            0 |             0 |         0 |         0 |
| **Hidden GCI Count**                |          984 |           954 |       988 |       988 |
| **Object property axioms**          |              |               |           |           |
| **SubObjectPropertyOf**             |          154 |           154 |       195 |       195 |
| **EquivalentObjectProperties**      |            0 |             0 |         0 |         0 |
| **InverseObjectProperties**         |           19 |            19 |        28 |        28 |
| **DisjointObjectProperties**        |            5 |             5 |        11 |        11 |
| **FunctionalObjectProperty**        |            1 |             1 |         4 |         4 |
| **InverseFunctionalObjectProperty** |            0 |             0 |         0 |         0 |
| **TransitiveObjectProperty**        |            4 |             4 |         4 |         4 |
| **SymmetricObjectProperty**         |            6 |             6 |         7 |         7 |
| **AsymmetricObjectProperty**        |            0 |             0 |         0 |         0 |
| **ReflexiveObjectProperty**         |            0 |             0 |         0 |         0 |
| **IrrefexiveObjectProperty**        |            0 |             0 |         0 |         0 |
| **ObjectPropertyDomain**            |           48 |            48 |        57 |        57 |
| **ObjectPropertyRange**             |           57 |            57 |        66 |        66 |
| **SubPropertyChainOf**              |            0 |             0 |         0 |         0 |
| **Data property axioms**            |              |               |           |           |
| **SubDataPropertyOf**               |          834 |           834 |       838 |       838 |
| **EquivalentDataProperties**        |            0 |             0 |         0 |         0 |
| **DisjointDataProperties**          |            0 |             0 |         0 |         0 |
| **FunctionalDataProperty**          |           19 |            19 |        21 |        21 |
| **DataPropertyDomain**              |           40 |            40 |        41 |        41 |
| **DataPropertyRange**               |           77 |            77 |        79 |        79 |
| **Individual axioms**               |              |               |           |           |
| **ClassAssertion**                  |       11,826 |        11,829 |    27,516 |    27,516 |
| **ObjectPropertyAssertion**         |       19,983 |        19,918 |    83,787 |    83,787 |
| **DataPropertyAssertion**           |           41 |            41 |       382 |       382 |
| **NegativeObjectPropertyAssertion** |            0 |             0 |         0 |         0 |
| **NegativeDataPropertyAssertion**   |            0 |             0 |         0 |         0 |
| **SameIndividual**                  |            0 |             0 |         0 |         0 |
| **DifferentIndividuals**            |            0 |             0 |         0 |         0 |
| **Annotation axioms**               |              |               |           |           |
| **AnnotationAssertion**             |    1,028,552 |     1,865,294 | 2,885,144 | 2,908,067 |
| **AnnotationPropertyDomain**        |           52 |            52 |        52 |        52 |
| **AnnotationPropertyRangeOf**       |           52 |            52 |        86 |        86 |
