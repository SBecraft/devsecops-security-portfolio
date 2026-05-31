# DevSecOps Security Portfolio

This repository contains vulnerability assessment reports and security findings
for projects in my development portfolio. All assessments were conducted using
industry standard DevSecOps tools and practices. As this portfolio grows,
security testing will be integrated earlier in the development lifecycle,
moving toward the DevSecOps principle of shifting security left.

## About

These assessments are part of my DevSecOps practice applying security testing
directly into the development workflow. Each assessment documents vulnerabilities
found, tools used, remediation steps taken, and accepted risk justifications
for any remaining findings.


## Tools and Methodology

| Tool | Type | Purpose |
|---|---|---|
| GitHub Dependabot | SCA | Dependency vulnerability scanning |
| GitHub CodeQL | SAST | Static source code analysis |
| GitHub Push Protection | Prevention | Block committed secrets |
| OWASP ZAP | DAST | Dynamic application security testing |
| Snyk | SAST/SCA | Code and dependency vulnerability scanning |


## Assessments

| Project | Type | Critical | High | Moderate | Remediated | Report |
|---|---|---|---|---|---|---|
| [world-map-country-data](https://github.com/SBecraft/angular-world-map-country-data) | Angular Web App | 0 | 16 | 22 | 31/38 | [View](angular-app-world-map/vulnerability-report-WorldMap.md) |

*Additional assessments will be added as projects are completed.*


## Repository Structure

```text
devsecops-security-portfolio/
├── project-name/
│   ├── FINDINGS-SUMMARY.md
│   ├── vulnerability-report.docx
│   ├── vulnerability-report.md
│   └── scans/
│       ├── before/
│       └── after/
```


## License
This work is licensed under CC BY-NC 4.0. See [LICENSE](LICENSE) for details.
