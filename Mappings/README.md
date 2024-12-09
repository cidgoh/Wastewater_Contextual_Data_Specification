# Mappings to External repositories and other standards

This folder contains mappings from the **Wastewater Contextual Data Specification** to external data standards such as INSDC and others. Each mapping is documented in a separate Excel file.

## Contents

- NCBI_mapping.xlsx: Maps fields from the PHA4GE Wastewater Contextual Data Specification to existing packages including; NCBI Biosample, SRA and ENA.
- PHES_ODM_mapping.xlsx

## Excel File Structure

Each Excel file includes the following columns:

Source Field: Field name in the Wastewater Contextual Data Specification.
Target Field: Corresponding field name in the external standard.
Description: Brief explanation of the target field and its purpose.
Transformation Logic (optional): Details about how the source field maps to the target field, including any transformations applied.
Examples: Example values to demonstrate the mapping.


## How to Use

**Review the mappings:** Open the relevant Excel file to understand how fields in the Wastewater Contextual Data Specification map to the target standard.

**Implement transformations:** Use the provided transformation logic to adapt your data for compatibility with the target standard.

**Contribute updates:** If you notice inaccuracies or have suggestions for improvements, please open an issue or submit a pull request to this repository.

## Contribution Guidelines

Ensure mappings are clear and consistent with the target standard's documentation.
Use examples that accurately reflect the use case of the mapped fields.
Include detailed descriptions and transformation logic where applicable.