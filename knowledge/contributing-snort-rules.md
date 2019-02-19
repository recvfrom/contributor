---
layout: page
title: Writing Snort Rules for the Community Ruleset
---

Table of Contents:
- TOC:
{:toc}

## Introduction to Snort
This section will provide an introduction to Snort, including how it's used, the types of detection that it supports, and hopefully provide a compelling case for why your contributions to Snort can have a big impact in protecting users around the world from network-based threats.

### About Snort
 - discuss IDS/IPS, brief history, basic open source info, platforms supported

### Capabilities
 - protocol parsing/re-assembly, app detection, rule capabilities, SO rules, Snort 2 vs. Snort 3

### Rule Format Overview
 - at a high level, show what rules look like

### Typical Deployments
  - Ex: hung off a network tap / span port, inline for IPS, etc.

### Usage metrics
 - how many people subscribe to rulesets, download code, etc.  Also, include geographic breakdown if possible.  Mention that pcaps in VT get tagged with alerts.  Briefly mention usage in Cisco products too (we should admit that we benefit directly from contributions too.)  Convey that contributing will have a big impact


## Overview of the Snort Open Source Environment

### Open Source
 - license, where the code lives, who manages Snort, etc

### Rulesets
 - community ruleset, ET, how the VRT rules fit in

### Resources
 - IRC, mailing lists, rule documentation database


## How to Write Snort Rules
 - Rule format, where to find docs/examples, etc.

### Writing Effective Rules
 - What makes a good rule, potential pitfalls, etc. - Ex: user-agent strings
 - considerations - is stream re-assembly required, etc.

### How to Test Rules 
 - TODO

#### How to generate pcaps for use with rule testing
 - How to run malware/exploits etc. and capture results
 - C2 server emulation, FakeNet, etc.
 - Leveraging docker for vulnerable service instantiation 

## How to Contribute Rules to the Community Ruleset

### Checking for Prior Coverage
 - Do this before writing a new rule

### Checking for Rule Best Practices
 - term ordering, one-line, categories, wording, etc.

### Steps for Submitting Signatures
 - provide an email template, where to send, what to provide (documentation, pcaps, etc.), etc.
 - Eliminate all doubt about how to do it

### Overview of the Rule Review Process

### After Rule Acceptance
 - Mention where their name will show up in the rule docs upon acceptance :)

