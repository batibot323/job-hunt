---
pdf_options:
  format: A4
  margin: 22mm 20mm 22mm 20mm
---

<style>
  body {
    font-family: "Charter", "Georgia", serif;
    font-size: 10pt;
    line-height: 1.42;
    color: #1a1a1a;
  }
  h1 {
    font-size: 22pt;
    font-weight: 700;
    margin-bottom: 0;
    letter-spacing: -0.5px;
  }
  h1 + p {
    margin-top: 2px;
    margin-bottom: 0;
  }
  h2 {
    font-size: 10.5pt;
    font-weight: 700;
    text-transform: uppercase;
    letter-spacing: 1.2px;
    border-bottom: 1.5px solid #2c2c2c;
    padding-bottom: 3px;
    margin-top: 18px;
    margin-bottom: 8px;
  }
  h3 {
    font-size: 10.5pt;
    font-weight: 700;
    margin-bottom: 1px;
    margin-top: 14px;
  }
  h4 {
    font-size: 9.5pt;
    font-weight: 700;
    font-style: italic;
    margin-top: 10px;
    margin-bottom: 3px;
  }
  p, li {
    font-size: 10pt;
  }
  ul {
    margin-top: 3px;
    margin-bottom: 3px;
    padding-left: 18px;
  }
  li {
    margin-bottom: 2px;
  }
  strong {
    font-weight: 700;
  }
  hr {
    display: none;
  }
  a {
    color: #1a1a1a;
    text-decoration: none;
  }
  .last-updated {
    font-size: 8.5pt;
    color: #666;
    margin-top: 24px;
    text-align: right;
  }
</style>

# Hani Herbert Ho

**Tech Lead / Senior Software Engineer**
Metro Manila, Philippines | +63 927 2997577 | hani.herbert.ho@gmail.com

## Professional Summary

Technology leader with 8+ years of experience in software engineering, specializing in payments and fintech. Currently serving as Tech Lead at Xendit/Dragonpay, responsible for architectural decisions, security initiatives, and mentoring a cross-functional team of engineers, business analysts, and IT support personnel. Combines deep technical expertise with business acumen — adept at translating complex technical matters for non-technical stakeholders and driving initiatives across organizational boundaries.

## Core Competencies

**Languages & Frameworks:** C#, .NET Core, Java, PHP, JavaScript/TypeScript, Angular, Node.js, RxJS, HTML/CSS
**Infrastructure & Tools:** Azure Cloud, Azure DevOps, Jenkins, Git/GitHub, CI/CD, Linux, Windows, Shell scripting
**Databases:** SQL (MSSQL, MySQL)
**Testing & Quality:** Selenium, E2E test automation, UAT coordination, VAPT
**Domain Expertise:** Payment systems, payment channel integrations, reconciliation, settlement, security, compliance, fraud prevention
**Leadership:** Technical direction, people development, cross-functional coordination, system design, incident management, postmortems, technical documentation

## Professional Experience

### Xendit / Dragonpay, Philippines — Tech Lead / Senior Software Engineer

**March 2024 – Present** *(Dragonpay acquired by Xendit)*

#### Leadership & People Development

- Serve as Tech Lead for the engineering function: own architectural direction, technical documentation, and act as primary liaison for audits and compliance engagements
- Directly manage a team of 4 engineers and 1 business analyst; additionally influence and mentor a 10+ person IT support team
- Developed one IT support team member into a QA Engineer role and another into a Database Administrator role
- Conduct regular 1:1s with direct reports and steer technical planning conversations to ensure sound decision-making
- Consult cross-functionally with marketing, product, and merchant operations on technical matters
- Enabled internal stakeholders to independently gather and leverage business intelligence data, reducing dependency on the engineering team

#### Security & Compliance

- Led a platform-wide security upgrade of merchant payment notification verification (webhooks/callbacks) end-to-end — designed the solution, built the implementation, and coordinated rollout across 6 departments (Sales, Marketing, IT Support, Operations, Risk, Legal/Compliance). This initiative protects merchants processing millions in daily TPV from spoofed payment confirmations that could result in losses exceeding PHP 100M.
- Spearheaded and implemented additional security measures: payout disabling, internal postback hardening, forced 2FA enrollment, and verification controls on credit card endpoints
- Disabled payout channels with elevated risk exposure to improve overall security posture
- Participated in Xendit ISS Vulnerability Assessment and Penetration Testing (VAPT)
- Serve as go-to resource for audits, compliance inquiries, and security matters across the organization

#### Payment Channel Integrations

- Delivered BPI Auto Debit (Recurring) within 1 month — led the project end-to-end, collaborated with architects on technical direction, developed all connector-side features (Account Linking, Unlinking, and Payments), and coordinated with Subscriptions, PAPI, and PSS teams for integration
- Built Netbank Virtual Account Webhook endpoint for the Shopee/AUB use case, including an authentication workaround and daily reconciliation to prevent money loss
- Implemented Just-in-time (JIT) prefunding for foreign remittance payouts, enabling use cases such as Menyala
- Built express settlement feature for accelerated merchant fund availability
- Implemented Netbank Post integration
- Designed and built the Xendit–AAA integration to support Xendit's VASP license application; subsequently maintained and extended the integration for additional settlement cycles
- Designed the Linking (Consent) domain architecture for multiple payment channels (EWallets, Direct Debit, Cards)

#### Reconciliation & Financial Operations

- Reworked the technical reconciliation system into a comprehensive and resilient architecture capable of handling complexity and resolving discrepancies automatically, preventing money loss
- Built new Bayad technical reconciliation process
- Resolved BDO multi-match issues: saved approximately 70 man-hours monthly across ~200 daily transactions, reducing the defect rate by 80%
- Created daily reconciliation for Netbank VA to prevent financial discrepancies
- Analyzed Static QR profitability using transaction data: generated approximately PHP 104K net revenue for Q2–Q3 2024, projecting ~PHP 400K in annual net revenue

#### Platform & Infrastructure

- Designed and championed a caching strategy to prevent system bottlenecks, influencing team-wide adoption as a standard practice
- Reduced operational toil by building an API to safely deactivate merchants in bulk (revocable, non-destructive operation)
- Developed VA reports for TikTok aggregators; investigated cross-border settlement flows (Transtone, MDAQ)
- Implemented VA sender details functionality
- Resolved VA issues: duplicate merchant transaction IDs, special character handling, double MUVA posting
- Implemented Security Bank scraping integration

#### Process & Culture

- Introduced blameless postmortems as standard incident response practice, driving continuous improvement across the organization
- Established writing-to-clarify-thinking culture and effective meeting practices within the team
- Delivered internal training sessions on Git, object-oriented programming, design patterns, system design, and organizational infrastructure/architecture
- First responder for production incidents — prioritize rapid resolution, then facilitate structured retrospectives
- Maintained high delivery velocity while expanding domain ownership across VAs, reconciliation, and internal tooling

#### Recognition

- Trailblazer Award — company-wide employee recognition
- Unstoppable Award — company-wide employee recognition

### Xendit, Philippines — Senior Software Engineer

**December 2022 – March 2024**

- Contributed to Xendit's unified payments initiative: authored summary documentation for Direct Debit Connectors and served as Direct Debit PIC for the Expanding Payment Channel group
- Led a pod of 3 engineers aligned with business targets, ensuring adherence to broader engineering direction and removing blockers for teammates
- Delivered and led builds for new payment channels across the platform
- Built features for internal tooling used by tech support, financial operations, and other departments
- Addressed Payouts domain issues: resolved a defect allowing inactive merchants to upload payout transactions; ensured source procedure updates upon payout transaction processing
- Improved Collections domain: blocked split payments for processors lacking settlement capability; enforced email address blocking regardless of Security Level classification

### Xendit, Philippines — Software Engineer

**October 2021 – December 2022**

- Delivered a cross-team feature to instantly activate merchants upon onboarding, removing approximately 100 hours of operational toil annually
- Co-pioneered an organization-wide initiative enabling all teams to categorize and track operational toil through Slack-Jira integration, contributing to a reduction of up to 50%
- Built a full-stack MVP and consulted with pilot merchants to drive the project forward; authored solution and architecture documents while serving as technical PIC

### Pointwest, Philippines — Software Engineer

**September 2018 – October 2021**

- Delivered fully-responsive web applications with attention to accessibility standards and semantic HTML
- Migrated all monolith API projects of a gas utility company into a microservices architecture
- Established CI/CD pipelines to enhance team productivity and eliminate opportunities for human error
- Conducted an intermediate-level virtual Git workshop for 30 participants across multiple teams
- Maintained and extended a website for a language company using .NET Core
- Developed a web scraper handling dynamic content using Node.js and Selenium
- Developed and published a C# library to NuGet for handling API requests to a payment gateway
- Built an automated end-to-end UI testing system using Jenkins to ensure quality in an Agile environment
- Developed web application projects using Angular:
  - Document portal for a gas company serving 1.6 million consumers (delivered near single-handedly)
  - Reusable table component published as an NPM library for client adoption
  - Questions module for a financial planning company website
  - User management system for an IT company handling customer and client relationships
- Authored comprehensive documentation establishing best practices and ensuring long-term maintainability

### Philippine Science High School — Special Science Teacher

**August 2017 – May 2018**

- Taught Object-Oriented Programming to Grade 10 students using Java
- Managed a homeroom class and served as faculty adviser for the basketball club

### Philippine Institute for Integrated Circuits (PIIC) — Special Research Assistant

**April 2014 – July 2014 & September 2016 – December 2016**

- Managed and delivered Microelectronics instruction to college students in accelerated courses (lecture and laboratory)
- Designed and implemented UART using Verilog for a microprocessor proof-of-concept

## Education

**University of the Philippines, Diliman** — 10 units towards MS Electrical Engineering (Microelectronics)
June 2014 – March 2016

**University of the Philippines, Diliman** — BS Computer Engineering
June 2008 – March 2014

## Certifications

- In-house IT Security Training (Pointwest, 2019) — OWASP Top 10

## Languages

- English — Native / Bilingual Proficiency
- Tagalog — Native / Bilingual Proficiency
- Spanish — Limited Working Proficiency

<div class="last-updated">Last updated: August 2026</div>
