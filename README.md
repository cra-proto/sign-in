# Accounts

*description of the project*

**Timeframe** 2026-04-29 - 2026-08-05

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/sign-in](https://cra-test-arc.canada.ca/sign-in)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-05-13

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Sign in to your CRA account)
    node4(Help with using your CRA account)
    node5(CRA account help - Multi-factor authentication #40;MFA#41;)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    click node1 "https://www.canada.ca/en.html" _blank
    click node2 "https://www.canada.ca/en/revenue-agency.html" _blank
    click node3 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services.html" _blank
    click node4 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services.html" _blank
    click node5 "https://www.canada.ca/en/revenue-agency/services/e-services/cra-login-services/help-cra-sign-in-services/multi-factor-authentication.html" _blank
    classDef inscope stroke:#7636ab,stroke-width:3px
    class node5 inscope
```
