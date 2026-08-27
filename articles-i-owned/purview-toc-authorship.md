# Microsoft Purview Documentation — TOC Authorship Inventory

Source: Microsoft Learn docset TOC (learn.microsoft.com/en-us/purview), retrieved 2026-08-27.

**Annotation convention:** change `[ ]` to `[S]` (sole author), `[C]` (contributing author), or delete the line if you didn't write it. Section headings can be tagged once (e.g., "## Sensitive information types [S — entire section]") instead of tagging every row.

**Coverage note:** article-level detail below covers Get started, Shared capabilities, AI, DSPM, Information Protection (SITs, classifiers, labels, scanner), all of DLP, Data Security Investigations, Insider Risk Management, plus Audit and eDiscovery. The remaining compliance solutions (Communication Compliance, Compliance Manager, Data Lifecycle Management, Records Management, Information Barriers, Privileged Access Management) are listed at section level only — say the word and I'll expand any of them.

Base URL for all relative links: `https://learn.microsoft.com/en-us/purview/`

---

## Get started with Purview

- [ ] Learn about the Purview portal (`purview-portal`)
- [ ] Purview setup guides (`purview-fast-track-setup-guides`)
- [ ] Permissions in the Purview portal (`purview-permissions`)
- [ ] Purview Role Assignment Migrator (`purview-role-assignment-migrator`)
- [ ] Learn about Purview billing models (`purview-billing-models`)
- [ ] Consent to use pay-as-you-go capabilities (`purview-payg-consent-based-enablement`)
- [ ] Enable Purview pay-as-you-go features for new customers (`purview-payg-subscription-based-enablement`)
- [ ] Manage pay-as-you-go and per-user licensing usage (`purview-billing-usage`)
- [ ] Governance free version: get started (`data-governance-free-version-get-started`)
- [ ] Governance free version: upgrade to enterprise (`data-governance-free-version-upgrade-to-enterprise`)
- [ ] Purview Suite trial (`purview-trial`)
- [ ] Compliance Manager premium assessments trial (`purview-compliance-manager-assessments-trial`)
- [ ] How data flows in Purview (`purview-data-flows`)
- [ ] Extensibility with Purview (`purview-extensibility`)

## Shared capabilities

### Zero Trust / scopes / admin units
- [ ] Zero Trust with Microsoft Purview (`zero-trust-microsoft-purview`)
- [ ] Adaptive protection for insider risk management (`insider-risk-management-adaptive-protection`)
- [ ] Adaptive protection in data loss prevention (`dlp-adaptive-protection-learn`)
- [ ] Adaptive protection configuration guide (`insider-risk-management-adaptive-protection-guide`)
- [ ] Adaptive scopes (`purview-adaptive-scopes`)
- [ ] Administrative units (`purview-admin-units`)

### Explorers
- [ ] Get started with data explorer (`data-classification-data-explorer`)
- [ ] Get started with content explorer (classic) (`data-classification-content-explorer`)
- [ ] Get started with activity explorer (`data-classification-activity-explorer`)
- [ ] Labeling actions reported in Activity explorer (`data-classification-activity-explorer-available-events`)

### Data connectors
- [ ] Learn about connectors for third-party data (`archive-third-party-data`)
- [ ] Microsoft connectors (Anthropic Claude, Bloomberg Message, Facebook Business, Generic EHR, HR data, HR data US Gov, ICE Chat, Insider Risk Indicators, Instant Bloomberg, LinkedIn, Physical badging, Twitter ×2) — 13 articles, `manage-anthropic-data`, `archive-*`, `import-*`
- [ ] TeleMessage connectors (Android, AT&T, Bell, Enterprise Number, HK CSL, O2, Rogers, Signal, T-Mobile, Telegram, TELUS, Verizon, WeChat, WhatsApp Archivers) — 14 articles, `archive-*`
- [ ] 17a-4 DataParser connectors (BlackBerry, Bloomberg, Cisco Jabber, Webex, FactSet, Fuze, FX Connect, ICE, InvestEdge, LivePerson, Quip, Refinitiv, ServiceNow, Skype for Business Server, Slack, SQL, Symphony, Zoom) — 18 articles, `archive-17a-4-*`
- [ ] CellTrust SL2 (`archive-data-from-celltrustsl2`)
- [ ] Search for third-party data (`use-content-search-to-search-third-party-data-that-was-imported`)
- [ ] View admin logs for data connectors (`data-connector-admin-logs`)

### Collection policies
- [ ] Collection Policies solution overview (`collection-policies-solution-overview`)
- [ ] Create and deploy collection policies (`collection-policies-create-deploy-policy`)
- [ ] Collection policies policy reference (`collection-policies-policy-reference`)

### Device onboarding
- [ ] Device health reports dashboard (`device-onboarding-health-reports-dashboard`)
- [ ] Onboard Windows devices: overview (`device-onboarding-overview`)
- [ ] Onboard Windows devices: Intune (`device-onboarding-mdm`)
- [ ] Onboard Windows devices: Configuration Manager (`device-onboarding-sccm`)
- [ ] Onboard Windows devices: Group Policy (`device-onboarding-gp`)
- [ ] Onboard Windows devices: local script (`device-onboarding-script`)
- [ ] Onboard Windows devices: non-persistent VDI (`device-onboarding-vdi`)
- [ ] Onboard macOS devices: overview (`device-onboarding-macos-overview`)
- [ ] Onboard macOS devices: Intune (`device-onboarding-offboarding-macos-intune`)
- [ ] Onboard macOS devices: Intune for MDE (`device-onboarding-offboarding-macos-intune-mde`)
- [ ] Onboard macOS devices: JAMF Pro (`device-onboarding-offboarding-macos-jamfpro`)
- [ ] Onboard macOS devices: JAMF Pro for MDE customers (`device-onboarding-offboarding-macos-jamfpro-mde`)
- [ ] Onboard macOS devices: any MDM without MDE (`device-onboarding-offboarding-any-mdm-no-mde`)
- [ ] Onboard macOS devices: any MDM for MDE customers (`device-onboarding-offboarding-macos-any-mdm`)
- [ ] Configure device proxy and internet connection settings (`device-onboarding-configure-proxy`)

### Other shared capabilities
- [ ] Learn about optical character recognition (`ocr-learn-about`)
- [ ] Estimate your OCR costs (`ocr-cost-estimator`)
- [ ] On-demand classification (`on-demand-classification`)
- [ ] Security Copilot in Purview (`copilot-in-purview-overview`)
- [ ] Copilot in Purview promptbooks (`copilot-in-purview-promptbooks`)
- [ ] Security Copilot Agents in Purview overview (`copilot-in-purview-agents-overview`)
- [ ] Data Security Triage Agent in Insider Risk Management (`copilot-in-purview-triage-irm-agent-get-started`)
- [ ] Data Security Triage Agent in Data Loss Prevention (`copilot-in-purview-triage-dlp-agent-get-started`)
- [ ] Configure Microsoft Teams for the Data Security Triage Agent (`copilot-in-purview-triage-dlp-agent-teams-config`)
- [ ] Data Security Posture Agent (`copilot-in-purview-posture-agent-get-started`)
- [ ] Data Security Posture Agent in Data Security Investigations (`data-security-investigations-posture-agent`)
- [ ] Learn about Microsoft Sentinel in Purview (`purview-sentinel`)
- [ ] Data risk graph in Data Security Investigations (`data-security-investigations-data-risk-graph`)
- [ ] Data risk graph in Insider Risk Management (`insider-risk-management-data-risk-graph`)
- [ ] Export policy configuration (`purview-policy-export`)

## Data security & compliance for AI

- [ ] Learn about data security & compliance for AI (`ai-microsoft-purview`)
- [ ] Microsoft 365 Copilot (`ai-m365-copilot`)
- [ ] Microsoft Security Copilot (`ai-security-copilot`)
- [ ] Copilot in Fabric (`ai-copilot-fabric`)
- [ ] Microsoft Copilot Studio (`ai-copilot-studio`)
- [ ] Microsoft Facilitator (`ai-teams-facilitator`)
- [ ] Channel Agent in Teams (`ai-teams-channel-agent`)
- [ ] Microsoft Agent 365 (`ai-agent-365`)
- [ ] Entra-registered AI apps (`ai-entra-registered`)
- [ ] Microsoft Foundry (`ai-azure-foundry`)
- [ ] ChatGPT Enterprise (`ai-chatgpt-enterprise`)
- [ ] Anthropic Claude (Enterprise) (`ai-claude-enterprise`)
- [ ] Other AI apps (`ai-other-apps`)
- [ ] AI agents (`ai-agents`)
- [ ] Considerations for Microsoft 365 Copilot and Channel Agent in Teams (`ai-m365-copilot-considerations`)

## Data Security Posture Management (DSPM)

- [ ] Learn about DSPM (`data-security-posture-management-learn-about`)
- [ ] Find familiar tasks from previous versions
- [ ] Prevent oversharing with data risk assessments
- [ ] Setup tasks for DSPM
- [ ] Permissions for DSPM
- [ ] Considerations for DSPM
- [ ] Application card for DSPM
- [ ] Supported AI sites for DSPM
- [ ] Previous versions of DSPM

## Data governance solutions (section level — expand on request)

- [ ] Data governance overview / Unified Catalog / Data Map / Master data management / Technical reference / Classic Data Governance

## Information protection

- [ ] Know your data, protect your data, prevent data loss (`information-protection`)
- [ ] Deploy an information protection solution
- [ ] Office 365 operated by 21Vianet
- [ ] Default labels and policies to protect your data
- [ ] Reports

### Sensitive information types — learn
- [ ] Learn about sensitive information types (`sit-sensitive-information-type-learn-about`)
- [ ] Learn about exact data match based SITs (`sit-learn-about-exact-data-match-based-sits`)
- [ ] Document fingerprinting (`sit-document-fingerprinting`)
- [ ] Learn about named entities (`sit-named-entities-learn`)

### Sensitive information types — get started
- [ ] Create a custom sensitive information type (`sit-create-a-custom-sensitive-information-type`)
- [ ] Test a sensitive information type (`sit-test-a-sit`)
- [ ] EDM workflow overview (new experience) (`sit-create-edm-sit-unified-ux-workflow`)
- [ ] Export source data (new experience) (`sit-get-started-exact-data-match-export-data`)
- [ ] Create an EDM SIT sample file (`sit-create-edm-sit-unified-ux-sample-file`)
- [ ] Create an EDM schema and EDM SIT (`sit-create-edm-sit-unified-ux-schema-rule-package`)
- [ ] Multi-token matching for corroborative evidence in EDM SITs (`sit-edm-use-multi-token-evidence`)
- [ ] Test an EDM sensitive information type (`sit-get-started-exact-data-match-test`)
- [ ] EDM classic experience workflow (`sit-create-edm-sit-classic-ux-workflow`)
- [ ] Create an EDM schema (classic) (`sit-get-started-exact-data-match-create-schema`)
- [ ] Hash and upload the sensitive information source table (classic) (`sit-get-started-exact-data-match-hash-upload`)
- [ ] Create EDM SIT/rule package (classic) (`sit-get-started-exact-data-match-create-rule-package`)

### Sensitive information types — use
- [ ] Customize a built-in SIT (`sit-customize-a-built-in-sensitive-information-type`)
- [ ] Modify EDM schema to use configurable match (`sit-modify-edm-schema-configurable-match`)
- [ ] Create notifications for EDM activities (`sit-edm-notifications-activities`)
- [ ] Manage custom SITs (`sit-manage-custom-sits-compliance-center`)
- [ ] SIT REGEX validators and additional checks (`sit-regex-validators-additional-checks`)
- [ ] Create a custom SIT — PowerShell (`sit-create-a-custom-sensitive-information-type-in-scc-powershell`)
- [ ] Remove a custom SIT — PowerShell (`sit-remove-a-custom-sensitive-information-type-in-powershell`)
- [ ] Modify a custom SIT — PowerShell (`sit-modify-a-custom-sensitive-information-type-in-powershell`)
- [ ] Create a keyword dictionary (`sit-create-a-keyword-dictionary`)
- [ ] Modify a keyword dictionary (`sit-modify-keyword-dictionary`)
- [ ] Manage your EDM schema (`sit-use-exact-data-manage-schema`)
- [ ] Refresh your EDM source table file (`sit-use-exact-data-refresh-data`)
- [ ] Use named entities in DLP policies (`sit-named-entities-use`)
- [ ] Common usage scenarios for SITs (`sit-common-scenarios`)

### Sensitive information types — reference
- [ ] Sensitive information type functions (`sit-functions`)
- [ ] Custom SIT filters reference (`sit-custom-sit-filters`)
- [ ] Sensitive information type limits (`sit-limits`)

### Sensitive information type entity definitions
*(One tag on this heading likely covers the whole set — ~300 articles, slugs `sit-defn-*`.)*

- [ ] Sensitive information type entity definitions index (`sit-sensitive-information-type-entity-definitions`)
- [ ] ABA routing number • All credentials • All full names • All medical terms and conditions • All physical addresses
- [ ] Amazon S3 client secret access key • ASP.NET machine key • Client secret / API key • General password • General symmetric key • GitHub personal access token • Google API key • Http authorization header • Microsoft Bing maps key • Slack access token • SQL Server connection string • User login credentials • X.509 certificate private key
- [ ] Azure credential SITs (~30: App Service deployment password, Batch shared access key, Bot Framework secret key, Bot service app secret, Cognitive Search API key, Cognitive Service key, Container Registry access key, Cosmos DB account access key, Databricks personal access token, DevOps app secret, DevOps personal access token, DocumentDB auth key, EventGrid access key, Function master/API key, IAAS database connection string, IoT connection string, IoT shared access key, Logic App SAS, ML web service API key, Maps subscription key, publish setting password, Redis cache connection strings, SAS, service bus connection string/SAS, shared access key/web hook token, SignalR access key, SQL connection string, storage account keys/SAS ×5, subscription management certificate)
- [ ] Microsoft Entra SITs (client access token, client secret, user credentials)
- [ ] Financial SITs (credit card number, EU debit card number, IBAN, SWIFT code, US bank account number, US ITIN, plus per-country bank account numbers: Australia, Canada, Israel, Japan, New Zealand)
- [ ] Medical/health SITs (blood test terms, brand/generic medication names, diseases, DEA number, ICD-9/ICD-10, impairments (US disability evaluation), lab test terms, lifestyles related to medical conditions, medical specialties, Medicare Beneficiary Identifier, surgical procedures, types of medication)
- [ ] Country/region identity SITs — Argentina, Australia, Austria, Belgium, Brazil, Bulgaria, Canada, Chile, China, Croatia, Cyprus, Czechia, Denmark, Ecuador, Estonia, EU (drivers license, national ID, passport, SSN, tax ID, debit card), Finland, France, Germany, Greece, Hong Kong, Hungary, Iceland, India, Indonesia, Ireland, Israel, Italy, Japan, Latvia, Liechtenstein, Lithuania, Luxemburg, Malaysia, Malta, Mexico, Netherlands, New Zealand, Norway, Philippines, Poland, Portugal, Qatar, Romania, Russia, Saudi Arabia, Singapore, Slovakia, Slovenia, South Africa, South Korea, Spain, Sweden, Switzerland, Taiwan, Thailand, Turkey, UAE, U.K., Ukraine, U.S. — drivers licenses, passports, national IDs, tax IDs, social security/insurance numbers, physical addresses (~200 articles, `sit-defn-<country>-*`)
- [ ] IP address SITs (IP address, IPv4, IPv6)

## Trainable classifiers

- [ ] Data classifiers overview (`data-classification-overview`)
- [ ] Learn about trainable classifiers (`trainable-classifiers-learn-about`)
- [ ] Get started with trainable classifiers (`trainable-classifiers-get-started-with`)
- [ ] Increase classifier accuracy (`data-classification-increase-accuracy`)
- [ ] Trainable classifier definitions (`trainable-classifiers-definitions`)

## Sensitivity labels

- [ ] Learn about sensitivity labels (`sensitivity-labels`)
- [ ] Get started with sensitivity labels (`get-started-with-sensitivity-labels`)
- [ ] Create and publish sensitivity labels (`create-sensitivity-labels`)
- [ ] Migrate to the modern label scheme (`migrate-sensitivity-label-scheme`)
- [ ] Restrict access to content by using sensitivity labels to apply encryption (`encryption-sensitivity-labels`)
- [ ] Automatically apply a sensitivity label (`apply-sensitivity-label-automatically`)
- [ ] Protect collaborative workspaces (`sensitivity-labels-teams-groups-sites`)
- [ ] Protect meetings (`sensitivity-labels-meetings`)
- [ ] Enable labels for Office files in SharePoint and OneDrive (`sensitivity-labels-sharepoint-onedrive-files`)
- [ ] Use sensitivity labels with Loop (`sensitivity-labels-loop`)
- [ ] Default label for SharePoint libraries (`sensitivity-labels-sharepoint-default-label`)
- [ ] Extend SharePoint permissions with a default label (`sensitivity-labels-sharepoint-extend-permissions`)
- [ ] Co-authoring for encrypted documents (`sensitivity-labels-coauthoring`)
- [ ] Default sharing link type via labels (`sensitivity-labels-default-sharing-link`)
- [ ] Manage sensitivity labels in Office apps (`sensitivity-labels-office-apps`)
- [ ] Minimum versions for labels in Office apps (`sensitivity-labels-versions`)
- [ ] Extend sensitivity labeling on Windows (`information-protection-client`)

## Information protection on-premises scanner

- [ ] Learn about the scanner (`deploy-scanner`)
- [ ] Get started with the scanner (`deploy-scanner-prereqs`)
- [ ] Configure & install the scanner (`deploy-scanner-configure-install`)
- [ ] Run the scanner (`deploy-scanner-manage`)
- [ ] Scanner feature control (preview) (`deploy-scanner-feature-control`)
- [ ] Custom reporting (preview) (`deploy-scanner-custom-reporting`)
- [ ] Supported sensitive information types (`deploy-scanner-supported-sits`)
- [ ] Upgrade the scanner (`upgrade-scanner-migrate`)

## Data loss prevention

### Learn about DLP
- [ ] Learn about data loss prevention (`dlp-learn-about-dlp`)
- [ ] Plan for data loss prevention (`dlp-overview-plan-for-dlp`)
- [ ] Design a DLP policy (`dlp-policy-design`)
- [ ] Create and deploy data loss prevention policies (`dlp-create-deploy-policy`)
- [ ] Test your DLP policies (`dlp-test-dlp-policies`)
- [ ] Learn about using regular expressions in DLP policies (`dlp-policy-learn-about-regex-use`)
- [ ] Learn about Adaptive Protection in DLP (`dlp-adaptive-protection-learn`)
- [ ] Learn about DLP simulation mode (`dlp-simulation-mode-learn`)
- [ ] Get started with DLP simulation mode (`dlp-simulation-mode-get-started`)
- [ ] Learn about Advanced Label Based Protection (`dlp-learn-about-advanced-label-protection`)
- [ ] Get started with Power Automate integration in Purview DLP (`dlp-powerautomate-int-get-started`)
- [ ] Use notifications and policy tips in DLP policies (`dlp-use-notifications-and-policy-tips`)
- [ ] Use sensitivity labels as a condition in DLP policies (`dlp-sensitivity-label-as-condition`)
- [ ] Learn about DLP file quarantine for SharePoint and OneDrive (`dlp-spo-odb-quarantine-learn`)

### Protect data in enterprise applications
- [ ] Help prevent sharing credit card numbers through email (`dlp-create-policy-cc-email`)
- [ ] Help prevent sharing sensitive items via SharePoint/OneDrive with external users (`dlp-create-policy-spo-odb-external`)
- [ ] Help prevent sharing Power BI reports with credit card numbers (`dlp-create-policy-powerbi-cc-numbers`)
- [ ] Create a DLP policy to protect documents with FCI or other properties (`dlp-protect-documents-that-have-fci-or-other-properties`)
- [ ] Learn about DLP on-premises scanner (`dlp-on-premises-scanner-learn`)
- [ ] Learn about the default DLP policy in Microsoft Teams (`dlp-teams-default-policy`)
- [ ] DLP and Microsoft Teams (`dlp-microsoft-teams`)
- [ ] Learn about the Microsoft 365 Copilot and Copilot Chat location (`dlp-microsoft365-copilot-location-learn-about`)
- [ ] Learn about the default DLP policy for Microsoft 365 Copilot location (`dlp-microsoft365-copilot-location-default-policy`)
- [ ] Get started with DLP on-premises repositories (`dlp-on-premises-scanner-get-started`)
- [ ] Use DLP with on-premises repositories (`dlp-on-premises-scanner-use`)
- [ ] Get started with DLP policies for Fabric and Power BI (`dlp-powerbi-get-started`)
- [ ] Get started with oversharing pop ups (`dlp-osp-get-started`)
- [ ] Use DLP policies for non-Microsoft cloud apps (`dlp-use-policies-non-microsoft-cloud-apps`)
- [ ] Learn about the default Office 365 DLP policy (`dlp-o365-default-policy`)
- [ ] Get started with DLP file quarantine for SharePoint and OneDrive (`dlp-spo-odb-quarantine-get-started`)
- [ ] Create a DLP policy to quarantine files in SharePoint and OneDrive (`dlp-create-policy-spo-odb-quarantine`)

### Protect data on enterprise devices (Endpoint DLP)
- [ ] Learn about Endpoint DLP (`endpoint-dlp-learn-about`)
- [ ] Get started with Endpoint DLP (`endpoint-dlp-getting-started`)
- [ ] Configure endpoint DLP settings (`dlp-configure-endpoint-settings`)
- [ ] Use Endpoint DLP (`endpoint-dlp-using`)
- [ ] Create policy to audit activities using a template (`endpoint-dlp-create-policy-audit-activities`)
- [ ] Create policy to manage printer access using authorization groups (`endpoint-dlp-create-policy-manage-printer-access`)
- [ ] Create policy to detect and alert on U.S. PII data exposure (`endpoint-dlp-create-policy-detect-pii-data-exposure`)
- [ ] Help prevent unauthorized sensitive data sharing with block actions and allow overrides (`endpoint-dlp-create-policy-unauthorized-data-sharing`)
- [ ] Help prevent risky user activity — sensitive service domains (`endpoint-dlp-create-policy-restrict-access-to-domains`)
- [ ] Help prevent leakage — restrict paste into browsers (`endpoint-dlp-create-policy-restrict-paste-in-browsers`)
- [ ] Auto-quarantine for OneDrive sync (`endpoint-dlp-create-policy-auto-quarantine-for-onedrive`)
- [ ] Unauthorized cloud apps and services (`endpoint-dlp-create-policy-unauthorized-cloud-apps-services`)
- [ ] File activities with network exceptions (`endpoint-dlp-create-policy-file-activities-using-network-exceptions`)
- [ ] Create policy that uses device scoping (`endpoint-dlp-create-policy-device-scoping`)
- [ ] Troubleshooting endpoint DLP configuration and policy sync (`dlp-edlp-tshoot-sync`)
- [ ] Learn about just-in-time protection (`endpoint-dlp-learn-about-jit`)
- [ ] Get started with just-in-time protection (`endpoint-dlp-get-started-jit`)
- [ ] Help protect files that Endpoint DLP fails to scan (`dlp-create-policy-edlp-scan-fails`)
- [ ] Help protect files that Endpoint DLP doesn't scan (`dlp-create-policy-files-edlp-doesnt-scan`)
- [ ] Protect against sharing of a defined set of unsupported files (`dlp-create-policy-sharing-set-unsupported-files`)
- [ ] Disable DLP scanning for some supported files and apply controls (`dlp-create-policy-disable-scan-supported-files`)
- [ ] Always-on diagnostics for endpoint DLP (`dlp-always-on-diagnostics`)
- [ ] Learn about the Purview extension for Chrome (`dlp-chrome-learn-about`)
- [ ] Get started with the Purview extension for Chrome (`dlp-chrome-get-started`)
- [ ] Learn about the Purview extension for Firefox (`dlp-firefox-extension-learn`)
- [ ] Get started with the Purview extension for Firefox (`dlp-firefox-extension-get-started`)
- [ ] Learn about evidence collection for file activities on devices (`dlp-copy-matched-items-learn`)
- [ ] Get started with collecting files that match DLP policies from devices (`dlp-copy-matched-items-get-started`)
- [ ] Get started with DLP protections for Recall (`dlp-recall-get-started`)
- [ ] Learn about the default DLP policy for devices (`endpoint-dlp-default-device-policy`)

### Protect data inline web traffic
- [ ] Learn about DLP for Cloud Apps in Edge for Business (`dlp-browser-dlp-learn`)
- [ ] Learn about Purview Network Data Security (`dlp-network-data-security-learn`)
- [ ] Network Data Security — unmanaged AI apps (`dlp-create-policy-ai-network-data-security`)
- [ ] Prevent sharing via Edge for Business to unmanaged AI apps (`dlp-create-policy-block-to-ai-via-edge`)
- [ ] Prevent sharing sensitive info with cloud apps in Edge for Business (`dlp-create-policy-prevent-cloud-sharing-from-edge-biz`)

### Investigate alerts
- [ ] Learn about investigating data loss prevention alerts (`dlp-alert-investigation-learn`)
- [ ] Get started with the DLP alert dashboard (`dlp-alerts-dashboard-get-started`)
- [ ] Get started with data loss prevention alerts (`dlp-alerts-get-started`)
- [ ] Get started with data loss prevention analytics (`dlp-analytics-get-started`)

### Migrate
- [ ] Migrate Exchange Online DLP policies to Purview portal (`dlp-migrate-exo-policy-to-unified-dlp`)
- [ ] Learn about the DLP migration assistant for Symantec and Forcepoint (`dlp-migration-assistant-for-symantec-learn`)
- [ ] Get started with the DLP migration assistant for Symantec and Forcepoint (`dlp-migration-assistant-for-symantec-get-started`)
- [ ] Use the DLP migration assistant for Symantec (`dlp-migration-assistant-for-symantec-use`)

### Reference
- [ ] Data loss prevention policy reference (`dlp-policy-reference`)
- [ ] What the DLP policy templates include (`dlp-policy-templates-include`)
- [ ] DLP Exchange conditions and actions reference (`dlp-exchange-conditions-and-actions`)
- [ ] DLP policy tips reference (`dlp-policy-tips-reference`)
- [ ] Policy tip reference — Outlook for Microsoft 365 (`dlp-ol365-win32-policy-tips`)
- [ ] Policy tip reference — Outlook on the Web (`dlp-owa-policy-tips`)
- [ ] Policy tip reference — SharePoint Online / OneDrive web (`dlp-spo-odbweb-policy-tips`)
- [ ] DLP in new Outlook for Windows (`dlp-policy-reference-new-outlook`)
- [ ] Policy tip reference — Outlook for Android, iOS, macOS (`dlp-outlook-mobile-policy-tip-ref`)

## Data Security Investigations

- [ ] Learn about Data Security Investigations
- [ ] Learn about the DSI workflow
- [ ] AI analysis in DSI
- [ ] Get started with DSI
- [ ] Create an investigation
- [ ] Search, review, and analyze incident information
- [ ] Review recommendations
- [ ] Take mitigation actions
- [ ] View and manage activities
- [ ] AI and privacy in DSI
- [ ] DSI references

## Insider Risk Management

- [ ] Solution overview (`insider-risk-management-solution-overview`)
- [ ] Learn about insider risk management (`insider-risk-management`)
- [ ] Plan (`insider-risk-management-plan`)
- [ ] Configure (`insider-risk-management-configure`)
- [ ] Permissions (`insider-risk-management-permissions`)
- [ ] Privacy guide (`insider-risk-solution-privacy`)
- [ ] Monitoring agents (`insider-risk-management-monitoring-agents`)
- [ ] Settings (15 articles: `insider-risk-management-settings*` — privacy, policy indicators, detection groups, global exclusions, policy timeframes, intelligent detections, data sharing, priority user groups, priority physical assets, Power Automate, Teams, analytics, admin notifications, inline alert customization)
- [ ] Learn about policy templates (`insider-risk-management-policy-templates`)
- [ ] Create and manage policies (`insider-risk-management-policies`)
- [ ] Investigate activities (`insider-risk-management-activities`)
- [ ] Data risk graph (`insider-risk-management-data-risk-graph`)
- [ ] Best practices for alert tuning (`insider-risk-management-best-practices-alert-tuning`)

## Compliance solutions

### Audit
- [ ] Audit solutions overview (`audit-solutions-overview`)
- [ ] Get started with auditing solutions (`audit-get-started`)
- [ ] Search the audit log (`audit-search`)
- [ ] Audit log activities (`audit-log-activities`)
- [ ] Use a PowerShell script to search the audit log (`audit-log-search-script`)
- [ ] Export, configure, and view audit log records (`audit-log-export-records`)
- [ ] Manage audit log retention policies (`audit-log-retention-policies`)

### eDiscovery
- [ ] Overview (`edisc`) • Workflow (`edisc-workflow`) • Get started (`edisc-get-started`)
- [ ] Search: query (`edisc-search-query`), KQL (`edisc-keyword-query-language`), condition builder (`edisc-condition-builder`), results (`edisc-search-results`), export (`edisc-search-export`)
- [ ] Cases (`edisc-cases-manage`) • Holds (`edisc-hold-create`) • Permissions (`edisc-permissions`) • Data sources (`edisc-data-sources`)
- [ ] Search and delete: mailbox (`edisc-search-mailbox-data`), Teams (`edisc-search-teams-data`), Copilot/AI data (`edisc-search-copilot-data`)
- [ ] Review sets: manage (`edisc-review-set-manage`), external data (`edisc-review-set-external-data`), filtering (`edisc-review-set-search`), explorer/KQL (`edisc-review-set-explorer`), query report (`edisc-review-set-query-report`), tagging (`edisc-review-set-tagging`), analytics (`edisc-review-set-analytics`), view (`edisc-review-set-view`)
- [ ] Cloud attachments (`edisc-cloud-attachments`) • Decryption (`edisc-decryption`) • Advanced indexing (`edisc-ref-advanced-indexing`) • Process tracking (`edisc-process-managers`, `edisc-process-report`) • Guest access (`edisc-settings-guest-users`) • Graph API (`edisc-ref-api-guide`)

### Section stubs — expand on request
- [ ] Communication Compliance (`communication-compliance-solution-overview`)
- [ ] Compliance Manager (`compliance-manager`)
- [ ] Data Lifecycle Management (`data-lifecycle-management`)
- [ ] Records Management (`records-management`)
- [ ] Information Barriers (`information-barriers`)
- [ ] Privileged Access Management (`privileged-access-management-solution-overview`)
