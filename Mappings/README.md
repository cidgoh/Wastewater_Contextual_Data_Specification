# Mappings to External repositories and other standards

This folder contains mappings from the **Wastewater Contextual Data Specification** to external data standards such as INSDC and others. Each mapping is documented in a separate Excel file.

## Contents

- NCBI_mapping.xlsx: Maps fields from the PHA4GE Wastewater Contextual Data Specification to existing packages including; NCBI Biosample, SRA and ENA.
- PHES_ODM_mapping.xlsx

## Excel File Structure

Each Excel file includes the following columns:

Source ID: The ontology ID attributed to the source field in the PHA4GE Wastewater Contextual Data Specification (e.g., GENEPIO:0001123).
Source field title: The name/title attributed to the PHA4GE field in the Wastewater Contextual Data Specification.
Target field title: Corresponding field name in the external standard.
Target Field Type: The data type of the target field (e.g., string, integer).
Transformation rule: A broad category that describes the transformation rule used to map the source field to the target field (e.g., one to one, concatenate).
Details: Additional information or instructions for the mapping, such as specific considerations or contextual notes (e.g. "in target_field concatenate values from 'sequencing protocol' and 'genomic target enrichment method' ").



## How to Use

**Review the mappings:** Open the relevant Excel file to understand how fields in the Wastewater Contextual Data Specification map to the target standard.

**Implement transformations:** Use the provided transformation logic to adapt your data for compatibility with the target standard.

**Contribute updates:** If you notice inaccuracies or have suggestions for improvements, please open an issue or submit a pull request to this repository.

## Contribution Guidelines

Ensure mappings are clear and consistent with the target standard's documentation.
Use examples that accurately reflect the use case of the mapped fields.
Include detailed descriptions and transformation logic where applicable.