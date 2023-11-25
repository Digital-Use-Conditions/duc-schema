# Digital Use Conditions - Schema 
This repository hosts the schema for the Digital Use Conditions machine readable consent and use conditions specification.

DUC provides a formal terms structure that makes use of existing vocabulary concepts (without directionality) to be referenced within its structure. What DUC primarily provides are “slots” to define the main condition concept, more details about that concept, the rule that applies, and whether the scope of this rule applies to the whole asset or only a part of the asset.

Hosted by the International Rare Disease Research Consortium (IRDiRC) as a Task Force formed in late 2020, the Digital Use Conditions working group of over 40 international members is completing the development of the “digital use conditions” (DUC) data structure to solve the above limitations.

Using this structure, simple or sophisticated sets of conditions can be designed to make the best use of existing ontology concepts. For instance, resource use that permits general research for a 12 month time limit on use could be expressed as the set of two condition statements:
- conditionTerm: General Research Use (DUO:0000042), rule: Permitted, scope: Whole of asset
- conditionTerm: Time limit on use (DUO:0000025), rule: Obligated, scope: Whole of asset, conditionParameter: Month (UO:0000035), conditionParameterValue: 12

## Extending ontologies
DUC can be used with either free text descriptions of use conditions. It works particularly well with concepts designed as part of the Common Conditions of Use Elements (CCEs). More information about CCEs is available from the [CCEs pre-print](https://doi.org/10.5281/zenodo.8200044).

But DUC can also extend existing controlled vocabularies/ontologies to define more detailed terms. For example, ontologies with entities with a web URI can be used such as [DUO](https://www.ebi.ac.uk/ols/ontologies/duo), [ICO](https://www.ebi.ac.uk/ols/ontologies/ico), [SNOMED](https://www.ebi.ac.uk/ols/ontologies/snomed), [DOID](https://www.ebi.ac.uk/ols/ontologies/doid), [UO](https://www.ebi.ac.uk/ols/ontologies/uo), and many others. By adopting controlled terms DUC affords more machine readibility and interpretation to further facilitate data findability and access.

## Learning to use DUC
An excellent collection of instructions on how to use DUC has been published online: https://duc.le.ac.uk/Learn/index.

## Tools to create DUC profiles
A few teams have created DUC profile creation tools that are compliant with the DUC specification herein.

- https://duc.le.ac.uk (code: https://github.com/CafeVariomeUoL/Duc_Profile)
- https://github.com/FrancisJMR/duc-profile-creator/
- https://irdirc.molgeniscloud.org
- https://ducejprd.le.ac.uk

## Official Releases
Official versioned releases of DUC will be available on Zenodo: https://doi.org/10.5281/zenodo.7767323.

## License
The DUC specification comes with the Creative Commons Zero v1.0 Universal (CC0) license: https://github.com/Digital-Use-Conditions/duc-schema/edit/main/LICENSE.
