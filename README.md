# Sales9ja — Online Marketplace and Delivery Operations

**Independent PHP/MySQL commerce project | Public portfolio case study**

**Developer:** [Isah Abba Namnai](https://github.com/isa9ice)  
**Website:** [sales9ja.com](https://sales9ja.com/)  
**Original application source:** Private repository (not included here)

> This is a documentation-only project showcase. The production application source, configuration, credentials, database exports and customer records are not published here.

## Overview

Sales9ja is an online shopping and retail operations application combining customer-facing shopping journeys with administration, order management, shipment coordination and customer-notification components. It is distinct from [9jaSales](https://github.com/isa9ice/9jasales-portfolio), a separate commerce application in my portfolio built using a different technology stack.

## Application areas

| Area | Components identified in the private codebase |
| --- | --- |
| Product discovery | Home page, product categories, item details and browsing interfaces |
| Shopping and checkout | Shopping carts, checkout, order summaries and payment-related pages |
| Orders | Order history, confirmations, receipts and returns/refunds information |
| Delivery | Shipment allocation, shipping administration, tracking and delivery verification interfaces |
| Administration | Dashboard, user-role management, categories and location management |
| Affiliate programmes | Affiliate enrolment, agent referrals and promotional settings |
| Notifications and mobile | Web app manifest, service worker, PWA and notification-related modules |

**Scope note:** The presence of these modules in source code does not independently establish that every workflow is deployed, integrated, security-tested or operational in production.

## Technology

- **Backend:** PHP with MySQL/MySQLi data access
- **Frontend:** Server-rendered PHP pages and browser-side JavaScript
- **Mobile:** Progressive Web App (PWA) manifest and service worker
- **Dependencies:** Google API Client and PHP web push support, plus mail-related components
- **Engineering focus:** Order lifecycle design, role-dependent administration, shipment management and database-driven workflows

## Engineering competencies demonstrated

1. Working with a traditional server-rendered **PHP/MySQL application** as well as modern JavaScript stacks.
2. Structuring multi-step **catalogue → cart → checkout → order** workflows.
3. Building interfaces for **operational roles**, customer orders and administrative functions.
4. Integrating **shipping and delivery-tracking concepts** into retail operations.
5. Incorporating **installable PWA functionality** and notification-related code.

## Conceptual workflow

    Browse catalogue → Product details → Cart → Checkout
                                               ↓
                                         Order handling
                                               ↓
                                        Shipment workflow
                                               ↓
                                        Delivery tracking

This diagram illustrates application components rather than a verified end-to-end production test.

## Further documentation

- [Technical overview](docs/TECHNICAL_OVERVIEW.md)
- [Safe screenshot publishing guide](docs/SCREENSHOT_GUIDE.md)

## Contact and disclosure

The operational source remains private to protect implementation details and sensitive configuration. A technical discussion or demonstration may be arranged without exposing credentials or customer data.

**Contact:** [GitHub](https://github.com/isa9ice) · [LinkedIn](https://www.linkedin.com/in/isah-abba-namnai-0b3623186/)

---

*This portfolio describes observed project components. It is not a claim of external certification, verified production readiness or independent security assessment.*