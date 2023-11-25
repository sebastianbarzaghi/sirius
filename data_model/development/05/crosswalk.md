|                       | **TBox term**               | **Model**   | **Refactored term**             | **Full URI**                                                                       | **Notes**                                                    |
|-----------------------|-----------------------------|-------------|---------------------------------|------------------------------------------------------------------------------------|--------------------------------------------------------------|
| **Class**             |                             |             |                                 |                                                                                    |                                                              |
|                       | `HeritageAsset`             | CIDOC-CRM   | `E24_Physical_Human-Made_Thing` | http://www.cidoc-crm.org/cidoc-crm/E24_Physical_Human-Made_Thing                   |                                                              |
|                       | `Aspect`                    | HeRO        | `Aspect`                        | http://purl.org/sirius/ontology/hero/Aspect                                        |                                                              |
|                       | `Dimension`                 | HeRO        | `Dimension`                     | http://purl.org/sirius/ontology/hero/Dimension                                     |                                                              |
|                       | `Document`                  | OWL         | `Thing`                         | http://www.w3.org/2002/07/owl#Thing                                                                                   | A contributing value can be documented by virtually anything |
|                       | `ValueAssessment`           | HeRO        | `ValueAssessment`               | http://purl.org/sirius/ontology/hero/ValueAssessment                               |                                                              |
|                       | `ContributingValue`         | HeRO        | `ContributingValue`             | http://purl.org/sirius/ontology/hero/ContributingValue                             |                                                              |
|                       | `TimeInterval`              | TI pattern  | `TimeInterval`                  | http://www.ontologydesignpatterns.org/cp/owl/timeinterval.owl#TimeInterval         |                                                              |
| **Object properties** |                             |             |                                 |                                                                                    |                                                              |
|                       | `hasPart`                   | CIDOC-CRM   | `P46_is_composed_of`            | http://www.cidoc-crm.org/cidoc-crm/P46_is_composed_of                              |                                                              |
|                       | `withinAspect`              | HeRO        | `withinAspect`                  | http://purl.org/sirius/ontology/hero/withinAspect                                  |                                                              |
|                       | `withDimension`             | HeRO        | `withDimension`                 | http://purl.org/sirius/ontology/hero/withDimension                                 |                                                              |
|                       | `assignsValueTo`            | HeRO        | `assignsValueTo`                | http://purl.org/sirius/ontology/hero/assignsValueTo                                |                                                              |
|                       | `assignsValue`              | HeRO        | `assignsValue`                  | http://purl.org/sirius/ontology/hero/assignsValue                                  |                                                              |
|                       | `isDocumentedBy`            | HeRO        | `isDocumentedBy`                | http://purl.org/sirius/ontology/hero/isDocumentedBy                                |                                                              |
|                       | `atTime`                    | TVC pattern | `atTime`                        | http://purl.org/spar/tvc/atTime                                                    |                                                              |
| **Data properties**   |                             |             |                                 |                                                                                    |                                                              |
|                       | `representsAssetPercentage` | HeRO        | `representsAssetPercentage`     | http://purl.org/sirius/ontology/hero/representsAssetPercentage                     |                                                              |
|                       | `hasScore`                  | HeRO        | `hasScore`                      | http://purl.org/sirius/ontology/hero/hasScore                                      |                                                              |
|                       | `hasNote`                   | HeRO        | `hasNote`                       | http://purl.org/sirius/ontology/hero/hasNote                                       |                                                              |
|                       | `hasStartDate`              | TI pattern  | `hasIntervalStartDate`          | http://www.ontologydesignpatterns.org/cp/owl/timeinterval.owl#hasIntervalStartDate |                                                              |
|                       | `hasEndDate`                | TI pattern  | `hasIntervalEndDate`            | http://www.ontologydesignpatterns.org/cp/owl/timeinterval.owl#hasIntervalEndDate   |                                                              |
| **Individuals**       |                             |             |                                 |                                                                                    |                                                              |
|                       | `form`                      | HeRO        | `form`                          | http://purl.org/sirius/ontology/hero/form                                          |                                                              |
|                       | `substance`                 | HeRO        | `substance`                     | http://purl.org/sirius/ontology/hero/substance                                     |                                                              |
|                       | `function`                  | HeRO        | `function`                      | http://purl.org/sirius/ontology/hero/function                                      |                                                              |
|                       | `tradition`                 | HeRO        | `tradition`                     | http://purl.org/sirius/ontology/hero/tradition                                     |                                                              |
|                       | `setting`                   | HeRO        | `setting`                       | http://purl.org/sirius/ontology/hero/setting                                       |                                                              |
|                       | `feeling`                   | HeRO        | `feeling`                       | http://purl.org/sirius/ontology/hero/feeling                                       |                                                              |
|                       | `historic`                  | HeRO        | `historic`                      | http://purl.org/sirius/ontology/hero/historical                                    |                                                              |
|                       | `artistic`                  | HeRO        | `artistic`                      | http://purl.org/sirius/ontology/hero/artistic                                      |                                                              |
|                       | `social`                    | HeRO        | `social`                        | http://purl.org/sirius/ontology/hero/social                                        |                                                              |
|                       | `scientific`                | HeRO        | `scientific`                    | http://purl.org/sirius/ontology/hero/scientific                                    |                                                              |