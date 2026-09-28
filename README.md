# PlaywrightADO — Playwright on Azure DevOps

Scaffold for running **Playwright** quality gates on **Azure DevOps** pipelines (ADO).

> Related: [PlaywrightTSFrameWork](https://github.com/Avinash258/PlaywrightTSFrameWork) · [HTD2.0Azure](https://github.com/Avinash258/HTD2.0Azure) · [Portfolio](https://avinash258.github.io/Protfolio/)

## Overview

Placeholder repository for Azure DevOps–centric Playwright pipeline patterns: install browsers on hosted agents, shard suites, publish HTML / JUnit / blob reports, and fail the build on quality-gate thresholds.

> **Note:** This repository is currently empty of application source. Use [PlaywrightTSFrameWork](https://github.com/Avinash258/PlaywrightTSFrameWork) for the full TypeScript framework and Azure YAML examples (`azure-pipelines*.yml`, `AZURE_SETUP.md`).

## Intended pipeline shape

1. `npm ci` + `npx playwright install --with-deps`
2. Sharded `npx playwright test --shard=n/m`
3. Merge blob / HTML reports
4. Publish artefacts and test results to ADO

## Author

**Pushanshu Avinash Sharma** — QA Automation Architect / Lead SDET  
[GitHub](https://github.com/Avinash258) · [LinkedIn](https://www.linkedin.com/in/p-avinash-sharma-8b0203b9/) · [Portfolio](https://avinash258.github.io/Protfolio/)
