# The Wastewater Contextual Data Specification

  - [About the PHA4GE Wastewater Contextual Data Specification](#about-the-pha4ge-wastewater-contextual-data-specification-an-interoperable-framework-for-wastewater-microbial-genomics-environmental-surveillance)
  - [ntegration with the international wastewater surveillance ecosystem?](#integration-with-the-international-wastewater-surveillance-ecosystem)
  - [What is genomics contextual data and why is it important?](#what-is-genomics-contextual-data-and-why-is-it-important)
    - [What are ontologies and how do they improve data quality?](#what-are-ontologies-and-how-do-they-improve-data-quality)
  - [The Wastewater Contextual Data Specification Package](#the--contextual-data-specification-package)
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

## About the PHA4GE Wastewater Contextual Data Specification: An interoperable framework for wastewater microbial genomics environmental surveillance

Wastewater genomics data is increasingly being used to support a wide variety of surveillance programs and research to support public health decision making and responses e.g. detection and monitoring of emerging and existing pathogens, detection and characterization of antimicrobial resistance (AMR) determinants, quantifying infectious disease genotypes and assessing prevalence, etc. Wastewater genomic surveillance integrates diverse data from various sources, agencies, and systems, presenting challenges in harmonization, integration and interpretation.  Structuring contextual data using data standards, aids accessibility and usability by both humans and computers supporting reuse. Standards providing guidance on which data elements are the most informative for different public health analyses, as well as any issues regarding their privacy and sensitivity, is also critical.

The PHA4GE Wastewater Contextual Data Specification Package is scoped for **data collection and sharing** (within organizations, within networks and if desired, with public repositories) of both pathogen-agnostic genomics contextual data and genotypic attributes (such as antimicrobial resistance genes) derived from amplicon-based, WGS, and metagenomic sequencing approaches. The goal of the specification is to create a **data interoperability framework** that enables exchange and communication between data generators and consumers using wastewater for surveillance, that is **extensible for other types of water-based surveillance** (e.g. agriculture-based water monitoring, freshwater and marine environmental studies, and wildlife vector investigations), and is **compatible with existing clinical and One Health standards**. The specification was designed through consultation with partners involved in different wastewater projects in **LMICs** and **HICs**. The specification package, when completed, will consist of: 

1. Ontology-based, standardized terminology implemented in public health-ready templates and tools
2. Supporting materials including terminology reference guides, a data curation SOP (containing ethical, privacy, and practical considerations for data sharing), and submission protocols
3. Mapping schemes between commonly used wastewater standards specifying an interchange format, and tools enabling automated data transformations between the different standards (under development)
4. A new term request system enabling users to request new fields and terms if vocabulary is missing and as data needs evolve

This is a resource co-developed by PHA4GE, the Centre for Infectious Disease Genomics and One Health (CIDGOH), the Public Health Agency of Canada, and the Bill & Melinda Gates Foundation to support wastewater microbial genomics-based surveillance and research.

## Integration with the international wastewater surveillance ecosystem?

1. Labs without data standards can adopt the PHA4GE standard. 
2. Labs that have their own standards may also use the PHA4GE interoperability framework to automate data transformations to facilitate data sharing and communication with other labs that are using different standards. 
3. As PHA4GE maintains its resources and evolves its standards over time, labs can communicate needs to PHA4GE and contribute to maintenance and development (and get credit for their contributions) of standards via consensus.
4. PHA4GE continues to work with international databases to make the standard available to labs for harmonization of public data.


## What is genomics contextual data and why is it important?

Microbial wastewater genomics data is composed of sequence data and contextual data. Contextual data consists of the sample metadata, as well as the environmental conditions and measurements, methods, and provenance information needed to attribute, analyze, and make sense of the sequence data. Wastewater genomics data is increasingly utilized in various surveillance programs and research, aiding public health decision-making and responses: e.g., detection and monitoring of emerging and existing pathogens, detection and characterization of antimicrobial resistance (AMR) determinants, quantifying infectious disease genotypes and assessing prevalence, etc. These activities often require information about **sample types** (environmental sites and materials), **surveillance and sampling scope** (target organisms, sampling strategies, wastewater systems, frequency and duration of testing, devices and methods of collection), **sequencing and enrichment methods** (amplicon sequencing, WGS, metagenomics; filtering; sequencing instrument), **bioinformatics processing and quality control metrics** (software, pipelines, reference databases, coverage, total/mapped reads), as well as **contributor information for establishing chains of custody and for follow-up**.  

Wastewater genomic surveillance often involves data streams originating from different sources, agencies, sectors, and information management systems. These data are generally structured in a variety of ways posing challenges for data harmonization, integration and meaningful interpretation. By structuring contextual data using data standards, this information can be more easily understood and used by both humans and computers and can be more easily reused for different types of analyses. Standards providing guidance on which data elements are the most informative for different public health analyses, as well as any issues regarding their privacy and sensitivity, is also critical.


## What are ontologies and how do they improve data quality and standardisation?

Labs collect, encode and store information in different ways. They use different fields, terms and formats, they categorize variables in different ways, and the meanings of words change depending on the focus of the organization (think of the word “plant”. To someone in agriculture, “plant” could mean an organism that carries out photosynthesis, while a food regulator might understand the word “plant” to mean a factory where food products are made). This variability makes comparing, integrating and analyzing data generated by different organizations like trying to compare apples, oranges and bananas, which is difficult to do.

Ontologies are collections of controlled vocabulary that are arranged in a hierarchy, where all the terms are linked using logical relationships. Ontologies are open source and meant to represent “universal truth” as much as possible (so not tied to one organization’s vocabulary of use case). Ontologies encode synonyms, which enables mapping between the specific languages used by different organizations, and every term in the ontology is assigned a globally unique and persistent identifier. Using ontology terms to standardize GRDI-AMR contextual data not only helps make data more interoperable by using a common language, it also helps to make contextual data [FAIR](https://www.go-fair.org/fair-principles/) (Findable, Accessible, Interoperable, Reusable).

## The Wastewater Contextual Data Specification Package

This specification is implemented via the [DataHarmonizer](https://github.com/cidgoh/DataHarmonizer), accompanying **Field** and **Term reference guides** (which provide definitions and additional specific guidance) and a curation **Standard Operating Procedure (SOP)**. New terms and/or term changes can be requested using issue request forms, with additional guidance on how to do so outline in the New Term Request (NTR) SOP. This resources are available in the files of this repository and listed below under **Package Contents**.

### Version Control

Please note that development of the specification is dynamic and it will be updated periodically to address user needs. Versioning is done in the format of `x.y.z`.

`x` = Field level changes <br>
`y` = Term value / ID level changes <br>
`z` = Definition, guidance, example, formatting, or other uncategorized changes

Descriptions of changes are provided in [release notes](https://github.com/cidgoh/Wastewater_Contextual_Data_Specification/releases) for every new version.

### Package Contents (IN-PROGRESS)

#### Data Collection Template (IN-PROGRESS)
- [Pathogen Genomics Package (**<INSERT SPEC TEMPLATE NAME>**)](https://github.com/cidgoh/pathogen-genomics-package/releases)
  - Template schema files can be found as `.yaml`/`.json`/`.tsv` under [pathogen-genomics-package/templates/](https://github.com/cidgoh/pathogen-genomics-package/tree/main/templates)**<INSERT SPEC TEMPLATE FOLDER NAME>**
- [DataHarmonizer App](https://github.com/cidgoh/DataHarmonizer)
  - The DataHarmonizer is a standardized browser-based spreadsheet editor and validator.
  - Instructions on "Getting Started" downloading and using the application can be found under **DataHarmonizer Instructions and SOP** below.
  - Further information about application functionality can be found on the [DataHarmonizer Wiki](https://github.com/cidgoh/pathogen-genomics-package/wiki/DataHarmonizer-Getting-Started).

#### Field and Term Reference Guides (IN-PROGRESS)
- [XLSX version]()
- PDF version
  - [Field Reference Guide]()
  - [Term Reference Guide]()
- [Online version]()

#### Curation SOP (IN-PROGRESS)
- [PDF version]()
- [Online version]()

#### DataHarmonizer Instructions and SOP (IN-PROGRESS)
- [PDF version]()
- [Online version]()

#### New Term Request (NTR) SOP (IN-PROGRESS)
- [PDF version]()
- [Online version]()

## Contacts
For more information and/or assistance, contact Dr. Emma Griffiths at <ega12@sfu.ca> or submit a repository [issue request](https://github.com/cidgoh/Wastewater_Contextual_Data_Specification/issues/new/choose).

## License

_Pending / To Be Determined_

## Acknowledgements

Brought to you by the [Centre for Infectious disease Genomics and One Health](https://cidgoh.ca/) and the [Public Health Alliance for Genomic Epidemiology](pha4ge.org) [Data Structures Workgroup](https://pha4ge.org/data-structures/).

![LogoCIDGOH2](https://github.com/cidgoh/specification-repo-template/assets/48695054/87fa713d-8fd7-453d-8542-fc413069e842)
![PHA4GE-logo](https://github.com/cidgoh/Wastewater_Contextual_Data_Specification/assets/48695054/10049f9b-6048-4fcf-8d32-fbcffbb10d58)

