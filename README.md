# Incident Response Report Templates

Reusable, print-ready HTML templates for SOC incident reporting, mirroring the structure of Trend Micro XDR Workbench reports. Each template is organized into six sections: General Information, Scope & Affected Assets, Incident Description & Analysis, Response & Remediation, Recommendations & Post-Incident, and Incident Closure. Fill in every field directly in the browser and export to PDF with a single print command—no external tools required.

## Usage

1. Open the HTML file (`Incident_Report_Template.html`) in any modern browser (Chrome, Firefox, Edge, Safari).
2. Click any `[placeholder]` field and type your content directly—the template is fully inline-editable.
3. Use the toolbar at the top of the page to toggle **preview mode** (hides edit controls) or switch back to **edit mode** at any time.
4. When the report is complete, choose **Print → Save as PDF** for the final, A4-formatted deliverable.

## Features

- **MITRE ATT&CK technique mapping table** — document each tactic, technique ID, technique name, and observable evidence.
- **IoC table** — structured columns for file hashes (MD5/SHA-256), malicious URLs, domains, and filesystem paths.
- **Containment / Eradication / Recovery checklists** — checkbox-driven action items with owner and timestamp fields.
- **Root Cause Analysis with control-failure breakdown** — identify the root cause, the failed control, and the corrective action in a dedicated section.
- **A4 print layout** — CSS print styles enforce A4 page size, correct margins, and page-break rules so the exported PDF is submission-ready.

## License

MIT
