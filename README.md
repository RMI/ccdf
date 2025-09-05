# The Carbon Crediting Data Framework (CCDF)

An open-source framework created by RMI Carbon Markets Initiative for structuring data about the emissions and socio-environmental impact of carbon credits on the voluntary carbon market (VCM).

## Overview

The Carbon Crediting Data Framework (CCDF) is an RMI initiative to harmonize the types, definitions, and formats of data behind a carbon crediting project. It integrates data-related requirements and recommendations from more than 160 sources to put all the key questions, and guidance on how to answer them, into one place. By standardizing the structure of carbon crediting data, the CCDF empowers voluntary carbon market (VCM) stakeholders to better assess carbon credits transparently and efficiently.

The core data fields of the CCDF are methodology-agnostic and applicable to all carbon crediting projects. The CCDF structure can be expanded to include methodology-specific data - an effort being underetaken by the data utility [Centigrade](https://centigrade.earth/?utm_campaign=RMI-ccdf&utm_source=rmi-blog&utm_medium=blog-post). The CCDF is designed to be a dynamic, open-source tool - capable of evolving as needed to support data standardization, interoperability, and transparency across the VCM.

Our team intentionally included socio-environmental considerations throughout the CCDF, because non-carbon attributes such as community buy-in, ecosystem health, and equitable benefit sharing directly impact the success of carbon credits. Read more about how the SE components of the framework were constructed in section 3.2 of our [report](https://rmi.org/carbon-crediting-data-framework/)

While we encourage full adoption of the CCDF, we also recognize that the socio-environmental portion can be valuable in its own right. We have highlighted a set of our socio-environmental fields, complete with their own implementation spreadsheet, technical documentation, and JSON schema, so they can be readily applied to advance climate equity. These resources reflect the same content and in the same structure as the broader CCDF, however, are limited in scope to only include socio-environmental fields that are not directly tied toward emissions accounting.

## Getting Started

- Read the [CCDF Report](https://rmi.org/carbon-crediting-data-framework/)
- All CCDF and SECCDF files are located within the releases folder and then in the ccdf and seccdf folders respectively. 
- This repository uses a date structure to record which files are the most current. To access the most current files, reference the folder with the most recent date in either of the two folders – ccdf or seccdf. 
- Once in the correct folder determine which file(s) are right for you and your purposes.
- For implementation guidance and detailed descriptions of the data, download either the [ccdf spreadsheet](https://github.com/RMI/ccdf/blob/main/releases/ccdf/2025-07-17/ccdf.xlsx) or [seccdf spreadsheet](https://github.com/RMI/ccdf/blob/main/releases/seccdf/2025-09-05/seccdf.xlsx) and view either the [ccdf](https://github.com/RMI/ccdf/blob/main/releases/ccdf/2025-07-17/ccdf.md) or [seccdf](https://github.com/RMI/ccdf/blob/main/releases/seccdf/2025-09-05/seccdf.md) technical documentation.
- Meanwhile the [ccdf](https://github.com/RMI/ccdf/blob/main/releases/ccdf/2025-07-17/ccdf.json) and [seccdf](https://github.com/RMI/ccdf/blob/main/releases/seccdf/2025-09-05/seccdf.json) JSON schemas can be used to build programmatic tools based on the CCDF.

## Framework Structure

The CCDF describes four tiers of carbon credit data, based on where that data fits in to the crediting lifecycle. Each tier has its own tab in the spreadsheet.

| Tier | Description |
| --- | --- |
| **Tier 0: Pre-Registration Data** | This tier focuses on initial project design and governance information for the beginning of the project development process, with data fields related to project location, project approach, and projected socio-environmental impacts. This data helps assess whether a project meets basic certification requirements as these fields are methodology-agnostic. This data tends to be most useful for registries, early-stage project developers, and validators. |
| **Tier 1: Forecast Data** | This tier provides data fields for the specifics of the project design at the validation stage. These data fields are often methodology-dependent, as they cover carbon accounting, baseline, and project eligibility requirements. This forecasted data can be beneficial for validators, buyers, and investors as they begin to explore pre-purchase agreements. |
| **Tier 2: Actuals Data** | This tier provides data fields that showcase the actual quantifications of a project’s measured, monitored, and verified impact on greenhouse gas emission, socio-economic, and ecological metrics. These data fields are most useful to groups like verifiers, MRV providers, and data or quality evaluators aiming to assess projects' actual performance against their forecasted plans. |
| **Tier 3: Differentiators** | This tier captures data fields related to innovations, certifications, and design considerations that exceed current methodology or registry requirements. For example, project developers can use this tier to showcase their use of credit stacking with additional biodiversity or gender credits, or their use of novel digital MRV technology beyond methodology requirements. These data fields are most useful to buyers and quality assessors with specialized focuses or requirements. |
| **Raw Data Export** | This tab contains the raw data fields in the CCDF. It was compiled and digitized by our technical partner, Centigrade, and includes 570 unique data points related to carbon crediting projects and carbon credits. It provides transparency into the CCDF’s data structure and is a useful reference for anyone who wants to understand the full scope of the framework. |

The carbon data within a tier is organized into categories, sub-categories, and individual data fields:

- **Categories** group the data fields by broad theme, such as Disclosures or Socio-Economic Impacts.

- **Sub-categories** are specific topics within a theme, such as Location Compliance or Stakeholder Participation.

- **Fields** represent the individual pieces of data--or data "asks"--that an individual carbon crediting project can provide. Most granular information about a project’s design or impact is captured in the data fields.

## Framework contents

The CCDF describes 570 fields, grouped into the 4 tiers, 25 overarching categories, and 26 sub-categories.

The “Raw Data Export” tab in the Excel file matches the JSON and Markdown versions exactly, including the unique IDs used to track each field.

The other Excel tabs (Tiers 0-3) present the same information in a more readable format, but do not include unique IDs.


Each data field includes columns for seven pieces of metadata, and each column has a drop-down menu to better organize the information in the tier.

| Column | Description |
| --- | --- |
| **A: Label** | The standardized name for the data field. |
| **B: Description** | An explanation of the data field, which can also include examples that clarify the data field where there is some ambiguity. |
| **C: Type** | The data format (e.g. String, Array, Boolean). |
| **D: Options** | When applicable, the predefined choices for the data field based on the component and type. |
| **F: Technical Documentation Reference** | When applicable, the section(s) in the technical documentation that provides further explanation and/or a visual of the data field and its options. This includes fields that require a data table format that are best visualized in a non-Excel format. |


## How to Provide Feedback

We welcome feedback to improve the CCDF!

### Email

To share feedback privately or discuss open-ended topics please email us at [carbonmarkets@rmi.org](mailto:carbonmarkets@rmi.org). We aim to respond within 5 business days.

### Github Issues

To comment on a specific field in the CCDF, report bugs, or suggest new features, you can [open an Issue](https://github.com/RMI/ccdf/issues) in this repository.

If you’re submitting an issue on a specific field please include the Tier and the unique ID from the “Raw Data Export” tab.

We are grateful for your engagement - thank you for contributing!


### Schedule a Call

For in-depth conversations or complex inquiries, you’re invited to request a meeting with our team. Please email [carbonmarkets@rmi.org](mailto:carbonmarkets@rmi.org) with your name, organization, area of interest, and a few suggested times.

## Versioning

The CCDF is a living framework and will continue to evolve. Updates will be published periodically to reflect new insights and feedback. Refer to the CHANGELOG file in this repository for version history and update notes.

## License

This CCDF Implementation Spreadsheet is licensed under the [MIT License](LICENSE.md). If you use or adapt this work, please include the following citation: RMI Carbon Markets Initiative. _CCDF Implementation Spreadsheet v1.0. 2025. (https://rmi.org/download/46001/)_

## About Us

Rocky Mountain Institute (RMI) transforms global energy systems through market-driven solutions to secure a prosperous, resilient, clean energy future for all. RMI works with businesses, policymakers, and communities to scale renewable energy solutions, reduce energy waste, and boost access to affordable clean energy.

## Contact

For questions or collaboration inquiries: [carbonmarkets@rmi.org](mailto:carbonmarkets@rmi.org)

## Acknowledgements

The CCDF was a truly collaborative effort, developed by our Carbon Markets Initiative team: Apoorva Sahay, Jacqueline Krikorian, Sebastian Weeks, Alexis Wilkman, Caitlin Smith, and Bonnie Lei.

We’d also like to acknowledge Josh Henretig and John McGrath for their input and guidance.

Special thanks to our partners and collaborators, Centigrade, who informed and supported this work, including Thomas Griffiths, Maddi Erdall, Andreas Merkl, Peter Rosberg, Calais Cronin, and Julio Contreras.

We would like to thank Aijing Li and Valentina Guido, previous CMI team members, for their invaluable efforts researching, structuring, and iterating on the CCDF until it was a tangible and implementable framework.

We are grateful for all the experts who we interviewed for this report, including but not limited to Thiabault Sorret, Regan Smyth, Jamison Ervin, Di Zhang, Drea Burbank, Rebecca Iwerks, Griffith Flannery, Kelly Cain, Sandra Dalfiume, Kamal-Deem Kassim, Tyler Marcus, Jeannette Gurung, Larissa Dominguez Fuentes, Nadine Sangala, Theresa Keith, Paul Fleming, Simas Gradeckas, Nina Jeffs, Alicia ElMamouni, Michael Johnson, Mohammed Kadhi, Oyana Lusk, Zoe Balmforth, Gustave d’Andlau, Kevin Boston, Donna Lee, Diego Navarette, Erin Alvey, Therese Tepe, Fabiano Godoy, John Gunn, Elizabeth Wilmott, Julia Taylor, Sarah Heard, Rio Richardson, Ronan Ferguson, Sophie Gilbert, and Brady Seals.

This project has been made possible by a grant from the Ripple Impact Fund, an advised fund of the Silicon Valley Community Foundation. We are also grateful to the Cisco Foundation for their support for an open-source VCM ecosystem.
