# Case institution & stakeholder metadata

Variable definitions and collection guidance for case institution and stakeholder.

## Basic Information

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_ID |
| Variable_ID | INST_001 |
| Definition | Unique identifier for the institution |
| Format | Text |
| Data_Collection_Guidance | Auto-generated. Format: [ISO country code][3-digit sequence]. Start at 001 for each country. |

### 

| Field | Value |
|---|---|
| Variable_Name | Country |
| Variable_ID | INST_002 |
| Definition | Country where institution is based |
| Format | Text |
| Data_Collection_Guidance | Use ISO 3166-1 alpha-2 codes only (ZA, KE, NG, etc.). For pan-African institutions, use country of headquarters. |

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_Name |
| Variable_ID | INST_003 |
| Definition | Official name of the institution |
| Format | Text |
| Data_Collection_Guidance | Search official websites, company registries, NGO databases. Example: 'Central Bank of Kenya (CBK)'. Use English name if multiple languages available. |

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_Type |
| Variable_ID | INST_004 |
| Definition | Primary institutional category |
| Format | Categorical: Government \| Private Sector \| Civil Society/NGO \| Media \| Academic/Research \| International Organization \| Hybrid/Multi-Sector |
| Data_Collection_Guidance | Determine based on legal status, funding, governance. Government = state-owned/controlled; Private = commercial entity; Civil Society = non-profit advocacy/service; Media = journalism focus; Academic = research/teaching; International = multilateral/foreign; Hybrid = multiple types. |

### 

| Field | Value |
|---|---|
| Variable_Name | Institution_Subtype |
| Variable_ID | INST_005 |
| Definition | More specific institutional classification |
| Format | Text |
| Data_Collection_Guidance | Examples: Ministry, Regulatory Agency, Central Bank, State-Owned Enterprise, Bank, Telco, Fintech, Payment Provider, Advocacy NGO, Think Tank, News Outlet, University, UN Agency. Use consistent terminology. |

## DPI Mandate & Role

### 

| Field | Value |
|---|---|
| Variable_Name | DPI_Mandate |
| Variable_ID | INST_006 |
| Definition | Whether institution has explicit DPI mandate in legislation/policy |
| Format | Categorical: Yes \| No \| Unclear |
| Data_Collection_Guidance | Search enabling laws, regulations, strategic plans for explicit mention of digital identity, digital payments, data exchange, or digital infrastructure responsibilities. Yes = clear mandate; No = no formal mandate; Unclear = ambiguous or emerging mandate. |

### 

| Field | Value |
|---|---|
| Variable_Name | DPI_Role |
| Variable_ID | INST_007 |
| Definition | Primary functional roles in DPI ecosystem |
| Format | Categorical : Policy Maker \| Regulator \| Implementer \| System Integrator \| Service Provider \| Funding Source \| Advocacy/Watchdog \| Research/Advisory \| Capacity Builder \| User Representative \| Technical Standards Setter \| Unknown |
| Data_Collection_Guidance | Review institutional functions, project portfolios, press releases, partnerships. Select ALL applicable roles. Separate with semicolon (;). Examples: 'Policy Maker;Regulator' or 'Service Provider;System Integrator'. |

### 

| Field | Value |
|---|---|
| Variable_Name | DPI_Focus_Areas |
| Variable_ID | INST_008 |
| Definition | Specific DPI domains where institution is active |
| Format | Categorical : Digital Identity \| Digital Payments \| Data Sharing/Exchange \| Connectivity Infrastructure \| Cybersecurity \| Data Protection/Privacy \| Digital Skills/Literacy \| Interoperability Standards \| Digital Public Services \| Other |
| Data_Collection_Guidance | Search reports, project descriptions, news articles about DPI work. Select ALL applicable areas. Separate with semicolon (;). Include 'Other' if significant work doesn't fit categories. |

### 

| Field | Value |
|---|---|
| Variable_Name | Legal_Authority |
| Variable_ID | INST_009 |
| Definition | Type of legal authority held by institution |
| Format | Categorical: Legislative Authority \| Regulatory Authority \| Policy Development Authority \| Operational Authority \| Advisory/Consultative \| Commercial/Market-Based \| None/Limited \| Unclear |
| Data_Collection_Guidance | Check enabling legislation, regulatory powers, licensing authority. Legislative = law-making power; Regulatory = rule-making/enforcement; Policy Development = strategy/guidance; Operational = implementation; Advisory = consultation only; Commercial = market participation; None/Limited = no formal authority. |

## Contact & Digital Presence

### 

| Field | Value |
|---|---|
| Variable_Name | Website_URL |
| Variable_ID | INST_010 |
| Definition | Official institutional website |
| Format | Text (URL) |
| Data_Collection_Guidance | Search Google for official website, verify authenticity. Use 'None' if no website exists, 'Unknown' if cannot be determined. Include protocol (https:// or http://). |

### 

| Field | Value |
|---|---|
| Variable_Name | Contact_Email |
| Variable_ID | INST_011 |
| Definition | General institutional contact email |
| Format | Text (Email) |
| Data_Collection_Guidance | Find on website contact page. Use general/info email, not personal addresses. Use 'None' if not publicly available. |

### 

| Field | Value |
|---|---|
| Variable_Name | Physical_Location |
| Variable_ID | INST_012 |
| Definition | City and country of headquarters |
| Format | Text |
| Data_Collection_Guidance | Find on website or company registry. Format: 'Nairobi, Kenya' or 'Cape Town, South Africa'. Use headquarters if multiple offices. |

## Influence Assessment

### 

| Field | Value |
|---|---|
| Variable_Name | Power_Level |
| Variable_ID | INST_013 |
| Definition | Overall ability to influence DPI outcomes |
| Format | Categorical : Very High \| High \| Medium \| Low \| Very Low |
| Data_Collection_Guidance | Consider authority, resources, network, expertise, track record. Very High = can veto/independently decide (minister, regulator); High = strong influence (director, influential advocate); Medium = moderate influence (program manager); Low = limited influence; Very Low = minimal influence. |

### 

| Field | Value |
|---|---|
| Variable_Name | Legitimacy |
| Variable_ID | INST_014 |
| Definition | Recognized right to be involved in DPI decisions |
| Format | Categorical : Very High \| High \| Medium \| Low \| Very Low |
| Data_Collection_Guidance | Assess formal mandate and recognized role. Very High = clear legal/constitutional mandate; High = strong regulatory/policy mandate; Medium = recognized stakeholder; Low = informal role; Very Low = limited/disputed legitimacy. |

### 

| Field | Value |
|---|---|
| Variable_Name | Decision_Authority |
| Variable_ID | INST_015 |
| Definition | Level of decision-making power in DPI domain |
| Format | Categorical : Full Authority \| Significant Authority \| Moderate Authority \| Limited Authority \| No Authority |
| Data_Collection_Guidance | Check governance documents, decision processes. Full = final decision-maker; Significant = most decisions within domain; Moderate = shared decision-making; Limited = advisory role; No Authority = observer/external. |

### 

| Field | Value |
|---|---|
| Variable_Name | Resource_Control |
| Variable_ID | INST_016 |
| Definition | Control over financial/technical resources for DPI |
| Format | Categorical : Full Control \| Significant Control \| Moderate Control \| Limited Control \| No Control |
| Data_Collection_Guidance | Check budget documents, funding announcements. Full = controls budget/resources; Significant = substantial allocation power; Moderate = some resource influence; Limited = minimal access; No Control = dependent on others. |

### 

| Field | Value |
|---|---|
| Variable_Name | Network_Strength |
| Variable_ID | INST_017 |
| Definition | Connectivity to other key DPI stakeholders |
| Format | Categorical : Very Strong \| Strong \| Moderate \| Weak \| Very Weak |
| Data_Collection_Guidance | Check forum participation, partnerships, board memberships, MOUs. Very Strong = central hub; Strong = well-connected to key actors; Moderate = connected to some actors; Weak = limited connections; Very Weak = isolated. |

### 

| Field | Value |
|---|---|
| Variable_Name | Technical_Expertise |
| Variable_ID | INST_018 |
| Definition | Level of technical knowledge in DPI domains |
| Format | Categorical : Expert \| Advanced \| Intermediate \| Basic \| Non-technical |
| Data_Collection_Guidance | Check publications, presentations, qualifications of staff, technical outputs. Expert = recognized technical authority; Advanced = strong technical knowledge; Intermediate = moderate understanding; Basic = limited knowledge; Non-technical = no technical expertise. |

## Engagement

### 

| Field | Value |
|---|---|
| Variable_Name | Interest_Level |
| Variable_ID | INST_019 |
| Definition | Degree of interest/priority given to DPI work |
| Format | Categorical : Very High \| High \| Medium \| Low \| Very Low |
| Data_Collection_Guidance | Check speeches, publications, project allocations, public statements. Very High = priority focus; High = significant interest; Medium = moderate interest; Low = peripheral interest; Very Low = minimal/no interest. |

### 

| Field | Value |
|---|---|
| Variable_Name | Current_Engagement |
| Variable_ID | INST_020 |
| Definition | Current level of active participation in DPI |
| Format | Categorical : Leading \| Active \| Involved \| Monitoring \| Inactive \| Unknown |
| Data_Collection_Guidance | Check recent activities, meeting minutes, project documents. Leading = actively driving initiatives; Active = regularly participating; Involved = occasionally participating; Monitoring = observing only; Inactive = no recent participation; Unknown = unclear. |

### 

| Field | Value |
|---|---|
| Variable_Name | DPI_Advocacy |
| Variable_ID | INST_021 |
| Definition | Public advocacy stance on DPI development |
| Format | Categorical : Strong Advocate \| Moderate Advocate \| Neutral \| Moderate Critic \| Strong Critic \| Unknown |
| Data_Collection_Guidance | Review public statements, policy positions, campaigns. Strong Advocate = actively promotes DPI; Moderate Advocate = generally supportive; Neutral = no clear position; Moderate Critic = raises concerns; Strong Critic = opposes DPI; Unknown = unclear. |

### 

| Field | Value |
|---|---|
| Variable_Name | Collaboration_Type |
| Variable_ID | INST_022 |
| Definition | Types of collaborative relationships with other stakeholders |
| Format | Categorical : Public-Private Partnership \| Co-governance \| Service Delivery Partnership \| Funding Relationship \| Research Collaboration \| Technical Advisory \| Regulator-Regulatee \| Multi-stakeholder Forum \| Informal Network \| None |
| Data_Collection_Guidance | Identify formal/informal collaboration mechanisms. Select ALL applicable. Separate with semicolon (;). Check partnership agreements, MOUs, forum participation, joint projects. |

### 

| Field | Value |
|---|---|
| Variable_Name | Engagement_Barriers |
| Variable_ID | INST_023 |
| Definition | Identified barriers to effective engagement |
| Format | Text |
| Data_Collection_Guidance | Document challenges from reports, interviews, news articles. Examples: funding constraints, technical capacity gaps, political interference, coordination failures, data access issues, regulatory uncertainty. Use 'None identified' if no barriers found. |

## Positioning

### 

| Field | Value |
|---|---|
| Variable_Name | Policy_Position |
| Variable_ID | INST_024 |
| Definition | Overall policy stance on DPI development approach |
| Format | Categorical : Strongly Supportive \| Supportive \| Neutral/Balanced \| Supportive (privacy concerns \| Supportive (equity concerns \| Supportive (governance concerns \| Critical \| Strongly Critical \| Unknown |
| Data_Collection_Guidance | Synthesize from policy documents, public statements, advocacy positions. Note specific concerns in parentheses (privacy, equity, governance) if generally supportive but with reservations. |

## Activity Tracking

### 

| Field | Value |
|---|---|
| Variable_Name | Recent_Activity |
| Variable_ID | INST_025 |
| Definition | Recent DPI-related activities, projects, statements (last 12-24 months) |
| Format | Text |
| Data_Collection_Guidance | Document recent activities with brief description and date/timeframe. Format: 'Activity description - Month Year; Another activity - Month Year'. Check press releases, annual reports, news coverage, project announcements. |

## Funding

### 

| Field | Value |
|---|---|
| Variable_Name | Funding_Source |
| Variable_ID | INST_026 |
| Definition | Primary sources of institutional funding |
| Format | Categorical : Government Budget \| Private Sector \| Donor/Development Partner \| Membership Fees \| Revenue Generation \| Mixed Sources \| Unknown |
| Data_Collection_Guidance | Check annual reports, financial statements, about pages. Select ALL significant sources (>10% of budget). Separate with semicolon (;). Mixed Sources = diverse funding without clear dominance. |

## Participation

### 

| Field | Value |
|---|---|
| Variable_Name | Multi_Stakeholder_Forums |
| Variable_ID | INST_027 |
| Definition | Participation in multi-stakeholder DPI forums/processes |
| Format | Categorical : Active Participant \| Occasional Participant \| Involved \| Not Participating \| Unknown |
| Data_Collection_Guidance | Check participation in national DPI forums, working groups, consultations, regional forums. Active = regular participation with substantive input; Occasional = attends but limited input; Involved = observes or minimal participation; Not Participating = absent from multi-stakeholder processes. |

## Data Provenance

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Source |
| Variable_ID | INST_028 |
| Definition | Sources consulted for institutional data |
| Format | Text |
| Data_Collection_Guidance | Document ALL sources used. Format: 'Source description \| URL \| YYYY-MM-DD'. Separate multiple sources with semicolon (;). Example: 'Institution website \| https://example.org \| 2026-03-09; Annual report \| https://example.org/report.pdf \| 2025-12-31'. |

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Collection_Date |
| Variable_ID | INST_029 |
| Definition | Date when data was collected |
| Format | Date |
| Data_Collection_Guidance | Use ISO 8601 format (YYYY-MM-DD). Record date when data collection was completed for this institution. |

### 

| Field | Value |
|---|---|
| Variable_Name | Data_Collector |
| Variable_ID | INST_030 |
| Definition | Person/team who collected the data |
| Format | Text |
| Data_Collection_Guidance | Record researcher name or initials for quality control and follow-up. Use consistent format within dataset. |
