# Privacy Principles

OpenSource for Humans must be private by default and secure by design.

## Main Rules

1. Searching for help must work without login.
2. The platform must not require name, tax ID, identity document, full address, or phone number for basic search.
3. At this initial stage, personal data from people seeking help and general visitors must not be stored server-side.
4. Location should be approximate whenever possible.
5. Personal data must have an explicit purpose.
6. Sensitive data should be avoided.
7. Data must be retained for the shortest necessary time.
8. Analytics should be aggregated, anonymized, and non-invasive.
9. Sharing with third parties must be minimal, documented, and justified.
10. People must be able to request access, correction, and deletion of their data.
11. Sensitive automated decisions must have human review.

## Privacy by Default

New features should start with the least possible data collection.

Example: to search for nearby help, the platform should accept a city or neighborhood instead of requiring precise GPS.

## Initial Server-Side Storage Ban

During the first stage of the project, the platform must not store server-side personal data from people seeking help or general visitors.

This includes:

- names;
- tax IDs or identity documents;
- private phone numbers;
- exact residential addresses;
- precise GPS coordinates;
- individual search history;
- individual eligibility answers;
- individual contact clicks;
- identifiable IP addresses in application logs;
- session replay or behavioral tracking tied to a person.

If statistics are needed, they must be generated from anonymized and aggregated data before storage.

The system may count events such as searches by category, city-level demand, result clicks, and reports, but it must not keep data that identifies or singles out a person.

This rule applies to people seeking help and general visitors. Organizational account data is handled separately and must follow a documented legal basis, limited purpose, and strict access control.

## Privacy by Design

Every relevant change must answer:

- what data is collected;
- why it is necessary;
- which legal basis allows the processing;
- how long it will be kept;
- who will have access;
- whether it can be avoided entirely on the server side;
- whether statistics can be produced only from anonymized and aggregated data;
- how people can exercise their rights;
- what harm could occur if it leaked;
- how to reduce that harm.

## Vulnerable People

The project must treat any flow involving people experiencing homelessness, migrants, refugees, children, adolescents, survivors of violence, mental health needs, food insecurity, or emergencies as high risk.
