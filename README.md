# Justin Ghetti

Process automation and analytics professional focused on enterprise service and support operations. I design and ship systems that turn manual, error-prone workflows into governed, automated pipelines, working across Snowflake, Power BI, Power Automate, Salesforce, and Python.

Most of my work sits at the intersection of business process and technical implementation: understanding how a support process actually runs end to end, then building the automation that enforces it consistently and removes the manual effort.

Based in Greater Boston, MA &nbsp;|&nbsp; [LinkedIn](https://www.linkedin.com/in/your-handle) &nbsp;|&nbsp; Justin.Ghetti@gmail.com

---

## Selected Projects

Each project below replaced a manual process with an automated, governed system. Repositories include the problem context, architecture, logic, and measured impact. All schema names, account identifiers, and sensitive data have been sanitized.

### Policy-Compliance Control Suite
Automated controls that continuously check entitlements on enterprise licenses against pricing and policy rules, auto-create cases, and notify account owners with corrective steps. Catches violations that previously went undetected, supporting audit readiness and internal controls without manual review.
`Snowflake` `Power Automate` `Salesforce`
&rarr; [View project](https://github.com/Justin-Ghetti/policy-compliance-controls)

### SSO Gap Detector
Python pipeline that finds Campus-Wide License email domains whose SSO status is misrecorded, validates the real configuration through live browser-based detection, and routes each gap to the right owner. Eliminated a daily manual review and replaced ad-hoc spreadsheet tracking across 50+ enterprise accounts.
`Python` `Selenium` `Snowflake`
&rarr; [View project](https://github.com/Justin-Ghetti/sso-gap-detector)

### CNU Weekly Activation ETL Pipeline
End-to-end pipeline that replaced a fully manual weekly license-activation process. A 9-CTE Snowflake query categorizes every activation, feeds a Power BI semantic model, and triggers Power Automate to create pre-populated Salesforce cases. Eliminated ~80+ hours of manual work per year across a team of 8.
`Snowflake SQL` `Power BI` `Power Automate` `Salesforce`
&rarr; [View project](https://github.com/Justin-Ghetti/cnu-activation-etl)

---

## Tools I work with

**Data & queries:** Snowflake, SQL, Power BI (semantic models, Power Query / M)
**Automation:** Power Automate, Office Scripts, Python
**Apps & integration:** Streamlit, Selenium, Salesforce (Email-to-Case)
**Process:** workflow redesign, ETL pipeline design, change management, documentation standards

---

*More projects coming soon, including a license-migration plan generator (Streamlit) and an automated reporting-requirements engine.*
