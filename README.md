# About Aibel
Aibel is a leading service company within the oil, gas and offshore wind industries. We provide our customers with optimal and innovative solutions within engineering, construction, modifications and maintenance throughout a project's entire life cycle.

https://aibel.com/

# Aibel's Material Master Data (MMD) Ontology
Aibel's Material Master Data (MMD) ontology defines the vocabulary Aibel uses for product classification and description. MMD is Master Data source for downstream engineering authoring tools, like 3D CAD and ERP systems. By using the ontology, Aibel has improved the data quality in project execution and reduced the time and cost associated with generating project product catalogs.

# License and Versions
This repository contains the MMD ontology published under the <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>. The ontology has been obscured to protect sensitive information, which is largely done by re-minting IRIs and literals, while still preserving the logical content of the ontology.

The ontology is written in <a href="https://www.w3.org/TR/owl2-overview/">OWL 2</a>, and it is provided in three different versions, all in serialized in <a href="https://www.w3.org/TR/turtle/">Turtle syntax</a>.

| Version | Description |
|---------|-------------|
| mmd-all | All of MMD. *Not* suitable for use with OWL 2 reasoners; use <a href="https://www.w3.org/TR/rdf-sparql-query/">SPARQL</a> instead. |
| mmd-ereasoner | A limited version suitable for use with an OWL 2 reasoner. Aibel uses <a href="http://www.hermit-reasoner.com/">HermiT</a>. Classified with HermiT in ~33 minutes. |
| mmd-reasoner | Even more stripped-down version. Classified with HermiT in ~13 minutes. |

# Keep Us Informed!
Aibel publishes the ontology with the primary intent of providing researchers and software developers with free access to a large-scale real industrial ontology and will therefore appreciate to be given access to or be made aware of any developments or new insights that result from the use of the ontology.

Questions or comments may be posted as issues to this repository.

# Ontology Metrics
|                                     | mmd-reasoner | mmd-ereasoner | mmd-all |
|-------------------------------------|-------------:|--------------:|--------:|
| **Metrics**                         |              |               |         |
| **Axiom**                           |       938625 |       1511835 | 1945224 |
| **Logical axiom count**             |       340955 |        530604 |  561120 |
| **Declaration axioms count**        |        69529 |        103284 |  111531 |
| **Class count**                     |        61961 |         95698 |  101602 |
| **Object property count**           |          149 |           149 |     181 |
| **Data property count**             |          724 |           724 |     727 |
| **Individual count**                |         9214 |          9231 |   21863 |
| **Annotation Property count**       |          321 |           337 |     392 |
| **Class axioms**                    |              |               |         |
| **SubClassOf**                      |       324920 |        514585 |  525986 |
| **EquivalentClasses**               |          748 |           748 |     752 |
| **DisjointClasses**                 |           24 |            24 |      28 |
| **GCI count**                       |            0 |             0 |       0 |
| **Hidden GCI Count**                |          721 |           721 |     725 |
| **Object property axioms**          |              |               |         |
| **SubObjectPropertyOf**             |          134 |           134 |     166 |
| **EquivalentObjectProperties**      |            0 |             0 |       0 |
| **InverseObjectProperties**         |           19 |            19 |      28 |
| **DisjointObjectProperties**        |            5 |             5 |      11 |
| **FunctionalObjectProperty**        |            1 |             1 |       1 |
| **InverseFunctionalObjectProperty** |            0 |             0 |       0 |
| **TransitiveObjectProperty**        |            4 |             4 |       4 |
| **SymmetricObjectProperty**         |            6 |             6 |       7 |
| **AsymmetricObjectProperty**        |            0 |             0 |       0 |
| **ReflexiveObjectProperty**         |            0 |             0 |       0 |
| **IrrefexiveObjectProperty**        |            0 |             0 |       0 |
| **ObjectPropertyDomain**            |           43 |            43 |      48 |
| **ObjectPropertyRange**             |           55 |            55 |      60 |
| **SubPropertyChainOf**              |            0 |             0 |       0 |
| **Data property axioms**            |              |               |         |
| **SubDataPropertyOf**               |          735 |           735 |     738 |
| **EquivalentDataProperties**        |            0 |             0 |       0 |
| **DisjointDataProperties**          |            0 |             0 |       0 |
| **FunctionalDataProperty**          |           15 |            15 |      15 |
| **DataPropertyDomain**              |           55 |            55 |      56 |
| **DataPropertyRange**               |           66 |            66 |      66 |
| **Individual axioms**               |              |               |         |
| **ClassAssertion**                  |         6748 |          6765 |    8993 |
| **ObjectPropertyAssertion**         |         7377 |          7344 |   24161 |
| **DataPropertyAssertion**           |            0 |             0 |       0 |
| **NegativeObjectPropertyAssertion** |            0 |             0 |       0 |
| **NegativeDataPropertyAssertion**   |            0 |             0 |       0 |
| **SameIndividual**                  |            0 |             0 |       0 |
| **DifferentIndividuals**            |            0 |             0 |       0 |
| **Annotation axioms**               |              |               |         |
| **AnnotationAssertion**             |       527896 |        877702 | 1272225 |
| **AnnotationPropertyDomain**        |           50 |            50 |      50 |
| **AnnotationPropertyRangeOf**       |           44 |            44 |      78 |
