# Case digital ID metadata

Variable definitions and collection guidance for case digital ID.

## System

### Digital ID System Name

| Field | Value |
|---|---|
| Variable Id | id-system-didname |
| Definition | Official name of the digital identity system in both local language and English where available, including acronyms |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record format: Local name [English translation] (ACRONYM). Include any alternative names used in legislation vs common usage. Note whether the name has changed over time and any predecessor system names. For the six case study countries: Benin (RAVIP/SNIPC), Côte d'Ivoire (RNPP/ONECI), Ethiopia (Fayda), Mozambique (e-BILHETE), Nigeria (NIN/NIMC), South Africa (Smart ID). |
| Data Collection Guidelines | Sources: ID authority official websites, government portals, legislation documents. Record both local and English names. If unknown, use '[Country] Digital Identity System' format. |

### Public Interface

| Field | Value |
|---|---|
| Variable Id | id-system-url |
| Definition | The url where members of the public can access the Digital Id system |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record the primary public-facing URL (portal or app landing page). If multiple URLs exist (e.g. separate enrollment portal, verification portal, mobile app store link), list all with brief labels. Note whether the URL is functional, intermittent, or defunct at time of research. |
| Data Collection Guidelines | Sources: ID authority official websites, Google Play/Apple App Store listings, government service portals. Test each URL for accessibility. If no public-facing URL exists, explain what access channels are available (e.g. in-person only, USSD). |

### Primary Credential Name

| Field | Value |
|---|---|
| Variable Id | id-system-credname |
| Definition | Official name of the primary ID credential issued for adults (e.g., national ID card, digital identity card) |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record format: Local name [English translation] (ACRONYM). Distinguish between the credential name and the system name if different. Note whether multiple credential types exist (e.g. physical card vs digital credential) and which is considered primary. Include the year the current credential was introduced. |
| Data Collection Guidelines | Sources: ID authority websites, credential samples, legislative documents. Distinguish between physical and digital credentials if both exist. |

### Legacy Systems

| Field | Value |
|---|---|
| Variable Id | id-system-legacy |
| Definition | What identity systems were in use, digital or otherwise, prior to the development of the current system? Is a legacy system still in use? How was/is the transition managed? |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Describe: (1) name and type of each predecessor system (paper-based, digital, hybrid); (2) approximate years of operation; (3) whether still in parallel use; (4) transition strategy (big bang, phased, voluntary migration); (5) data migration approach (automated, manual re-enrollment, no migration). Note any populations still reliant on legacy credentials. |
| Data Collection Guidelines | Sources: Government policy documents, ID authority historical pages, World Bank project appraisals, ID4Africa presentations. Check for transition timelines, parallel running periods, and populations that may still hold only legacy credentials. |

### Authentication Method(s)

| Field | Value |
|---|---|
| Variable Id | id-system-authmethod |
| Definition | The specific technology or approach used for identity verification including biometric (fingerprint, facial recognition, iris), PIN, multi-factor authentication, PKI, or mobile-based methods |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Categories to cover: Fingerprint, Facial recognition, Iris scan, PIN/password, Multi-factor authentication (MFA), PKI/digital certificate, Mobile OTP, USSD, QR code, NFC. List all methods in use, distinguishing between: (a) enrollment authentication; (b) credential issuance authentication; (c) service-access authentication. Note whether methods differ for in-person vs remote use. |
| Data Collection Guidelines | Sources: Technical specifications from ID authority, implementation documentation, DPI Map, biometricupdate.com. Check for explicit mentions of authentication methods in system documentation or service descriptions. |

### Technology Platform

| Field | Value |
|---|---|
| Variable Id | id-system-techplatform |
| Definition | The underlying technology platform or architecture used (e.g., MOSIP, custom-built, commercial vendor solution) |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record: platform name, vendor/developer, whether open-source or proprietary, version if known. Common platforms in Africa: MOSIP, Thales/Gemalto, IDEMIA, TECH5, HID Global, custom-built. Note any platform migrations (e.g. from proprietary to MOSIP). Include hosting arrangement (on-premise, cloud, hybrid) if known. |
| Data Collection Guidelines | Sources: Technical documentation, procurement records, press releases, biometricupdate.com, World Bank project documentation. Note whether open-source or proprietary. |

### Credential Type

| Field | Value |
|---|---|
| Variable Id | id-system-credtype |
| Definition | Format and type of credential issued including physical cards, mobile credentials, digital wallets, or verifiable credentials |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Categories: Physical card (specify: polycarbonate/PVC/paper; with/without chip; contact/contactless), Mobile app, Digital wallet, Verifiable credential, Paper document, e-ID on SIM. For physical cards note: chip type (contact, contactless, dual-interface), security features (hologram, laser engraving, UV printing). Note if multiple credential formats coexist and which is primary. |
| Data Collection Guidelines | Sources: ID authority websites, credential samples, mobile app stores. Note material for physical cards (polycarbonate, PVC, paper) and chip presence. Check for digital/mobile options. |

## Ownership

### System Ownership

| Field | Value |
|---|---|
| Variable Id | id-ownership-system |
| Definition | Who owns the technology used by the system, including production of credentials? Distinguish between legal ownership, technology IP ownership, and credential production. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Distinguish between: (1) legal/institutional owner (which government entity); (2) technology owner (who built/owns the software IP); (3) production owner (who manufactures credentials — government printing works, contracted vendor, or outsourced). Note any PPP or concession arrangements. Name specific companies/entities involved. |
| Data Collection Guidelines | Sources: Procurement contracts, PPP agreements, ID authority annual reports, government gazette notices. Check for technology transfer clauses, IP ownership terms, and credential production contracts. |

### Platform

| Field | Value |
|---|---|
| Variable Id | id-ownership-platform |
| Definition | Who owns and controls the platform that hosts the identity system? Include hosting infrastructure, software control, and data residency details. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Clarify: (1) who owns the hosting infrastructure (government data centre, private cloud provider, international cloud); (2) who controls the platform software (government IT, vendor, open-source community); (3) data residency (where is data physically stored). Note any data sovereignty concerns or requirements. |
| Data Collection Guidelines | Sources: Technology contracts, cloud hosting agreements, data protection impact assessments, data localisation legislation. Check whether platform hosting complies with any national data residency requirements. |

## Governance

### Governing Authority

| Field | Value |
|---|---|
| Variable Id | id-governance-govauthority |
| Definition | The government ministry, agency, or department responsible for managing and operating the digital identity system |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record format: Authority name — institutional home (ministry/department). Note: (1) whether authority is autonomous or embedded; (2) legal basis for its mandate (legislation name and year); (3) whether it has a governing board; (4) reporting line (e.g. reports to Minister of Interior). Example: National Identification Authority (NIA) — Ministry of Interior. |
| Data Collection Guidelines | Sources: Legislation, government organizational charts, ID authority websites. Note institutional home (ministry/department) and whether authority is independent or embedded. |

## Finance

### Investments

| Field | Value |
|---|---|
| Variable Id | id-finance-investments |
| Definition | The sources and values of investments made in the development, deployment, and ongoing operation of the digital identity system. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record: (1) total investment value (local currency and USD where available); (2) funding sources (government budget, World Bank/IDA, bilateral donors, PPP, vendor financing) with amounts per source; (3) time period covered; (4) breakdown if available (capital vs operating, development vs rollout); (5) any known cost-per-registration or cost-per-credential figures. |
| Data Collection Guidelines | Sources: World Bank project documents (PADs, ICRs), government budget documents, donor project databases (IATI), procurement notices, news reports on contract awards. Note currency and exchange rate date. Flag where investment figures combine ID with broader e-government spending. |

## Inclusivity

### Mobile and Fixed Registration

| Field | Value |
|---|---|
| Variable Id | id-inclusivity-regsites |
| Definition | Number and deployment of mobile registration units for reaching remote or underserved populations. And number and types of permanent registration sites. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Cover both dimensions: MOBILE units — number, deployment frequency, geographic targeting (rural, nomadic, refugee camps, border areas); FIXED sites — total number, types (dedicated centres, multi-service government offices, partner locations such as banks or telcos), geographic distribution. Note any data on population-to-registration-site ratios. |
| Data Collection Guidelines | Sources: ID authority reports, field operations documentation. Note geographic coverage, frequency of deployment, and populations targeted (rural, nomadic, refugee camps). |

### Inclusive Design Features

| Field | Value |
|---|---|
| Variable Id | id-inclusivity-inclusivefeatures |
| Definition | Special features designed for accessibility by persons with disabilities, illiterate persons, the elderly, or other marginalized groups |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Categories to cover: Multilingual support (list languages), Braille materials, Audio/voice assistance, Simplified enrollment process, Assisted enrollment (helpers permitted), Wheelchair/physical accessibility, Age-specific accommodations (elderly, children), Gender-sensitive procedures (e.g. female enrollment officers). Note whether features are policy-mandated or ad hoc. Record "None documented" if no evidence found. |
| Data Collection Guidelines | Sources: ID authority accessibility policies, registration procedures. Check for language support, disability accommodations, literacy alternatives (thumbprint, witness signatures). |

### Alternative Documentation

| Field | Value |
|---|---|
| Variable Id | id-inclusivity-altdocs |
| Definition | Whether alternatives are available for applicants who cannot provide standard required documents like birth certificates |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Start with Yes/No, then describe: types of alternative evidence accepted (witness testimony, community leader declaration, affidavit, baptismal certificate, school records); any late birth registration pathway; refugee/stateless person provisions; fee waivers for vulnerable groups. Note whether alternatives are codified in law or applied informally. |
| Data Collection Guidelines | Sources: Registration requirements, late registration policies. Document witness statements, affidavits, local authority declarations, or other acceptable alternatives. |

## Functionality

### Biometric Storage on Credential

| Field | Value |
|---|---|
| Variable Id | id-functionality-credbiometricstore |
| Definition | Whether biometric data is stored electronically on the credential via chip or barcode, and which modalities |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | For each modality state whether it is: (a) collected at enrollment; (b) stored in central database; (c) stored on credential (chip or 2D barcode). Modalities: Fingerprint, Face/photograph, Iris. Note chip specifications if available (contact/contactless, storage capacity). Distinguish between biometric template and raw biometric data storage. |
| Data Collection Guidelines | Sources: Technical specifications, credential design documentation. Distinguish between biometrics collected vs stored on credential. Check chip specifications and barcode content. |

### Credential Verification Methods

| Field | Value |
|---|---|
| Variable Id | id-functionality-credverification |
| Definition | Methods available for verifying the authenticity and validity of credentials including online verification, biometric matching, or visual security features |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Methods to cover: Online verification API/portal, Biometric match-on-card, QR code scanning, Barcode scanning, NFC/contactless reading, Visual security features (hologram, UV), USSD-based verification. Distinguish between: (a) government-to-government verification; (b) government-to-private-sector verification; (c) individual self-verification. Note whether verification services are free or fee-based. |
| Data Collection Guidelines | Sources: Verification systems documentation, service provider integration guides. Check for online verification portals, API availability, and offline verification capabilities. |

### Credential Expiration Policy

| Field | Value |
|---|---|
| Variable Id | id-functionality-credexpire |
| Definition | Whether credentials expire, validity period, and any adjustments for children or seniors |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record: (1) whether credential expires (Yes/No/Lifetime); (2) standard validity period in years; (3) renewal process (automatic, requires re-enrollment, fee); (4) age-based variations (child credential validity, senior lifetime credential); (5) consequences of expired credential (services denied, grace period, automatic extension). Note any difference between physical and digital credential validity. |
| Data Collection Guidelines | Sources: ID legislation, issuance policies, ID4D dataset. Note validity periods, age-based variations, and lifetime credential policies. |

## Uptake

### Public Sector Adoption

| Field | Value |
|---|---|
| Variable Id | id-uptake-adoptpublic |
| Definition | Details of public entities beyond the ID authority that use the ID infrastructure for service delivery |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | List specific government entities/services that use the ID system for authentication or data sharing. Group by sector: health, education, social protection, taxation, justice/police, immigration, electoral, civil service. Note approximate number of integrated agencies. Describe depth of integration (authentication only, data sharing, full transactional). |
| Data Collection Guidelines | Sources: DPI Map, government interoperability reports, e-government strategies. Count distinct agencies, departments, or services using digital ID for authentication or data sharing. |

### Private Sector Adoption

| Field | Value |
|---|---|
| Variable Id | id-uptake-adoptprivate |
| Definition | Whether and how private entities use the ID infrastructure, particularly financial institutions, telecom operators, and service providers |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Start with Yes/No for private sector integration, then describe: which sectors (banking/KYC, telecom/SIM registration, insurance, fintech/mobile money, agriculture, health); legal mandate or voluntary adoption; any API/SDK available for private sector; fee structure for private verification. Name specific companies if documented. |
| Data Collection Guidelines | Sources: Partnership agreements, financial sector integration, SIM registration systems. Document private sector integration for customer onboarding, KYC, service delivery. |

## Credibility

### Technical Standards Compliance

| Field | Value |
|---|---|
| Variable Id | id-credibility-techstandards |
| Definition | Whether the ID system complies with recognized international technical standards (ISO, ICAO, eIDAS, W3C, etc.) |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Standards to check: ISO/IEC 18013 (mobile driving licence), ISO/IEC 19794 (biometrics), ISO/IEC 24745 (biometric template protection), ICAO 9303 (machine-readable travel documents), eIDAS, W3C Verifiable Credentials, MOSIP compliance, ITU standards. Note whether compliance is self-declared, independently certified, or formally audited. |
| Data Collection Guidelines | Sources: Technical documentation, procurement specifications, certification documents. Check compliance with: ISO/IEC 18013 (mDL), ISO/IEC 19794 (biometrics), ICAO 9303 (travel documents). |

### Certification Authority

| Field | Value |
|---|---|
| Variable Id | id-credibility-certauthority |
| Definition | Whether trusted authority exists to issue digital certificates and manage PKI infrastructure for the ID system |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Start with Yes/No, then describe: authority name, whether national or international CA, role in the ID system (credential signing, document authentication, PKI root), legal basis. Note whether the country has a national PKI framework and how the ID system relates to it. |
| Data Collection Guidelines | Sources: PKI documentation, digital signature frameworks. Check for national certificate authority supporting digital ID cryptographic functions. |

### Technical Support Organizations

| Field | Value |
|---|---|
| Variable Id | id-credibility-techsupport |
| Definition | Organizations providing technical expertise, implementation support, or technology platforms for the ID system |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | List organisations with their specific roles: technology vendor (platform provider), systems integrator, biometrics provider, card manufacturer, technical advisor (e.g. World Bank, UNDP), standards body. Common organisations in Africa: MOSIP, Thales/Gemalto, IDEMIA, TECH5, Veridos, Mühlbauer, IN Groupe, Giesecke+Devrient. Note contract type (ongoing support, implementation only, capacity building). |
| Data Collection Guidelines | Sources: Implementation contracts, vendor partnerships, technical assistance agreements. Document technology vendors, implementation partners, and technical advisors (e.g., MOSIP, Thales, Idemia). |

### Fraud Incidents

| Field | Value |
|---|---|
| Variable Id | id-credibility-fraudincidents |
| Definition | Documented cases of ID fraud, system breaches, or security incidents if publicly reported |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Record: (1) number of publicly documented incidents; (2) time period; (3) type of incident (data breach, identity fraud, system manipulation, insider abuse, credential forgery); (4) scale/impact; (5) institutional response; (6) any resulting policy changes. Note that absence of reported incidents may reflect limited transparency rather than absence of fraud. |
| Data Collection Guidelines | Sources: News reports, audit reports, parliamentary inquiries, data protection authority reports. Often sensitive information. Document major publicized incidents and responses. |

## Public Value

### Service Efficiency Gains

| Field | Value |
|---|---|
| Variable Id | id-public value-serviceefficiency |
| Definition | Documented improvements in government service delivery speed, cost, or quality attributed to digital ID system |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Types of evidence to seek: time savings (e.g. registration reduced from days to hours), cost savings (per-transaction or aggregate), error reduction rates, queue reduction, digital vs manual processing comparisons. Include specific before/after metrics where available. Note whether evidence comes from formal evaluation, government claims, or anecdotal reports. |
| Data Collection Guidelines | Sources: Government efficiency reports, case studies, impact evaluations. Document time reductions (e.g., registration from days to hours), cost savings, reduced duplicate payments. |

### Financial Inclusion Impact

| Field | Value |
|---|---|
| Variable Id | id-public value-financialinclusion |
| Definition | Evidence of digital ID contributing to increased access to financial services, particularly for previously unbanked populations |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Metrics to seek: bank account ownership rates before/after ID rollout, mobile money adoption linked to ID verification, KYC simplification impact, previously unbanked populations gaining access. Reference World Bank Findex data waves (2011, 2014, 2017, 2021) for trend data. Note whether causation or correlation with ID system is established. |
| Data Collection Guidelines | Sources: Central bank financial inclusion reports, World Bank Findex data, impact studies. Check for correlation between ID rollout and bank account opening rates. |

### Stakeholder Engagement

| Field | Value |
|---|---|
| Variable Id | id-public value-stakeholderengage |
| Definition | Whether ID system design and governance involves multi-stakeholder participation including civil society, domain experts, and affected communities |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Assessment scale: Yes (formal multi-stakeholder mechanisms) / Limited (ad hoc consultation) / No (no documented engagement). Describe: consultation mechanisms (advisory board, public hearings, comment periods), civil society participation, academic involvement, private sector representation, affected community voices. Note whether engagement is ongoing governance or one-off design phase. |
| Data Collection Guidelines | Sources: ID system governance documents, consultation records, advisory board compositions. Check for formal civil society involvement, public consultations, advisory committees. |

### Performance Reviews

| Field | Value |
|---|---|
| Variable Id | id-public value-performancereview |
| Definition | Whether ID authority performance and system governance is regularly reviewed and publicly reported |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Start with Yes/No, then describe: review type (annual report, parliamentary committee, audit office, independent evaluation), frequency, whether publicly available, key performance indicators reported (registration numbers, service delivery, financial performance, user satisfaction). Note any gap between review mandate and actual practice. |
| Data Collection Guidelines | Sources: Annual reports, parliamentary oversight, audit reports. Check for regular public reporting on registration numbers, service delivery, financial performance. |

### Anti-Corruption Benefits

| Field | Value |
|---|---|
| Variable Id | id-public value-anticorruption |
| Definition | Documented cases where digital ID has reduced corruption, duplicate payments, ghost workers, or fraud in government systems |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Types of evidence: ghost worker elimination (number removed, payroll savings), duplicate benefit removal (social protection, pensions), procurement transparency improvements, identity fraud reduction in public services. Include monetary savings estimates where documented. Note whether evidence comes from official audits, media reports, or donor evaluations. |
| Data Collection Guidelines | Sources: Audit reports, anti-corruption commission reports, case studies. Document ghost worker elimination, duplicate benefit removal, procurement transparency improvements. |

### Economic Value Generated

| Field | Value |
|---|---|
| Variable Id | id-public value-econvalue |
| Definition | Estimated economic value or GDP contribution from digital ID enabling digital economy activities, reducing transaction costs, or improving market efficiency |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Types of evidence: McKinsey/World Bank economic impact estimates, national digital economy strategy targets, transaction cost reductions, market efficiency gains, new digital services enabled. Report values in both local currency and USD with exchange rate date. Distinguish between projected/modelled estimates and measured outcomes. Reference McKinsey estimate of 3-13% GDP contribution by 2030 as benchmark. |
| Data Collection Guidelines | Sources: Economic impact studies, World Bank reports, national digital economy assessments. McKinsey estimates digital ID can contribute 3-13% of GDP by 2030. Context-specific. |

### Public Trust Indicators

| Field | Value |
|---|---|
| Variable Id | id-public value-publictrust |
| Definition | Evidence of public trust or distrust in the digital ID system including survey data, voluntary adoption rates, or documented concerns |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Types of evidence: Afrobarometer data, national surveys, civil society reports (e.g. Access Now, Privacy International, Article 19), media analysis, court challenges, public protests or boycotts, voluntary vs mandatory adoption rates. High voluntary adoption indicates trust. Document both positive trust indicators and documented concerns/resistance. Note mandatory vs voluntary nature of the system. |
| Data Collection Guidelines | Sources: Public opinion surveys, civil society reports, media analysis, voluntary vs mandatory adoption rates. High voluntary adoption indicates trust. Document privacy concerns or resistance. |

## Social Equity

### Rural-Urban Coverage Gap

| Field | Value |
|---|---|
| Variable Id | id-social equity-ruralurbangap |
| Definition | Difference in digital ID coverage between rural and urban populations |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Ideal format: Urban coverage (X%) — Rural coverage (Y%) = Gap (Z percentage points). Where exact figures unavailable, describe qualitatively using available evidence. Cover: registration coverage gap, credential possession gap, access to registration sites, barriers (distance, cost, awareness, connectivity). Note data source and year. Reference DHS or census data where available. |
| Data Collection Guidelines | Sources: ID authority reports with geographic disaggregation, census data, household surveys. Document barriers to rural access: distance to registration sites, costs, awareness. |

### Disability Accessibility

| Field | Value |
|---|---|
| Variable Id | id-social equity-disabilityaccess |
| Definition | Whether registration and credential use accommodates persons with disabilities and coverage rates among disabled populations if available |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Assessment: Accessible / Partially accessible / Not accessible. Cover: physical accessibility of registration sites, alternative enrollment methods (home visits, mobile units), sensory accommodations (visual, hearing, cognitive), credential usability for persons with disabilities, any coverage data for disabled populations. Reference CRPD compliance status. |
| Data Collection Guidelines | Sources: Disability rights assessments, accessibility audits, registration procedures. Check for physical access, alternative enrollment methods, assisted services, accessible credentials. |

### Literacy Barriers

| Field | Value |
|---|---|
| Variable Id | id-social equity-literacybarriers |
| Definition | Whether illiteracy presents barriers to enrollment and what accommodations exist |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Assessment: High barrier / Moderate / Low. Factors: whether signature required vs thumbprint accepted, forms available in local languages, audio/visual guidance at enrollment, assisted enrollment by staff, whether literacy is needed for ongoing credential use (e.g. reading PIN). Include national literacy rate as context. Note any documented cases of exclusion due to illiteracy. |
| Data Collection Guidelines | Sources: Registration procedures, literacy rate data, impact assessments. Check if signature required vs thumbprint accepted. Document assistance available for illiterate persons. |

### Ethnic/Linguistic Minority Access

| Field | Value |
|---|---|
| Variable Id | id-social equity-ethnicminority |
| Definition | Whether ethnic or linguistic minorities face barriers to ID access and any special provisions |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Issues to explore: language of enrollment forms and interfaces, documentation requirements that may exclude minorities (e.g. requiring documents in official language only), name/script compatibility, ethnic profiling risks, nomadic population provisions, refugee and stateless person access. Note whether the country has recognized ethnic minorities and any constitutional protections. |
| Data Collection Guidelines | Sources: Civil society reports, minority rights organizations, human rights assessments. Check for language support, cultural sensitivity, documentation requirements affecting minorities. |

### Equity Impact Assessment

| Field | Value |
|---|---|
| Variable Id | id-social equity-equityassessment |
| Definition | Whether formal assessments of equity impacts have been conducted and findings documented |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Start with Yes/No, then describe: type of assessment (human rights impact assessment, data protection impact assessment, equity audit, inclusion study), commissioning body (government, donor, civil society), date, key findings, whether findings were acted upon. Reference any IDS/Research ICT Africa assessments or World Bank safeguard reviews. |
| Data Collection Guidelines | Sources: Impact evaluations, human rights assessments, third-party audits. Check for studies on exclusion, discrimination, differential impacts across groups. |

### Human Rights Safeguards

| Field | Value |
|---|---|
| Variable Id | id-social equity-rightssafeguards |
| Definition | Documented safeguards to ensure ID system does not infringe on human rights including rights to services without ID, non-discrimination provisions |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Safeguards to check: right to access services without digital ID (alternative channels), non-discrimination provisions in ID legislation, data protection/privacy safeguards, consent requirements, grievance/redress mechanisms, judicial oversight, sunset clauses, purpose limitation. Note whether ID is de jure mandatory, de facto mandatory (needed for essential services), or voluntary. Reference Principles on Identification (World Bank) compliance. |
| Data Collection Guidelines | Sources: Human rights legislation, ID legislation, civil society assessments. Check that ID is not sole credential for basic rights, non-discrimination provisions exist, vulnerable groups protected. |
