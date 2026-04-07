# Case digital payment metadata

Variable definitions and collection guidance for case digital payment.

## System

### Payment System Name

| Field | Value |
|---|---|
| Variable Id | pay-system-dpaysysname |
| Definition | Official name(s) of the country's primary digital payment system(s) or interoperability platform(s) in both local language and English where available. Includes formal real-time/instant payment systems, mobile money interoperability schemes, and national payment switches. If multiple systems exist (e.g., separate bank-led and mobile money systems), list all major systems. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Include acronym if commonly used (e.g., "NIBSS Instant Payment (NIP)"). Note if system is bank-only, mobile money-only, or interoperable. |
| Data Collection Guidelines | Search: "[Country] payment system name", "[Country] digital payment name", central bank payment system documents, national switch operator websites. Cross-reference with BIS/World Bank SIIPS (Significantly Important Instant Payment Systems) Report and regional payment system listings. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Payment System Type

| Field | Value |
|---|---|
| Variable Id | pay-system-dpaysystype |
| Definition | Classification of the digital payment system based on its architecture and participant ecosystem, distinguishing between bank-centric, mobile money-centric, or interoperable models that bridge multiple payment service provider types. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Bank-only IPS; Mobile Money-only IPS; Bank-MNO Interoperable; Universal Interoperable; Multiple Separate Systems. Bank-only: Only banks as participants. Mobile Money-only: Only mobile network operators. Bank-MNO: Banks and MNOs integrated. Universal: Banks, MNOs, fintechs, PSPs all eligible. Multiple: Distinct systems operating in parallel. |
| Data Collection Guidelines | Search: "[Country] payment system interoperability", "[Country] mobile money bank interoperability", scheme rules documents, participant eligibility criteria. Check mobile money interoperability reports, central bank licensing frameworks. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Technical Standards Compliance

| Field | Value |
|---|---|
| Variable Id | pay-system-techstandards |
| Definition | International or regional technical standards, protocols, and messaging formats adopted by the payment system for transaction processing, security, and interoperability (e.g., ISO 20022, ISO 8583, Mojaloop, EMV standards). |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Common standards: ISO 20022 (messaging), ISO 8583 (card transactions), EMV (chip cards), Mojaloop (open-source mobile money), GSMA Mobile Money API. Note if standards are partial or full implementation. |
| Data Collection Guidelines | Search: "[Country] payment system technical standards", "[Country] ISO 20022", system operator technical documentation, scheme rules technical specifications, tender documents for payment system infrastructure. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Interoperability Model

| Field | Value |
|---|---|
| Variable Id | pay-system-interopmodel |
| Definition | The architectural approach used to achieve interoperability between payment service providers, distinguishing between centralized hub/switch models, distributed peer-to-peer models, standards-based federation, or merchant aggregation approaches. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Centralized Hub/Switch; Peer-to-Peer; Standards-Based Federation; Hybrid; No Interoperability. Centralized: Single national switch/hub routes all transactions. Peer-to-Peer: Direct bilateral connections. Standards-Based: Common standards enable connectivity without central switch. Hybrid: Combination of approaches. |
| Data Collection Guidelines | Search: "[Country] payment switch", "[Country] interoperability model", "[Country] national payment hub", payment system architecture documents, GhIPSS model references, Mojaloop implementations. Check if central bank or third party operates switch. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Supported Payment Channels

| Field | Value |
|---|---|
| Variable Id | pay-system-paymentchannels |
| Definition | All access channels through which end users can initiate and receive digital payments, including mobile applications, USSD codes, web platforms, point-of-sale terminals, QR codes, agent networks, and API integrations. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note if channel requires smartphone vs feature phone. Indicate 24/7 availability or restrictions per channel. Comment on accessibility for rural/offline environments. |
| Data Collection Guidelines | Search: "[Country] payment channels", "[Country] USSD payments", "[Country] QR code payments", user guides for payment systems, mobile banking app features, scheme participant documentation, fintech integrations. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Payment Instruments Supported

| Field | Value |
|---|---|
| Variable Id | pay-system-paymentinstruments |
| Definition | Types of payment instruments and stored value accounts that can be linked to and used as source or destination for digital payments, including bank accounts, mobile wallets, prepaid cards, and other regulated payment accounts. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Distinguish between bank-issued accounts, MNO wallets, independent payment service provider accounts. Note if instrument types can interoperate (e.g., bank to mobile wallet). |
| Data Collection Guidelines | Search: "[Country] mobile wallet bank transfer", "[Country] payment instruments", scheme rules on account types, mobile money regulations, interoperability documentation, participant types allowed. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

## Governance

### Governing Authority

| Field | Value |
|---|---|
| Variable Id | pay-governance-paygovauthority |
| Definition | The entity or entities responsible for regulatory oversight, rule-setting, licensing, and supervision of the payment system and its participants. Typically includes central bank, financial regulatory authority, telecommunications regulator, or dedicated payment system oversight body. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify primary vs secondary oversight. Note if authority covers prudential regulation, conduct regulation, or both. Indicate if multiple authorities share jurisdiction (e.g., central bank + telecom regulator). |
| Data Collection Guidelines | Search: "[Country] payment system regulation", "[Country] central bank payment oversight", legal framework for payment systems, payment system acts/laws, regulatory authority websites, licensing regimes for payment service providers. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Payment System Operator

| Field | Value |
|---|---|
| Variable Id | pay-governance-payoperator |
| Definition | The organization(s) responsible for operating the payment system infrastructure, managing day-to-day technical operations, participant onboarding, transaction routing, and system maintenance. May be central bank, private company, or public-private entity. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Operator types: Central Bank, National Switch Company, Private Consortium, Public-Private Partnership, Individual MNOs. Note founding year if available. Indicate if different operators for different systems (bank vs mobile money). |
| Data Collection Guidelines | Search: "[Country] payment system operator", "[Country] national switch", "[Country] payment infrastructure company", company registries, central bank subsidiaries, GhIPSS-type entities, NIBSS-type entities. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Ownership Model

| Field | Value |
|---|---|
| Variable Id | pay-governance-payownership |
| Definition | Ownership structure of the payment system infrastructure, indicating whether owned by central bank, commercial banks, mobile operators, government, private sector consortium, or combination. Reflects governance and incentive structures. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Central Bank-Owned; Bank Consortium; MNO Consortium; Government-Owned; Private Company; Public-Private Partnership; Mixed/Shared. Specify ownership percentages if available (e.g., "Central Bank 60%, Banks 40%"). Note if ownership has evolved over time. Comment on implications for neutrality and competition. |
| Data Collection Guidelines | Search: "[Country] payment system ownership", "[Country] national switch shareholders", company ownership records, central bank subsidiaries, payment system operator annual reports, governance documents. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

## Inclusivity

### Participant Eligibility Scope

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-participanteligibility |
| Definition | Types of financial service providers legally eligible to participate as direct participants (not just as agents) in the payment system, reflecting the breadth of the ecosystem. Includes banks, mobile network operators, fintechs, payment service providers, microfinance institutions, and non-bank entities. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note licensing requirements (e.g., "Must hold PSP license"). Distinguish between direct participants (settle on own behalf) and indirect participants (through sponsor bank). Comment on barriers to entry (capital, technical, operational). |
| Data Collection Guidelines | Search: "[Country] payment system participant eligibility", "[Country] payment service provider licensing", scheme rules on participation, central bank licensing categories, participant directories, mobile money regulations, fintech licensing frameworks. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Number of Direct Participants

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-participantcount |
| Definition | Total count of payment service providers directly connected to and actively participating in the digital payment system as of the most recent reporting date. Reflects market breadth and competitive landscape. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify if count includes banks only, banks+MNOs, or all PSP types. Note breakdown by type if available (e.g., "23 banks, 4 MNOs, 6 fintechs"). Include inactive vs active distinction if disclosed. Note growth trend if historical data exists. |
| Data Collection Guidelines | Search: "[Country] payment system participants", "[Country] banks connected to payment system", participant directories, payment system operator reports, central bank statistics, scheme membership lists, regulatory licensing databases. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Transaction Fee for Person-to-Person Payments

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-transactionfeep2p |
| Definition | Fee structure charged to end users (sender or receiver) for person-to-person digital payments within the country. Includes flat fees, percentage fees, tiered structures, or free transactions. Critical affordability indicator. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify who pays (sender/receiver/both). Note fee caps if imposed by regulation. Distinguish between bank-to-bank, mobile-to-mobile, and bank-to-mobile fees if different. Include minimum and maximum fees for tiered structures. Date pricing as of latest available. |
| Data Collection Guidelines | Search: "[Country] P2P payment fees", "[Country] transfer charges", "[Country] mobile money transfer tariffs", provider pricing pages, scheme rules on pricing, regulatory fee caps, consumer associations fee comparisons, central bank tariff surveys. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Tiered KYC/CDD Requirements

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-kyctiering |
| Definition | Whether risk-based, tiered know-your-customer (KYC) and customer due diligence (CDD) requirements exist that allow simplified verification for lower-risk, lower-value accounts and transactions, enabling access for individuals without full documentation. Critical for including informal sector and rural populations. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Yes - Multi-Tier System; Simplified KYC Only; No - Uniform Requirements. Multi-Tier: Usually 3+ tiers with different requirements and transaction limits. Simplified: Single reduced requirement option. Describe tier structure if multi-tier (e.g., "Tier 1: Name+phone; Tier 2: +ID; Tier 3: +proof of address"). Note transaction limits per tier. |
| Data Collection Guidelines | Search: "[Country] tiered KYC", "[Country] simplified customer due diligence", "[Country] risk-based KYC regulations", AML/CFT regulations, central bank KYC directives, mobile money KYC rules, financial inclusion KYC policy, FATF guidance implementation. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Agent Network Availability

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-agentnetwork |
| Definition | Availability, size, and geographic distribution of agent networks providing cash-in/cash-out services, account opening assistance, and transaction support for digital payments. Particularly important for rural areas and populations lacking digital literacy or connectivity. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Include agent count, agents per 100,000 adults, rural vs urban distribution, agent types (bank agents, mobile money agents, retail agents). Note regulatory framework for agents. Comment on agent liquidity challenges if documented. Mention super-agent models if applicable. |
| Data Collection Guidelines | Search: "[Country] agent banking", "[Country] mobile money agents", "[Country] agent network size", provider annual reports, central bank agent statistics, GSMA mobile money reports, agent network operator disclosures, financial access surveys with agent data. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Accessibility Features for Vulnerable Groups

| Field | Value |
|---|---|
| Variable Id | pay-inclusivity-accessibilityfeatures |
| Definition | Special design features, accommodations, and services that enhance accessibility of digital payment systems for persons with disabilities, illiterate users, elderly populations, or other marginalized groups, including voice-based interfaces, screen readers, simplified UIs, assisted transactions. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note if features are mandatory (regulatory requirement) or voluntary. Specify which providers offer features. Comment on effectiveness/uptake if studied. Mention training programs for vulnerable groups. Reference accessibility standards compliance (WCAG, etc.). |
| Data Collection Guidelines | Search: "[Country] payment accessibility disability", "[Country] illiterate-friendly payment", "[Country] inclusive payment design", provider accessibility statements, disability rights legislation applied to payments, financial inclusion reports on vulnerable groups, assistive technology integrations. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

## Functionality

### Offline Payment Capability

| Field | Value |
|---|---|
| Variable Id | pay-functionality-offlinepayments |
| Definition | Whether payments can be initiated, authorized, and completed (at least temporarily) without internet connectivity, using USSD, SMS, SIM-based applications, or other offline technologies. Critical for rural and low-connectivity areas. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Yes - Full Offline; Partial - USSD/SMS Only; No - Internet Required. Full Offline: Transactions complete without internet (may sync later). Partial: USSD/SMS work but require basic GSM. Specify offline technologies supported (USSD, SMS, SIM toolkit, NFC offline, Bluetooth). Note transaction limits for offline if different. |
| Data Collection Guidelines | Search: "[Country] USSD payments", "[Country] offline digital payments", "[Country] SMS payments", payment channels documentation, USSD payment codes, offline payment technologies, feature phone payment capabilities. |

## Uptake

### Annual Transaction Volume

| Field | Value |
|---|---|
| Variable Id | pay-uptake-transactionvolume |
| Definition | Total number of payment transactions (count) processed through the digital payment system annually, reflecting system usage intensity. Includes all transaction types (P2P, P2B, G2P, etc.). |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify year of data. Note if volume includes all system types or specific subset. Provide growth rate vs previous year if available. Distinguish successful vs attempted transactions if disclosed. Source data (system operator, central bank, regulator). |
| Data Collection Guidelines | Search: "[Country] payment transaction volume", "[Country] payment system statistics", payment system operator annual reports, central bank payment statistics, financial stability reports, BIS/World Bank SIIPS (Significantly Important Instant Payment Systems) Report data, regulatory filings. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Annual Transaction Value

| Field | Value |
|---|---|
| Variable Id | pay-uptake-transactionvalue |
| Definition | Total monetary value of all transactions processed through the digital payment system annually, reflecting economic activity channeled through digital payments. Includes all transaction types. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify year and currency. Convert to USD if helpful (note exchange rate and date). Provide growth rate vs previous year if available. Note if GDP percentage disclosed. Compare to cash transaction estimates if available. Source data. |
| Data Collection Guidelines | Search: "[Country] payment transaction value", "[Country] digital payment GDP", payment system operator annual reports, central bank payment statistics, financial sector assessments, BIS/World Bank SIIPS (Significantly Important Instant Payment Systems) Report, transaction value trends. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Banking Sector Adoption

| Field | Value |
|---|---|
| Variable Id | pay-uptake-bankadoption |
| Definition | Extent of banking sector participation in and utilization of the digital payment system, measured by percentage of banks connected and volume/value of bank-initiated or bank-intermediated transactions. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify banks connected as percentage of total licensed banks. Note if large banks vs small banks have different adoption rates. Distinguish transactions originating from bank accounts vs bank mobile apps. Compare bank vs non-bank (mobile money) usage if available. |
| Data Collection Guidelines | Search: "[Country] bank payment system participation", "[Country] banks connected digital payment", banking association reports, payment system participant lists, central bank bank supervision reports, transaction statistics by originator type. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

### Mobile Money Transaction Share

| Field | Value |
|---|---|
| Variable Id | pay-uptake-mobilemoneyshare |
| Definition | Share of digital payment system transactions originating from or intermediated by mobile money accounts compared to traditional bank accounts, indicating relative importance of mobile money vs banking channels. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify if share by transaction volume (count) or value (amount), as these often differ significantly. Note country context (mobile money-led vs bank-led market). Source data. Comment on trends if historical data available. |
| Data Collection Guidelines | Search: "[Country] mobile money vs bank transactions", "[Country] mobile money market share", GSMA State of the Industry reports, central bank payment statistics by channel, financial inclusion surveys, payment system statistics by participant type. For UEMOA/CEMAC member states, also search regional central bank (BCEAO/BEAC) payment system documentation and regional interoperability initiatives. |

## Credibility

### Security Standards and Certifications

| Field | Value |
|---|---|
| Variable Id | pay-credibility-securitystandards |
| Definition | Security protocols, international standards, and third-party certifications implemented to protect the payment system infrastructure and user data from cybersecurity threats, including encryption, authentication, monitoring, and incident response capabilities. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note if certifications are for system operator, participants, or both. Specify encryption standards (TLS, AES-256). Mention authentication methods (PIN, biometric, OTP, 2FA). Include audit frequency if disclosed. Cite cybersecurity regulations applied. |
| Data Collection Guidelines | Search: "[Country] payment system security", "[Country] payment cybersecurity standards", payment system security documentation, PCI-DSS compliance disclosures, central bank cybersecurity directives, ISO 27001 certifications, security audit reports, incident response frameworks. |

### Fraud and Scam Incidents

| Field | Value |
|---|---|
| Variable Id | pay-credibility-fraudrate |
| Definition | Documented rate of fraud, unauthorized transactions, scams, or security incidents affecting the payment system, typically expressed as fraud value as percentage of total transaction value or fraud incidents per million transactions. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify fraud types included (unauthorized access, account takeover, merchant fraud, social engineering scams). Note if rate is for successful fraud only or attempts. Distinguish system vulnerabilities vs user-targeted scams. Source (regulator, operator, police). Comment on trend. |
| Data Collection Guidelines | Search: "[Country] payment fraud rate", "[Country] mobile money fraud", "[Country] digital payment scams", central bank consumer complaints, payment system operator security reports, police cybercrime statistics, consumer protection authority reports, media reports on payment fraud. |

### Dispute Resolution Mechanism

| Field | Value |
|---|---|
| Variable Id | pay-credibility-disputeresolution |
| Definition | Formal processes and institutional arrangements available for users to report and resolve payment errors, unauthorized transactions, fraud, or service quality issues, including complaint channels, resolution timeframes, and appeal mechanisms. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Formal Mechanism Exists; Informal/Provider-Level Only; No Clear Mechanism. If formal mechanism exists, describe: complaint channels (hotline, online, in-person), resolution timeline (e.g., "within 10 business days"), escalation path, regulatory oversight, compensation/refund policies. Note if financial ombudsman covers payments. |
| Data Collection Guidelines | Search: "[Country] payment dispute resolution", "[Country] payment complaint mechanism", "[Country] financial ombudsman", scheme rules on disputes, consumer protection regulations, payment service provider complaint procedures, central bank complaint handling frameworks, ombudsman services. |

### Consumer Awareness and Education Programs

| Field | Value |
|---|---|
| Variable Id | pay-credibility-customerawareness |
| Definition | Whether systematic, organized programs exist to educate users about payment system features, security best practices, fraud prevention, user rights, and safe usage, delivered by regulators, operators, providers, or civil society. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Yes - Comprehensive Programs; Limited - Ad Hoc Initiatives; No. Comprehensive: Regular, multi-channel education with measurable reach. Limited: Occasional campaigns. If Yes, describe programs: financial literacy training, security awareness campaigns, user guides, helplines, school programs. Note reach (e.g., "trained 1M users in 2023"). |
| Data Collection Guidelines | Search: "[Country] financial literacy digital payments", "[Country] payment security awareness", "[Country] mobile money education", central bank financial literacy programs, payment operator user education, consumer protection campaigns, NGO financial education programs, media public service announcements. |

### Regulatory Oversight and Supervision

| Field | Value |
|---|---|
| Variable Id | pay-credibility-regulatoryoversight |
| Definition | Extent, nature, and effectiveness of regulatory oversight of payment system operations, risk management, financial soundness, consumer protection, and participant conduct by central bank, financial regulator, or other authorities. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Comprehensive Oversight; Basic Oversight; Limited Oversight. Comprehensive: Regular inspections, prudential standards, conduct monitoring, enforcement actions. Basic: Licensing and reporting only. Describe oversight activities: on-site inspections, off-site surveillance, stress testing, risk assessments. Note enforcement actions taken if disclosed. |
| Data Collection Guidelines | Search: "[Country] payment system supervision", "[Country] central bank payment oversight", payment system regulations, central bank supervision reports, payment system designations (systemically important), regulatory frameworks, enforcement actions, supervisory approach statements. |

### Development Partner and Technical Assistance Support

| Field | Value |
|---|---|
| Variable Id | pay-credibility-techsupport |
| Definition | Development partners, donors, technical assistance providers, or international organizations that have provided or are providing financial grants, technical expertise, capacity building, or infrastructure support for payment system development and operations. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify support type: funding/grants, technical design, capacity building, software/infrastructure, policy advisory, governance support. Note if support is historical (system launch) or ongoing. Mention specific projects/programs if known (e.g., "AFIN project", "Payment Systems Development"). |
| Data Collection Guidelines | Search: "[Country] payment system development partners", "[Country] digital payment technical assistance", "[Country] World Bank payment project", project databases (World Bank, AfDB, donors), payment system operator acknowledgments, central bank collaboration statements, donor reports, technical assistance facility disclosures. |

## Public Value

### Economic Impact and GDP Contribution

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-econimpact |
| Definition | Estimated economic value or GDP contribution from digital payment system including direct transaction value, productivity gains, cost savings, formalization effects, and multiplier impacts on economic activity. May be from economic studies, modeling, or official statistics. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note methodology (econometric study, input-output model, payment value as proxy). Distinguish direct contribution (transaction value) vs induced effects (productivity, formalization). Cite source study. Comment on counterfactual assumptions (vs cash economy). |
| Data Collection Guidelines | Search: "[Country] digital payment economic impact", "[Country] mobile money GDP contribution", economic impact studies, World Bank/IMF economic assessments, academic research on payment impact, payment industry reports, central bank financial stability assessments, fintech economic contribution studies. |

### Financial Inclusion Impact

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-financialinclusion |
| Definition | Evidence that the digital payment system has expanded financial inclusion, particularly bringing previously unbanked or underbanked populations into the formal financial system, with supporting data on account ownership growth, demographic reach, or inclusion metrics. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Include account ownership growth, unbanked reduction, rural inclusion, gender gap closure, youth inclusion. Distinguish correlation vs causation. Note if payment access is gateway to other services (credit, savings, insurance). Cite Global Findex, FinScope, or national surveys. |
| Data Collection Guidelines | Search: "[Country] financial inclusion growth", "[Country] unbanked reduction digital payments", "[Country] mobile money inclusion impact", Global Findex time series, FinScope surveys, financial inclusion strategies with baseline/targets, impact evaluation studies, central bank inclusion reports. |

### Benefits for Micro and Small Businesses

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-smebenefits |
| Definition | Documented benefits for micro, small, and medium enterprises from accepting and using digital payments, including increased sales, reduced cash handling costs, improved recordkeeping, access to credit based on transaction data, or business formalization. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note types of benefits documented: sales growth %, cost reduction %, credit access, digital recordkeeping, tax compliance, supplier payments. Distinguish quantified impacts vs qualitative perceptions. Cite MSME surveys, case studies, payment provider impact reports. |
| Data Collection Guidelines | Search: "[Country] MSME digital payments benefits", "[Country] small business mobile money impact", MSME surveys, IFC/World Bank enterprise surveys, payment provider MSME programs, fintech MSME lending linked to payments, MSME association reports, academic studies on MSME digitization. |

### Government Service Delivery Efficiency

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-govtefficiency |
| Definition | Documented improvements in government efficiency from digital payments including faster disbursement speeds, reduced leakage and fraud in social programs, lower administrative costs, improved targeting accuracy, and better reconciliation. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note efficiency gains: disbursement speed, leakage reduction %, administrative cost savings, duplicate beneficiary elimination, real-time visibility. Distinguish G2P vs P2G efficiency. Cite government assessments, donor evaluations, audit reports. |
| Data Collection Guidelines | Search: "[Country] G2P digitization efficiency", "[Country] social transfer leakage reduction digital", "[Country] digital payment government savings", treasury reports, social protection program evaluations, World Bank G2P assessments, IMF PFM reforms, government digital transformation impact reports, audit reports on program efficiency. |

### Anti-Corruption and Transparency Benefits

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-reducedcorruption |
| Definition | Evidence that digital payment trails, transaction transparency, and reduced cash handling have reduced corruption, petty bribery, or fraud, or improved government accountability through better audit trails and real-time monitoring. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note corruption reduction evidence: petty bribery in service delivery, ghost workers eliminated, procurement transparency, payment trail for audits. Distinguish measured reduction vs perception surveys. Cite anti-corruption agency reports, governance indices, audit findings, transparency assessments. |
| Data Collection Guidelines | Search: "[Country] digital payments reduce corruption", "[Country] transparency digital government payments", "[Country] ghost workers eliminated digital payments", anti-corruption commission reports, audit general reports, governance perception surveys (TI Corruption Perceptions, Afrobarometer), PFM assessments, digital governance impact studies. |

### Governance Transparency Index

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-transparencyindex |
| Definition | Composite assessment of transparency in payment system governance including availability of public documentation (scheme rules, performance data, governance structure), stakeholder consultation processes, public reporting frequency, and information accessibility. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | High: Public scheme rules, regular performance reporting, governance documentation, stakeholder consultation. Moderate: Some public info but gaps. Low: Limited public disclosure. Summarise the publicly available governance documentation (scheme rules, performance reports, consultation records) and assess transparency as High/Moderate/Low with brief justification based on evidence from other governance variables. |
| Data Collection Guidelines | This is primarily a synthetic variable derived from other governance variables (scheme rules availability, performance reporting, stakeholder engagement). Assess based on: publicly available documentation, reporting frequency/detail, consultation mechanisms, governance clarity. Cross-check payment system operator transparency practices. |

### Multi-Stakeholder Participation

| Field | Value |
|---|---|
| Variable Id | pay-publicvalue-stakeholderengage |
| Definition | Whether payment system governance involves diverse stakeholders beyond banks and government, including civil society organizations, consumer representatives, MSME associations, fintech sector, mobile operators, and affected communities in policy-making, rule-setting, or oversight. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Yes - Broad Multi-Stakeholder; Limited - Industry Only; No - Closed Governance. Broad: Includes CSOs, consumer groups, diverse PSPs. Limited: Banks/MNOs only. Describe participation mechanisms: advisory boards, public consultations, co-governance structures. Note frequency and influence of stakeholder input. Cite specific committees or forums. |
| Data Collection Guidelines | Search: "[Country] payment system stakeholder consultation", "[Country] payment governance committees", governance documents, stakeholder advisory board membership, public consultation notices, civil society participation in policy, consumer group representation, scheme governance structures, regulatory consultation processes. |

## Social Equity

### Rural-Urban Access and Usage Gap

| Field | Value |
|---|---|
| Variable Id | pay-socialequity-ruralurbangap |
| Definition | Difference in digital payment access (account ownership, agent availability) and usage (active users, transaction frequency) between rural and urban populations, reflecting infrastructure and service availability disparities. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify if gap in account ownership, active usage, agent access, network coverage. Note absolute gap and trend. Distinguish access (can obtain account) vs usage (actively transacting). Comment on rural-specific barriers (connectivity, literacy, agent liquidity). Source surveys. |
| Data Collection Guidelines | Search: "[Country] rural urban financial inclusion gap", "[Country] rural digital payments", "[Country] mobile money rural", Global Findex urban/rural breakdowns, FinScope spatial analysis, household surveys with rural/urban, mobile network coverage maps, agent network rural distribution, financial access strand surveys. |

### Wealth/Income Inequality in Access

| Field | Value |
|---|---|
| Variable Id | pay-socialequity-wealthgap |
| Definition | Difference in digital payment access and usage across income quintiles or poverty status (poorest vs richest, poor vs non-poor), indicating whether payment systems are reaching low-income populations or exacerbating financial exclusion. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Specify if by income quintile, wealth quintile, or poverty status. Note gap magnitude and if narrowing/widening. Comment on affordability barriers for poor (fees, device costs, minimum balance). Distinguish account ownership vs active usage by wealth. Source household surveys with income/wealth data. |
| Data Collection Guidelines | Search: "[Country] financial inclusion by income", "[Country] poor unbanked digital", Global Findex wealth/income quintile data, FinScope income analysis, household income surveys with financial access modules, poverty assessments with digital payment usage, pro-poor payment studies. |

### Women Economic Empowerment

| Field | Value |
|---|---|
| Variable Id | pay-socialequity-womenempowerment |
| Definition | Evidence that digital payments have enhanced women's economic agency, control over finances, economic participation, and bargaining power within households and communities, including qualitative and quantitative evidence. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Note evidence types: women controlling own accounts/income, increased business participation, intrahousehold bargaining power, economic decision-making autonomy. Distinguish measured impacts vs perception studies. Cite women empowerment studies, gender impact assessments, mobile money gender research. |
| Data Collection Guidelines | Search: "[Country] women economic empowerment digital payments", "[Country] mobile money women empowerment", "[Country] gender impact digital finance", gender impact assessments, women economic empowerment studies, GSMA mobile money gender research, household decision-making studies, qualitative research on women financial autonomy, DFS gender impact evaluations. |

### Equity and Inclusion Impact Assessment

| Field | Value |
|---|---|
| Variable Id | pay-socialequity-equityassessment |
| Definition | Whether formal assessments of equity impacts, exclusion risks, and distributional effects of the payment system have been conducted by government, regulator, operators, academics, or civil society, and whether findings informed policy or design changes. |
| Format | Text (400 characters max); "NA" if unknown or not applicable |
| Other Metadata | Classification anchors: Yes - Comprehensive Assessment; Partial - Limited Assessment; No Assessment. Comprehensive: Multi-dimensional equity analysis with policy follow-up. Partial: Single study or ad hoc analysis. If Yes, cite assessment, date, conducting organization, key findings. Note if assessment led to policy/design changes (e.g., fee caps, tiered KYC, rural targets). |
| Data Collection Guidelines | Search: "[Country] payment system equity assessment", "[Country] digital financial inclusion impact evaluation", "[Country] payment system inclusion analysis", government impact assessments, regulatory reviews, academic impact studies, World Bank/donor evaluations, civil society equity reports, financial sector assessments with inclusion analysis. |
