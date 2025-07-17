# provenance-projectDetails
## name
<a name="name"></a>Name used to refer to the carbon project being developed

| Id | 1 |
| :---- | :------------------------------- |
| **Label** | Project name |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | string |

## displayImage
<a name="displayImage"></a>

| Id | 1854 |
| :---- | :------------------------------- |
| **Label** | Display image |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | object |

## projectSummary
<a name="projectSummary"></a>

| Id | 3 |
| :---- | :------------------------------- |
| **Label** | General project description |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | string |

## projectMission
<a name="projectMission"></a>

| Id | 2 |
| :---- | :------------------------------- |
| **Label** | Brief project summary |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | string |

## projectActivities
<a name="projectActivities"></a>

| Id | 4 |
| :---- | :------------------------------- |
| **Label** | Description of activities |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | string |

## domain
<a name="domain"></a>Link to the project website

| Id | 5 |
| :---- | :------------------------------- |
| **Label** | Project website |
| **Tier** | -1 |
| **Section** | provenance-projectDetails |
| **type** | string |

## links
<a name="links"></a>Collection of relevant media links (e.g. articles, blog posts)

| Id | 6 |
| :---- | :------------------------------- |
| **Label** | Media links |
| **Tier** | -1 |
| **Section** | provenance-projectDetails |
| **type** | string |

## projectMedia
<a name="projectMedia"></a>

| Id | 7 |
| :---- | :------------------------------- |
| **Label** | Project photos or videos |
| **Tier** | -1 |
| **Section** | provenance-projectDetails |
| **type** | array |

## projectProponentName
<a name="projectProponentName"></a>

| Id | 2034 |
| :---- | :------------------------------- |
| **Label** | Project proponent name |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | null |

## projectStartYear
<a name="projectStartYear"></a>

| Id | 539 |
| :---- | :------------------------------- |
| **Label** | Project start year |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | number |

## projectEndYear
<a name="projectEndYear"></a>

| Id | 540 |
| :---- | :------------------------------- |
| **Label** | Project end year |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | number |

## termLength
<a name="termLength"></a>Projects must commit to a minimum project term of 40 years

| Id | 468 |
| :---- | :------------------------------- |
| **Label** | Project term commitment (in years) |
| **Tier** | -1 |
| **Section** | provenance-projectDetails |
| **type** | number |

## creditStart
<a name="creditStart"></a>The start of the crediting period, in which verified GHG emission reductions or removals from to a project activity can result in the issuance of carbon credits (i.e., the year that the project begins issuing credits)

| Id | 60 |
| :---- | :------------------------------- |
| **Label** | Crediting start year |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | number |

## creditEnd
<a name="creditEnd"></a>The end of the crediting period, in which verified GHG emission reductions or removals from to a project activity can result in the issuance of carbon credits (i.e., the year that the project stops issuing credits)

| Id | 61 |
| :---- | :------------------------------- |
| **Label** | Crediting end year |
| **Tier** | 0 |
| **Section** | provenance-projectDetails |
| **type** | number |

## projectTimeline
<a name="projectTimeline"></a>Additional details might include an implementation schedule, indicating key dates and milestones in the project's development as well as justification for that schedule

| Id | 463 |
| :---- | :------------------------------- |
| **Label** | Additional details on project timeline |
| **Tier** | -1 |
| **Section** | provenance-projectDetails |
| **type** | string |

# provenance-projectApproach
## projectScale
<a name="projectScale"></a>An indication of the estimated tonnes of CO2e to be sequestered or avoided over the life of the project

| Id | 8 |
| :---- | :------------------------------- |
| **Label** | Project scale |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Micro (fewer than 1,000 tCO2e) |
| | Small (1,000 - 10,000 tCO2e) |
| | Medium (10,000 - 100,000 tCO2e) |
| | Large (100,000+ tCO2e) |
| | Unknown |

## additionalCertificationUpload
<a name="additionalCertificationUpload"></a>

| Id | 1840 |
| :---- | :------------------------------- |
| **Label** | Additional certification supporting documents |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | array |

## primaryGhg
<a name="primaryGhg"></a>

| Id | 1640 |
| :---- | :------------------------------- |
| **Label** | Primary GHG mitigated |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Carbon dioxide |
| | Methane |
| | Nitrous oxide |
| | Other |

## classificationCategory
<a name="classificationCategory"></a>Ecological benefit category for the project

| Id | 9 |
| :---- | :------------------------------- |
| **Label** | Classification category |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | array |
| **Options** | Carbon avoidance |
| | Carbon reduction |
| | Carbon removal |
| | Undefined |

## classificationMethod
<a name="classificationMethod"></a>Category of the mitigation activity

| Id | 10 |
| :---- | :------------------------------- |
| **Label** | Classification method |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Natural - The activity claim uses natural methods (e.g. IFM) |
| | Technological - The activity claim uses technology (e.g. DAC) |
| | Both: Natural and Technological - The activity claim uses both natural and technology methods (e.g. BECCS) |

## projectType
<a name="projectType"></a>Emission reduction or sequestration pathway of project (eg. IFM, REDD++, Biochar, DAC etc.)

| Id | 11 |
| :---- | :------------------------------- |
| **Label** | Project type |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Agricultural Land Management (ALM) |
| | Afforestation Reforestation and Revegetation (ARR) |
| | Avoided Conversion of Grasslands and Shrublands (ACoGS) |
| | Biochar |
| | Bioenergy with Carbon Capture and Storage (BECCS) |
| | Biomass-based materials |
| | Blue Carbon |
| | Cookstoves |
| | Concrete utilization |
| | Direct Air Capture (DAC) |
| | Enhanced Rock Weathering (ERW) |
| | Improved Forest Management (IFM) |
| | Gas beneficial reuse |
| | Macroalgae |
| | Methane Gas Leak Detection and Repair |
| | Ocean Alkalinity Enhancement (OAE) |
| | Reduced Emissions from Deforestation and Degradation (REDD) |
| | Wetlands Restoration and Conservation (WRC) |
| | Other |
| | Biomass Carbon Removal & Storage (BiCRS) |

## projectOther
<a name="projectOther"></a>

| Id | 1220 |
| :---- | :------------------------------- |
| **Label** | Other project type |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |

## methodology
<a name="methodology"></a>Methodology or protocol used for credit generation

| Id | 12 |
| :---- | :------------------------------- |
| **Label** | Methodology |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | VM0045 Methodology for Improved Forest Management v1.0 |
| | VM0045 Methodology for Improved Forest Management v1.1 |
| | ACR Improved Forest Management (IFM) on Non-Federal U.S. Forestlands v2.0 |
| | Puro Standard Biochar Methodology Edition 2022 v3 |
| | Other |

## projectStatus
<a name="projectStatus"></a>Indicates the current stage of the project's development: (A) Under development: the project is in the early stages and has not yet completed validation; (B) Validated: The project has been reviewed and approved against the relevant methodology and standards but is not yet generating verified credits; (C) Verified: The project has undergone verification and is actively generating verified credits.

| Id | 944 |
| :---- | :------------------------------- |
| **Label** | Project status |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Under development |
| | Validated |
| | Verified |

## enhancementSelect
<a name="enhancementSelect"></a>

| Id | 1330 |
| :---- | :------------------------------- |
| **Label** | Additional certifications |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | array |
| **Options** | ICVCM CCP Label |
| | Verra ABACUS Label |
| | Verra CCB Label |
| | BeZero AAA Rating |
| | BeZero AA Rating |
| | BeZero A Rating |
| | BeZero BBB Rating |
| | BeZero BB Rating |
| | BeZero B Rating |
| | BeZero C Rating |
| | BeZero D Rating |
| | Sylvera AAA Rating |
| | Sylvera AA Rating |
| | Sylvera A Rating |
| | Sylvera BBB Rating |
| | Sylvera BB Rating |
| | Sylvera B Rating |
| | Sylvera C Rating |
| | Sylvera D Rating |
| | Verra SD VISta Label |
| | Calyx Global AAA |
| | Calyx Global AA |
| | Calyx Global A |
| | Calyx Global BBB |
| | Calyx Global BB |
| | Calyx Global B |
| | Calyx Global C |
| | Calyx Global D |
| | None |
| | Keeling Curve Prize |
| | Earthshot Prize |
| | St Andrews Prize |
| | Equator Prize |
| | XPRIZE Finalist |
| | XPRIZE Top 100 |
| | XPRIZE Runner Up |
| | Renoster - Excellent |
| | Renoster - Good |
| | Renoster - Poor |
| | Renoster - Neutral |
| | Renoster - Suspect |

## creditIssuer
<a name="creditIssuer"></a>The body responsible for issuing the credits

| Id | 13 |
| :---- | :------------------------------- |
| **Label** | Credit issuer |
| **Tier** | 0 |
| **Section** | provenance-projectApproach |
| **type** | string |
| **Options** | Verra |
| | American Carbon Registry |
| | Gold Standard |
| | Climate Action Reserve |
| | Puro |
| | Other |
| | Self issuing |
| | Not applicable |
| | Isometric |

## creditIssuerOther
<a name="creditIssuerOther"></a>

| Id | 14 |
| :---- | :------------------------------- |
| **Label** | Other credit issuer |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |

## standardVersion
<a name="standardVersion"></a>Carbon crediting programs (e.g., Verra, ACR, CAR, Puro Earth) publish general rules and documentation that projects must adhere to in addition to a given methodology. These programs or standards are updated periodically (e.g., ACR Standard Version 8.0, Puro General Rules Version 4.0, etc.)

| Id | 466 |
| :---- | :------------------------------- |
| **Label** | Registry standard version used |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |

## projectRegistryLink
<a name="projectRegistryLink"></a>If relevant, the link to the project's registry listing page

| Id | 769 |
| :---- | :------------------------------- |
| **Label** | Project registry link |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |

## projectRegistryID
<a name="projectRegistryID"></a>If relevant, the project's unique ID in the project's respective registry

| Id | 779 |
| :---- | :------------------------------- |
| **Label** | Project registry ID |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |

## approachComments
<a name="approachComments"></a>If relevant, any additional or missing information about the project's fundamental approach

| Id | 15 |
| :---- | :------------------------------- |
| **Label** | Additional comments on project approach |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | string |

## pdd
<a name="pdd"></a>If relevant, the project plan document (e.g., GHG plan, PDD)

| Id | 586 |
| :---- | :------------------------------- |
| **Label** | Project plan document |
| **Tier** | -1 |
| **Section** | provenance-projectApproach |
| **type** | array |

# provenance-locationDetails
## countries
<a name="countries"></a>Country or countries where the project activities take place

| Id | 16 |
| :---- | :------------------------------- |
| **Label** | Country or countries of project activity |
| **Tier** | 0 |
| **Section** | provenance-locationDetails |
| **type** | string |

## conflictAreas
<a name="conflictAreas"></a>Conflict-affected areas as defined by the World Bank here: https://thedocs.worldbank.org/en/doc/b3c737c4687db176ec98f5c434d0de91-0090082024/original/FCSListFY25.pdf

| Id | 17 |
| :---- | :------------------------------- |
| **Label** | Project takes place in conflict-affected or disputed areas |
| **Tier** | 0 |
| **Section** | provenance-locationDetails |
| **type** | boolean |

## conflictMoreInfo
<a name="conflictMoreInfo"></a>Additional context on the conflict-affected area(s) and the additional measures taken to implement the project

| Id | 563 |
| :---- | :------------------------------- |
| **Label** | Additional information about the conflict-affected area(s) |
| **Tier** | -1 |
| **Section** | provenance-locationDetails |
| **type** | string |

## geographicLocation
<a name="geographicLocation"></a>Project boundary files for project locations indicated

| Id | 18 |
| :---- | :------------------------------- |
| **Label** | Project boundary file |
| **Tier** | -1 |
| **Section** | provenance-locationDetails |
| **type** | array |

## locationComments
<a name="locationComments"></a>Additional comments and context on project location including relevant coordinates where project activities take place

| Id | 19 |
| :---- | :------------------------------- |
| **Label** | Location details |
| **Tier** | -1 |
| **Section** | provenance-locationDetails |
| **type** | string |

# provenance-organizationOverview
## organizationClassification
<a name="organizationClassification"></a>

| Id | 789 |
| :---- | :------------------------------- |
| **Label** | Organization classification |
| **Tier** | 0 |
| **Section** | provenance-organizationOverview |
| **type** | string |
| **Options** | 501(c)(3) |
| | B Corporation (B-Corp) |
| | Cooperative (Co-op) |
| | Foundation |
| | Governmental Organization |
| | Non-Governmental Organization (NGO) |
| | Non-Profit Organization (NPO) |
| | Partnership |
| | Private Company |
| | Public Company |
| | Social Enterprise |
| | Sole Proprietorship |
| | Trust |
| | Other |

## organizationClassificationOther
<a name="organizationClassificationOther"></a>

| Id | 791 |
| :---- | :------------------------------- |
| **Label** | Organization classification |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## ownershipStructure
<a name="ownershipStructure"></a>Major shareholders and/or owners of the organization

| Id | 787 |
| :---- | :------------------------------- |
| **Label** | Ownership structure |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## governanceStructure
<a name="governanceStructure"></a>How the organization is governed; all stakeholders involved and systems that guide the organization's decision-making and operations

| Id | 788 |
| :---- | :------------------------------- |
| **Label** | Governance structure |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationStructureUpload
<a name="organizationStructureUpload"></a>

| Id | 790 |
| :---- | :------------------------------- |
| **Label** | Ownership and governance structure documentation |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | array |

## organizationHeadquarters
<a name="organizationHeadquarters"></a>Where the main office of the organization is located

| Id | 1647 |
| :---- | :------------------------------- |
| **Label** | Headquarters city and state |
| **Tier** | 0 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationHeadquartersCountry
<a name="organizationHeadquartersCountry"></a>

| Id | 1637 |
| :---- | :------------------------------- |
| **Label** | Headquarters country |
| **Tier** | 0 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationIncorporation
<a name="organizationIncorporation"></a>Where the organization is incorporated

| Id | 796 |
| :---- | :------------------------------- |
| **Label** | Incorporation city and state |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationIncorporationCountry
<a name="organizationIncorporationCountry"></a>

| Id | 795 |
| :---- | :------------------------------- |
| **Label** | Incorporation country |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## projectEmployees
<a name="projectEmployees"></a>Full-time and part-time employees and contractors who directly work on the project 

| Id | 792 |
| :---- | :------------------------------- |
| **Label** | Number of employees staffed on project |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | number |

## orgMission
<a name="orgMission"></a>

| Id | 1857 |
| :---- | :------------------------------- |
| **Label** | Organization mission |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationFoundingYear
<a name="organizationFoundingYear"></a>

| Id | 786 |
| :---- | :------------------------------- |
| **Label** | Organization founding year |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | number |

## organizationExperiencePathway
<a name="organizationExperiencePathway"></a>The number of projects developed by the organization within the specific pathway

| Id | 797 |
| :---- | :------------------------------- |
| **Label** | Number of projects within pathway |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | number |

## organizationExperienceProjects
<a name="organizationExperienceProjects"></a>The total number of projects developed by the organization

| Id | 798 |
| :---- | :------------------------------- |
| **Label** | Number of total projects developed |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | number |

## totalProjectsIssued
<a name="totalProjectsIssued"></a>

| Id | 1222 |
| :---- | :------------------------------- |
| **Label** | Number of projects with issued credits |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationExperienceDetails
<a name="organizationExperienceDetails"></a>

| Id | 799 |
| :---- | :------------------------------- |
| **Label** | Organization history and experience details |
| **Tier** | -1 |
| **Section** | provenance-organizationOverview |
| **type** | string |

## organizationOperationYears
<a name="organizationOperationYears"></a>The number of years the organization has been actively operating projects within this specific pathway or mitigation activity

| Id | 794 |
| :---- | :------------------------------- |
| **Label** | Years developing carbon projects |
| **Tier** | 0 |
| **Section** | provenance-organizationOverview |
| **type** | number |

# provenance-disclosures
## laborChildren
<a name="laborChildren"></a>

| Id | 25 |
| :---- | :------------------------------- |
| **Label** | Project will not employ persons under the age of 15 |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## laborChildDevelopment
<a name="laborChildDevelopment"></a>Indicates compliance with the ILO Convention 138 Minimum Age Convention 1973 and/or national labor laws related to minimum age

| Id | 26 |
| :---- | :------------------------------- |
| **Label** | Project complies with age-related legal frameworks |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |
| **Options** | ILO Convention 138 Minimum Age Convention 1973 |
| | National laws |

## laborWorkersRights
<a name="laborWorkersRights"></a>The rights of workers as defined by the ILO Declaration of Fundamental Principles and Rights at Work

| Id | 27 |
| :---- | :------------------------------- |
| **Label** | Project intends to protect and uphold the rights of workers |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## laborUpload
<a name="laborUpload"></a>

| Id | 28 |
| :---- | :------------------------------- |
| **Label** | International standards-compliant code of conduct or other labor rights documentation |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | array |

## laborComments
<a name="laborComments"></a>

| Id | 29 |
| :---- | :------------------------------- |
| **Label** | Additional comments on labor rights and protection of workers |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## legalComplianceTable
<a name="legalComplianceTable"></a>

| Id | 1336 |
| :---- | :------------------------------- |
| **Label** | Legal compliance |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | object |

### Table structure
| Law, regulation, or legislation | Compliance status | Explanation | Compliance verification | 
| :---- | :---- | :---- | :---- |
| | | | |

## nationalLawsCompliance
<a name="nationalLawsCompliance"></a>Attestation of compliance with the applicable national laws of the project country

| Id | 20 |
| :---- | :------------------------------- |
| **Label** | Compliance with all applicable national laws |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | string |

## nationalLawsMethod
<a name="nationalLawsMethod"></a>

| Id | 22 |
| :---- | :------------------------------- |
| **Label** | Method of compliance proof |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |
| **Options** | Government verified |
| | Third-party verified |
| | Not verified |

## communityFrameworks
<a name="communityFrameworks"></a>If relevant, description of the measures taken to adhere to national or international frameworks supporting the rights of Indigenous, tribal and local communities (including the UN Declaration on the Rights of Indigenous Peoples)

| Id | 677 |
| :---- | :------------------------------- |
| **Label** | Measures taken to comply with frameworks governing the rights of Indigenous, tribal, and local communities |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## culturalSite
<a name="culturalSite"></a>Disclosure of proximity to dedicated areas of archaeological or cultural significance which are recognized by municipalities, counties, state, national and/or international registries

| Id | 1467 |
| :---- | :------------------------------- |
| **Label** | The project site includes or borders archaeological sites or districts listed in national or international registries of historical or cultural significance |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## culturalSiteDesignation
<a name="culturalSiteDesignation"></a>Indication of the type of historical, cultural, or archeological distinction granted to the site

| Id | 1470 |
| :---- | :------------------------------- |
| **Label** | Purpose of the site's designation |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | array |
| **Options** | History |
| | Architecture |
| | Archeology |
| | Engineering |
| | Cultural |
| | Other |

## archaeologicalActivity
<a name="archaeologicalActivity"></a>Areas designated can be at the local, regional, state, national, or international level

| Id | 1469 |
| :---- | :------------------------------- |
| **Label** | Project site contains, or is contiguous with, an area designated as sensitive for archaeological activity |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## culturalSiteRegistry
<a name="culturalSiteRegistry"></a>Examples include UNESCO World Heritage registry and/or national equivalents

| Id | 1468 |
| :---- | :------------------------------- |
| **Label** | Registry recognizing the site |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## parisNdcApplicability
<a name="parisNdcApplicability"></a>

| Id | 1471 |
| :---- | :------------------------------- |
| **Label** | The project is counted towards the country's Nationally Determined Contributions (NDCs) |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |
| **Options** | Yes, counted towards the country's NDC where project occurs  |
| | Yes, counted towards the funding country's NDC |
| | No, not counted towards a national-level NDC |
| | I don't know |

## parisCompliance
<a name="parisCompliance"></a>

| Id | 34 |
| :---- | :------------------------------- |
| **Label** | The country where this project occurs is a party to the Paris Agreement  |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## parisLetter
<a name="parisLetter"></a>Link to the letter of approval for the corresponding adjustment if needed

| Id | 35 |
| :---- | :------------------------------- |
| **Label** | Evidence of project's inclusion in the Nationally Determined Contribution (NDC) and/or Paris Agreement |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | array |

## carbonRightsDetails
<a name="carbonRightsDetails"></a>Overview of the project's right to claim the carbon credits generated by the project activity

| Id | 1858 |
| :---- | :------------------------------- |
| **Label** | Carbon rights overview |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## carbonAuthorization
<a name="carbonAuthorization"></a>Authorization of carbon use indicates that the project activity is legally allowed to be executed

| Id | 31 |
| :---- | :------------------------------- |
| **Label** | Project is authorized for carbon use |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |
| **Options** | Yes, I have a government concession |
| | Yes, I have authorization from the owner (private) |
| | I own the land |
| | No |
| | Yes, I have full rights over the carbon |

## carbonCreditOwnership
<a name="carbonCreditOwnership"></a>Documentation or supporting evidence of carbon credit rights/ownership

| Id | 613 |
| :---- | :------------------------------- |
| **Label** | Carbon credit ownership documentation |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | array |

## carbonConservationContract
<a name="carbonConservationContract"></a>Relevant for public land projects

| Id | 32 |
| :---- | :------------------------------- |
| **Label** | Concession contract is at least the same length as the crediting period |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## carbonUpload
<a name="carbonUpload"></a>

| Id | 33 |
| :---- | :------------------------------- |
| **Label** | Land or facility ownership documentation |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | array |

## carbonIssuing
<a name="carbonIssuing"></a>

| Id | 456 |
| :---- | :------------------------------- |
| **Label** | Project is receiving or seeking credit for reductions and removals under another GHG program |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## carbonIssuingYes
<a name="carbonIssuingYes"></a>

| Id | 457 |
| :---- | :------------------------------- |
| **Label** | Evidence of no double issuance |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## carbonRegistration
<a name="carbonRegistration"></a>

| Id | 458 |
| :---- | :------------------------------- |
| **Label** | Project has registered under other GHG programs |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## carbonRegistrationYes
<a name="carbonRegistrationYes"></a>

| Id | 459 |
| :---- | :------------------------------- |
| **Label** | Registration number and date of project inactivity under other GHG program |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## carbonRejection
<a name="carbonRejection"></a>

| Id | 460 |
| :---- | :------------------------------- |
| **Label** | Project has been rejected by another GHG program |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | boolean |

## carbonRejectionYes
<a name="carbonRejectionYes"></a>

| Id | 461 |
| :---- | :------------------------------- |
| **Label** | Program name(s), reason(s) and date of rejection |
| **Tier** | -1 |
| **Section** | provenance-disclosures |
| **type** | string |

## organizationNameAndRole
<a name="organizationNameAndRole"></a>Entities could include (but are not limited to) GIS advisory; feasibility study; technical document service; administrative service; biodiversity advisory, political advocacy; project consultants; financial institutions 

| Id | 2047 |
| :---- | :------------------------------- |
| **Label** | Organization name and role |
| **Tier** | 0 |
| **Section** | provenance-disclosures |
| **type** | string |

# provenance-socioeconomicDueDiligence
## economicDisplacementExplain
<a name="economicDisplacementExplain"></a>Possible risks or impacts to the project community that would create obstacles to the ability to find, retain, or secure economic opportunity in the project area

| Id | 588 |
| :---- | :------------------------------- |
| **Label** | Expected economic displacement effects |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## physicalDisplacementExplain
<a name="physicalDisplacementExplain"></a>Relocation, loss of residential land, or loss of shelter as a result of involuntary acquisition of land and/or involuntary restrictions on land use or on access

| Id | 587 |
| :---- | :------------------------------- |
| **Label** | Expected physical displacement effects |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## economicDisplacementPlan
<a name="economicDisplacementPlan"></a>Project plan to mitigate possible obstacles to economic opportunity for the project community due to project activities

| Id | 37 |
| :---- | :------------------------------- |
| **Label** | Mitigation plan in place to address economic displacement effects |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## physicalMitigation
<a name="physicalMitigation"></a>Project plan to mitigate possible relocation, loss of residential land, or loss of shelter due to project activities

| Id | 593 |
| :---- | :------------------------------- |
| **Label** | Mitigation plan in place to address physical displacement effects |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## physicalMitigationDetails
<a name="physicalMitigationDetails"></a>Mitigation may include, but is not limited to, avoidance, minimization, mitigation, and/or compensation activities

| Id | 594 |
| :---- | :------------------------------- |
| **Label** | Details of mitigation plan to address physical displacement |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## economicDisplacementPlanEvidence
<a name="economicDisplacementPlanEvidence"></a>Supporting evidence of the economic displacement mitigation plan

| Id | 30 |
| :---- | :------------------------------- |
| **Label** | Documentation of mitigation plan for economic displacement |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## economicDisplacementDetails
<a name="economicDisplacementDetails"></a>Mitigation may include, but is not limited to, avoidance, minimization, mitigation, and/or compensation activities

| Id | 589 |
| :---- | :------------------------------- |
| **Label** | Overview of activities included in the mitigation plan |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## physicalDisplacementSupportingEvidence
<a name="physicalDisplacementSupportingEvidence"></a>Supporting evidence of the physical displacement mitigation plan

| Id | 595 |
| :---- | :------------------------------- |
| **Label** | Documentation of mitigation plan for physical displacement |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## communityDescription
<a name="communityDescription"></a>The communities and other stakeholders impacted (or potentially impacted) by project activities

| Id | 39 |
| :---- | :------------------------------- |
| **Label** | Communities and other stakeholders impacted or potentially impacted by the project |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## stakeholderIdentificationProcess
<a name="stakeholderIdentificationProcess"></a>Overview of the method utilized to identify stakeholders that may be affected by project activities

| Id | 929 |
| :---- | :------------------------------- |
| **Label** | Stakeholder identification process |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## communityImpactDetails
<a name="communityImpactDetails"></a>Overview of the potential impacts the project could incur on the various identified stakeholders

| Id | 40 |
| :---- | :------------------------------- |
| **Label** | Details on expected impacts to communities and stakeholders |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## expectedImpactsDocument
<a name="expectedImpactsDocument"></a>Documentation, evidence, or recommendation records which substantiate expected stakeholder impacts

| Id | 668 |
| :---- | :------------------------------- |
| **Label** | Expected stakeholder impacts supporting documents |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## stakeholderConsultationActual
<a name="stakeholderConsultationActual"></a>This plan describes how the project will engage, inform, and gather feedback from people or groups affected by or interested in its success

| Id | 930 |
| :---- | :------------------------------- |
| **Label** | Project has developed a stakeholder consultation plan |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## communityConsultationNegativeDetails
<a name="communityConsultationNegativeDetails"></a>

| Id | 42 |
| :---- | :------------------------------- |
| **Label** | Justification for the absence of a stakeholder consultation plan |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## consultationDetails
<a name="consultationDetails"></a>This can include frequency of meetings, format types (e.g. 1-1 interview, roundtable discussions, focus groups), and how these discussions will be recorded and addressed

| Id | 170 |
| :---- | :------------------------------- |
| **Label** | Overview of stakeholder consultation plan |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## consultationDocuments
<a name="consultationDocuments"></a>Documents could include a community consultation process overview, consultation timeline, registry-specific documents or questionnaires, etc. 

| Id | 669 |
| :---- | :------------------------------- |
| **Label** | Stakeholder consultation plan supporting documents |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## healthImpactDisclosure
<a name="healthImpactDisclosure"></a>Outcome of expected community health impacts due to project activities (e.g., changes in potable water quality, pollutant impact, hazardous wastes)

| Id | 2044 |
| :---- | :------------------------------- |
| **Label** | Expected health impact disclosure |
| **Tier** | 0 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | null |

## healthImpactCommunication
<a name="healthImpactCommunication"></a>In the case a project has expected health impacts to the community, these risks will be communicated to stakeholders during the consultation and engagement process

| Id | 2043 |
| :---- | :------------------------------- |
| **Label** | Potential health impacts disclosure will be communicated during consultations |
| **Tier** | 0 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | null |

## socialGroupRiskPlanUpload
<a name="socialGroupRiskPlanUpload"></a>Documents showcasing risk mitigation plans

| Id | 1474 |
| :---- | :------------------------------- |
| **Label** | Risk mitigation plan for identified social groups documentation  |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## socialGroup
<a name="socialGroup"></a>The specific groups that carry a particular emphasis in the consultation or engagement plans

| Id | 45 |
| :---- | :------------------------------- |
| **Label** | Groups expected to be the focus of outreach and consultations  |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |
| **Options** | Women |
| | Children |
| | Elderly communities |
| | Disabled communities |
| | Racial/Ethnic Minorities |
| | LGBTQIA+ communities |
| | Migrant Workers |
| | Indigenous and/or Tribal Community Members |
| | Other |

## socialGroupConsult
<a name="socialGroupConsult"></a>Indicates whether the project is expected to consult specific groups, such as women, people with disabilities, and/or other minority groups (among others) who may be disproportionately affected by the project compared to other groups

| Id | 46 |
| :---- | :------------------------------- |
| **Label** | Project plans to consult and engage with specific vulnerable social groups |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## socialGroupConsultDetails
<a name="socialGroupConsultDetails"></a>Engagement plans or processes with the identified specific vulnerable communities (e.g., women-only consultations or focus groups)

| Id | 50 |
| :---- | :------------------------------- |
| **Label** | Overview of consultation/engagement plans with identified social groups |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## socialGroupRiskDetails
<a name="socialGroupRiskDetails"></a>Description of any possible risks and/or negative impacts the project may have on the identified social groups

| Id | 47 |
| :---- | :------------------------------- |
| **Label** | Potential risks to the identified social groups |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## socialGroupPositiveImpacts
<a name="socialGroupPositiveImpacts"></a>Expected benefits for the identified social groups (e.g., increased leisure time for a targeted demographic due to the project's implementation)

| Id | 177 |
| :---- | :------------------------------- |
| **Label** | Expected positive impacts of the project activity on the identified social groups |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## genderActionPlanResources
<a name="genderActionPlanResources"></a>Identification of frameworks, resources, or other tools used to inform the project's gender action plan

| Id | 1473 |
| :---- | :------------------------------- |
| **Label** | Resources and tools used for gender action plan development |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |
| **Options** | UNFCCC |
| | Asian Development Bank |
| | Global Environmental Facility |
| | W+ Standard |
| | Other |

## genderActionPlan
<a name="genderActionPlan"></a>Action plan identifying gender inequalities and detailing how the project will address them

| Id | 1472 |
| :---- | :------------------------------- |
| **Label** | Gender action plan |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## womenEmpowerment
<a name="womenEmpowerment"></a>

| Id | 51 |
| :---- | :------------------------------- |
| **Label** | Project monitors gender equality/empowerment impacts |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## socialGroupMonitoringPlan
<a name="socialGroupMonitoringPlan"></a>Overview of the project's approach to monitoring and/or addressing gendered impacts (e.g., safeguarding against negative impacts or enabling positive impacts)

| Id | 198 |
| :---- | :------------------------------- |
| **Label** | Description of gender action plan and resources utilized |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## exploitation
<a name="exploitation"></a>Indication of whether the project addresses exploitation, harassment of women and/or minority groups in the community

| Id | 175 |
| :---- | :------------------------------- |
| **Label** | Project addresses harrassment or exploitation of women within the household or other project areas |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## socialGroupGenderConsultations
<a name="socialGroupGenderConsultations"></a>Examples include data collection methods comprised of women-only respondents

| Id | 199 |
| :---- | :------------------------------- |
| **Label** | Project plans to conduct gender sensitive consultations |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## womenRights
<a name="womenRights"></a>For example, if women are formally and fairly entitled to project-related land, water, or other types of resources

| Id | 49 |
| :---- | :------------------------------- |
| **Label** | Women are formally and fairly entitled to project-related resources |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## womenRightsDescription
<a name="womenRightsDescription"></a>Description of how women are formally and fairly entitled to project related land water and or other types of resources

| Id | 2035 |
| :---- | :------------------------------- |
| **Label** | Overview of gendered resource entitlement |
| **Tier** | 0 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## communityExists
<a name="communityExists"></a>Project activities either take place in, border, or affect resources that impact nearby recognized or known indigenous territories

| Id | 38 |
| :---- | :------------------------------- |
| **Label** | Project activities take place in close proximity to tribal or Indigenous lands or otherwise affect Indigenous peoples |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## communityConsultation
<a name="communityConsultation"></a>Following principles of Free, Prior, and Informed Consent as indicated in international humanitarian law, such as the UN Declaration on the Rights to Indigenous People

| Id | 41 |
| :---- | :------------------------------- |
| **Label** | Indigenous people and/or local communities, including minority groups within, have been informed and agreed to project activities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## landRightsRec
<a name="landRightsRec"></a>In line with Free, Prior, and Informed Consent principles, the project and the indigenous, tribal, and/or local community have agreed on clear contractual terms governing project activities and operations

| Id | 590 |
| :---- | :------------------------------- |
| **Label** | Project contains explicit contracts with Indigenous, tribal, and local communities before the project begins |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## carbonContractLength
<a name="carbonContractLength"></a>Indication of contract length or agreed upon time before reassessment of contract terms with relevant indigenous, tribal, or local communities

| Id | 610 |
| :---- | :------------------------------- |
| **Label** | Length of project contract with Indigenous, tribal, and local communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | number |

## contractPublic
<a name="contractPublic"></a>Openly available documentation of contracts

| Id | 611 |
| :---- | :------------------------------- |
| **Label** | Publicly available information on the contracts with communities or governments |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## contractPenalty
<a name="contractPenalty"></a>Description of any contract clauses that hold the counterparty responsible for compensation (e.g., financial payments, infrastructure repairs) in case of breach

| Id | 612 |
| :---- | :------------------------------- |
| **Label** | Penalty clauses on the contracts for Indigenous, tribal, and local communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## specialMeasureDetails
<a name="specialMeasureDetails"></a>Details on how data was integrated into free, prior, and informed consent

| Id | 189 |
| :---- | :------------------------------- |
| **Label** | Data integration into free, prior, and informed consent |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## grievance
<a name="grievance"></a>Indicates whether the project will set up a formal process or channel (e.g., email, written submissions, listening sessions) for individuals, groups, or communities to raise complaints or concerns about project impacts, with structured procedures for recording grievances and responses

| Id | 603 |
| :---- | :------------------------------- |
| **Label** | Project will establish a grievance mechanism to enable stakeholders to report and address concerns |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## grievanceReport
<a name="grievanceReport"></a>Indicates whether the public and project community have access to uncensored records of submitted grievances

| Id | 606 |
| :---- | :------------------------------- |
| **Label** | Grievances and other reported issues are made public |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## grievanceDate
<a name="grievanceDate"></a>Date when the grievance mechanism first became (or will become) operational (e.g., project start date)

| Id | 604 |
| :---- | :------------------------------- |
| **Label** | Date by which grievance mechanism was/will be open to communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## grievanceDetails
<a name="grievanceDetails"></a>Description of the grievance mechanism, including how it works, who can access it, and the general measures for responding to grievances (e.g., monthly community listening sessions with follow-up, a monitored email inbox with a ticketing system, or other methods suited to the local context)

| Id | 169 |
| :---- | :------------------------------- |
| **Label** | Overview of the grievance mechanism available for stakeholders |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## grievanceSupport
<a name="grievanceSupport"></a>Uploads may include details on the grievance mechanism's structure, reported issues addressed, and availability date

| Id | 608 |
| :---- | :------------------------------- |
| **Label** | Grievance mechanism supporting documents |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## benefitSharing
<a name="benefitSharing"></a>Benefit sharing with the local community (e.g. subsidization of products, revenue sharing etc.)

| Id | 44 |
| :---- | :------------------------------- |
| **Label** | Project will implement a benefit sharing model |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## benefitSharingNoExplanation
<a name="benefitSharingNoExplanation"></a>If relevant, explanation of how benefits related to the carbon credit project are established and assigned to different stakeholders

| Id | 1636 |
| :---- | :------------------------------- |
| **Label** | Rationale for no benefit sharing |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## benefitSharingExplanation
<a name="benefitSharingExplanation"></a>If relevant, explanation of how benefits related to the carbon credit project are established and assigned to different stakeholders

| Id | 667 |
| :---- | :------------------------------- |
| **Label** | Benefit sharing model explanation |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | string |

## benefitUpload
<a name="benefitUpload"></a>Supporting evidence of the benefit sharing agreement

| Id | 591 |
| :---- | :------------------------------- |
| **Label** | Benefit sharing agreement supporting documentation |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |

## benefitSharingCommunities
<a name="benefitSharingCommunities"></a>Indicates whether a benefit-sharing agreement exists specifically with Indigenous communities near the project area

| Id | 943 |
| :---- | :------------------------------- |
| **Label** | Benefit sharing agreement in place with Indigenous communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | boolean |

## benefitSharingType
<a name="benefitSharingType"></a>Indicates the type of benefit-sharing agreement established

| Id | 190 |
| :---- | :------------------------------- |
| **Label** | Benefit sharing type offered to Indigenous, tribal, and/or local communtities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | array |
| **Options** | Monetary incentives - Community funds |
| | Monetrary incentives - Tax abatements |
| | In-kind benefits or public goods - Local infrastructure improvements |
| | Monetary incentives - Cash payments |
| | In-kind benefits or public goods - Local employment |
| | In-kind benefits - gifts or products |

## iplcOwnershipPercent
<a name="iplcOwnershipPercent"></a>Percentage of ownership held by Indigenous Peoples and Local Communities (IPLC) in the company or organization developing the project

| Id | 194 |
| :---- | :------------------------------- |
| **Label** | Current or projected % of company owned by Indigenous, tribal, and local communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | number |

## benefitSharingPercent
<a name="benefitSharingPercent"></a>Percentage of the carbon credit sale price projected to go directly to Indigenous, tribal, or local communities involved in the project

| Id | 192 |
| :---- | :------------------------------- |
| **Label** | Projected % sale price going to Indigenous, tribal, and local communities |
| **Tier** | -1 |
| **Section** | provenance-socioeconomicDueDiligence |
| **type** | number |

# provenance-ecologicalDueDiligence
## airMonitoringPlan
<a name="airMonitoringPlan"></a>Air pollution monitoring plans often include pollutants to be monitored, frequency of monitoring, and outlined data collection/mangement practices

| Id | 52 |
| :---- | :------------------------------- |
| **Label** | Project has or will implement an air pollution monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## airMonitoringPlanEvidence
<a name="airMonitoringPlanEvidence"></a>Evidence of the project plans to monitor air pollution

| Id | 1475 |
| :---- | :------------------------------- |
| **Label** | Air pollution monitoring plan documentation |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |

## baselineComparisonPlan
<a name="baselineComparisonPlan"></a>If the project conducts a baseline air quality study (before project start or using a control site), monitoring results will be compared against these baseline levels

| Id | 1476 |
| :---- | :------------------------------- |
| **Label** | Project plans to measure pollutants against baseline air quality |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## airExpectedImpacts
<a name="airExpectedImpacts"></a>Description of expected air quality impacts, such as improved indoor air quality for households using the project technology

| Id | 1668 |
| :---- | :------------------------------- |
| **Label** | Summary of expected air quality impacts of the project activity |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## airMonitoringDomains
<a name="airMonitoringDomains"></a>Project plans may focus on indoor air quality, ambient air quality, or both

| Id | 916 |
| :---- | :------------------------------- |
| **Label** | Domains included in the air pollution monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Indoor air pollution |
| | Ambient air pollution |

## airMonitoringDescription
<a name="airMonitoringDescription"></a>Details of the air pollution monitoring plan the project intends to implement

| Id | 917 |
| :---- | :------------------------------- |
| **Label** | Description of air pollution monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## airMonitoringBaseline
<a name="airMonitoringBaseline"></a>Air monitoring can include continuous measurement of criteria air pollutants or tracking of the air quality index in a target region, for example

| Id | 54 |
| :---- | :------------------------------- |
| **Label** | Pollutants monitored in baseline air quality |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Ozone |
| | VOCs |
| | NOx |
| | PM2.5 |
| | PM10 |
| | Carbon Monoxide (CO) |
| | Polycyclic aromatic hydrocarbons (PAHs) |
| | Other |

## airBaselineDescription
<a name="airBaselineDescription"></a>Information on baseline or control air quality in the project area before project activities (indoor, ambient, or both)

| Id | 919 |
| :---- | :------------------------------- |
| **Label** | Description of baseline air quality |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## airBaselineEvidence
<a name="airBaselineEvidence"></a>Documents related to baseline air pollution, including air quality measurements or calculations. Baseline indoor air pollution data may come from field or lab tests, technology operation models, or expert opinions, while ambient pollution data may use regional datasets

| Id | 1002 |
| :---- | :------------------------------- |
| **Label** | Baseline air quality documentation |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |

## baselineWaterEvidence
<a name="baselineWaterEvidence"></a>Evidence or documentation of baseline water analysis

| Id | 1485 |
| :---- | :------------------------------- |
| **Label** | Baseline water resource supporting documents |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |

## waterMonitoringFrequency
<a name="waterMonitoringFrequency"></a>Details on how frequently the project developer will monitor water resources affected by the project activity

| Id | 940 |
| :---- | :------------------------------- |
| **Label** | Monitoring frequency of water resources |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## waterMonitoringPlan
<a name="waterMonitoringPlan"></a>Water monitoring plans typically specify which pollutants and water levels or availability will be monitored, along with procedures for data collection and management

| Id | 937 |
| :---- | :------------------------------- |
| **Label** | Project plans to monitor water resources |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## waterStewardship
<a name="waterStewardship"></a>Classification of water-related activities undertaken as part of the project activity (e.g., water demand reduction, water efficiency measures, land restoration, etc.)

| Id | 209 |
| :---- | :------------------------------- |
| **Label** | Water-related activity classification within the project activity |
| **Tier** | 3 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Land conservation and restoration - Land conservation (protection and preservation) |
| | Land conservation and restoration - Land cover restoration |
| | Water supply reliability - Agricultural water demand reduction measures |
| | Water supply reliability - Operational efficiency measures |
| | Water supply reliability - Leak repair |
| | Water supply reliability - Consumer use efficiency measures |
| | Water supply reliability - Water reuse |
| | Water supply reliability - New water supply for water irrigation |
| | Water supply reliability - Rainwater harvesting |
| | Water access - Access to drinking water supply |
| | Water Quality - Agricultural best management practices |
| | Water Quality - Stormwater management |
| | Water Quality - Constructed wetland treatment systems |
| | Water Quality - Wastewater treatment plants |
| | Aquatic habitat restoration - Wetland protection |
| | Aquatic habitat restoration - Wetland restoration and creation |
| | Aquatic habitat restoration - Legal transactions to keep water in-stream |
| | Aquatic habitat restoration - In-stream barrier removal |
| | Aquatic habitat restoration - Dam reoperation |
| | Aquatic habitat restoration - Floodplain inundation/reestablish hydrologic connection |
| | Water Governance - direct engagement in water governance and pulic water management |
| | Catalytic activities - Activities that pave the way for longer-term water stewardship outcomes |

## waterImpact
<a name="waterImpact"></a>Project is located near an area where water (from rainfall, snowmelt, or groundwater) collects and flows into a body of water such as a river, lake, or ocean

| Id | 143 |
| :---- | :------------------------------- |
| **Label** | Project activity takes place near a water basin |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## waterMonitorIntention
<a name="waterMonitorIntention"></a>Details of the water monitoring plan the project intends to implement

| Id | 144 |
| :---- | :------------------------------- |
| **Label** | Description of water resources monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## expectedWaterImpacts
<a name="expectedWaterImpacts"></a>Type of water-related impact anticipated from project activities

| Id | 938 |
| :---- | :------------------------------- |
| **Label** | Expected water impacts as a result of the project activity |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Project impacts water quality |
| | Project impacts water flow |
| | Project impacts water temperature |
| | Project impacts water availability |
| | Project affects local ground water recharge rates |
| | Project affects water treatment costs |
| | Project affects sanitation and hygiene |
| | Project affects water governance |
| | Project affects important water-related ecosystems |
| | Other |
| | None |

## waterLocalDetails
<a name="waterLocalDetails"></a>Description of any expected impacts on water quality or availability

| Id | 187 |
| :---- | :------------------------------- |
| **Label** | Summary of expected water impacts of the project activity |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## waterBaselineCondition
<a name="waterBaselineCondition"></a>Project conducts a baseline water survey

| Id | 183 |
| :---- | :------------------------------- |
| **Label** | Project evaluates initial water resources |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## waterBaselineDescription
<a name="waterBaselineDescription"></a>Summary of baseline water resources (i.e., baseline water survey results)

| Id | 939 |
| :---- | :------------------------------- |
| **Label** | Description of baseline water resources |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## endangeredSpeciesConditional
<a name="endangeredSpeciesConditional"></a>Identification of any expected negative impacts on threatened or endangered species

| Id | 1477 |
| :---- | :------------------------------- |
| **Label** | Project may pose risks to threatened or endangered species |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## ecosystemBiome
<a name="ecosystemBiome"></a>Type of biome in which the project operates

| Id | 56 |
| :---- | :------------------------------- |
| **Label** | Biome type |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Tropical-subtropical forests |
| | Temperate-boreal forests and woodlands |
| | Shrublands and shrubby woodlands |
| | Savannas and grasslands |
| | Deserts and semi-deserts |
| | Polar-alpine |
| | Intensive land-use systems |
| | Supralittoral coastal systems |
| | Palustrine wetlands |
| | Brackish tidal systems |
| | Shoreline systems |
| | Unknown |

## biodiversityMonitoringPlan
<a name="biodiversityMonitoringPlan"></a>Documentation or supporting evidence of the biodiversity monitoring plan

| Id | 1478 |
| :---- | :------------------------------- |
| **Label** | Biodiversity monitoring plan documentation |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |

## ecosystemCategorization
<a name="ecosystemCategorization"></a>As per the IUCN, ecosystem risk refers to an ecosystem's vulnerability of collapse, determined by reductions in geographical distribution or degradation of the components of ecosystems and the services they provide (more information can be found here: https://assessments.iucnrle.org/)

| Id | 57 |
| :---- | :------------------------------- |
| **Label** | Ecosystem categorization |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |
| **Options** | Collapsed |
| | Critically endangered |
| | Endangered |
| | Vulnerable |
| | Near threatened |
| | Least concern |
| | Data deficient |
| | Not evaluated |

## biomeDescription
<a name="biomeDescription"></a>Biome type in the context of the IUCN Global Ecosystem Typology Version 2.0

| Id | 138 |
| :---- | :------------------------------- |
| **Label** | Description of the biome |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## biomeRiskCategory
<a name="biomeRiskCategory"></a>Biome risk category in the context of the IUCN Global Ecosystem Typology Version 2.0

| Id | 139 |
| :---- | :------------------------------- |
| **Label** | Description of the biome risk category |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## biodiversityMonitoring
<a name="biodiversityMonitoring"></a>Project plans ongoing biodiversity monitoring of the broader environment or at least one identified variable (e.g., at-risk species)

| Id | 58 |
| :---- | :------------------------------- |
| **Label** | Project plans to identify and monitor related biodiversity impacts before, during, and after project implementation |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## baselineBiodiversity
<a name="baselineBiodiversity"></a>Biodiversity baseline survey conducted to monitor elements such as species abundance, habitat area, and related factors

| Id | 676 |
| :---- | :------------------------------- |
| **Label** | Project has conducted an initial biodiversity survey |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## biodiversityImpactDrivers
<a name="biodiversityImpactDrivers"></a>Description of expected biodiversity and other ecosystem impacts of the project and their drivers. Impacts can include both positive and negative impacts, as well as both inside and outside the project area. 

| Id | 59 |
| :---- | :------------------------------- |
| **Label** | Summary of expected biodiversity impacts of the project activity |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## threatenedSpecies
<a name="threatenedSpecies"></a>Overview of the threatened and endangered species in the surrounding geographic region or otherwise potentially affected by project activities

| Id | 140 |
| :---- | :------------------------------- |
| **Label** | International Union for Conservation (IUCN) threatened and endangered species |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## biodiversityMonitoringProcess
<a name="biodiversityMonitoringProcess"></a>The process of identifying and monitoring relevant biodiversity indicators (e.g., fauna, flora, and non-timber forest products) before and after project intervention

| Id | 182 |
| :---- | :------------------------------- |
| **Label** | Biodiversity monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## biodiversityLegal
<a name="biodiversityLegal"></a>The regulatory frameworks governing monitoring, protection, or project impacts on threatened or endangered species

| Id | 141 |
| :---- | :------------------------------- |
| **Label** | Legal framework governing the threatened and endangered species |
| **Tier** | 1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## baselineSoilSurvey
<a name="baselineSoilSurvey"></a>Indicates whether a baseline soil quality study (before project start or using a control site) has been conducted

| Id | 1481 |
| :---- | :------------------------------- |
| **Label** | A baseline soil health survey been conducted |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## soilType
<a name="soilType"></a>Each of the twelve soil orders represents a grouping of soils with distinct characteristics and ecological significance

| Id | 1479 |
| :---- | :------------------------------- |
| **Label** | Primary type of soil order type of project site |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | null |
| **Options** | Alfisols |
| | Andisols |
| | Aridisols |
| | Entisols |
| | Gelisols |
| | Histosols |
| | Inceptisols |
| | Mollisols |
| | Oxisols |
| | Spodosols |
| | Ultisols |
| | Vertisols |

## baselineSoilSurveyUpload
<a name="baselineSoilSurveyUpload"></a>Baseline soil health survey documentation (e.g., survey findings, template)

| Id | 1482 |
| :---- | :------------------------------- |
| **Label** | Baseline soil health survey  |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | array |

## erosionDiligence
<a name="erosionDiligence"></a>High erosion risk, defined by the World Atlas of Desertification Global Erosion Map, with R factors of 20 or higher indicating ‘high erosion risk’

| Id | 1480 |
| :---- | :------------------------------- |
| **Label** | Area in which the project takes place is at high risk for erosion |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## soilMonitoringPlanDetails
<a name="soilMonitoringPlanDetails"></a>Description of the soil monitoring plan, including testing types and frequency

| Id | 1484 |
| :---- | :------------------------------- |
| **Label** | Overview of soil monitoring plan |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

## soilMonitoringPlan
<a name="soilMonitoringPlan"></a>Indicates if the project will follow a protocol to sample, measure, and analyze soil health and changes caused by project activities

| Id | 1483 |
| :---- | :------------------------------- |
| **Label** | Plan in place for soil testing and monitoring |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | boolean |

## soilEffects
<a name="soilEffects"></a>Description of expected soil impacts (e.g., physical, chemical, and biological soil ecosystem impacts). If relevant and known, the assessment should reference soil temperature, type, and chemistry)


| Id | 623 |
| :---- | :------------------------------- |
| **Label** | Summary of expected soil impacts of the project activity |
| **Tier** | -1 |
| **Section** | provenance-ecologicalDueDiligence |
| **type** | string |

# forecast-baselineScenario
## baseline
<a name="baseline"></a>A description of the expected scenario if the project were not implemented, such as the likely alternative use or disposal of biomass feedstock in biomass-based projects, along with the underlying assumptions used to estimate baseline emissions

| Id | 272 |
| :---- | :------------------------------- |
| **Label** | Baseline scenario overview |
| **Tier** | 1 |
| **Section** | forecast-baselineScenario |
| **type** | string |

## baselineSupporting
<a name="baselineSupporting"></a>

| Id | 273 |
| :---- | :------------------------------- |
| **Label** | Baseline scenario supporting documents |
| **Tier** | -1 |
| **Section** | forecast-baselineScenario |
| **type** | array |

## fixedBaselinePeriod
<a name="fixedBaselinePeriod"></a>If applicable. Some standards or methodologies require that the baseline scenrio is based on a fixed ("static") historical lookback period or schedule of previous land management activities.

| Id | 2036 |
| :---- | :------------------------------- |
| **Label** | Current fixed baseline period or historical look-back period |
| **Tier** | 1 |
| **Section** | forecast-baselineScenario |
| **type** | string |

## dynamicBaseline
<a name="dynamicBaseline"></a>Baselines are traditionally established by predicting what would have happened in the absence of the project. Dynamic baselines can take different formats, but are usually estbalished by observing a reference area as it changes over time.

| Id | 71 |
| :---- | :------------------------------- |
| **Label** | The project implements dynamic baselining  |
| **Tier** | 1 |
| **Section** | forecast-baselineScenario |
| **type** | boolean |

## dynamicBaselineSummary
<a name="dynamicBaselineSummary"></a>Overview of the project's dynamic baselining approach

| Id | 951 |
| :---- | :------------------------------- |
| **Label** | Overview of dynamic baselining approach |
| **Tier** | 1 |
| **Section** | forecast-baselineScenario |
| **type** | string |

# forecast-projectDesign
## conservativeMeasures
<a name="conservativeMeasures"></a>Overview of measures taken to ensure that the GHG emission reductions or removals from the mitigation activity are be robustly quantified, based on conservative approaches, completeness, and scientific methods

| Id | 1847 |
| :---- | :------------------------------- |
| **Label** | Summary of initiatives undertaken to ensure the project's integrity and scientific robustness |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## scalability
<a name="scalability"></a>Overview of the project's plans and/or ability to increase in scale

| Id | 1077 |
| :---- | :------------------------------- |
| **Label** | Project scalability |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## netNegativityPartial
<a name="netNegativityPartial"></a>Indication of whether the project will result in more GHG emissions removed from the atmosphere than would be emitted

| Id | 1011 |
| :---- | :------------------------------- |
| **Label** | Project has a net carbon negative impact |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | boolean |

## netNegativityPartialExplain
<a name="netNegativityPartialExplain"></a>Description of how the project activity results in net carbon negativity

| Id | 1012 |
| :---- | :------------------------------- |
| **Label** | Net carbon negativity overview |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## deviations
<a name="deviations"></a>Includes information such as whether the deviation meets the criteria for permitted methodology deviations, whether the deviation negatively impacts the conservativeness of the quantification of emission reductions or removals (except where they result in increased accuracy), or any previously validated methodology deviations

| Id | 542 |
| :---- | :------------------------------- |
| **Label** | Methodology deviations |
| **Tier** | 1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## sensitiveInformation
<a name="sensitiveInformation"></a>Explanation of why some proprietary information has been redacted or not included

| Id | 543 |
| :---- | :------------------------------- |
| **Label** | Commercially sensitive information |
| **Tier** | 1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## generalDocumentUploac
<a name="generalDocumentUploac"></a>A general document upload field, in which any documents that are not explicitly asked for can be uploaded 

| Id | 614 |
| :---- | :------------------------------- |
| **Label** | General document upload |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | array |

## technologyManufacturer
<a name="technologyManufacturer"></a>If relevant, the providers or manufacturers of any technology or equipment used substantially in the project activity

| Id | 749 |
| :---- | :------------------------------- |
| **Label** | Technology manufacturer or provider |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | string |

## technicalUpload
<a name="technicalUpload"></a>Documentation regarding the project technology (e.g., manufacturer specifications, field reports, standard certifications) or technical processes (e.g., process flow diagrams)

| Id | 625 |
| :---- | :------------------------------- |
| **Label** | Project technology and technical process supporting documents |
| **Tier** | -1 |
| **Section** | forecast-projectDesign |
| **type** | array |

# forecast-spatialBoundaries
## projectBoundaries
<a name="projectBoundaries"></a>

| Id | 2040 |
| :---- | :------------------------------- |
| **Label** | Total area within project boundaries |
| **Tier** | 1 |
| **Section** | forecast-spatialBoundaries |
| **type** | string |

## stratificationStrategy
<a name="stratificationStrategy"></a>Strata may be defined based on soil type and depth, water table depth, vegetation, salinity, land type or expected changes in these characteristics. 

| Id | 2041 |
| :---- | :------------------------------- |
| **Label** | Strategy for stratification of project area |
| **Tier** | 1 |
| **Section** | forecast-spatialBoundaries |
| **type** | string |

## spatialInformation
<a name="spatialInformation"></a>Stratification helps improve the accuracy of carbon stock and GHG flux estimates, based on specifics of the project's land use characteristics. Individual strata areas must be spatially discrete, identifiable with accurate spatial data, and sum to the total project area. Land use/land cover maps must be ground-truthed, less than 10 years old, or proven to be accurate.

| Id | 2037 |
| :---- | :------------------------------- |
| **Label** | Spatial information on stratified project area |
| **Tier** | 1 |
| **Section** | forecast-spatialBoundaries |
| **type** | null |

# forecast-systemBoundaries
## emissionSourcesTable
<a name="emissionSourcesTable"></a>

| Id | 1337 |
| :---- | :------------------------------- |
| **Label** | Emission sources included in the project boundary |
| **Tier** | 1 |
| **Section** | forecast-systemBoundaries |
| **type** | object |

### Table structure
| Scenario | Gas | Source | Inclusion status | Justification | 
| :---- | :---- | :---- | :---- | :---- |
| | | | | |

# forecast-lifeCycleAssessment
## lcaPartial
<a name="lcaPartial"></a>

| Id | 1025 |
| :---- | :------------------------------- |
| **Label** | LCA is used to quantify emissions |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | boolean |

## lcaTable
<a name="lcaTable"></a>

| Id | 1349 |
| :---- | :------------------------------- |
| **Label** | LCA repository |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | object |

### Table structure
| LCA type | LCA provider | LCA completion date | Functional unit | 
| :---- | :---- | :---- | :---- |
| | | | |

## lca
<a name="lca"></a>

| Id | 274 |
| :---- | :------------------------------- |
| **Label** | LCA has been completed |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | boolean |

## lcaUpload
<a name="lcaUpload"></a>

| Id | 276 |
| :---- | :------------------------------- |
| **Label** | LCA upload |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | array |

## systemBoundaryDetails
<a name="systemBoundaryDetails"></a>The system boundary of the project's life cycle assessment

| Id | 627 |
| :---- | :------------------------------- |
| **Label** | System boundary overview and justification |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | string |

## systemBoundaryFigure
<a name="systemBoundaryFigure"></a>Relevant figures depicting the process flows and system boundaries

| Id | 628 |
| :---- | :------------------------------- |
| **Label** | System boundary figure |
| **Tier** | -1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | array |

## lcaPuroResultsTable
<a name="lcaPuroResultsTable"></a>The results from the most recent life cycle assessment

| Id | 1350 |
| :---- | :------------------------------- |
| **Label** | LCA results |
| **Tier** | 1 |
| **Section** | forecast-lifeCycleAssessment |
| **type** | object |

### Table structure
| Reporting period start | Reporting period end | Level 1 | Level 2 | Level 3 | Climate impact in kg CO2-eq per functional unit | Climate impact in kg CO2-eq per reporting period | 
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| | | | | | | |

# forecast-forecastedCredits
## forecastConditional
<a name="forecastConditional"></a>Forecasting carbon removals or reductions is the process of estimating the amount of greenhouse gases that a project is expected to remove from or prevent from entering the atmosphere over a future period, based on scientific models, historical data, and project-specific assumptions

| Id | 876 |
| :---- | :------------------------------- |
| **Label** | Project forecasts emission reductions and/or removals |
| **Tier** | 1 |
| **Section** | forecast-forecastedCredits |
| **type** | boolean |

## totalForecast
<a name="totalForecast"></a>The total estimated issued credits over the crediting period (i.e., tonnes of CO2e removed, avoided, or reduced)

| Id | 1156 |
| :---- | :------------------------------- |
| **Label** | Credit period forecast |
| **Tier** | -1 |
| **Section** | forecast-forecastedCredits |
| **type** | number |

## partialForecast
<a name="partialForecast"></a>The estimated credits per vintage year throughout the crediting period

| Id | 1015 |
| :---- | :------------------------------- |
| **Label** | Credit forecast by vintage |
| **Tier** | -1 |
| **Section** | forecast-forecastedCredits |
| **type** | object |
| **Options** | [object Object] |
| | [object Object] |
| | [object Object] |
| | [object Object] |

## forecastAssumptions
<a name="forecastAssumptions"></a>Credit forecasting mechanism and assumptions refers to the approach, models, and key assumptions used to estimate future carbon credit generation

| Id | 878 |
| :---- | :------------------------------- |
| **Label** | Credit forecasting mechanism and assumptions |
| **Tier** | -1 |
| **Section** | forecast-forecastedCredits |
| **type** | string |

## forecastComments
<a name="forecastComments"></a>Optional additional context on the credit forecast

| Id | 84 |
| :---- | :------------------------------- |
| **Label** | Additional comments on forecast |
| **Tier** | 1 |
| **Section** | forecast-forecastedCredits |
| **type** | string |

## forecastWorkbook
<a name="forecastWorkbook"></a>Documentation may include registry-specific forecast templates (such as the ACR ERT calculator) and other templates or documents that support the calculations

| Id | 85 |
| :---- | :------------------------------- |
| **Label** | Forecast supporting documents |
| **Tier** | -1 |
| **Section** | forecast-forecastedCredits |
| **type** | array |

# forecast-monitoringPlan
## parametersFixedTable
<a name="parametersFixedTable"></a>Fixed (ex-ante) parameters are values set at the start of the project and typically  remain constant throughout a crediting period. They are usually based on established scientific research, default factors, or regulatory guidance.

| Id | 1340 |
| :---- | :------------------------------- |
| **Label** | Ex-ante fixed parameters |
| **Tier** | 1 |
| **Section** | forecast-monitoringPlan |
| **type** | object |

### Table structure
| Parameter | Description | Unit | Purpose | Source of data | Value applied | Comments | 
| :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| | | | | | | |

## parametersMonitoredTable
<a name="parametersMonitoredTable"></a>Monitored parameters are measured or observed during the project’s implementation and reporting periods. They reflect actual project performance and environmental conditions.

| Id | 1341 |
| :---- | :------------------------------- |
| **Label** | Monitored parameters overview |
| **Tier** | 1 |
| **Section** | forecast-monitoringPlan |
| **type** | object |

### Table structure
| Parameter | Description | Unit | Purpose | Source of data | Frequency of monitoring | Quantification method | Description of quantification method | QA/QC procedures | Comments | 
| :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- | :---- |
| | | | | | | | | | |

## dataParameters
<a name="dataParameters"></a>Optional additional context regarding the fixed and monitored parameters used in project calculations

| Id | 556 |
| :---- | :------------------------------- |
| **Label** | Additional comments on fixed and monitored parameters |
| **Tier** | 1 |
| **Section** | forecast-monitoringPlan |
| **type** | string |

## monitoringPlan
<a name="monitoringPlan"></a>The monitoring plan may include: technical description of the monitoring tasks, data to be collected, overview of data collection procedures, quality control and quality assurance procedures, data archiving and organization and responsibilities of the parties involved

| Id | 555 |
| :---- | :------------------------------- |
| **Label** | MRV protocol and monitoring plan overview |
| **Tier** | 1 |
| **Section** | forecast-monitoringPlan |
| **type** | string |

## monitoringTimeline
<a name="monitoringTimeline"></a>Overview of the monitoring timeline embedded within the project's monitoring plan

| Id | 773 |
| :---- | :------------------------------- |
| **Label** | Monitoring timeline |
| **Tier** | -1 |
| **Section** | forecast-monitoringPlan |
| **type** | string |

## monitoringTeam
<a name="monitoringTeam"></a>

| Id | 2038 |
| :---- | :------------------------------- |
| **Label** | Roles, responsibilities, and capacity of monitoring team and management |
| **Tier** | 1 |
| **Section** | forecast-monitoringPlan |
| **type** | string |

## dataProcess
<a name="dataProcess"></a>Overview of the methods used to collect, clean, and securely store project monitoring data to ensure accuracy, traceability, and long-term accessibility

| Id | 558 |
| :---- | :------------------------------- |
| **Label** | Data processing and storage procedures |
| **Tier** | -1 |
| **Section** | forecast-monitoringPlan |
| **type** | string |

## monitoringWorkbook
<a name="monitoringWorkbook"></a>Documents underpinning the monitoring approach (e.g., details on the parameters monitored, monitoring plan documentation etc.)

| Id | 641 |
| :---- | :------------------------------- |
| **Label** | Monitoring supporting documents  |
| **Tier** | -1 |
| **Section** | forecast-monitoringPlan |
| **type** | array |

# forecast-permanenceForecast
## permanenceNumber
<a name="permanenceNumber"></a>The projected duration (in years) over which removed carbon will be stored or prevented from entering the atmosphere, accounting for risks of reversal over time

| Id | 945 |
| :---- | :------------------------------- |
| **Label** | Permanence |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |
| **Options** | 10-100 years |
| | 101-1,000 years |
| | 1,001-10,000 years |
| | 10,000+ years |

## removalProcess
<a name="removalProcess"></a>Carbon removal process refers to the specific mechanism by which a carbon dioxide removal (CDR) method sequesters CO₂ from the atmosphere, categorized according to the IPCC AR6 framework based on its role in the carbon cycle (e.g., biological, geochemical, ocean-based, or chemical pathways)

| Id | 757 |
| :---- | :------------------------------- |
| **Label** | Carbon removal process |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |
| **Options** | Land-based biological |
| | Ocean-based biological |
| | Geochemical |
| | Chemical |
| | Other |

## removalProcessOther
<a name="removalProcessOther"></a>

| Id | 1223 |
| :---- | :------------------------------- |
| **Label** | Other carbon removal process  |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## storageType
<a name="storageType"></a>Carbon storage type refers to the form and location in which removed carbon is stored, categorized by the IPCC as terrestrial/biological (e.g., biomass, soil), geological (e.g., rock formations), marine/oceanic, or product-based (e.g., durable materials), each with varying levels of stability and permanence

| Id | 64 |
| :---- | :------------------------------- |
| **Label** | Storage type |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |
| **Options** | Terrestrial |
| | Marine |
| | Geologic |
| | Engineered product |
| | Other |

## storageTypeOther
<a name="storageTypeOther"></a>

| Id | 1224 |
| :---- | :------------------------------- |
| **Label** | Other storage type |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## carbonStorageDetails
<a name="carbonStorageDetails"></a>Details on how the carbon is stored and the estimated duration for which it remains stored in a safe and stable manner

| Id | 661 |
| :---- | :------------------------------- |
| **Label** | Carbon storage overview |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## unavoidableRiskTable
<a name="unavoidableRiskTable"></a>

| Id | 1343 |
| :---- | :------------------------------- |
| **Label** | Assessment of unavoidable risks |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | object |

### Table structure
| Unintentional or unavoidable reversal risk | Assessment and/or mitigation strategy | 
| :---- | :---- |
| | |

## avoidableRiskTable
<a name="avoidableRiskTable"></a>Avoidable or intentional risks for carbon projects are risks that can be reasonably mitigated through proper project design, implementation, and management (e.g., financial viability, operational or technical risks related to project management, project design and execution, project governance, contractual breaches, disputes, etc.)

| Id | 1342 |
| :---- | :------------------------------- |
| **Label** | Assessment of avoidable risks |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | object |

### Table structure
| Intentional or avoidable reversal risk | Assessment and/or mitigation strategy | 
| :---- | :---- |
| | |

## reversalRiskOther
<a name="reversalRiskOther"></a>Optional additional context on the assessment of potential project risks (i.e., risks to carbon durability, risks to project viability, and/or risks to credit delivery) 

| Id | 541 |
| :---- | :------------------------------- |
| **Label** | Project risk assessment |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## riskSummaryUpload
<a name="riskSummaryUpload"></a>Any documentation supporting the risk assessment

| Id | 1228 |
| :---- | :------------------------------- |
| **Label** | Risk assessment documentation |
| **Tier** | -1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

## opportunityCostAnalysisRmifw
<a name="opportunityCostAnalysisRmifw"></a>Opportunity cost analysis shall be based on the net present value (NPV) of the alternative land uses identified in the project's additionality assessment, except where most baseline activities are subsistence driven. Where most baseline activities are subsistence driven, an NPV analysis is not required.

| Id | 2175 |
| :---- | :------------------------------- |
| **Label** | Opportunity cost analysis |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

## financialViabilityRmifw
<a name="financialViabilityRmifw"></a>Financial viability includes two main components: 1. The number of years until breakeven is reached (i.e.,the payback period). 2. The funding secured relative to what is needed to implement and operate the project until reaching breakeven.

| Id | 2174 |
| :---- | :------------------------------- |
| **Label** | Financial viability |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

## durStakeholderAnalysisRmifw
<a name="durStakeholderAnalysisRmifw"></a>All stakeholders includes all indigenous peoples and local communities with statutory or customary rights to land or resources in the project area(s) as well as description of past/ongoing disputes over land or resources in the project area(s) and their resolution or future resolution.

| Id | 2172 |
| :---- | :------------------------------- |
| **Label** | Durability stakeholder analysis |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## politicalRiskRmifw
<a name="politicalRiskRmifw"></a>Mean should be averaged over the most recent five years of available data

| Id | 2176 |
| :---- | :------------------------------- |
| **Label** | Political risk  |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## riskManagementPlan
<a name="riskManagementPlan"></a>A risk management plan encompasses a strategy for managing and mitigating risks that could impact a carbon project's ability to generate valid credits

| Id | 163 |
| :---- | :------------------------------- |
| **Label** | Risk management plan in place |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | boolean |

## riskPlan
<a name="riskPlan"></a>Overview of the project's plan to mitigate risk (i.e., a systematic overview of the measures taken to mitigate and/or monitor reversal and project risks)

| Id | 68 |
| :---- | :------------------------------- |
| **Label** | Risk management plan |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## riskManagementPlanUpload
<a name="riskManagementPlanUpload"></a>

| Id | 164 |
| :---- | :------------------------------- |
| **Label** | Risk management plan supporting documents |
| **Tier** | -1 |
| **Section** | forecast-permanenceForecast |
| **type** | object |

## reversalRiskMitigationStrategy
<a name="reversalRiskMitigationStrategy"></a>The strategy to address the potential loss of sequestered carbon by using financial tools or reserves, such as insurance or buffer pools, to compensate for potential reversals and ensure long-term credit validity

| Id | 65 |
| :---- | :------------------------------- |
| **Label** | Reversal risk mitigation strategy |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |
| **Options** | Pooled buffer reserves |
| | Non-pooled buffer reserves |
| | Temporary credits |
| | Discounting |
| | Monetary payments |
| | Insurance |
| | Contingency funds |
| | Other |
| | None |

## otherReversalRiskMitigationStrategy
<a name="otherReversalRiskMitigationStrategy"></a>

| Id | 66 |
| :---- | :------------------------------- |
| **Label** | Other reversal risk mitigation strategy type |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## insuranceOwner
<a name="insuranceOwner"></a>

| Id | 67 |
| :---- | :------------------------------- |
| **Label** | Insurance policy issuer and owner |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | string |

## insuranceEvidence
<a name="insuranceEvidence"></a>

| Id | 758 |
| :---- | :------------------------------- |
| **Label** | Insurance supporting evidence |
| **Tier** | -1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

## adaptiveCapacityEvaluationSeceltionRmifw
<a name="adaptiveCapacityEvaluationSeceltionRmifw"></a>Adaptive capacity can be described as considerations a project proponent has taken into account when developing a project that mitigates future risk of climate change. Please refer to the Verra AFOLU Non Permanence Risk Tool for further details on the options provided.

| Id | 2178 |
| :---- | :------------------------------- |
| **Label** | Adaptive capacity evaluation selection |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |
| **Options** | Variety |
| | Learning Capacity |
| | Room for Change |
| | Leadership |
| | Resources |
| | Fair Governance |
| | Innovation |

## durStakeholderConsultationRmifw
<a name="durStakeholderConsultationRmifw"></a>

| Id | 2173 |
| :---- | :------------------------------- |
| **Label** | Durability stakeholder consultation |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

## adaptiveCapacityEvaluationSupportinEvidenceRmifw
<a name="adaptiveCapacityEvaluationSupportinEvidenceRmifw"></a>

| Id | 2179 |
| :---- | :------------------------------- |
| **Label** | Adaptive capacity evaluation supporting evidence |
| **Tier** | 1 |
| **Section** | forecast-permanenceForecast |
| **type** | array |

# forecast-additionality
## additionalityApproachUsed
<a name="additionalityApproachUsed"></a>Evaluating additionality ensures that carbon credits are granted only to mitigation activities that would not have occurred without the incentives provided by the carbon credit

| Id | 811 |
| :---- | :------------------------------- |
| **Label** | Additionality approaches used in the project |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | array |
| **Options** | Prior consideration of carbon credits |
| | First-of-its-kind |
| | Regulatory additionality |
| | Common practice / penetration |
| | Financial additionality |
| | Barrier analysis |
| | Performance-based additionality |
| | Counterfactual analysis |
| | Positive list |
| | Other standardized approach |

## noAdditionalityValidationDetails
<a name="noAdditionalityValidationDetails"></a>

| Id | 1848 |
| :---- | :------------------------------- |
| **Label** | Justification for the absence of additionality validation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | string |

## validationAdditionality
<a name="validationAdditionality"></a>All elements of the chosen additionality approaches have been assessed by a validation or verification body and/or a carbon-crediting program or standard

| Id | 226 |
| :---- | :------------------------------- |
| **Label** | The selected additionality approaches have been validated |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## validationAdditionalityThirdParty
<a name="validationAdditionalityThirdParty"></a>

| Id | 810 |
| :---- | :------------------------------- |
| **Label** | Additionality validation body |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## recentUpdate
<a name="recentUpdate"></a>The most recent year that the assessment for the standardized approach was reviewed

| Id | 261 |
| :---- | :------------------------------- |
| **Label** | Latest review |
| **Tier** | 3 |
| **Section** | forecast-additionality |
| **type** | number |

## firstOfItsKind
<a name="firstOfItsKind"></a>First-of-its-kind projects implement innovative approaches or technologies that set them apart from any existing practices or solutions within a given sector or region

| Id | 812 |
| :---- | :------------------------------- |
| **Label** | Project mitigation activity is the first-of-its-kind |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## firstOfItsKindAnalysis
<a name="firstOfItsKindAnalysis"></a>

| Id | 813 |
| :---- | :------------------------------- |
| **Label** | First-of-its-kind mitigation activity details and justification |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## firstOfItsKindUpload
<a name="firstOfItsKindUpload"></a>

| Id | 814 |
| :---- | :------------------------------- |
| **Label** | Supporting documentation for first-of-its-kind projects |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## regulatorySurplus
<a name="regulatorySurplus"></a>Regulatory additionality ensures that a carbon credit can only be issued for a mitigation activity that goes beyond what is required by existing laws or regulations

| Id | 130 |
| :---- | :------------------------------- |
| **Label** | The project is not required by and/or exceeds existing applicable laws, regulations, or other binding obligations |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## regulatorySurplusTestDetails
<a name="regulatorySurplusTestDetails"></a>Overview of applicable laws and regulations used to justify regulatory additionality by demonstrating that the mitigation activity is not legally required

| Id | 514 |
| :---- | :------------------------------- |
| **Label** | Relevant laws, regulations, and/or binding obligations justifying the regulatory surplus test |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## regulatorySurplusUpload
<a name="regulatorySurplusUpload"></a>

| Id | 131 |
| :---- | :------------------------------- |
| **Label** | Supporting documentation demonstrating legal and regulatory additionality |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | array |

## commonPractice
<a name="commonPractice"></a>The common practice or market penetration test evaluates whether a mitigation activity is widely adopted in a sector or region. If the activity is already standard practice, it is not considered additional and is therefore ineligible for carbon credits.

| Id | 515 |
| :---- | :------------------------------- |
| **Label** | The project demonstrates a low level of penetration or successfully passes the common practice test within a similar sector, region, or activity |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## threshold
<a name="threshold"></a>

| Id | 255 |
| :---- | :------------------------------- |
| **Label** | Threshold or maximum adoption level for market penetration |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## commonPracticeDetails
<a name="commonPracticeDetails"></a>Overview of the approach used to determine additionality and the methodology, carbon-crediting program, or equivalent entity responsible for determining the threshold for market penetration

| Id | 516 |
| :---- | :------------------------------- |
| **Label** | Common practice test details |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## commonPracticeUpload
<a name="commonPracticeUpload"></a>

| Id | 815 |
| :---- | :------------------------------- |
| **Label** | Common practice additionality supporting documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## initialAdditionality
<a name="initialAdditionality"></a>Project is not financially feasible or is less financially attractive without carbon credit revenues compared to the alternatives of the mitigation activity

| Id | 133 |
| :---- | :------------------------------- |
| **Label** | Project is a direct result of carbon credit finance |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## additionalityDemonstration
<a name="additionalityDemonstration"></a>

| Id | 135 |
| :---- | :------------------------------- |
| **Label** | Demonstration that the project activities are a result of carbon finance |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | array |

## investmentMethod
<a name="investmentMethod"></a>Indicates which assessment method is used for the financial investment analysis

| Id | 236 |
| :---- | :------------------------------- |
| **Label** | Investment analysis approach |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | array |
| **Options** | Simple cost analysis |
| | Benchmark analysis |
| | Investment comparison analysis |
| | Other |

## simpleCostAdditionality
<a name="simpleCostAdditionality"></a>

| Id | 817 |
| :---- | :------------------------------- |
| **Label** | Project has no other income or minimal capital expenditures compared to operational expenditures |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |
| **Options** | Simple cost analysis |
| | Benchmark analysis |
| | Investment comparison analysis |
| | Other |

## simpleCostAnalysis
<a name="simpleCostAnalysis"></a>Simple cost analysis is a financial additionality test that compares a project's expected costs and revenues to determine if it would be economically unattractive without carbon credit income. If the project does not generate sufficient returns or would operate at a loss without the added revenue from credits, it may be deemed additional.

| Id | 818 |
| :---- | :------------------------------- |
| **Label** | Simple cost analysis details |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## simpleCostUpload
<a name="simpleCostUpload"></a>

| Id | 819 |
| :---- | :------------------------------- |
| **Label** | Simple cost analysis documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |
| **Options** | Simple cost analysis |
| | Benchmark analysis |
| | Investment comparison analysis |
| | Other |

## financialIndicator
<a name="financialIndicator"></a>The suitable financial indicator, such as the net present value (NPV) or internal rate of return (IRR) used consistently throughout calculations

| Id | 229 |
| :---- | :------------------------------- |
| **Label** | Chosen financial indicator |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |
| **Options** | Net Present Value (NPV) |
| | Internal Rate of Return (IRR) |
| | Payback period |
| | Cost benefit ratio |
| | Unit cost of service |
| | Other |

## financialIndicatorOther
<a name="financialIndicatorOther"></a>

| Id | 230 |
| :---- | :------------------------------- |
| **Label** | If "Other", explanation |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## benchmarkUsed
<a name="benchmarkUsed"></a>The benchmark approach compares a project's expected return (e.g., IRR or NPV) to a predefined financial benchmark. If the project's return falls below this benchmark without carbon credit revenue, it may be considered financially additional.

| Id | 238 |
| :---- | :------------------------------- |
| **Label** | Project uses a financial benchmark approach |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## benchmarkJustification
<a name="benchmarkJustification"></a>

| Id | 239 |
| :---- | :------------------------------- |
| **Label** | Justification and results of the financial benchmark analysis |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## benchmarkUpload
<a name="benchmarkUpload"></a>

| Id | 820 |
| :---- | :------------------------------- |
| **Label** | Financial benchmark calculations and documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## investmentComparisonDetails
<a name="investmentComparisonDetails"></a>The investment comparison approach assesses whether the proposed project is less economically attractive than one or more alternative investment options. If the project would not be chosen over more financially viable alternatives without carbon credit revenue, it may be considered additional.

| Id | 821 |
| :---- | :------------------------------- |
| **Label** | Justification and results of the investment comparison analysis |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## investmentComparisonUpload
<a name="investmentComparisonUpload"></a>

| Id | 822 |
| :---- | :------------------------------- |
| **Label** | Investment comparison calculations and documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## sensitivityAnalysis
<a name="sensitivityAnalysis"></a>A sensitivity analysis is required to show whether the conclusion regarding the financial attractiveness is robust to reasonable variation in the critical assumptions

| Id | 234 |
| :---- | :------------------------------- |
| **Label** | Project conducts a sensitivity analysis |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## sensitivityAnalysisDetails
<a name="sensitivityAnalysisDetails"></a>

| Id | 823 |
| :---- | :------------------------------- |
| **Label** | Results of sensitivity analysis |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## sensitivityUpload
<a name="sensitivityUpload"></a>

| Id | 235 |
| :---- | :------------------------------- |
| **Label** | Sensitivity analysis documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | object |

## projectRevenues
<a name="projectRevenues"></a>Detailed breakdown of all revenue, including cost savings and public subsidies, related to the project

| Id | 816 |
| :---- | :------------------------------- |
| **Label** | Breakdown of project revenue |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## costs
<a name="costs"></a>Detailed breakdown of all project-related costs, including both operational expenditures and capital expenditures

| Id | 231 |
| :---- | :------------------------------- |
| **Label** | Breakdown of project costs |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## barrier
<a name="barrier"></a>Barrier analysis is an additionality test used to identify and assess the key obstacles (e.g., financial, technical, regulatory, or market-related) that would prevent a project from being implemented without carbon credit revenue

| Id | 246 |
| :---- | :------------------------------- |
| **Label** | The project faces an implementation barrier for which carbon credit revenues are the decisive element in overcoming the barrier |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## barrierType
<a name="barrierType"></a>Indicates which type of barrier analysis is conducted. Examples of each include: financial barriers, institutional barriers, information barriers, other barriers specific to the project and/or region where the project is implemented if these barriers are explicitly identified and elaborated in the relevant quantification methodology or other program documents.

| Id | 247 |
| :---- | :------------------------------- |
| **Label** | Implementation barrier(s) the project faces |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | array |
| **Options** | Financial barriers |
| | Institutional barriers |
| | Information barriers |
| | Technological barriers |
| | Other barriers |

## barrierTypeOther
<a name="barrierTypeOther"></a>

| Id | 249 |
| :---- | :------------------------------- |
| **Label** | Other barrier type(s) |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## fiancialBarrierDetails
<a name="fiancialBarrierDetails"></a>

| Id | 518 |
| :---- | :------------------------------- |
| **Label** | Explanation and results of chosen barrier(s) |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## barrierDemo
<a name="barrierDemo"></a>Evidence to (i) demonstrate each identified barrier and (ii) show that carbon credit revenues are the key factor in overcoming each barrier

| Id | 250 |
| :---- | :------------------------------- |
| **Label** | Demonstration of barriers |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## barrierAlternative
<a name="barrierAlternative"></a>Demonstration that at least one other alternative to the project does not face significant barriers, including the barriers faced by the project

| Id | 251 |
| :---- | :------------------------------- |
| **Label** | Alternative scenario barrier details |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## barrierAlternativeUpload
<a name="barrierAlternativeUpload"></a>

| Id | 826 |
| :---- | :------------------------------- |
| **Label** | Supporting documentation for alternative scenario barrier(s) |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## performanceAdditionality
<a name="performanceAdditionality"></a>Performance-based additionality is an approach where a project’s carbon credit eligibility is tied to its actual performance in achieving emission reductions or removals

| Id | 827 |
| :---- | :------------------------------- |
| **Label** | Project activity exceeds a relevant emission reductions and/or removals benchmark |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## performanceAdditionalityDetails
<a name="performanceAdditionalityDetails"></a>

| Id | 828 |
| :---- | :------------------------------- |
| **Label** | Details and results of performance-based additionality approach |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## performanceAdditionalityUpload
<a name="performanceAdditionalityUpload"></a>

| Id | 829 |
| :---- | :------------------------------- |
| **Label** | Evidence and documentation of performance-based additionality |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## alternativeScenarios
<a name="alternativeScenarios"></a>The counterfactuals, or alternative scenarios, that could happen if the mitigation activity did not occur

| Id | 243 |
| :---- | :------------------------------- |
| **Label** | Counterfactuals or alternative scenarios |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## counterfactualAnalysis
<a name="counterfactualAnalysis"></a>A summary of the counterfactual scenario outlining what would likely have occurred in the absence of carbon finance, where CO2 removals are considered additional only when measured against a conservative baseline representing this alternative scenario

| Id | 714 |
| :---- | :------------------------------- |
| **Label** | Counterfactual or alternative scenario details and results |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## counterfactualEvidence
<a name="counterfactualEvidence"></a>Counter-factual analysis based on baselines that are project-specific, conservative and periodically updated

| Id | 715 |
| :---- | :------------------------------- |
| **Label** | Counterfactual or alternative scenario documentation |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## priorConsiderationOfCredits
<a name="priorConsiderationOfCredits"></a>An additionality test that assesses whether carbon revenue was considered or planned for before a project’s implementation. Evidence of such "prior consideration" helps demonstrate that the project would not have been developed without the financial incentive from carbon credits.

| Id | 824 |
| :---- | :------------------------------- |
| **Label** | Carbon credits considered prior to the start date of the project |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## priorConsiderationDetails
<a name="priorConsiderationDetails"></a>

| Id | 825 |
| :---- | :------------------------------- |
| **Label** | Details of prior consideration of carbon credits |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## priorConsideration
<a name="priorConsideration"></a>

| Id | 222 |
| :---- | :------------------------------- |
| **Label** | Evidence of prior consideration of carbon credits |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

## standardizedApproach
<a name="standardizedApproach"></a>

| Id | 257 |
| :---- | :------------------------------- |
| **Label** | The project uses another standardized approach to demonstrate additionality |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | boolean |

## additionalAdditionality
<a name="additionalAdditionality"></a>

| Id | 136 |
| :---- | :------------------------------- |
| **Label** | Name of other standardized additionality approach |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## additionalAdditionalityDeatils
<a name="additionalAdditionalityDeatils"></a>

| Id | 830 |
| :---- | :------------------------------- |
| **Label** | Details and results of the standardized additionality approach |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## activitiesApplicable
<a name="activitiesApplicable"></a>The standardized approach must be defined at an appropriate level of aggregation of technologies/activities and at a high level of stringency

| Id | 258 |
| :---- | :------------------------------- |
| **Label** | Applicable activities and / or technologies |
| **Tier** | 1 |
| **Section** | forecast-additionality |
| **type** | string |

## additionalAdditionalityEvidence
<a name="additionalAdditionalityEvidence"></a>

| Id | 137 |
| :---- | :------------------------------- |
| **Label** | Supporting evidence for other additionality measures |
| **Tier** | -1 |
| **Section** | forecast-additionality |
| **type** | array |

# forecast-validation
## validationReportSummary
<a name="validationReportSummary"></a>

| Id | 1680 |
| :---- | :------------------------------- |
| **Label** | Validation report summary |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

## validationPlanned
<a name="validationPlanned"></a>

| Id | 1669 |
| :---- | :------------------------------- |
| **Label** | Validation date is planned |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | boolean |

## validationPlannedDate
<a name="validationPlannedDate"></a>

| Id | 1670 |
| :---- | :------------------------------- |
| **Label** | Planned validation date |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

## projectValidation
<a name="projectValidation"></a>

| Id | 1155 |
| :---- | :------------------------------- |
| **Label** | Project has been validated by a third-party |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | boolean |

## validationDate
<a name="validationDate"></a>

| Id | 545 |
| :---- | :------------------------------- |
| **Label** | Last validation date |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

## validationUpload
<a name="validationUpload"></a>

| Id | 512 |
| :---- | :------------------------------- |
| **Label** | Validation documentation |
| **Tier** | -1 |
| **Section** | forecast-validation |
| **type** | array |

## validationBodySectoralScopes
<a name="validationBodySectoralScopes"></a>

| Id | 1679 |
| :---- | :------------------------------- |
| **Label** | Accredited sectoral scopes of the validation body |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | array |
| **Options** |   1. Energy (renewable/non-renewable)  |
| | 2. Energy distribution |
| | 3. Energy demand   |
| |   4. Manufacturing industries |
| |   5. Chemical industry |
| | 6. Construction   |
| | 7. Transport |
| | 8. Mining/mineral production |
| |   9. Metal production |
| | 10. Fugitive emissions – from fuel |
| | 11. Fugitive emissions – from Industrial gases (halocarbons and sulphur hexafluoride) |
| | 12. Solvents use |
| | 13. Waste handling and disposal  |
| | 14. Agriculture, Forestry and Other Land Use (AFOLU) |
| | 15. Livestock and manure management |
| | 16. Carbon capture and storage |

## validationBodyAccreditation
<a name="validationBodyAccreditation"></a>

| Id | 1673 |
| :---- | :------------------------------- |
| **Label** | Validation body accreditation or membership |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | array |
| **Options** | ANSI National Accreditation Board (ANAB) |
| | International Accreditation Forum (IAF) |
| | Global Accreditation Bureau (GAB) |
| | UNFCCC / CDM |
| | Standards Council of Canada (SCC) |
| | Other |

## validationBodySelection
<a name="validationBodySelection"></a>

| Id | 1671 |
| :---- | :------------------------------- |
| **Label** | Validation body selection method |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |
| **Options** | Carbon standard or registry approved |
| | Third party approved (e.g., insurance company) |
| | Self-selected |
| | Other |

## validationBodyTeamTable
<a name="validationBodyTeamTable"></a>

| Id | 1690 |
| :---- | :------------------------------- |
| **Label** | Validation body team |
| **Tier** | -1 |
| **Section** | forecast-validation |
| **type** | object |

### Table structure
| Name | Role | Email | Involvement | 
| :---- | :---- | :---- | :---- |
| | | | |

## validationBodyAccreditationOther
<a name="validationBodyAccreditationOther"></a>

| Id | 1678 |
| :---- | :------------------------------- |
| **Label** | Other validation body accreditation or membership |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

## validationBody
<a name="validationBody"></a>

| Id | 544 |
| :---- | :------------------------------- |
| **Label** | Validation body |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

## validationBodySelectionOther
<a name="validationBodySelectionOther"></a>

| Id | 1672 |
| :---- | :------------------------------- |
| **Label** | Other method of selecting validation body |
| **Tier** | 1 |
| **Section** | forecast-validation |
| **type** | string |

# actuals-mrvActuals
## mrvProtocol
<a name="mrvProtocol"></a>

| Id | 618 |
| :---- | :------------------------------- |
| **Label** | Actual MRV protocol is consistent with previously validated protocol |
| **Tier** | 2 |
| **Section** | actuals-mrvActuals |
| **type** | boolean |

## mrvProtocolUpdates
<a name="mrvProtocolUpdates"></a>Detail changes made to the previously validated MRV protocol described in tier 1

| Id | 559 |
| :---- | :------------------------------- |
| **Label** | If "No", detailed overview of updates to MRV protocol |
| **Tier** | 2 |
| **Section** | actuals-mrvActuals |
| **type** | string |

## mrvProvider
<a name="mrvProvider"></a>

| Id | 524 |
| :---- | :------------------------------- |
| **Label** | MRV provider(s) |
| **Tier** | -1 |
| **Section** | actuals-mrvActuals |
| **type** | string |

## mrvThirdParty
<a name="mrvThirdParty"></a>

| Id | 1638 |
| :---- | :------------------------------- |
| **Label** | MRV is conducted by an independent third party |
| **Tier** | 2 |
| **Section** | actuals-mrvActuals |
| **type** | boolean |

## mrvResultsDocs
<a name="mrvResultsDocs"></a>Documents may include monitoring reports, MRV workbooks, images, or other data types, etc.

| Id | 619 |
| :---- | :------------------------------- |
| **Label** | MRV results documentation |
| **Tier** | 2 |
| **Section** | actuals-mrvActuals |
| **type** | array |

## mrvResultsLinks
<a name="mrvResultsLinks"></a>

| Id | 620 |
| :---- | :------------------------------- |
| **Label** | MRV results external links |
| **Tier** | 2 |
| **Section** | actuals-mrvActuals |
| **type** | string |

# actuals-permanenceActuals
## reversalEvent
<a name="reversalEvent"></a>Reversal events can include fire, pest and disease, extreme weather (e.g., drought, hurricane), geological risk (e.g., earthquakes, volcanoes), sea-level rise, and other events

| Id | 153 |
| :---- | :------------------------------- |
| **Label** | Reversal event(s) has occured |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | boolean |

## reversalEventType
<a name="reversalEventType"></a>

| Id | 154 |
| :---- | :------------------------------- |
| **Label** | Type of reversal event(s) |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | array |
| **Options** | Natural causes |
| | Human causes |
| | Unplanned cessation |
| | Other |

## reversalEventTypeOther
<a name="reversalEventTypeOther"></a>

| Id | 155 |
| :---- | :------------------------------- |
| **Label** | Additional details on reversal event(s) |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | string |

## reversalEventTypeLink
<a name="reversalEventTypeLink"></a>

| Id | 156 |
| :---- | :------------------------------- |
| **Label** | Evidence of reversal event(s) |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | array |

## reversalEventStatus
<a name="reversalEventStatus"></a>

| Id | 157 |
| :---- | :------------------------------- |
| **Label** | Status of reversal event(s) |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | string |
| **Options** | In process |
| | Finished |
| | Unknown |

## reversalEventStatusLink
<a name="reversalEventStatusLink"></a>

| Id | 158 |
| :---- | :------------------------------- |
| **Label** | Evidence of status of reversal event(s) |
| **Tier** | -1 |
| **Section** | actuals-permanenceActuals |
| **type** | array |

## upwardAdjustmentBaseline
<a name="upwardAdjustmentBaseline"></a>Some carbon crediting programs allow or require that a new baseline be established in the event of a reversal. Does the program used allow or require for a baseline adjustment to occur in the event of an unavoidable reversal?

| Id | 2042 |
| :---- | :------------------------------- |
| **Label** | Project allowment of upward adjustment to the baseline |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | null |

## upwardAdjustmentBaselineDetails
<a name="upwardAdjustmentBaselineDetails"></a>Provide context on decision of how to adjust the baseline (if applicable) in the event that an unavoidable reversal occurs. 

| Id | 2039 |
| :---- | :------------------------------- |
| **Label** | Upward adjustment to the baseline decision details |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | string |

## compensation
<a name="compensation"></a>

| Id | 161 |
| :---- | :------------------------------- |
| **Label** | Risk mitigation mechanism(s) have been implemented |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | boolean |
| **Options** | Yes |
| | No |

## compensationMechanismDescription
<a name="compensationMechanismDescription"></a>

| Id | 783 |
| :---- | :------------------------------- |
| **Label** | Description of risk mitigation mechanism(s) in place |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | string |

## compensationDetails
<a name="compensationDetails"></a>

| Id | 162 |
| :---- | :------------------------------- |
| **Label** | Evidence of implementation of risk mitigation mechanism(s) |
| **Tier** | 2 |
| **Section** | actuals-permanenceActuals |
| **type** | array |

# actuals-leakageActuals
## leakageActualsConditional
<a name="leakageActualsConditional"></a>

| Id | 785 |
| :---- | :------------------------------- |
| **Label** | Project accounts for leakage |
| **Tier** | 2 |
| **Section** | actuals-leakageActuals |
| **type** | boolean |

## leakageSourceTable
<a name="leakageSourceTable"></a>Non-CO2 emissions are generally considered significant if they are likely to account for more than 20% of the total leakage emissions (in terms of CO2-equivalent) 

| Id | 1809 |
| :---- | :------------------------------- |
| **Label** | Leakage sources |
| **Tier** | -1 |
| **Section** | actuals-leakageActuals |
| **type** | object |

### Table structure
| Type of leakage | Potential source | Inclusion status | Justification | 
| :---- | :---- | :---- | :---- |
| | | | |

## leakageDataGrid
<a name="leakageDataGrid"></a>Leakage values calculated per vintage in tCO2e

| Id | 311 |
| :---- | :------------------------------- |
| **Label** | Leakage values |
| **Tier** | 2 |
| **Section** | actuals-leakageActuals |
| **type** | object |
| **Options** | [object Object] |

## additionalCommentsLeakage
<a name="additionalCommentsLeakage"></a>Overview of the project's approach to calculating and/or accounting for leakage

| Id | 551 |
| :---- | :------------------------------- |
| **Label** | Overview of leakage quantification |
| **Tier** | -1 |
| **Section** | actuals-leakageActuals |
| **type** | string |

## leakageManagementPlan
<a name="leakageManagementPlan"></a>Description of measures the project will take to mitigate leakage

| Id | 2045 |
| :---- | :------------------------------- |
| **Label** | Leakage management plan |
| **Tier** | 2 |
| **Section** | actuals-leakageActuals |
| **type** | string |

## leakageBelt
<a name="leakageBelt"></a>If applicable, land area surrounding or adjacent to the project area in which baseline activities could be displaced due to project implementation.

| Id | 2046 |
| :---- | :------------------------------- |
| **Label** | Leakage belt |
| **Tier** | 2 |
| **Section** | actuals-leakageActuals |
| **type** | null |

## leakageWorkbook
<a name="leakageWorkbook"></a>

| Id | 637 |
| :---- | :------------------------------- |
| **Label** | Leakage supporting documents |
| **Tier** | -1 |
| **Section** | actuals-leakageActuals |
| **type** | array |

# actuals-uncertaintyActuals
## uncertaintyActualsConditional
<a name="uncertaintyActualsConditional"></a>

| Id | 1329 |
| :---- | :------------------------------- |
| **Label** | The project calculates uncertainty |
| **Tier** | 2 |
| **Section** | actuals-uncertaintyActuals |
| **type** | boolean |

## uncertaintyActuals
<a name="uncertaintyActuals"></a>

| Id | 599 |
| :---- | :------------------------------- |
| **Label** | Uncertainty actual values |
| **Tier** | 2 |
| **Section** | actuals-uncertaintyActuals |
| **type** | object |
| **Options** | [object Object] |

## additionalActualUncertainty
<a name="additionalActualUncertainty"></a>

| Id | 600 |
| :---- | :------------------------------- |
| **Label** | Overview of uncertainty calculation |
| **Tier** | 2 |
| **Section** | actuals-uncertaintyActuals |
| **type** | string |

## uncertaintyWorkbook
<a name="uncertaintyWorkbook"></a>

| Id | 638 |
| :---- | :------------------------------- |
| **Label** | Uncertainty supporting documents |
| **Tier** | -1 |
| **Section** | actuals-uncertaintyActuals |
| **type** | array |

# actuals-bufferActuals
## bufferActualsConditional
<a name="bufferActualsConditional"></a>

| Id | 772 |
| :---- | :------------------------------- |
| **Label** | Project maintains a carbon credit buffer pool |
| **Tier** | 2 |
| **Section** | actuals-bufferActuals |
| **type** | boolean |

## biocharBufferActual
<a name="biocharBufferActual"></a>0 if there is no buffer allocation

| Id | 310 |
| :---- | :------------------------------- |
| **Label** | Buffer values |
| **Tier** | 2 |
| **Section** | actuals-bufferActuals |
| **type** | object |
| **Options** | [object Object] |

## additionalCommentsBuffer
<a name="additionalCommentsBuffer"></a>

| Id | 550 |
| :---- | :------------------------------- |
| **Label** | Overview of buffer determination |
| **Tier** | -1 |
| **Section** | actuals-bufferActuals |
| **type** | string |

## bufferWorkbook
<a name="bufferWorkbook"></a>

| Id | 660 |
| :---- | :------------------------------- |
| **Label** | Buffer supporting documents |
| **Tier** | -1 |
| **Section** | actuals-bufferActuals |
| **type** | array |

# actuals-actuals
## partialActual
<a name="partialActual"></a>

| Id | 1016 |
| :---- | :------------------------------- |
| **Label** | Credit actuals by vintage |
| **Tier** | -1 |
| **Section** | actuals-actuals |
| **type** | object |
| **Options** | [object Object] |
| | [object Object] |
| | [object Object] |
| | [object Object] |

## actualsWorkbook
<a name="actualsWorkbook"></a>

| Id | 658 |
| :---- | :------------------------------- |
| **Label** | Project actuals supporting documents |
| **Tier** | -1 |
| **Section** | actuals-actuals |
| **type** | array |

# actuals-verification
## verificationBodySectoralScopes
<a name="verificationBodySectoralScopes"></a>

| Id | 1686 |
| :---- | :------------------------------- |
| **Label** | Accredited sectoral scopes of the verification body |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | array |
| **Options** |   1. Energy (renewable/non-renewable)  |
| | 2. Energy distribution |
| | 3. Energy demand   |
| |   4. Manufacturing industries |
| |   5. Chemical industry |
| | 6. Construction   |
| | 7. Transport |
| | 8. Mining/mineral production |
| |   9. Metal production |
| | 10. Fugitive emissions – from fuel |
| | 11. Fugitive emissions – from Industrial gases (halocarbons and sulphur hexafluoride) |
| | 12. Solvents use |
| | 13. Waste handling and disposal  |
| | 14. Agriculture, Forestry and Other Land Use (AFOLU) |
| | 15. Livestock and manure management |
| | 16. Carbon capture and storage |

## verificationBodySelection
<a name="verificationBodySelection"></a>

| Id | 1682 |
| :---- | :------------------------------- |
| **Label** | Verification body selection method |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | string |
| **Options** | Carbon standard or registry approved |
| | Third party approved (e.g., insurance company) |
| | Self-selected |
| | Other |

## verificationBodyTeamTable
<a name="verificationBodyTeamTable"></a>

| Id | 1695 |
| :---- | :------------------------------- |
| **Label** | Verification body team |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | object |

### Table structure
| Name | Role | Email | Involvement | 
| :---- | :---- | :---- | :---- |
| | | | |

## verificationSame
<a name="verificationSame"></a>

| Id | 1681 |
| :---- | :------------------------------- |
| **Label** | Verification body is the same as the validation body |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | boolean |

## verificationBodyAccreditationOther
<a name="verificationBodyAccreditationOther"></a>

| Id | 1685 |
| :---- | :------------------------------- |
| **Label** | Other verification body accreditation or membership |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | string |

## verificationBodyAccreditation
<a name="verificationBodyAccreditation"></a>

| Id | 1684 |
| :---- | :------------------------------- |
| **Label** | Verification body accreditation or membership |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | array |
| **Options** | ANSI National Accreditation Board (ANAB) |
| | International Accreditation Forum (IAF) |
| | Global Accreditation Bureau (GAB) |
| | UNFCCC / CDM |
| | Standards Council of Canada (SCC) |
| | Other |

## verification
<a name="verification"></a>

| Id | 525 |
| :---- | :------------------------------- |
| **Label** | Emission reductions and / or removals have been verified by a third-party |
| **Tier** | 2 |
| **Section** | actuals-verification |
| **type** | boolean |

## verificationBodySelectionOther
<a name="verificationBodySelectionOther"></a>

| Id | 1683 |
| :---- | :------------------------------- |
| **Label** | Other method of selecting verification body |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | string |

## verificationReportSummary
<a name="verificationReportSummary"></a>

| Id | 1687 |
| :---- | :------------------------------- |
| **Label** | Most recent verification report summary |
| **Tier** | 1 |
| **Section** | actuals-verification |
| **type** | string |

## verificationTable
<a name="verificationTable"></a>

| Id | 1345 |
| :---- | :------------------------------- |
| **Label** | Verification events and reporting periods |
| **Tier** | 2 |
| **Section** | actuals-verification |
| **type** | object |

### Table structure
| Reporting period start | Reporting period end | Verification date | Verification body | Emissions reductions (tCO2e) | Emissions removals (tCO2e) | 
| :---- | :---- | :---- | :---- | :---- | :---- |
| | | | | | |

## verificationResampling
<a name="verificationResampling"></a>Description of the activities conducted during the verification site visit (e.g., resampling of the carbon stock measurements)

| Id | 527 |
| :---- | :------------------------------- |
| **Label** | Verification field visit overview |
| **Tier** | -1 |
| **Section** | actuals-verification |
| **type** | string |

## verificationUpload
<a name="verificationUpload"></a>

| Id | 528 |
| :---- | :------------------------------- |
| **Label** | Verification documentation |
| **Tier** | -1 |
| **Section** | actuals-verification |
| **type** | array |

# actuals-creditSales
## creditsInventory
<a name="creditsInventory"></a>

| Id | 805 |
| :---- | :------------------------------- |
| **Label** | Carbon credit inventory by vintage |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | object |
| **Options** | [object Object] |
| | [object Object] |
| | [object Object] |
| | [object Object] |

## creditSalesStage
<a name="creditSalesStage"></a>Spot: A sale where carbon credits are exchanged and delivered immediately at the current market price.
Offtake Agreement: A long-term contract where a buyer agrees to purchase a specific volume of carbon credits over time, often before they are issued.
Forward: A contract where carbon credits are sold at an agreed-upon price for delivery at a future date.
Other: Any other type of carbon credit sale that doesn’t fit the standard definitions, such as custom agreements or hybrid structures.

| Id | 808 |
| :---- | :------------------------------- |
| **Label** | Credit sales type |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | number |
| **Options** | Spot |
| | Offtake agreement |
| | Forwards |
| | Other |

## carbonCreditBuyer
<a name="carbonCreditBuyer"></a>Buyers who have purchased carbon credits from this project

| Id | 809 |
| :---- | :------------------------------- |
| **Label** | Carbon credit buyers |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | string |

## creditSalesComments
<a name="creditSalesComments"></a>

| Id | 1641 |
| :---- | :------------------------------- |
| **Label** | Additional comments on credit sales |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | string |

## estimatedPriceMin
<a name="estimatedPriceMin"></a>Project proponent-generated estimated minimum price to sell one credit of tCO2e

| Id | 806 |
| :---- | :------------------------------- |
| **Label** | Estimated minimum price (USD) |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | number |

## estimatedPriceMax
<a name="estimatedPriceMax"></a>Project proponent-generated estimated maximum price to sell one credit of tCO2e

| Id | 807 |
| :---- | :------------------------------- |
| **Label** | Estimated maximum price (USD) |
| **Tier** | -1 |
| **Section** | actuals-creditSales |
| **type** | number |

# actuals-socioeconomicImpacts
## socioImpactSummary
<a name="socioImpactSummary"></a>A high-level overview of the socioeconomic impacts associated with the project activities

| Id | 1689 |
| :---- | :------------------------------- |
| **Label** | Summary of actual socioeconomic impacts due to project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## socioParentConditional
<a name="socioParentConditional"></a>

| Id | 1606 |
| :---- | :------------------------------- |
| **Label** | Socioeconomic impacts monitored by the project |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Involuntary displacement |
| | Stakeholder participation |
| | Workforce and capacity building |
| | Economic and benefit sharing |
| | Health and sanitation |

## engagementPolicy
<a name="engagementPolicy"></a>Indicates whether the project engages in policy advocacy to promote socio-environmental benefits (e.g., supporting conservation policies, improving workforce safety, etc.)

| Id | 1565 |
| :---- | :------------------------------- |
| **Label** | Project engages with local policy makers, community/tribal members, or other organizational groups to inform policy recommendations |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## engagementHours
<a name="engagementHours"></a>The total number of hours the project has spent engaging with the local community and other relevant stakeholders

| Id | 1559 |
| :---- | :------------------------------- |
| **Label** | Number of project administration hours spent in stakeholder consultations and engagement |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## engagementIndigenous
<a name="engagementIndigenous"></a>Project maintains ongoing engagement with identified groups beyond the initial consultation

| Id | 1564 |
| :---- | :------------------------------- |
| **Label** | Project continually consults and engages specifically with identified vulnerable social groups |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |
| **Options** | Yes |
| | No |
| | Not applicable |

## engagementChannels
<a name="engagementChannels"></a>Communication channels appropriate and accessible to the project area (e.g., WhatsApp, Viber, email, or text groups)

| Id | 1560 |
| :---- | :------------------------------- |
| **Label** | Project uses tailored communication channels to communicate relevant project news to stakeholders |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## stakeholderEngagementImpact
<a name="stakeholderEngagementImpact"></a>Community engagement is integrated into project operations (e.g., monthly focus groups, quarterly meetings, stakeholder listening sessions)

| Id | 43 |
| :---- | :------------------------------- |
| **Label** | Project demonstrates ongoing engagement with identified stakeholder throughout the project lifetime |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## engagementFrequency
<a name="engagementFrequency"></a>Indicates the frequency of stakeholder consultation or engagement

| Id | 1562 |
| :---- | :------------------------------- |
| **Label** | Frequency of stakeholder engagement meetings and consultations |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Weekly |
| | Monthly |
| | Quarterly |
| | Semi-annually |
| | Annually |
| | Sporadic frequency |

## engagementChannelsDetails
<a name="engagementChannelsDetails"></a>

| Id | 1561 |
| :---- | :------------------------------- |
| **Label** | Description of identified communication channels |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## stakeholderEngagementDetails
<a name="stakeholderEngagementDetails"></a>Details include items like processes implemented for ongoing communication, format, and frequency of engagements, etc.

| Id | 171 |
| :---- | :------------------------------- |
| **Label** | Overview of the project's engagement with stakeholders |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## stakeholderEngagementUpload
<a name="stakeholderEngagementUpload"></a>Supporting documentation outlining the project’s stakeholder engagement plan

| Id | 172 |
| :---- | :------------------------------- |
| **Label** | Stakeholder engagement plan supporting documents  |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## engagementNotes
<a name="engagementNotes"></a>Indicates whether the notes and records of stakeholder meetings are accessible to the public and community members

| Id | 1563 |
| :---- | :------------------------------- |
| **Label** | Stakeholder engagement session notes and outcomes are publicly available |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## grievanceReporting
<a name="grievanceReporting"></a>Indicates whether any grievances, complaints, or issues have been reported through the grievance mechanism

| Id | 1491 |
| :---- | :------------------------------- |
| **Label** | Grievances have been reported through the established grievance mechanism |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## grievanceMechanismPublic
<a name="grievanceMechanismPublic"></a>Grievance mechanism for submitted complaints is available and accessible to the public

| Id | 1492 |
| :---- | :------------------------------- |
| **Label** | Grievance reporting mechanism is publicly available |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## grievancesDescription
<a name="grievancesDescription"></a>Summary of grievances submitted and actions taken to address each issue

| Id | 1493 |
| :---- | :------------------------------- |
| **Label** | Grievances and resolution pathways reported to date |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderImpactUpload
<a name="genderImpactUpload"></a>Documents that demonstrate how gender-related data is collected, what indicators are used, and/or how the results are analyzed and reported

| Id | 1497 |
| :---- | :------------------------------- |
| **Label** | Gender performance impacts supporting documents |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## genderIndicatorSelection
<a name="genderIndicatorSelection"></a>Description of the frameworks and methodologies used to select the gender indicators against which impact is measured

| Id | 1496 |
| :---- | :------------------------------- |
| **Label** | Resources and tools used for gender performance indicator selection |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderIndicator
<a name="genderIndicator"></a>The project uses defined indicators to assess its gender-specific impacts

| Id | 1494 |
| :---- | :------------------------------- |
| **Label** | Project evaluates gender impacts against specific indicators |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## genderIndicatorsDetails
<a name="genderIndicatorsDetails"></a>Summary of the gender-related indicators tracked by the project (e.g., percentage of women in leadership roles, increase in women’s leisure time due to project activities)

| Id | 1495 |
| :---- | :------------------------------- |
| **Label** | Overview of gendered impact and indicators against which impact is measured |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderDataCollection
<a name="genderDataCollection"></a>Description of how data on gender-related indicators is gathered

| Id | 920 |
| :---- | :------------------------------- |
| **Label** | Gender impact data collection mechanisms |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Literature review |
| | Interviews |
| | Focus group discussions |
| | Surveys |
| | Community and social mappings |
| | Statistics available in databases |
| | Other |

## genderDataDetails
<a name="genderDataDetails"></a>High-level summary of how gender-related data will be collected, including methods such as private interviews or group discussions, timing, format, and how participants will be screened, sampled, and selected

| Id | 921 |
| :---- | :------------------------------- |
| **Label** | Overview of approaches for collecting gender impact data |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderHarassmentMeasures
<a name="genderHarassmentMeasures"></a>Actions the project has taken to safeguard against gender-based inequality, such as ensuring wage equity or improving women’s access to markets

| Id | 922 |
| :---- | :------------------------------- |
| **Label** | Measures taken to lessen harrassment or exploitation of women within the household and/or other project areas |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderConsultation
<a name="genderConsultation"></a>Description of how women affected by the project were consulted and how their concerns were addressed

| Id | 923 |
| :---- | :------------------------------- |
| **Label** | Gender-related concerns identified through consultation |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderPowerPositions
<a name="genderPowerPositions"></a>Female-identifying individuals in managerial or senior project roles

| Id | 924 |
| :---- | :------------------------------- |
| **Label** | Percentage of women that hold decision making powers or leadership roles within the project |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## genderSuccess
<a name="genderSuccess"></a>Project success is achieved when it meets or exceeds the W+ Standards requirements for one or more of six success indicators, which span these domains: Income and Assets; Time; Education and Knowledge; Leadership; Food Security; and Health. To demonstrate success, a project must clearly define the activities that have improved women’s lives and provide meaningful, quantifiable evidence of these positive outcomes.

| Id | 48 |
| :---- | :------------------------------- |
| **Label** | Women are central to the project's success |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## womenConsultation
<a name="womenConsultation"></a>Consultation may include one-on-one interviews, women-only focus groups, and/or additional field survey methods that enable separate consultation with women

| Id | 592 |
| :---- | :------------------------------- |
| **Label** | Project consults women separately on their perspectives and concerns |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## indigenousContractUpdates
<a name="indigenousContractUpdates"></a>Indicates whether any agreements between parties have been updated

| Id | 1556 |
| :---- | :------------------------------- |
| **Label** | Contract updates with local communities and/or Indigenous groups have occurred |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |
| **Options** | Yes |
| | No |
| | Not applicable |

## indigenousContractDate
<a name="indigenousContractDate"></a>Date of most recent contractual update

| Id | 1557 |
| :---- | :------------------------------- |
| **Label** | Date of the latest contract with community or government stakeholders |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## indigenousContractDetails
<a name="indigenousContractDetails"></a>Summary of additional information (e.g., penalty clauses) in the contracts with Indigenous, tribal, and local communities

| Id | 1558 |
| :---- | :------------------------------- |
| **Label** | Description of updated contracts with Indigenous, tribal, and local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## dataInfringementIndigenous
<a name="dataInfringementIndigenous"></a>In accordance with UNDRIP principles, affirming Indigenous Peoples’ rights to access and control data about their communities, territories, cultures, and resources

| Id | 188 |
| :---- | :------------------------------- |
| **Label** | Data collection respects privacy rights of Indigenous peoples and local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## dataInfringementIndigenousDetails
<a name="dataInfringementIndigenousDetails"></a>Overview of how data privacy considerations have been integrated into project engagements and operation

| Id | 609 |
| :---- | :------------------------------- |
| **Label** | Description of privacy protection measures for Indigenous peoples and local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## householdsResettled
<a name="householdsResettled"></a>

| Id | 1486 |
| :---- | :------------------------------- |
| **Label** | Number of households involuntarily resettled due to project activities |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## resettlementOutcome
<a name="resettlementOutcome"></a>This includes both economic displacement, which encompasses the loss of land, access to assets, income sources, or means of livelihoods, and physical displacement, encompassing the result of eviction, acquisition, rehabilitation, or demolition of property, or the expiration of covenants housing. These activities can be due to involuntary acquisition / restrictions on land use or limiting access to legally designated parks and protected areas.

| Id | 36 |
| :---- | :------------------------------- |
| **Label** | Project activities have resulted in involuntary displacement |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## resettlementProjectFunds
<a name="resettlementProjectFunds"></a>Funds allocated for household resettlement due to project activities

| Id | 1487 |
| :---- | :------------------------------- |
| **Label** | Funds allocated to support the resettlement of affected community members |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## resettlementShelterProvision
<a name="resettlementShelterProvision"></a>Indication that resources like job placements and project housing have been offered to support resettlement assistance

| Id | 1488 |
| :---- | :------------------------------- |
| **Label** | Project has made efforts to provide shelter, safety, and economic opportunities for affected persons |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## resettlementCauses
<a name="resettlementCauses"></a>Activities causing resettlement (e.g., protected areas restricting access, land use limitations)

| Id | 1489 |
| :---- | :------------------------------- |
| **Label** | Activities leading to involuntary resettlement and internally displaced persons (IDP) status |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## resettlementAssistanceDetails
<a name="resettlementAssistanceDetails"></a>Overview of actions taken to provide necessary resettlement assistance

| Id | 1490 |
| :---- | :------------------------------- |
| **Label** | Overview of project resettlement assistance |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## wageRateProject
<a name="wageRateProject"></a>

| Id | 1554 |
| :---- | :------------------------------- |
| **Label** | Median wage rate for individuals employed as part of project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentImpact
<a name="employmentImpact"></a>This can include positions within habitat/nature restoration, technical assistance, logistics, maintenance, and/or other roles which contribute to project activities

| Id | 1542 |
| :---- | :------------------------------- |
| **Label** | Project has created employment opportunities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## wageRateProjectDetails
<a name="wageRateProjectDetails"></a>

| Id | 1555 |
| :---- | :------------------------------- |
| **Label** | Overview of project wages |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## wageRateRegionUpload
<a name="wageRateRegionUpload"></a>Median wage rate in the project area (i.e., area defined as regions within 20km of project boundary)

| Id | 1553 |
| :---- | :------------------------------- |
| **Label** | Median wage rate supporting documents |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## wageRateRegion
<a name="wageRateRegion"></a>Median wage rate in the project area (i.e., area defined as regions within 20km of project boundary)

| Id | 1552 |
| :---- | :------------------------------- |
| **Label** | Median wage rate in the area in which the project is being developed |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentPositionsWomen
<a name="employmentPositionsWomen"></a>The total number of roles created by the project that are currently held by women

| Id | 1550 |
| :---- | :------------------------------- |
| **Label** | Number of positions generated occupied by women |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentPositionsIndigenous
<a name="employmentPositionsIndigenous"></a>Positions held by members of identified vulnerable community groups or Indigenous peoples

| Id | 1551 |
| :---- | :------------------------------- |
| **Label** | Number of project positions held by Indigenous or community stakeholders |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## employmentAge
<a name="employmentAge"></a>Average age ranges of people employed by the project

| Id | 1549 |
| :---- | :------------------------------- |
| **Label** | Average age range of project employees |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | 15-18 |
| | 18-25 |
| | 25-35 |
| | 35-45 |
| | 45-55 |
| | 55+ |

## employmentDetails
<a name="employmentDetails"></a>Summary of job opportunities created through the project

| Id | 1543 |
| :---- | :------------------------------- |
| **Label** | Overview of employment opportunities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentFullNumber
<a name="employmentFullNumber"></a>As the average for OPEC and EU work weeks, full time defined at 36 + hours per week, for at least one year. This is not a contractor employment status.

| Id | 1544 |
| :---- | :------------------------------- |
| **Label** | Number of full-time job opportunities created through project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentPartTimeNumber
<a name="employmentPartTimeNumber"></a>ILO defines part-time work for statistical purposes as any paid job providing less than 35 hours per week. This includes contractor positions and "on-call work".

| Id | 1545 |
| :---- | :------------------------------- |
| **Label** | Number of part-time job opportunities created through project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentInternshipNumber
<a name="employmentInternshipNumber"></a>Apprenticeships and internships defined as unpaid, or compensated by academic credit, learning opportunities to build skillsets that contribute to future employment opportunities

| Id | 1546 |
| :---- | :------------------------------- |
| **Label** | Number of apprenticeships or internship opportunities created through project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## employmentPolicies
<a name="employmentPolicies"></a>For example, if employment not only follows local laws and regulations, but has adidtional protocols or hiring screening criteria to promote equity

| Id | 1547 |
| :---- | :------------------------------- |
| **Label** | Formal policies exist within project employment opportunities to prevent and mitigate harassment |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## employmentPoliciesUpload
<a name="employmentPoliciesUpload"></a>

| Id | 1548 |
| :---- | :------------------------------- |
| **Label** | Employment policies documentation |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## educationImpact
<a name="educationImpact"></a>Opportunities such as educational webinars, on-site training on implementing project technologies or practices, and skill-sharing sessions, etc.

| Id | 1530 |
| :---- | :------------------------------- |
| **Label** | Project has created additional opportunities for education or skills-building |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## educationQuantification
<a name="educationQuantification"></a>Examples include improvements in school infrastructure, classes or training sessions hosted by the project, maintenance and operation of project materials, and the development of citizen science skills

| Id | 1531 |
| :---- | :------------------------------- |
| **Label** | Number of people with increased access to education or new skills due to project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## educationTeachingHours
<a name="educationTeachingHours"></a>Examples include webinars, on-site training on implementing project technologies or practices, and skill-sharing sessions

| Id | 1532 |
| :---- | :------------------------------- |
| **Label** | Number of hours spent teaching or providing training to community members and project partners since project inception |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## educationTrainingSessions
<a name="educationTrainingSessions"></a>

| Id | 1533 |
| :---- | :------------------------------- |
| **Label** | Overview of training sessions for community members focused on knowledge and skill transfer |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## educationTrainingChildren
<a name="educationTrainingChildren"></a>Examples include outreach to schools, organizing school visits to the project site, or collaborating on the development of environmentally-conscious curriculum

| Id | 1534 |
| :---- | :------------------------------- |
| **Label** | Engagement activities for local children to explore project resources, opportunities, and environmental benefits |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## educationSessionCadence
<a name="educationSessionCadence"></a>

| Id | 1535 |
| :---- | :------------------------------- |
| **Label** | Cadence of training sessions, workshops, or capacity building events |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |
| **Options** | Daily |
| | Weekly |
| | Monthly |
| | Quarterly |
| | Semi-annually |
| | Annually |

## educationScholarship
<a name="educationScholarship"></a>

| Id | 1536 |
| :---- | :------------------------------- |
| **Label** | Number of scholarships created through project activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## monetaryBenefitConditional
<a name="monetaryBenefitConditional"></a>Monetary benefit sharing refers to the distribution of financial gains from carbon credit revenues or related project income to local stakeholders who contribute to or are affected by the project

| Id | 1632 |
| :---- | :------------------------------- |
| **Label** | Project engages in monetary benefit sharing |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## monetaryBenefitSecondary
<a name="monetaryBenefitSecondary"></a>In the case a credit's primary sale is to a broker, trader, or investor, this field indicates whether there is a benefit sharing during the second point of sale — when the broker, investor, or trader sells to another party

| Id | 1539 |
| :---- | :------------------------------- |
| **Label** | Project provides financial benefit sharing at secondary sale |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## percentOwnedIndigenous
<a name="percentOwnedIndigenous"></a>Percent of project owned—with decision-making power—by Indigenous, tribal, or local communities

| Id | 1541 |
| :---- | :------------------------------- |
| **Label** | Percent of project owned by Indigenous, tribal, and/or local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## monetaryBenefitPrimary
<a name="monetaryBenefitPrimary"></a>When sold to a broker or organization, the project provides a financial benefit share when the project sells a credit directly from the PD to a second party

| Id | 1538 |
| :---- | :------------------------------- |
| **Label** | Project provides financial benefit sharing at primary sale |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## monetaryBenefitType
<a name="monetaryBenefitType"></a>Monetary payment types adapted from definitions within the UN Nagoya Protocol

| Id | 1537 |
| :---- | :------------------------------- |
| **Label** | Types of monetary benefits shared |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Fees/fee per credit sold or otherwise acquired |
| | Up-front payments |
| | Milestone payments |
| | Payment of royalties |
| | Licence fees in case of commercialization |
| | Research funding |
| | Establishment and contributions to a community fund |
| | Other |

## paymentPercentIndigenous
<a name="paymentPercentIndigenous"></a>How much indigenous, tribal, and/or local communities recieve from the sale of a carbon credit that has been generated

| Id | 1540 |
| :---- | :------------------------------- |
| **Label** | Percent of sale price going to Indigenous, tribal, and/or local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## revenueShare
<a name="revenueShare"></a>Differentiates whether communities recieve a percentage of profits or revenues of the project per benefit sharing agreements

| Id | 596 |
| :---- | :------------------------------- |
| **Label** | Monetary benefit-sharing incorporates profit or revenue distribution |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Profit |
| | Revenue |
| | Unknown |

## payementsMade
<a name="payementsMade"></a>Total monetary amount distributed, including unit of currency (e.g., X USD, X yen, X pesos), as part of benefit sharing with communities

| Id | 195 |
| :---- | :------------------------------- |
| **Label** | Benefit sharing financial payments made to date |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## paymentsMethod
<a name="paymentsMethod"></a>Mechanism through which the project provides monetary benefits to relevant stakeholders (e.g., direct payments, community funds, revenue sharing)

| Id | 196 |
| :---- | :------------------------------- |
| **Label** | Payment method |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Cash |
| | Mobile Banking |
| | Digital Wallets |
| | Alternative Banking |
| | Combination |
| | Other |

## fairTradePricing
<a name="fairTradePricing"></a>As outlined by FCC price methodology https://files.fairtrade.net/standards/FCC_price_methodology.pdf

| Id | 193 |
| :---- | :------------------------------- |
| **Label** | Project engages in fairtrade pricing |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## smartContracts
<a name="smartContracts"></a>A smart contract is a digital agreement that is signed and stored on a blockchain network, which executes automatically when the contract's terms and conditions are met

| Id | 197 |
| :---- | :------------------------------- |
| **Label** | Transaction is enabled by smart contracts |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## socialGroupBenefitSharing
<a name="socialGroupBenefitSharing"></a>Details on how much money is reaching vulnerable groups, which groups/communities the payments are reaching, and how money is being used (if information is available)

| Id | 173 |
| :---- | :------------------------------- |
| **Label** | Financial benefit sharing impact on women, Indigenous, Tribal and/or other minority groups |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## socialGroupBenefitSharingUpload
<a name="socialGroupBenefitSharingUpload"></a>

| Id | 174 |
| :---- | :------------------------------- |
| **Label** | Financial benefit sharing documentation |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## paymentsFrequencyIndigenous
<a name="paymentsFrequencyIndigenous"></a>Frequency of monetary payments made to Indigenous, tribal, and local communities (e.g., monthly, annually, per verification cycle)

| Id | 191 |
| :---- | :------------------------------- |
| **Label** | Frequency of payments to Indigenous, tribal, and/or local communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |
| **Options** | Weekly |
| | Monthly |
| | Quarterly |
| | Semi-annually |
| | Annually |
| | Continuous |
| | Not applicable |

## benefitOther
<a name="benefitOther"></a>Examples of non-financial benefits can include the sharing of products or goods, technology transfer, and/or local infrastructure improvements

| Id | 1526 |
| :---- | :------------------------------- |
| **Label** | The project engages in benefit sharing aside from financial payments |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## benefitOtherActivity
<a name="benefitOtherActivity"></a>Non-monetary payment types adapted from definitions within the UN Nagoya Protocol

| Id | 1527 |
| :---- | :------------------------------- |
| **Label** | Non-monetary benefits implemented by the project activity |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Tax abatements |
| | Sharing of research and development results |
| | Scientific collaboration and or joint publication |
| | Development of citizen science skills |
| | Institutional and professional relationships |
| | Organic material transfer (eg; Biochar, compost) |
| | Language skill development |
| | Local infrastructure improvements |
| | Technology transfer  |
| | Other |

## benefitOtherDetails
<a name="benefitOtherDetails"></a>High-level summary of benefits shared that are not provided as an exchange of money

| Id | 1528 |
| :---- | :------------------------------- |
| **Label** | Description of non-monetary benefit sharing activities  |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## benefitOtherUpload
<a name="benefitOtherUpload"></a>Evidence of agreement, model, and/or distribution of non-monetary benefits

| Id | 1529 |
| :---- | :------------------------------- |
| **Label** | Non-monetary benefit sharing supporting documents |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## localEconomyImprovement
<a name="localEconomyImprovement"></a>Specific activity or sector-based economies have long-term benefits as a result of project activities (i.e., fisheries industry, tourism industry)

| Id | 1498 |
| :---- | :------------------------------- |
| **Label** | Local economies have benefitted and improved in the project area |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## localEconomyDetails
<a name="localEconomyDetails"></a>Summary of the economic benefits provided by the project and details on how such benefits were measured or evaluated

| Id | 1499 |
| :---- | :------------------------------- |
| **Label** | Summary of economic benefits |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## localEconomyUpload
<a name="localEconomyUpload"></a>

| Id | 1500 |
| :---- | :------------------------------- |
| **Label** | Economic benefits supporting documents |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## povertyReduction
<a name="povertyReduction"></a>Indicates additional poverty reduction measures beyond monetary benefit sharing (expansion of safety net programs, providing microfinance loans, etc)

| Id | 1501 |
| :---- | :------------------------------- |
| **Label** | Project works to reduce poverty beyond benefit sharing   |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## povertyReductionTypes
<a name="povertyReductionTypes"></a>

| Id | 1502 |
| :---- | :------------------------------- |
| **Label** | Activities undertaken for poverty reduction initiatives |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Skill building sessions |
| | Virtual learning resources |
| | Physical learning resources (pamphlets, courses) |
| | Policy engagement |
| | Food assistance |
| | Tax credits |
| | Housing assistance |
| | Increased energy access |
| | Other |

## povertyReductionDetails
<a name="povertyReductionDetails"></a>Overview of the approach taken towards poverty reduction

| Id | 1503 |
| :---- | :------------------------------- |
| **Label** | Overview of the poverty reduction activities implemented |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## povertyReductionQuantification
<a name="povertyReductionQuantification"></a>Number of people that were the focus of engagement sessions, tax abatements, housing assistance, etc. 

| Id | 1504 |
| :---- | :------------------------------- |
| **Label** | Number of people impacted by poverty reduction initiatives |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## housingImpact
<a name="housingImpact"></a>This can include housing with energy efficiency (EE) upgrades such as low-flow water devices (including shower heads and bathroom or kitchen aerators); LED lighting; smart thermostats; and high-efficiency heating, ventilation, and air conditioning (HVAC) systems; as well as photovoltaic (PV) solar installations. Safety measures can include examples such as carbon monoxide monitors or smoke alarms.

| Id | 1505 |
| :---- | :------------------------------- |
| **Label** | Project engages in work to assist in the creation of safer, healthier, and more affordable homes |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## housingRetro
<a name="housingRetro"></a>Outside of the main project activities, the number of homes using more energy efficient measures within the project area due to project investment or programs

| Id | 1506 |
| :---- | :------------------------------- |
| **Label** | Number of units retrofitted with measures to create safer, healthier, or more affordable homes |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## housingEnergyNumber
<a name="housingEnergyNumber"></a>The number of community members benefitting from additional or retrofitted housing

| Id | 1508 |
| :---- | :------------------------------- |
| **Label** | Number of people with increased access to energy-efficicent housing |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## housingEnergy
<a name="housingEnergy"></a>Outside of the main project activities, project has built or contributed investment towards energy efficient homes in the project community

| Id | 1507 |
| :---- | :------------------------------- |
| **Label** | Project has created units of energy efficient housing within the area of operation |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## housingDetails
<a name="housingDetails"></a>Summary of measures taken to provide energy efficient housing

| Id | 1509 |
| :---- | :------------------------------- |
| **Label** | Measures taken to increase safe, reliable, and/or energy efficient housing  |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## tourismQuantification
<a name="tourismQuantification"></a>Number of guests or tourists who have attended or completed activities offered (e.g., facility tours, voluntourism programs, educational open farm days, etc)

| Id | 1513 |
| :---- | :------------------------------- |
| **Label** | Number of visitors that have interacted with project leisure initiatives |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | number |

## tourismActivity
<a name="tourismActivity"></a>

| Id | 1511 |
| :---- | :------------------------------- |
| **Label** | Types of leisure / tourism activities offered through the project |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Language classes |
| | Cultural showcases/classes |
| | General tours |
| | Organizational visits |
| | Craft fairs/events |
| | Food/beverage experiences |
| | Voluntourism opportunities |
| | Other |

## tourismImpact
<a name="tourismImpact"></a>Includes activities such as facility tours, voluntourism opportunities, agritourism, cultural shows, cooking classes/demonstrations, etc

| Id | 1510 |
| :---- | :------------------------------- |
| **Label** | Project engages in leisure or tourism activities to increase project awareness |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## tourismDetails
<a name="tourismDetails"></a>Summary of programs or activities offered to increase tourism opportunities for the project

| Id | 1512 |
| :---- | :------------------------------- |
| **Label** | Description of measures taken to increase tourism in the region |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## healthOutcomeQuantified
<a name="healthOutcomeQuantified"></a>Quantifiable metrics assessed and measured concerning health access and outcomes (i.e., the number of people reached through health training programs, the  number of health facilities updated since start of project activities, etc.)

| Id | 1516 |
| :---- | :------------------------------- |
| **Label** | Quantifiable project impact on health access and outcomes |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## healthOutcomeImpacts
<a name="healthOutcomeImpacts"></a>Examples of this can include providing health facilities, funding new machinery or health technology, providing health trainings as it relates to project materials (e.g. pesticide handling, stove use), or taking measures to protect or amplify native medinal knowledge.

| Id | 1514 |
| :---- | :------------------------------- |
| **Label** | Project undertakes initiatives to enhance health outcomes or mitigate adverse impacts within the project region |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## healthRiskIncrease
<a name="healthRiskIncrease"></a>

| Id | 1519 |
| :---- | :------------------------------- |
| **Label** | Project activities may increase the following health risks |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Air pollution |
| | Water pollution |
| | Chemical exposure |
| | Radiation |
| | Occupational hazards |
| | Infectious disease |
| | Other |
| | Not applicable |

## healthRiskReduction
<a name="healthRiskReduction"></a>

| Id | 1518 |
| :---- | :------------------------------- |
| **Label** | Project activities reduce the following health risks |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Air pollution |
| | Water pollution |
| | Chemical exposure |
| | Radiation |
| | Occupational hazards |
| | Infectious disease |
| | Other |
| | Not applicable |

## healthOutcomeUpload
<a name="healthOutcomeUpload"></a>

| Id | 1517 |
| :---- | :------------------------------- |
| **Label** | Health initiative impacts documentation |
| **Tier** | -1 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## healthOutcomeDetails
<a name="healthOutcomeDetails"></a>Overview of strategies and actions implemented to mitigate community health risks

| Id | 1515 |
| :---- | :------------------------------- |
| **Label** | Description of the initiatives undertaken to increase health in the operational region |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## healthOutcomePlan
<a name="healthOutcomePlan"></a>Overview of any measures or plans in place to mitigate risks to community health within the project boundary

| Id | 1520 |
| :---- | :------------------------------- |
| **Label** | Description of health risk monitoring and remediation plans |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## sanitationUpload
<a name="sanitationUpload"></a>Documents supporting sanitation intiatives and/or impacts

| Id | 1525 |
| :---- | :------------------------------- |
| **Label** | Sanitation-related activities and impacts supporting documents |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |

## sanitationDetails
<a name="sanitationDetails"></a>Overview of programs, initiatives, and strategies implemented to improve sanitation access and outcomes

| Id | 1523 |
| :---- | :------------------------------- |
| **Label** | Description of sanitation activities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## sanitationImpact
<a name="sanitationImpact"></a>Examples include initiatives which help build waste management capacity, increase ease and access to potable water, and any type of sewage or wastewater treatment within the project area

| Id | 1521 |
| :---- | :------------------------------- |
| **Label** | Project engages in activities to increase sanitation accessibility and outcomes |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | boolean |

## sanitationQuantification
<a name="sanitationQuantification"></a>Description of the project’s impact on sanitation-related access and outcomes (e.g., number of households gaining reliable potable water access, increased waste management facility capacity within the project area, etc.)

| Id | 1524 |
| :---- | :------------------------------- |
| **Label** | Quantifiable project impacts on sanitation processes and access |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | string |

## sanitationActivity
<a name="sanitationActivity"></a>Types of activities taken to increase sanitation accessibility, outcomes, and awareness

| Id | 1522 |
| :---- | :------------------------------- |
| **Label** | Sanitation activities undertaken within project areas and/or surrounding communities |
| **Tier** | 2 |
| **Section** | actuals-socioeconomicImpacts |
| **type** | array |
| **Options** | Waste management facilities (landfills, recycling centers, in-home composters) |
| | Potable water access |
| | Sewage infrastrusture |
| | Wastewater treatment |
| | Other |

# actuals-ecologicalImpacts
## ecoParentConditional
<a name="ecoParentConditional"></a>

| Id | 1567 |
| :---- | :------------------------------- |
| **Label** | Ecological impacts monitored by the project |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Air quality |
| | Water quality |
| | Water availability |
| | Biodiversity |
| | Soil quality |
| | Marine and coastal health |
| | Noise pollution |
| | Infrastructure development |

## ecoImpactsSummary
<a name="ecoImpactsSummary"></a>

| Id | 1688 |
| :---- | :------------------------------- |
| **Label** | Summary of actual ecological impacts due to project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airQualityModeling
<a name="airQualityModeling"></a>Overview of the methodology used to model air quality and synthesize resulting impact assessments

| Id | 1569 |
| :---- | :------------------------------- |
| **Label** | Overview of the approach used to model and estimate air quality effects |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## communityAirRisk
<a name="communityAirRisk"></a>Indicates whether project activities increase exposure to harmful air pollutants

| Id | 1570 |
| :---- | :------------------------------- |
| **Label** | Community members near the project site face increased risk of air pollutant exposure |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## airMonitoringPollutants
<a name="airMonitoringPollutants"></a>Pollutants that are monitored as part of the project activity

| Id | 179 |
| :---- | :------------------------------- |
| **Label** | Project pollutants monitored |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Ozone |
| | VOCs |
| | NOx |
| | Pollen |
| | PM2.5 |
| | PM10 |
| | Carbon Monoxide (CO) |
| | Polycyclic aromatic hydrocarbons (PAHs) |
| | Other |

## airImpactsSummary
<a name="airImpactsSummary"></a>Assessment of cumulative air quality impacts attributable to project-related activities

| Id | 1573 |
| :---- | :------------------------------- |
| **Label** | Summary of quantifiable project air quality impacts |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airHealthRisks
<a name="airHealthRisks"></a>Detailed assessment of health risks associated with exposure to air pollutants resulting from project activities, including any documented or observed impacts on affected populations

| Id | 1571 |
| :---- | :------------------------------- |
| **Label** | Assessment of health risks from air pollutant exposure linked to project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airMonitoringOther
<a name="airMonitoringOther"></a>Additional pollutants monitored beyond those previously specified

| Id | 180 |
| :---- | :------------------------------- |
| **Label** | Other pollutant(s) monitored |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airMonitoringStatus
<a name="airMonitoringStatus"></a>

| Id | 1568 |
| :---- | :------------------------------- |
| **Label** | Air quality monitoring status and approach |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | Project does not currently monitor and record air pollution |
| | Project models and estimates air quality impacts |
| | Project monitors air pollution and has specific reduction targets |
| | Project monitors air pollution and has met specific reduction targets during the last year of operations |
| | Project monitors and records air pollution (no reduction targets) |
| | Project has eliminated hazardous and toxic air pollutants from project activities entirely |
| | Not applicable |

## airPollutionMonitoring
<a name="airPollutionMonitoring"></a>The air pollution monitoring plan may consider indoor air quality, ambient air quality, or human pollutant exposure

| Id | 931 |
| :---- | :------------------------------- |
| **Label** | Project follows an air pollution monitoring plan which considers the following |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Indoor air quality |
| | Ambient air quality  |
| | Human exposure to pollutants |
| | Other |
| | None |

## airMonitoringBaselineFrequency
<a name="airMonitoringBaselineFrequency"></a>Details on how frequently the project will monitor relevant air pollutants

| Id | 181 |
| :---- | :------------------------------- |
| **Label** | Monitoring frequency of pollutants |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airMonitoringMechanism
<a name="airMonitoringMechanism"></a>Overview of the approach taken to monitor pollutants

| Id | 932 |
| :---- | :------------------------------- |
| **Label** | Pollutant monitoring mechanisms |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## exposureMonitoringMechanism
<a name="exposureMonitoringMechanism"></a>

| Id | 933 |
| :---- | :------------------------------- |
| **Label** | Human exposure monitoring mechanism |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## airDetails
<a name="airDetails"></a>Indicates if project activities reduce outdoor air pollution compared to the baseline scenario

| Id | 53 |
| :---- | :------------------------------- |
| **Label** | Project activities reduce ambient air pollution |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## indoorAirDetails
<a name="indoorAirDetails"></a>Indicates if project activities reduce indoor air pollution compared to the baseline scenario

| Id | 918 |
| :---- | :------------------------------- |
| **Label** | Project activities reduce indoor air pollution |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## airEvidence
<a name="airEvidence"></a>Documentation supporting the quantification or attribution of ambient air impacts, such as field test reports, manufacturer certifications, laboratory analyses, and similar evidence

| Id | 663 |
| :---- | :------------------------------- |
| **Label** | Ambient air pollution impacts documentation |
| **Tier** | 3 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## indoorAirEvidence
<a name="indoorAirEvidence"></a>Documentation supporting the quantification or attribution of indoor air impacts, including field test reports, manufacturer certifications, laboratory analyses, and related evidence

| Id | 934 |
| :---- | :------------------------------- |
| **Label** | Indoor air pollution impacts documentation |
| **Tier** | 3 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## airVerification
<a name="airVerification"></a>Claimed impacts are supported by third-party verification, validation, or accreditation

| Id | 935 |
| :---- | :------------------------------- |
| **Label** | Ambient and/or indoor air impacts claimed are third-party verified |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## airVerificationBody
<a name="airVerificationBody"></a>The third-party verifier of reported ambient and indoor air impacts

| Id | 936 |
| :---- | :------------------------------- |
| **Label** | Verification body for claimed ambient and indoor air impacts |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## habitatFragmentation
<a name="habitatFragmentation"></a>Habitat fragmentation refers to the process of fragmenting large, continuous habitats into smaller, isolated patches, typically caused by human activities such as infrastructure development, construction, roads, or agriculture

| Id | 1602 |
| :---- | :------------------------------- |
| **Label** | Project activities have led to species' habitat fragmentation |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## biodiversityHabitatExtension
<a name="biodiversityHabitatExtension"></a>Overview of species experiencing habitat expansion and additional ecological benefits resulting from project activities

| Id | 1601 |
| :---- | :------------------------------- |
| **Label** | Overview of species with expanded habitats and benefits from project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## habitatFragmentationDetails
<a name="habitatFragmentationDetails"></a>Overview of species experiencing habitat fragmentation within the project area

| Id | 1603 |
| :---- | :------------------------------- |
| **Label** | Overview of species experiencing habitat fragmentation |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## biodiversitySurveyDate
<a name="biodiversitySurveyDate"></a>

| Id | 1618 |
| :---- | :------------------------------- |
| **Label** | Date of most recent biodiversity survey |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## biodiversitySpeciesHabitat
<a name="biodiversitySpeciesHabitat"></a>Overall habitat for species monitored by the project has increased due to project activities (i.e.,  conservation activities, marine protected areas, etc)

| Id | 1600 |
| :---- | :------------------------------- |
| **Label** | Species habitats identified in baseline surveys have expanded due to project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## biodiversityEvidence
<a name="biodiversityEvidence"></a>Documentation related to the project's ecological or biodiversity impacts, monitoring plans or reports, permits, registry-specific assessments (e.g., the ACR Environmental and Social Impact Assessment Report template)

| Id | 664 |
| :---- | :------------------------------- |
| **Label** | Ecological and biodiversity impacts documentation |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## biodiversityImpactsTimeline
<a name="biodiversityImpactsTimeline"></a>Frequency of biodiversity impact data collection, analysis, and documentation

| Id | 207 |
| :---- | :------------------------------- |
| **Label** | Reporting timeline of biodiversity impacts |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## biodiversityInvasive
<a name="biodiversityInvasive"></a>Interventions such as invasive species removal efforts designed to support the restoration and ecological balance of native ecosystems

| Id | 1604 |
| :---- | :------------------------------- |
| **Label** | Project has engaged in efforts to control invasive species within project boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## biodiversityInvasiveMitigation
<a name="biodiversityInvasiveMitigation"></a>

| Id | 1605 |
| :---- | :------------------------------- |
| **Label** | Implemented measures for invasive species control |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## biodiversitySpeciesNumber
<a name="biodiversitySpeciesNumber"></a>

| Id | 1599 |
| :---- | :------------------------------- |
| **Label** | Number of species (flora and fauna) within project boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## threatenedSpeciesNumber
<a name="threatenedSpeciesNumber"></a>

| Id | 1617 |
| :---- | :------------------------------- |
| **Label** | Number of identified species which are categorized as IUCN threatened and endangered species |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## biodiversitySpeciesApproach
<a name="biodiversitySpeciesApproach"></a>How the project will collect data on threatened/endangered species

| Id | 142 |
| :---- | :------------------------------- |
| **Label** | Species tracking and monitoring approach |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## speciesSelected
<a name="speciesSelected"></a>The type of species selected for monitoring, including but not limited to sentinel species, rare species, endangered species, umbrella species, keystone species, endemic species, etc.

| Id | 200 |
| :---- | :------------------------------- |
| **Label** | Species selected for tracking and monitoring |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Sentinel species |
| | Rare species |
| | Endangered species |
| | Umbrella species |
| | Trafficked species |
| | Keystone species |
| | Emblematic species |
| | Endemic species |
| | Other |

## speciesTrackingConditional
<a name="speciesTrackingConditional"></a>Project directly tracks and monitors flora or fauna species as part of the project activity

| Id | 674 |
| :---- | :------------------------------- |
| **Label** | Project tracks and monitors species within the project area (flora or fauna) |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## speciesMonitoringFrequency
<a name="speciesMonitoringFrequency"></a>

| Id | 202 |
| :---- | :------------------------------- |
| **Label** | Species monitoring frequency |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | Weekly |
| | Monthly |
| | Quarterly |
| | Semi-annually |
| | Annually |
| | Continuous |

## specieisSamplingDensity
<a name="specieisSamplingDensity"></a>Percentage of area sampled per hectare

| Id | 203 |
| :---- | :------------------------------- |
| **Label** | Sampling density (per hectare) |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | 10% |
| | 20% |
| | 30% |
| | 40% |
| | 50% |
| | 60% |
| | 70% |
| | 80% |
| | 90% |
| | 100% |

## speciesCollectionMethod
<a name="speciesCollectionMethod"></a>

| Id | 204 |
| :---- | :------------------------------- |
| **Label** | Species diversity data collection method(s) |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Cell phones |
| | Audio recording |
| | Camera trap |
| | Selectively tagged animals |
| | Other  |

## speciesCollectionAudit
<a name="speciesCollectionAudit"></a>All biodiversity monitoring is conducted through virtual methods (e.g., citizen science apps, photo recognition tools, GPS tracking) and is auditable through digital records rather than paper documentation or verbal accounts

| Id | 205 |
| :---- | :------------------------------- |
| **Label** | Species diversity data is digital and can be audited |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## specieisCollectionMethodDetails
<a name="specieisCollectionMethodDetails"></a>Details on the technique and/or platform used for species identifcation (e.g., eDNA), data cataloguing, and collection

| Id | 206 |
| :---- | :------------------------------- |
| **Label** | Overview of species identification and data collection methods |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## speciesSelectedOther
<a name="speciesSelectedOther"></a>Description of other species monitored, such as indicator species

| Id | 201 |
| :---- | :------------------------------- |
| **Label** | Other species and related monitoring indicators |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## soilQualityImpacts
<a name="soilQualityImpacts"></a>Category of soil quality improvement

| Id | 1597 |
| :---- | :------------------------------- |
| **Label** | Soil quality improvements due to project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Increased soil organic matter |
| | Increased infiltration rates |
| | Increased aggregate soil stability |
| | Increased soil cation exchange capacity (CEC)  |
| | Decreased soil compaction |
| | Other |

## soilPractice
<a name="soilPractice"></a>Examples include cover crops, contour buffer strips, rotational planting, rotational grazing, fallow periods, reduced tillage, no tillage, companion planting, native plant use, soil fertilizers etc.

| Id | 1595 |
| :---- | :------------------------------- |
| **Label** | Practices implemented to enhance soil health |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Cover crops |
| | Contour buffer strips |
| | Rotational planting |
| | Rotational grazing |
| | Fallow periods |
| | Reduced tillage |
| | No tillage |
| | Companion planting |
| | Native plant use |
| | Integrated pest management plan |
| | Strong root system establishment |
| | Soil fertilizers |
| | Other |

## soilTesting
<a name="soilTesting"></a>

| Id | 1593 |
| :---- | :------------------------------- |
| **Label** | Soil testing is done on a consistent basis |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## soilSamplingFrequency
<a name="soilSamplingFrequency"></a>

| Id | 1594 |
| :---- | :------------------------------- |
| **Label** | Soil sampling frequency |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | Weekly |
| | Monthly |
| | Quarterly |
| | Semi-annually |
| | Annually |

## soilHealthEvidence
<a name="soilHealthEvidence"></a>Supporting documentation for claimed soil health impacts

| Id | 1598 |
| :---- | :------------------------------- |
| **Label** | Soil health indicators and impacts supporting documents |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## soilPracticeDetails
<a name="soilPracticeDetails"></a>Summary of practices contributing to improved soil health

| Id | 1596 |
| :---- | :------------------------------- |
| **Label** | Overview of practices used to increase soil health |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterQualityPracticesDetails
<a name="waterQualityPracticesDetails"></a>Overview of water treatment and testing protocols and approaches

| Id | 1612 |
| :---- | :------------------------------- |
| **Label** | Description of water treatment or quality safeguarding practices |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterQualityMonitoring
<a name="waterQualityMonitoring"></a>

| Id | 1607 |
| :---- | :------------------------------- |
| **Label** | Project approach to hazardous and toxic wastewater monitoring |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | Project does not currently monitor and record wastewater |
| | Project monitors and records wastewater (no reduction targets) |
| | Project monitors wastewater and has specific reduction targets |
| | Project monitors wastewater and has met specific reduction targets during the last year of operations |
| | Project has eliminated hazardous and toxic wastewater from project activities entirely |
| | Not applicable |

## waterQualityLand
<a name="waterQualityLand"></a>Water quality practices on cultivated land may include the application of nematicides, riparian buffer zones, etc.

| Id | 1611 |
| :---- | :------------------------------- |
| **Label** | Project implements water quality practices on cultivated land to protect local water sources |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | There is no application of nematicides within 20 meters of any permanent water body |
| | There is no application of agrochemicals within 10 meters of any permanent water body |
| | There is a riparian buffer zone at least 25 feet in width from any permanent water body |
| | Other |
| | Not applicable |

## waterQualityVolume
<a name="waterQualityVolume"></a>The amount of water treated by the project and identified unit (cubic meters, liters, etc.)

| Id | 1610 |
| :---- | :------------------------------- |
| **Label** | Volume of water treated by project |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## waterPollutants
<a name="waterPollutants"></a>Summary of water pollutants monitored by project, with indication if not applicable to project

| Id | 1574 |
| :---- | :------------------------------- |
| **Label** | Overview of water pollutants monitored |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterQualityImprovement
<a name="waterQualityImprovement"></a>

| Id | 1608 |
| :---- | :------------------------------- |
| **Label** | Project activities have improved the quality of relevant water resources |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## waterQualityHouseholds
<a name="waterQualityHouseholds"></a>

| Id | 1609 |
| :---- | :------------------------------- |
| **Label** | Number of households benefiting from improved water quality due to project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## waterQualityEvidence
<a name="waterQualityEvidence"></a>Documents supporting claimed impacts to water quality

| Id | 208 |
| :---- | :------------------------------- |
| **Label** | Water quality impacts supporting documents |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## waterQualityPractices
<a name="waterQualityPractices"></a>Activities undertaken to enhance or maintain the quality of water resources, such as water filtration, desalination, grey water remediation, etc.

| Id | 215 |
| :---- | :------------------------------- |
| **Label** | Water remediation and quality improvement practices |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Water filtration before re-introduction to water table |
| | Use of settling ponds to clean water before re-entry to water table |
| | Grey water remediation |
| | Desalination |
| | Other |
| | Not applicable |

## waterAvailabilityMonitoring
<a name="waterAvailabilityMonitoring"></a>Methods used to monitor and record the quantity of available water resources in the project area, including groundwater, rivers, streams, or other relevant water bodies

| Id | 1613 |
| :---- | :------------------------------- |
| **Label** | Project approach to monitoring water availability |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |
| **Options** | Project does not currently monitor and record water volume and availability |
| | Project monitors and records available water volume and availability (no recharge/conservation targets) |
| | Project monitors water availability and has specific recharge/conservation targets |
| | Project monitors water availability and has met specific water recharge/conservation targets  |
| | Not applicable |

## waterConservation
<a name="waterConservation"></a>Indicates whether the project adopts any practices, programs, initiatives, or technical approaches aimed at conserving water within the project area or surrounding community

| Id | 1614 |
| :---- | :------------------------------- |
| **Label** | Project implements water conservation practices |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## waterConservationDetails
<a name="waterConservationDetails"></a>Summary of water conservation strategies adopted by the project, such as rainwater harvesting, drip irrigation, mulching, reuse systems, or behavioral change initiatives aimed at reducing water use.

| Id | 1616 |
| :---- | :------------------------------- |
| **Label** | Description of the implemented water conservation practices |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterConservationType
<a name="waterConservationType"></a>Specific practices or interventions carried out to conserve water resources, such as rainwater harvesting, efficient irrigation systems, soil moisture retention techniques, water reuse initiatives, or community-based conservation programs

| Id | 1615 |
| :---- | :------------------------------- |
| **Label** | Water conservation practices implemented by project |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Traditional irrigation (e.g. flood irrigation) |
| | Rainwater harvesting |
| | Gray-water use for irrigation |
| | Hydroponic or aeroponic growing |
| | Drip technology |
| | Low-pressure micro-sprinklers |
| | Irrigation water use based on monitoring and analysis of soil moisture and weather data |
| | Other |
| | Not applicable |

## waterVWBConditional
<a name="waterVWBConditional"></a>The Volumetric Water Benefit Accounting, published by WRI, is a common tool used to calculate and communicate volumetric water benefits of activities that contribute to meeting water stewardship outcomes, SDG targets, and help solve shared water challenges

| Id | 941 |
| :---- | :------------------------------- |
| **Label** | Project uses Volumetric Water Benefit (VWB) indicators |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## waterVWBIndicators
<a name="waterVWBIndicators"></a>The Volumetric Water Benefit Accounting framework can be found at https://www.wri.org/research/volumetric-water-benefit-accounting-vwba-method-implementing-and-valuing-water-stewardship

| Id | 210 |
| :---- | :------------------------------- |
| **Label** | Volumetric Water Benefit (VWB) indicators chosen |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Avoided runoff |
| | Improved flow regime |
| | Increased recharge |
| | Maintained recharge |
| | Reduced consumption |
| | Reduced runoff |
| | Reduced withdrawals |
| | Volume captured |
| | Volume provided |
| | Volume treated |

## waterMonitoringIndicator
<a name="waterMonitoringIndicator"></a>Any supplementary indicators tracked by the project beyond the core Verra Water Benefit (VWB) indicators, such as community water access, seasonal flow rates, pollution levels, or ecosystem health metrics

| Id | 212 |
| :---- | :------------------------------- |
| **Label** | Other relevant indicators used for monitoring water availability impacts |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterAvailabilityNumber
<a name="waterAvailabilityNumber"></a>Number of individuals who have gained increased or more reliable access to water as a result of the project’s conservation efforts (e.g., beneficiaries of stream or river recharge, improved groundwater availability, or enhanced well-system performance)

| Id | 211 |
| :---- | :------------------------------- |
| **Label** | Number of people who have benefitted from increased water availability as a result of project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterMonitoringIndicatorDetails
<a name="waterMonitoringIndicatorDetails"></a>The reasoning behind the choice of specific water quality parameters and metrics used in the monitoring program

| Id | 213 |
| :---- | :------------------------------- |
| **Label** | Rationale for the selected water monitoring indicators |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## waterEnhancement
<a name="waterEnhancement"></a>Volume of water refers to surface water availability and/or groundwater availability which has increased due to project activities

| Id | 218 |
| :---- | :------------------------------- |
| **Label** | Project enhances the volume of water in a given location |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## waterUpload
<a name="waterUpload"></a>Evidence demonstrating water availability impacts

| Id | 662 |
| :---- | :------------------------------- |
| **Label** | Water availability impacts documentation |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## waterVerification
<a name="waterVerification"></a>Claimed impacts have been verified, validated, or accredited by a third party group

| Id | 217 |
| :---- | :------------------------------- |
| **Label** | Water benefits claimed are third-party verified |
| **Tier** | 3 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## waterVerificationBody
<a name="waterVerificationBody"></a>

| Id | 942 |
| :---- | :------------------------------- |
| **Label** | Verification body for claimed water resource impacts |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineBaselineUpload
<a name="marineBaselineUpload"></a>Images or documents related to the region's ecological baseline  (e.g., baseline biodiversity in the region, ecological composition or condition, proximity and types of neighboring ecosystems, etc.)

| Id | 1622 |
| :---- | :------------------------------- |
| **Label** | Baseline coastal or aquatic health supporting documents |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## marineHealthIndicatorsDetails
<a name="marineHealthIndicatorsDetails"></a>

| Id | 1629 |
| :---- | :------------------------------- |
| **Label** | Description of indentified and/or other marine and coastal health indicators |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## oceanFloorDetails
<a name="oceanFloorDetails"></a>Changes in ocean floor substrate coverage (i.e., increase in seagrass or coral cover) due to project activities

| Id | 1625 |
| :---- | :------------------------------- |
| **Label** | Overview of changes to ocean floor substrate cover |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineSpeciesNumber
<a name="marineSpeciesNumber"></a>The number or estimated count of plant species present within the project area

| Id | 1620 |
| :---- | :------------------------------- |
| **Label** | Number of species of vegetation within project boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## marineImpacts
<a name="marineImpacts"></a>For example if species diversity was monitored, a summary of changes in flora and fauna composition and diversity through project activities compared to baseline conditions

| Id | 1630 |
| :---- | :------------------------------- |
| **Label** | Summary of project impacts on coastal and marine ecosystem health as a result of project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineEcosystemProximity
<a name="marineEcosystemProximity"></a>Any ecosystems not directly within but in close proximity to project geographic boundaries (seagrass meadows, mangrove forests, etc.)

| Id | 1623 |
| :---- | :------------------------------- |
| **Label** | Ecosystem(s) in close proximity to project's aquatic boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineHealthIndicators
<a name="marineHealthIndicators"></a>Indicators may include surface water temperature, salinity, turbidity, pH, water depth, sediment/soil type, wave exposure, etc.

| Id | 1628 |
| :---- | :------------------------------- |
| **Label** | Marine and coastal health indicators monitored by the project |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |
| **Options** | Surface water temperature |
| | Bottom water temperature |
| | Salinity |
| | Turbidity |
| | pH |
| | Suspended sediment |
| | Total dissolved solids |
| | Dissolved oxygen levels |
| | Fish/crustacean stocks |
| | Juvenile fish/crustacean diversity |
| | Wave exposure |
| | Average current speed |
| | Water depth |
| | Tidal zone |
| | Sediment/soil type |
| | Sediment/soil pollutants (pesticides, excesss fertilizer, and/or heavy metals) |
| | Litter production |
| | Other |

## marineBaselineConditional
<a name="marineBaselineConditional"></a>This baseline can include ocean/river water quality and ecology, including aquatic and terrestrial flora and fauna species presence and abundance

| Id | 1619 |
| :---- | :------------------------------- |
| **Label** | Project evaluates baseline aquatic or coastal ecological health in the project region |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## marineBaselineEvaluation
<a name="marineBaselineEvaluation"></a>Indication of how the project evaluates baseline aquatic health (e.g., direct measurements, model estimations, etc.)

| Id | 1627 |
| :---- | :------------------------------- |
| **Label** | Overview of baseline aquatic health evaluation |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineEcologyDetails
<a name="marineEcologyDetails"></a>Overview of the ecological composition and condition of the project area (e.g., ecosystem type - marsh, coral atolls, types of species present, etc.)

| Id | 1621 |
| :---- | :------------------------------- |
| **Label** | Overview of coastal or aquatic ecology within project boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## marineImpactsUpload
<a name="marineImpactsUpload"></a>Visual and analytical materials demonstrating project effects, such as environmental assessments, biodiversity surveys, aerial imagery, and satellite data

| Id | 1631 |
| :---- | :------------------------------- |
| **Label** | Project impacts on marine and coastal health supporting documents |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## oceanFloorUpload
<a name="oceanFloorUpload"></a>Documents supporting any reported changes to ocean floor substrate coverage

| Id | 1626 |
| :---- | :------------------------------- |
| **Label** | Ocean floor substrate coverage supporting documents |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## oceanFloorConditional
<a name="oceanFloorConditional"></a>Indicates whether ocean floor substrate has changed due to project activities (i.e., density of seagrass meadows, coral cover, etc)

| Id | 1624 |
| :---- | :------------------------------- |
| **Label** | Ocean floor substrate coverage has changed as result of project activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## noisePlan
<a name="noisePlan"></a>The World Health Organization (WHO) defines noise above 65 decibels (dB) as noise pollution. Indicates whether there is a plan in place to mitigate project noise levels over this level.

| Id | 1582 |
| :---- | :------------------------------- |
| **Label** | Noise pollution mitigation plan in place |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## noiseDistance
<a name="noiseDistance"></a>Distance of project from nearest non-project community settlement (with indication of meters, miles, kilometres, etc)

| Id | 1584 |
| :---- | :------------------------------- |
| **Label** | Distance of project location from nearest human residents |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## noiseImpactEvidence
<a name="noiseImpactEvidence"></a>Documents such as sound level readings from baseline conditions as well as project conditions

| Id | 1592 |
| :---- | :------------------------------- |
| **Label** | Noise pollution impacts supporting documents |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## noiseProjectDay
<a name="noiseProjectDay"></a>Average daytime noise level in decibles post project initiation

| Id | 1589 |
| :---- | :------------------------------- |
| **Label** | Average daytime noise levels after project completion in decibels |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## noisePlanEvidence
<a name="noisePlanEvidence"></a>Documentation of noise mitigation plans

| Id | 1583 |
| :---- | :------------------------------- |
| **Label** | Noise mitigation plan documentation |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## noiseDistanceEvidence
<a name="noiseDistanceEvidence"></a>Documentation of the proximity of the project activity to the nearest human populations

| Id | 1585 |
| :---- | :------------------------------- |
| **Label** | Evidence of proximity to nearest human residents |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## noiseBaselineNight
<a name="noiseBaselineNight"></a>Average night-time noise level in decibles before project operations  

| Id | 1588 |
| :---- | :------------------------------- |
| **Label** | Baseline average nighttime noise levels in decibels |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## noiseImpact
<a name="noiseImpact"></a>Project activities (such as the sound of construction or operation) contribute to increased noise pollution

| Id | 1591 |
| :---- | :------------------------------- |
| **Label** | Project activities contribute to increased noise pollution |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## noiseProjectNight
<a name="noiseProjectNight"></a>Average night-time noise level in decibles during project operations

| Id | 1590 |
| :---- | :------------------------------- |
| **Label** | Average nighttime noise levels after project completion in decibels |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## noiseBaseline
<a name="noiseBaseline"></a>Noise pollution testing involves measuring sound levels using a sound level meter to determine if they exceed acceptable limits. The results are often compared to regulations or standards to ensure compliance.

| Id | 1586 |
| :---- | :------------------------------- |
| **Label** | Baseline noise level survey has been conducted |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## noiseBaselineDay
<a name="noiseBaselineDay"></a>Average daytime noise level in decibles before project operations

| Id | 1587 |
| :---- | :------------------------------- |
| **Label** | Baseline average daytime noise levels (decibels) |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | number |

## infrastructureConditional
<a name="infrastructureConditional"></a>Indicates whether buildings, roads, or infrastructure such as irrigation systems have been built for project operations

| Id | 1575 |
| :---- | :------------------------------- |
| **Label** | Project has resulted in new construction of roads, buildings, or other structures within project boundaries |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## infrastructureAccess
<a name="infrastructureAccess"></a>Indicates whether the roads or infrastructure used for the project are public   and/or whether the community has limited accessibility to the infrastructure

| Id | 1576 |
| :---- | :------------------------------- |
| **Label** | The structures or roads are publicly available and accessible to all community members |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | boolean |

## infrastructureDetails
<a name="infrastructureDetails"></a>Overview of any infrastructure that has been built specifically as part of the project activity

| Id | 1577 |
| :---- | :------------------------------- |
| **Label** | Summary of constructed structures, roads, and access management |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## infrastructureSpecies
<a name="infrastructureSpecies"></a>Overview of the species affected by the project activity and any plans, actions, or initiatives taken to limit impact (i.e., fish bridges, wildlife corridors, etc.)

| Id | 1579 |
| :---- | :------------------------------- |
| **Label** | Species affected by development and any remediation measures taken by project |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## infrastructureOtherImpacts
<a name="infrastructureOtherImpacts"></a>Other than noise pollution and habitat fragmentation, any consequential environmental impacts due to infrastructure or building construction

| Id | 1580 |
| :---- | :------------------------------- |
| **Label** | Other ecological impacts of infrastructure development and mitigation activities |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

## infrastructureEvidence
<a name="infrastructureEvidence"></a>Documentation such as building plans, timelines, or blueprints of construction needed for project operations

| Id | 1581 |
| :---- | :------------------------------- |
| **Label** | Project infrastructure development plans and supporting documents |
| **Tier** | -1 |
| **Section** | actuals-ecologicalImpacts |
| **type** | array |

## infrastructureHabitatImpacts
<a name="infrastructureHabitatImpacts"></a>Indicates whether buildings, roads, or infrastructure contribute to habitat fragmentation (i.e., inhibit the ability of species to move freely within their habitats)

| Id | 1578 |
| :---- | :------------------------------- |
| **Label** | Infrastructure development has contributed to habitat fragmentation for monitored species |
| **Tier** | 2 |
| **Section** | actuals-ecologicalImpacts |
| **type** | string |

# enhancements-keyDifferentiators
## kd1Title
<a name="kd1Title"></a>

| Id | 738 |
| :---- | :------------------------------- |
| **Label** | First key differentiator title |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd1Details
<a name="kd1Details"></a>

| Id | 739 |
| :---- | :------------------------------- |
| **Label** | Details about the first differentiator |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd1Media
<a name="kd1Media"></a>

| Id | 740 |
| :---- | :------------------------------- |
| **Label** | Key differentiator image or video |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | object |

## kd2Title
<a name="kd2Title"></a>

| Id | 741 |
| :---- | :------------------------------- |
| **Label** | Second key differentiator title |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd2Details
<a name="kd2Details"></a>

| Id | 742 |
| :---- | :------------------------------- |
| **Label** | Details about the second differentiator |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd2Media
<a name="kd2Media"></a>

| Id | 743 |
| :---- | :------------------------------- |
| **Label** | Key differentiator image or video |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | object |

## kd3Title
<a name="kd3Title"></a>

| Id | 744 |
| :---- | :------------------------------- |
| **Label** | Third key differentiator title |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd3Details
<a name="kd3Details"></a>

| Id | 745 |
| :---- | :------------------------------- |
| **Label** | Details about the third differentiator |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | string |

## kd3Media
<a name="kd3Media"></a>

| Id | 746 |
| :---- | :------------------------------- |
| **Label** | Key differentiator image or video |
| **Tier** | -1 |
| **Section** | enhancements-keyDifferentiators |
| **type** | object |

# enhancements-sdg
## sdgTable1
<a name="sdgTable1"></a>

| Id | 1836 |
| :---- | :------------------------------- |
| **Label** | Sustainable development goal overview |
| **Tier** | -1 |
| **Section** | enhancements-sdg |
| **type** | object |

### Table structure
| Sustainable development goals (SDGs) | SDG target & indicator | Project contribution to SDG | SDG monitoring approach | Source or reference | 
| :---- | :---- | :---- | :---- | :---- |
| | | | | |

## sdgUpload
<a name="sdgUpload"></a>

| Id | 639 |
| :---- | :------------------------------- |
| **Label** | SDG documentation |
| **Tier** | -1 |
| **Section** | enhancements-sdg |
| **type** | array |

## sdgVerification
<a name="sdgVerification"></a>

| Id | 999 |
| :---- | :------------------------------- |
| **Label** | SDG claims have been third party verified |
| **Tier** | 3 |
| **Section** | enhancements-sdg |
| **type** | boolean |

## sdgVerificationBody
<a name="sdgVerificationBody"></a>

| Id | 1000 |
| :---- | :------------------------------- |
| **Label** | SDG verification body |
| **Tier** | 3 |
| **Section** | enhancements-sdg |
| **type** | string |

## sdgVerificationEvidence
<a name="sdgVerificationEvidence"></a>

| Id | 1001 |
| :---- | :------------------------------- |
| **Label** | SDG verification supporting documents |
| **Tier** | -1 |
| **Section** | enhancements-sdg |
| **type** | array |

