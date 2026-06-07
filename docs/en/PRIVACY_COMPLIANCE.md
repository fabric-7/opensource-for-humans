# LGPD and GDPR/RGPD Compliance

This document defines OpenSource for Humans' minimum data protection standard.

The project must comply with both:

- Brazil's LGPD: Lei Geral de Protecao de Dados Pessoais, Law No. 13,709/2018.
- Europe's GDPR/RGPD: General Data Protection Regulation, Regulation (EU) 2016/679.

When there is a difference between laws, interpretations, or practices, the rule that gives the data subject the highest level of protection must prevail.

This document is an operational policy for the project and does not replace professional legal review.

## Maximum Protection Rule

If LGPD and GDPR/RGPD address the same topic differently, OpenSource for Humans must apply the most protective standard for:

- data minimization;
- avoiding server-side storage of user personal data whenever possible;
- transparency;
- consent;
- legal basis;
- data subject rights;
- security;
- retention;
- portability;
- erasure;
- objection;
- review of automated decisions;
- protection of sensitive data;
- protection of children and adolescents;
- international transfers;
- incident response;
- impact assessments.

## Initial No-Storage Rule

At this initial stage, personal data from people seeking help and general visitors must not be stored server-side.

The product should be designed so basic usage leaves no server-side user profile, search history, precise location record, eligibility-answer record, or contact-click trail tied to a person.

Application logs and analytics must be configured to avoid storing identifiable user data. When operational logs are technically necessary, identifiers such as IP addresses should be removed, truncated, anonymized, or retained only for the shortest security-critical period.

If user-related data is ever needed for statistics, it must be anonymized and aggregated before storage. The stored statistics must not allow the project, partners, or third parties to identify, single out, track, or re-identify a person.

This rule applies to people seeking help and general visitors. Organizational account data is handled separately and requires documented legal basis, limited purpose, strict access control, and retention limits.

## Legal Bases

Each personal data processing activity must have a documented legal basis.

Example purposes:

- enabling anonymous search by city or neighborhood;
- allowing organizations to maintain institutional data;
- receiving reports about incorrect data;
- preventing fraud and abuse;
- measuring usage only in anonymized and aggregate form;
- sending optional alerts when the person requests them.

When consent is used, it must be freely given, informed, specific, and revocable.

## Sensitive Data

Sensitive data must be avoided by default.

When strictly necessary, it requires:

- documented justification;
- appropriate legal basis;
- stronger technical protection;
- restricted access;
- short retention;
- impact assessment;
- human review.

## People's Rights

The project must provide ways to request:

- confirmation of processing;
- access;
- correction;
- anonymization;
- deletion;
- portability when applicable;
- information about sharing;
- withdrawal of consent;
- objection;
- review of automated decisions when applicable.

## Children and Adolescents

The project should avoid collecting data from children and adolescents.

When a service supports this audience, the page should describe the service without identifying children or adolescents individually.

## AI and Automated Decisions

AI must not make final decisions about eligibility, priority, benefit rights, health, safety, shelter, emergency support, or access to care.

Any automated recommendation must use probabilistic language, such as:

> You may be eligible. Confirm with the responsible organization.

Sensitive flows must allow human review.

## International Transfers

Before transferring personal data between countries or international providers, the project must document:

- which data will be transferred;
- to which country;
- to which provider;
- under which legal basis;
- which contractual and technical safeguards exist;
- how the data subject can exercise rights.

## Retention

Personal data must have a defined retention period.

When the purpose ends, data must be deleted, anonymized, or aggregated.

## Incidents

Security incidents must be quickly assessed for:

- type of affected data;
- number of affected people;
- risk to vulnerable people;
- containment measures;
- need to notify data subjects;
- need to notify authorities.

## DPO or Data Protection Lead

The project must appoint a person or group responsible for data protection when it operates publicly with real users.

This function must serve as a channel for data subjects, the community, organizations, and authorities.

## Official References

- LGPD: https://www.gov.br/int/pt-br/acesso-a-informacao/lgpd
- GDPR/RGPD: https://www.edps.europa.eu/general-data-protection-regulation_en
