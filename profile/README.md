# Penn State University
## [Endpoint Management](https://uem.psu.edu)

Dedicated to the deployment of system operating systems and software, these repositories assist in the process of managing Penn State endpoints.

### [UEM Patch Reporting](https://github.com/psu-em/patch_reports)


A selection of actions running functions for UEM, CLM, and Jamf.

#### Reports

[![Build UEM Jamf Reports](https://github.com/psu-em/patch_reports/actions/workflows/build_jamf.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/build_jamf.yml)
[![Build UEM BigFix Reports](https://github.com/psu-em/patch_reports/actions/workflows/build_bf.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/build_bf.yml)
[![Build UEM MCM Reports](https://github.com/psu-em/patch_reports/actions/workflows/build_mcm.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/build_mcm.yml)

#### Emails

[![Email Patch Reports](https://github.com/psu-em/patch_reports/actions/workflows/patch.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/patch.yml)
[![Email Stale Devices Reports](https://github.com/psu-em/patch_reports/actions/workflows/stale.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/stale.yml)
[![Email Missing Username Devices Reports](https://github.com/psu-em/patch_reports/actions/workflows/missing_user_email.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/missing_user_email.yml)

#### Actions
[![Isolate Stale Devices](https://github.com/psu-em/patch_reports/actions/workflows/isolate.yml/badge.svg)](https://github.com/psu-em/patch_reports/actions/workflows/isolate.yml)

### [macOS AutoPkg Recipes](https://github.com/psu-em/autopkg-recipes)

A private collection of [AutoPkg](https://github.com/autopkg/autopkg) recipes used by Endpoint Management for [Unified Endpoint Management](https://pennstateoffice365.sharepoint.com/sites/UEM) services.

[![AutoPkg Daily Run](https://github.com/psu-em/autopkg-recipes/actions/workflows/cron.yml/badge.svg)](https://github.com/psu-em/autopkg-recipes/actions/workflows/cron.yml)
[![AutoPkg workflow](https://github.com/psu-em/autopkg-recipes/actions/workflows/push.yml/badge.svg)](https://github.com/psu-em/autopkg-recipes/actions/workflows/push.yml)

### [Windows AutoPkg Recipes](https://github.com/psu-em/autopkg-recipes-win)

A private collection of Windows [AutoPkg](https://github.com/autopkg/autopkg) recipes used by Endpoint Management for [Unified Endpoint Management](https://pennstateoffice365.sharepoint.com/sites/UEM) services.

[![AutoPkg Win Daily Run](https://github.com/psu-em/autopkg-recipes-win/actions/workflows/daily.yml/badge.svg?branch=master)](https://github.com/psu-em/autopkg-recipes-win/actions/workflows/daily.yml)

### [macOS Service Discovery Tool](https://github.com/psu-em/ServiceDiscoveryTool/)


Python3 script that formats DHCP Request and BSDP Inform packets, broadcasts them on the local network, and then reports the responses. Responses provide insight into the DHCP and NetBoot services clients are able to reach.

[![ServiceDiscoveryTool workflow](https://github.com/psu-em/ServiceDiscoveryTool/actions/workflows/python-app.yml/badge.svg)](https://github.com/psu-em/ServiceDiscoveryTool/actions/workflows/python-app.yml)

## UEM Exports

### [mcm-exports](https://github.com/psu-em/mcm_exports)

This repo contains the exported MCM content for PSU.

[![Export Applications from MCM instance(s)](https://github.com/psu-em/mcm_exports/actions/workflows/applications.yml/badge.svg)](https://github.com/psu-em/mcm_exports/actions/workflows/applications.yml)

### [jamf-exports](https://github.com/psu-em/jamf_exports)

This repo contains the exported Jamf scripts and extension attributes for PSU.

[![export scripts from jamf](https://github.com/psu-em/jamf_exports/actions/workflows/export.yml/badge.svg?branch=main)](https://github.com/psu-em/jamf_exports/actions/workflows/export.yml)

### [bes-exports](https://github.com/psu-em/bes_exports)

This repo contains the exported BigFix sites for PSU.

[![export scripts from BigFix](https://github.com/psu-em/bes_exports/actions/workflows/BESexport.yml/badge.svg)](https://github.com/psu-em/bes_exports/actions/workflows/BESexport.yml)

## [UEM Codebase](https://github.com/psu-em/UEM-Codebase)

UEM Codebase for various systems and tools within EDM.

[![Retry UEM Jamf Apps in Jamf](https://github.com/psu-em/UEM-Codebase/actions/workflows/retry-apps.yml/badge.svg)](https://github.com/psu-em/UEM-Codebase/actions/workflows/retry-apps.yml)
[![Update Warranty in Jamf](https://github.com/psu-em/UEM-Codebase/actions/workflows/jamf-asm-warranty.yml/badge.svg)](https://github.com/psu-em/UEM-Codebase/actions/workflows/jamf-asm-warranty.yml)

## [macOS Labs Code](https://github.com/psu-em/macOS-Labs)

The scripts and launch agents used to turn vanilla macOS into a customized lab system for Penn State

[![macOS Lab Code Workflow](https://github.com/psu-em/macOS-Labs/actions/workflows/main.yml/badge.svg)](https://github.com/psu-em/macOS-Labs/actions/workflows/main.yml)

## [macOS pyPowerDaemon](https://github.com/psu-em/pypowerdaemon)

The PyPowerDaemon is used to manage wake times throughout the day for check-ins and maintenance.

[![macOS PowerDaemon Workflow](https://github.com/psu-em/pypowerdaemon/actions/workflows/main.yaml/badge.svg)](https://github.com/psu-em/pypowerdaemon/actions/workflows/main.yaml)

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
