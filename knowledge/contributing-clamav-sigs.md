---
layout: page
title: Writing ClamAV Signatures for the Official ClamAV Virus Database (CVD)
---

(TODO This should probably live in the ClamAV manual)

Table of Contents:
- TOC:
{:toc}

## Introduction to ClamAV
This section will provide an introduction to ClamAV, including how it's used, the types of detection that it supports, and hopefully provide a compelling case for why your contributions to ClamAV can have a big impact in protecting users around the world from malware.

### About ClamAV
 - discuss AV types, brief history, basic open source info, platforms supported, ruleset definition

### Capabilities
 - file type detection, unpacking/extraction, bytecode rules, authenticode whitelisting, yara

### Signature Format Overview
 - at a high level, show what rules look like (hdb, ldb, etc.)

### Typical Deployments
 - mail server, NAS, etc.

### Usage Metrics
 - how many people actively run freshclam, download code, etc.  Also, include geographic breakdown if possible.  Mention that ClamAV is run against in VirusTotal.  Briefly mention usage in Cisco products too.  Convey that contributing will have a big impact


## Overview of the ClamAV Open Source Environment

### Open Source
 - license, where the code lives, who manages ClamAV, etc

### Virus Database
 - CVD - official sigs, third-party sigs (SaneSecurity)

### Resources
 - IRC, mailing lists


## How to Write ClamAV Signatures

For a detailed introduction to writing ClamAV signatures, including an overview of the signature formats and capabilities built in to ClamAV, check out the [Creating signatures for ClamAV](https://www.clamav.net/documents/creating-signatures-for-clamav) page in the ClamAV manual.

### Writing Effective Signatures
 - TODO

### How to Test Signatures
 - TODO

### Supporting Tools for Signature Writing
 - Sigtool, CASC, BASS, Scripts, etc.


## How to Contribute Signatures to the Official CVD
### Checking for Prior Coverage
 - Do this before writing a new signature

### Checking for Common Signature Mistakes
 - TODO

### Steps for Submitting Signatures
 - what to submit, how, etc.

### Overview of the Signature Review Process

### After Rule Acceptance
 - TODO Is there anywhere that their name gets published?

