# Lab 3 – Content Tree and Justification

## Content Tree (Sitemap)

- **Home (Root)**

  - **Employee Resources**
    - Employee Handbook
      - Code of Conduct
      - Workplace Behavior & Expectations
      - Office Guidelines
    - Compensation & Benefits
      - Health Benefits
      - Paid Time Off (PTO)
      - Employee Incentives
    - Work Policies
      - Remote / Hybrid Work Policy
      - Office Schedule & Hours
      - Communication Guidelines

  - **Marketing & Company Overview**
    - Company Overview
    - Brand Identity & Messaging
    - Product / Marketing Highlights

  - **Technical Documentation**
    - Server Configuration
    - Deployment Instructions
    - Development Environment Setup

  - **Archive**
    - Marketing Blurb 2020 (Outdated Content)

---

## ROT Analysis

During the audit of the legacy files, several examples of Redundant, Outdated, and Trivial (ROT) content were identified.

### Employee Handbook (employee_handbook_v3_FINAL.docx)

The handbook contains several outdated and conflicting policies. For example, the remote work policy includes multiple updates that contradict each other, referencing a Friday-only remote policy, a fully remote COVID policy, and a hybrid schedule. The document also references outdated technologies such as Internet Explorer 11, Adobe Flash Player, and Skype for Business.

Additionally, the handbook contains trivial information such as kitchen etiquette rules and includes sensitive information like server IP addresses and passwords, which should not be published in documentation.

### Marketing Blurb (marketing_blurb_2020.pdf)

This marketing document is outdated because it promotes a 2020 product release and references technologies that are no longer supported, such as Adobe Flash and Internet Explorer. Because the document is no longer accurate for current marketing messaging, most of the content would either be rewritten or archived.

### Server Configuration Notes (server_config_notes.txt)

This file contains highly technical configuration details intended for developers or IT staff. The content is unstructured and includes informal comments and internal notes. While some configuration information may still be useful for engineering teams, the document should be cleaned up and moved into structured technical documentation rather than being published directly.

---

## Justification

I organized the legacy files into sections based on who would most likely use the information. Instead of keeping the original documents as large files, the content was broken into smaller pages so users can find the information more easily.

The **Employee Handbook** originally included many different topics in a single document, including policies, benefits, and workplace expectations. Breaking this information into separate sections under "Employee Resources" allows employees to quickly locate the specific information they need without searching through a long document.

The **Marketing Blurb from 2020** appears to be outdated marketing material. Because it references older product information and technologies that are no longer commonly used, most of the content would likely need to be updated or rewritten. For this reason, it was placed in an archive section rather than migrated directly into the active documentation.

The **Server Configuration Notes** contain technical configuration details that are mainly useful for developers or IT staff. Since this type of information is not relevant to most employees or external audiences, it makes more sense to place it under a separate "Technical Documentation" section.
