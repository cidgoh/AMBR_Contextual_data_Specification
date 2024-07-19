# The <insert name> Contextual Data Specification

  - [About](#about)
  - [What are ontologies and how do they improve data quality?](#what-are-ontologies-and-how-do-they-improve-data-quality)
  - [The  Contextual Data Specification Package](#the--contextual-data-specification-package)
    - [Version Control](#version-control)
    - [Package Contents](#package-contents)
      - [Data Collection Template](#data-collection-template)
      - [Field and Term Reference Guides](#field-and-term-reference-guides)
      - [Curation SOP](#curation-sop)
      - [DataHarmonizer Instructions and SOP](#dataharmonizer-instructions-and-sop)
      - [New Term Request (NTR) SOP](#new-term-request-ntr-sop)
  - [Contacts](#contacts)
  - [License](#license)
  - [Acknowledgements](#acknowledgements)

## About

<Blurb>
<SETUP: you'll need to manual create "term request" and "field request" labels in order for the issue forms to apply them when generated. You'll also want to go through documentation and replace all the <INSERT values with appropriate information.>

The AMBR Project, led by the Harrison Lab at the University of Calgary, is an interdisciplinary study aimed at using 16S sequencing as part of a culturomics platform to identify antibiotic potentiators from the natural products of microbiota. The AMBR DataHarmonizer template was designed to standardize isolate and methodological contextual data associated with the Alberta Microbiota Repository (AMBR) repository

## What are ontologies and how do they improve data quality?

Labs collect, encode and store information in different ways. They use different fields, terms and formats, they categorize variables in different ways, and the meanings of words change depending on the focus of the organization (think of the word “plant”. To someone in agriculture, “plant” could mean an organism that carries out photosynthesis, while a food regulator might understand the word “plant” to mean a factory where food products are made). This variability makes comparing, integrating and analyzing data generated by different organizations like trying to compare apples, oranges and bananas, which is difficult to do.

Ontologies are collections of controlled vocabulary that are arranged in a hierarchy, where all the terms are linked using logical relationships. Ontologies are open source and meant to represent “universal truth” as much as possible (so not tied to one organization’s vocabulary of use case). Ontologies encode synonyms, which enables mapping between the specific languages used by different organizations, and every term in the ontology is assigned a globally unique and persistent identifier. Using ontology terms to standardize GRDI-AMR contextual data not only helps make data more interoperable by using a common language, it also helps to make contextual data [FAIR](https://www.go-fair.org/fair-principles/) (Findable, Accessible, Interoperable, Reusable).

## The AMBR Contextual Data Specification Package

This specification is implemented via a DataHarmonizer validation template,accompanying **Field** and **Term reference guides** (which provide definitions and additional specific guidance) and a curation **Standard Operating Procedure (SOP)**. 

New terms and/or term changes can be requested using issue request forms, with additional guidance on how to do so outline in the New Term Request (NTR) SOP. This resources are available in the files of this repository and listed below under **Package Contents**.

### Version Control

Please note that development of the specification is dynamic and it will be updated periodically to address user needs. Versioning is done in the format of `x.y.z`.

`x` = Field level changes <br>
`y` = Term value / ID level changes <br>
`z` = Definition, guidance, example, formatting, or other uncategorized changes

Descriptions of changes are provided in [release notes](https://github.com/cidgoh/AMBR/releases) for every new version.

### Package Contents

#### Data Collection Template
- [Pathogen Genomics Package (**AMBR**)](https://github.com/cidgoh/pathogen-genomics-package/releases)
  - Template schema files can be found as `.yaml`/`.json`/`.tsv` under [pathogen-genomics-package/templates/](https://github.com/cidgoh/pathogen-genomics-package/tree/main/templates)**AMBR**
- [DataHarmonizer App](https://github.com/cidgoh/DataHarmonizer)
  - The DataHarmonizer is a standardized browser-based spreadsheet editor and validator.
  - Instructions on "Getting Started" downloading and using the application, as well as application functionality can be found on the [DataHarmonizer Wiki](https://github.com/cidgoh/pathogen-genomics-package/wiki/DataHarmonizer-Getting-Started).

#### Field and Term Reference Guides
- [XLSX version]()
- PDF version
  - [Field Reference Guide]()
  - [Term Reference Guide]()
- [Online version]()

#### Curation SOP
- [PDF version]()
- [Online version]()

#### New Term Request (NTR) SOP
- [PDF version]()
- [Online version]()

## Contacts
For more information and/or assistance, contact Emma Griffiths at emma_griffiths@sfu.ca or submit a repository [issue request](https://github.com/cidgoh/AMBR_Contextual_data_Specification/issues/new/choose).

## License

_Pending / To Be Determined_

## Acknowledgements

Brought to you by The [Centre for Infectious disease Genomics and One Health](https://cidgoh.ca/) Harrison Lab at the University of Calgary.

![LogoCIDGOH2](https://github.com/cidgoh/specification-repo-template/assets/48695054/87fa713d-8fd7-453d-8542-fc413069e842)
