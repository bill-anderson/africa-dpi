# Case individual stakeholder metadata

Variable definitions and collection guidance for case individual stakeholder.

## Linkage

### 

| Field | Value |
|---|---|
| Variable_Name | Individual_ID |
| Variable_ID | IND_001 |
| Definition | Unique identifier for the individual |
| Format | Text |
| Data_Collection_Guidance | Auto-generated. Format: [ISO country code]I[3-digit sequence]. The 'I' distinguishes individuals from institutions. Start at 001 for each country. Use country where individual is primarily based/active. |

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_ID |
| Variable_ID | IND_002 |
| Definition | Links individual to their primary institution (if applicable) |
| Format | Text (Foreign Key - Optional) |
| Data_Collection_Guidance | OPTIONAL. If individual works for mapped institution, use exact Institution_ID (e.g., ZA001). If independent (journalist, consultant, retired), use 'Independent'. If works for non-mapped institution (e.g., minor university, African Union, foreign org), use 'Non-Mapped Institution' and specify in Institution_Name_If_Not_Mapped. |

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_Name_If_Not_Mapped |
| Variable_ID | IND_003 |
| Definition | Name of institution if individual is affiliated but institution not in main dataset |
| Format | Text |
| Data_Collection_Guidance | Fill ONLY if Institution_ID = 'Non-Mapped Institution'. Examples: 'African Union Commission', 'University of Lagos', 'Independent Consultant', 'Freelance Journalist'. Leave blank if Institution_ID links to mapped institution or if truly independent. |

## Basic Information

### 

| Field | Value |
|---|---|
| Variable_Name | Individual_Name |
| Variable_ID | IND_004 |
| Definition | Full name of the individual |
| Format | Text |
| Data_Collection_Guidance | Search leadership pages, LinkedIn, news articles, conference speakers, publications. Use format 'FirstName LastName'. Add [Partial] if only surname known: 'Unknown [Partial] Surname'. Verify spelling across multiple sources. |

### 

| Field | Value |
|---|---|
| Variable_Name | Job_Title |
| Variable_ID | IND_005 |
| Definition | Current official job title/position or professional designation |
| Format | Text |
| Data_Collection_Guidance | For institutional roles: use exact title from website/LinkedIn (e.g., 'Chief Executive Officer', 'Director of Digital Identity'). For independent: use professional descriptor (e.g., 'Independent Digital Policy Consultant', 'Investigative Journalist specializing in tech policy', 'Emeritus Professor of Computer Science', 'Senior Research Fellow'). Verify current position. |

### 

| Field | Value |
|---|---|
| Variable_Name | Role_Category |
| Variable_ID | IND_006 |
| Definition | Standardized role category for analysis |
| Format | Categorical: Senior Leadership C-suite/Director \| Technical Lead \| Policy/Strategy Lead \| Operational Manager \| Program Manager \| Advocacy/Communications Lead \| Research Lead \| Legal/Compliance Lead \| Independent Expert/Consultant \| Journalist/Media \| Other |
| Data_Collection_Guidance | Categorize based on title and primary role. Senior Leadership = CEO, Executive Director, Minister, Director-General, VP; Technical Lead = CTO, Head of Engineering, Technical Director; Policy/Strategy = Chief Policy Officer, Head of Strategy; Independent Expert/Consultant = consultants, advisors not employed by mapped institution; Journalist/Media = journalists, editors, media analysts; Research Lead = Research Director, Principal Investigator, Professor. |

## Tenure

### 

| Field | Value |
|---|---|
| Variable_Name | Tenure_Start |
| Variable_ID | IND_007 |
| Definition | Start date in current position or independent practice |
| Format | Date (Partial) |
| Data_Collection_Guidance | Search LinkedIn, institution announcements, news archives. For independent consultants: when they started independent practice. For journalists: when they began covering DPI/digital policy. Use YYYY-MM if exact month known, YYYY if only year. Add ~ prefix for approximate dates (~2023). Use 'Unknown' if cannot be determined. |

### 

| Field | Value |
|---|---|
| Variable_Name | Years_In_Role |
| Variable_ID | IND_009 |
| Definition | Approximate years in current role or practice area |
| Format | Numeric |
| Data_Collection_Guidance | Calculate from Tenure_Start to present (or Tenure_End if departed). For independent experts: years focusing on DPI domain. Round to 1 decimal place. Use 'Unknown' if tenure dates unavailable. |

## DPI Experience

### 

| Field | Value |
|---|---|
| Variable_Name | DPI_Focus_Areas |
| Variable_ID | IND_010 |
| Definition | Individual's specific DPI domains of work/expertise |
| Format | Categorical: (Multiple) Digital Identity \| Digital Payments \| Data Sharing/Exchange \| Connectivity Infrastructure \| Cybersecurity \| Data Protection/Privacy \| Digital Skills/Literacy \| Interoperability Standards \| Digital Public Services \| Other |
| Data_Collection_Guidance | May differ from institutional focus. Check individual's project portfolio, publications, speeches, LinkedIn profile, articles written, research conducted. Select ALL areas where individual has demonstrated expertise/leadership. Separate with semicolon (;). |

### 

| Field | Value |
|---|---|
| Variable_Name | Previous_DPI_Role |
| Variable_ID | IND_011 |
| Definition | Previous relevant position in DPI ecosystem |
| Format | Text |
| Data_Collection_Guidance | Document most recent/relevant previous DPI role. Format: 'Job Title, Institution Name, YYYY-YYYY'. Example: 'Director of Payments, Central Bank, 2018-2022' or 'Senior Correspondent, Tech News Africa, 2015-2020'. Use LinkedIn, CVs, biographical profiles. |

## Expertise

### 

| Field | Value |
|---|---|
| Variable_Name | Technical_Expertise |
| Variable_ID | IND_012 |
| Definition | Level of individual's technical knowledge in DPI |
| Format | Categorical: Expert \| Advanced \| Intermediate \| Basic \| Non-technical \| Unknown |
| Data_Collection_Guidance | Check publications, presentations, qualifications, technical outputs. Expert = recognized technical authority, advanced degree/certification; Advanced = strong technical knowledge, can lead technical projects; Intermediate = moderate understanding; Basic = limited knowledge; Non-technical = policy/management/journalism focus without technical background. |

### 

| Field | Value |
|---|---|
| Variable_Name | Educational_Background |
| Variable_ID | IND_013 |
| Definition | Highest relevant degree and field |
| Format | Text |
| Data_Collection_Guidance | Search LinkedIn, bios, conference profiles. Format: 'PhD in Computer Science, MIT' or 'MBA, University of Cape Town'. Focus on highest/most relevant degree. Use 'Unknown' if not found. |

## Influence

### 

| Field | Value |
|---|---|
| Variable_Name | Decision_Authority |
| Variable_ID | IND_015 |
| Definition | Individual's decision-making power in DPI matters |
| Format | Categorical: Full Authority \| Significant Authority \| Moderate Authority \| Limited Authority \| No Authority \| Unknown |
| Data_Collection_Guidance | Assess from job title, organizational structure, decision documents. Full = can make final decisions (CEO, Minister); Significant = substantial decision power (Director); Moderate = shared decision-making (Manager); Limited = advisory role; No Authority = implementation only. For independent experts/journalists: typically 'Limited Authority' or 'No Authority' unless serving in advisory capacity to decision-makers. |

### 

| Field | Value |
|---|---|
| Variable_Name | Budget_Authority |
| Variable_ID | IND_016 |
| Definition | Whether individual controls DPI-related budget |
| Format | Categorical: Yes - Full \| Yes - Partial \| No \| Unknown |
| Data_Collection_Guidance | Check if individual has budget allocation/approval powers for DPI projects. Full = complete budget control; Partial = shared or limited budget authority; No = no budget control (typical for independent consultants, journalists, academics without grant management); Unknown = unclear. |

### 

| Field | Value |
|---|---|
| Variable_Name | Network_Position |
| Variable_ID | IND_017 |
| Definition | Position within DPI stakeholder networks |
| Format | Categorical: Central Hub \| Well-Connected \| Moderately Connected \| Peripheral \| Isolated \| Unknown |
| Data_Collection_Guidance | Assess from forum participation, board memberships, speaking engagements, co-authorships, partnerships, media citations. Central Hub = key connector across sectors, frequently referenced; Well-Connected = strong networks across multiple stakeholder types; Moderately Connected = some connections, mainly within sector; Peripheral = limited networks; Isolated = few connections. Independent experts/journalists with high visibility can be 'Central Hub' or 'Well-Connected'. |

### 

| Field | Value |
|---|---|
| Variable_Name | Influence_Type |
| Variable_ID | IND_018 |
| Definition | Primary mechanism through which individual exerts influence |
| Format | Categorical: (Multiple) Formal Authority \| Technical Expertise \| Thought Leadership \| Media Influence \| Network Position \| Research/Evidence \| Advocacy/Activism \| Funding Control \| Implementation Capacity \| Other |
| Data_Collection_Guidance | Select ALL applicable influence mechanisms. Formal Authority = official position power; Technical Expertise = recognized expert status; Thought Leadership = shapes discourse through ideas; Media Influence = shapes public opinion through journalism/commentary; Network Position = connector/broker role; Research/Evidence = influences through credible research; Advocacy = campaigns and mobilization; Funding Control = resource allocation power; Implementation = makes things happen. Separate with semicolon (;). |

## Engagement

### 

| Field | Value |
|---|---|
| Variable_Name | Public_Visibility |
| Variable_ID | IND_019 |
| Definition | Level of public visibility in DPI discussions |
| Format | Categorical: Very High \| High \| Medium \| Low \| Very Low \| Unknown |
| Data_Collection_Guidance | Assess from media presence, speaking engagements, social media, publications. Very High = regular media presence, keynote speaker, high social media following; High = frequent public commentary; Medium = occasional visibility; Low = rare public presence; Very Low = behind-the-scenes only. Independent journalists/analysts often have 'High' or 'Very High' visibility. |

### 

| Field | Value |
|---|---|
| Variable_Name | Publications_Output |
| Variable_ID | IND_020 |
| Definition | Recent publications on DPI topics |
| Format | Text |
| Data_Collection_Guidance | Document recent (last 3 years) publications, reports, papers, articles on DPI. Format: 'Title, YYYY'. Include: research papers, reports, policy briefs, op-eds, investigative journalism pieces, blog posts (if influential). Separate multiple with semicolon (;). Include links if available. Use 'None found' if no publications. |

### 

| Field | Value |
|---|---|
| Variable_Name | Speaking_Engagements |
| Variable_ID | IND_021 |
| Definition | Recent conference/event speaking engagements |
| Format | Text |
| Data_Collection_Guidance | Document recent (last 2 years) speaking at conferences, panels, webinars on DPI. Format: 'Event Name, YYYY-MM' or 'Event Name, YYYY'. Separate multiple with semicolon (;). Check conference programs, LinkedIn, YouTube. Use 'None found' if not available. |

## Data Provenance

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Source |
| Variable_ID | IND_025 |
| Definition | Sources consulted for individual data |
| Format | Text |
| Data_Collection_Guidance | Document ALL sources used. Format: 'Source description \| URL \| YYYY-MM-DD'. Separate multiple sources with semicolon (;). Example: 'LinkedIn profile \| https://linkedin.com/in/name \| 2026-03-09; Personal website \| https://example.com \| 2026-03-09; News byline \| https://news.com/author/name \| 2026-03-05'. |

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Collection_Date |
| Variable_ID | IND_026 |
| Definition | Date when data was collected |
| Format | Date |
| Data_Collection_Guidance | Use ISO 8601 format (YYYY-MM-DD). Record date when data collection was completed for this individual. |

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Collector |
| Variable_ID | IND_027 |
| Definition | Person/team who collected the data |
| Format | Text |
| Data_Collection_Guidance | Record researcher name or initials for quality control and follow-up. Use consistent format within dataset. |
