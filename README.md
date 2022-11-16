# Digital Use Conditions - Schema 
This repository hosts the schema for the Digital Use Conditions machine readable consent and use conditions specification.

DUC provides a formal terms structure that makes use of existing vocabulary concepts (without directionality) to be referenced within its structure. What DUC primarily provides are “slots” to define the main condition concept, more details about that concept, the rule that applies, and whether the scope of this rule applies to the whole asset or only a part of the asset.

Hosted by the International Rare Disease Research Consortium (IRDiRC) as a Task Force formed in late 2020, the Digital Use Conditions working group of over 40 international members is completing the development of the “digital use conditions” (DUC) data structure to solve the above limitations.

Using this structure, simple or sophisticated sets of conditions can be designed to make the best use of existing ontology concepts. For instance, resource use that permits general research for a 12 month time limit on use could be expressed as the set of two condition statements:
- conditionTerm: General Research Use (DUO:0000042), rule: Permitted
- conditionTerm: Time limit on use (DUO:0000025), conditionDetail: Month (UO:0000035), conditionDetailValue: 12, rule: Obligated

DUC is meant to work alone using free text descriptions of use conditions and details, or by using DUC slots with existing controlled vocabularies/ontologies such as [DUO](https://www.ebi.ac.uk/ols/ontologies/duo), [ICO](https://www.ebi.ac.uk/ols/ontologies/ico), [SNOMED](https://www.ebi.ac.uk/ols/ontologies/snomed), [DOID](https://www.ebi.ac.uk/ols/ontologies/doid), [UO](https://www.ebi.ac.uk/ols/ontologies/uo), and many others. By adopting controlled terms DUC will afford more machine readibility and interpretation to further facilitate data findability and access.
