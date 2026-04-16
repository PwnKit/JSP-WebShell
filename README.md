# Java Shell GTX100 Analysis

## Overview
This repository is a research archive for a JSP specimen labeled **"Java Shell GTX100"**.

The specimen appears to provide:
- a system-information view
- a file-browser mode
- direct file download behavior when a file path is supplied

## Purpose
This repository is shared for:
- malware / web-shell research
- defensive analysis
- secure code review
- detection engineering and forensic study

## Important Notice
This repository is **not intended for deployment or operational use**.
Do not install, expose, or run this code on any server you do not fully control and isolate for authorized research.

## Observed Behaviors
Based on static review, the JSP:
- accepts `mod` and `path` parameters
- defaults to an info mode when `mod` is absent
- shows Java system properties in info mode
- lists directories and files in archive/browser mode
- returns file contents as `application/octet-stream` when the supplied path points to a file

## Repository Contents
- `specimen/` — original sample
- `notes/` — analysis notes
- `screenshots/` — UI captures and supporting material

## Recommended Use
- keep this repository private unless publication is necessary
- redact any sensitive paths, IPs, or case-specific identifiers
- use this material only for defensive or academic research

## Disclaimer
The code in this repository may be dangerous if deployed. It is preserved strictly for research, documentation, and detection-oriented analysis.
