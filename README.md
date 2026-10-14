# ALITA AVIATION

## Coming Soon Website & Development Roadmap

Luxury Private Helicopter Charter & Aviation Experiences

**Project:** ALITA Aviation  
**Repository:** https://github.com/whslater/alita-coming-soon  
**Temporary hosting:** GitHub Pages  
**Status:** Coming Soon — Initial Development  
**Last updated:** October 2026

---

## 1. Project Overview

ALITA Aviation is a luxury private helicopter charter company.

The website will provide a premium digital experience for customers
looking to arrange private helicopter journeys, wedding charters,
private flying experiences and lessons.

The project will be developed in two stages:

1. A temporary Coming Soon website hosted on GitHub Pages.
2. A complete PHP/Twig website with SQL database, secure
   administration, charter enquiries and booking management.

The design will be mobile-first, fully responsive and consistent
with the official ALITA Aviation branding.

---

## 2. Current Website — Phase 1

### Technology

- HTML5
- CSS3
- Vanilla JavaScript
- Git / GitHub
- GitHub Pages
- Google Fonts

### Current Features

- Responsive desktop and mobile layout
- Official ALITA Aviation branding
- Minimal navigation logo
- Full landing page logo
- Helicopter background photography
- Coming Soon announcement
- Private Charter introduction
- Wedding Charter introduction
- Flying Experiences introduction
- Contact email link
- Footer branding
- Smooth section navigation
- Automatic copyright year

### Current Limitations

The Coming Soon website is static.

It does not currently support:

- PHP or Twig execution
- SQL database connections
- Server-side contact forms
- Customer accounts
- Online booking management
- Automated transactional emails
- Administration dashboard

These features are planned for the production website.

### Project Structure

alita-coming-soon/
index.html
styles.css
script.js
README.md
assets/
images/
backgrounds/
landing-background.png
logos/
alita-logo-1774x887.png
alita-minimal-logo-1774x887.png
videos/

### Local Development

Open the project folder in Visual Studio Code.

Install the Live Server extension and open index.html
using Live Server.

Changes can be previewed locally before publishing.

### Deployment

The Coming Soon website is designed for GitHub Pages.

Repository:
https://github.com/whslater/alita-coming-soon

Expected GitHub Pages URL:
https://whslater.github.io/alita-coming-soon/

GitHub Pages settings:

- Source: Deploy from a branch
- Branch: main
- Directory: / (root)

Deployment commands:

    git add .
    git commit -m "Update ALITA Aviation website"
    git push origin main

GitHub Pages will redeploy after changes are pushed.

---

## 3. Production Technology Stack — Phase 2

### Backend

- PHP 8.3 or newer, using a supported version
- Composer dependency management
- Twig templating engine
- MySQL or MariaDB
- PDO for database access
- Server-side input validation
- Session-based authentication
- CSRF protection
- Secure password hashing
- Role-based administration permissions

### Frontend

- HTML5
- CSS3
- JavaScript
- Responsive mobile-first layouts
- Progressive enhancement
- Accessible navigation and forms
- Optimised images and media

### Infrastructure

Production hosting must support:

- PHP execution
- Composer packages
- MySQL/MariaDB database
- HTTPS/SSL certificates
- SFTP or SSH file management
- Scheduled tasks / cron jobs
- Secure environment configuration
- Database backups
- Email API or SMTP integration
- Error logging

GitHub will remain the source-code repository.

GitHub Pages will not host the production PHP backend.

---

## 4. Domains & Hosting

### Domains

Required:

- alitaaviation.com
- alitaaviation.co.uk

Domain availability and ownership must be confirmed.

One domain will act as the primary website address.
The second will redirect to the primary domain.

### Recommended Hosting Approach

Start with a managed PHP hosting package that includes
a SQL database, SSL, backups and SFTP/SSH access.

A VPS is not required for the initial launch unless
specific infrastructure requirements justify it.

Potential providers to evaluate:

- Krystal
- Hostinger
- IONOS
- Cloudways

Compare PHP version support, database availability,
backup policies, cron jobs, Composer/SSH access,
renewal pricing and support quality before purchasing.

---

## 5. Initial Infrastructure Budget

All figures below are indicative planning allowances
in GBP, not verified provider quotations.

### Setup Costs

| Item                        | Estimated Cost |
| --------------------------- | -------------- |
| GitHub repository           | £0             |
| GitHub Pages                | £0             |
| SSL certificate             | £0 if included |
| .com domain, first year     | £10–£20        |
| .co.uk domain, first year   | £5–£15         |
| PHP hosting setup           | £0–£20         |
| SQL database setup          | £0 if included |
| Composer / Twig             | £0             |
| Basic email setup           | £0–£15         |
| **Estimated initial setup** | **£15–£70**    |

This excludes professional development time,
premium assets and any optional paid services.

### Ongoing Costs

| Service                     | Monthly Allowance |
| --------------------------- | ----------------- |
| PHP hosting with SQL        | £5–£15            |
| Domains, annualised         | £1.25–£3          |
| Business email mailbox      | £2–£6             |
| Transactional email         | £0–£10            |
| SSL certificate             | £0 if included    |
| Database                    | £0 if included    |
| GitHub                      | £0                |
| **Estimated monthly total** | **£8.25–£34**     |

Estimated annual recurring budget:
Approximately £99–£408.

These allowances exclude promotional-price changes,
VAT differences, payment processing, and usage-based
charges outside any included email allowances.

Domain renewals and hosting renewal rates must be
checked before purchasing.

---

## 6. Production Public Website

### Home

- Cinematic helicopter landing page
- ALITA Aviation logo
- Animated "Right this way" CTA
- Brand introduction
- Featured services
- Enquiry CTA

### Our Experiences

Private Charter:

- Bespoke private helicopter journeys
- Destination information
- Charter enquiries

Wedding Charter:

- Wedding arrivals and departures
- Bespoke wedding experiences
- Wedding enquiry form

Private Flights & Lessons:

- Flying experiences
- Private flying lessons
- Experience enquiries

### Explore

- Where We Fly
- Aircraft
- Gallery

### About

- About ALITA Aviation
- Pilot information
- Company information

### Enquiries

- Request a Charter
- Quote request
- Contact information

---

## 7. Administration Dashboard

The production website will include a secure
administration area.

### Dashboard

- Recent enquiries
- Upcoming flights
- Outstanding quotes
- Booking statuses
- Operational overview

### Charter Management

- Charter enquiries
- Availability calendar
- Booking records
- Booking status updates
- Flight information

### Commercial Management

- Pricing management
- Quote builder
- Quote history
- Customer records

### Website Management

- Aircraft records
- Locations
- Service content
- Gallery assets

### Communications

- Email templates
- Automated emails
- Customer correspondence history

Administration pages must require authentication
and appropriate permissions.

---

## 8. Database Requirements

The initial database design should consider:

- users
- customers
- enquiries
- bookings
- booking_statuses
- aircraft
- locations
- pricing_rules
- quotes
- quote_items
- availability
- email_templates
- email_logs

Relationships, constraints and permissions will be
defined before production implementation.

Database migrations should be version-controlled.

Customer information must not be committed to GitHub.

---

## 9. Email Requirements

### Business Email

A branded business mailbox is required.

Example:
hello@alitaaviation.com

This address is provisional and must be created
before it is used publicly.

### Transactional Email

The production platform should support:

1. Enquiry received
2. Quote sent
3. Quote accepted
4. Booking confirmed
5. Pre-flight reminder
6. Flight completed / thank you

Potential transactional email providers:

- Brevo
- Postmark
- Mailgun

The final provider must be selected based on
cost, deliverability, API support and volume.

### Email Security

Configure:

- SPF
- DKIM
- DMARC

Email credentials and API keys must be stored
outside the public repository.

The website must never expose email API keys
in client-side JavaScript.

---

## 10. Security & Data Protection

Production requirements include:

- HTTPS across the website
- Secure admin authentication
- Password hashing
- CSRF protection
- Input validation
- Prepared SQL statements
- Access controls
- Database backups
- Restricted database permissions
- Secure secret management
- Logging and error handling
- Privacy policy
- Cookie consent where applicable
- UK GDPR compliance considerations
- Defined data retention policies

Production backups and recovery procedures
must be tested before launch.

---

## 11. Development Roadmap

### Phase 1 — Coming Soon

- [x] Create static website
- [x] Add responsive layout
- [x] Add ALITA branding
- [x] Add helicopter background
- [x] Add service introductions
- [x] Add footer branding
- [ ] Confirm public contact email
- [ ] Test mobile and desktop
- [ ] Push current changes to GitHub
- [ ] Enable and verify GitHub Pages

### Phase 2 — Infrastructure

- [ ] Confirm domain availability
- [ ] Purchase domains
- [ ] Select PHP hosting
- [ ] Configure DNS
- [ ] Configure SSL
- [ ] Configure PHP environment
- [ ] Install Composer and Twig
- [ ] Create SQL database
- [ ] Configure business email
- [ ] Configure transactional email

### Phase 3 — Public Website

- [ ] Build Twig layout system
- [ ] Build homepage
- [ ] Build charter service pages
- [ ] Build aircraft pages
- [ ] Build location pages
- [ ] Build gallery
- [ ] Build contact forms
- [ ] Build charter enquiry forms

### Phase 4 — Admin Platform

- [ ] Admin authentication
- [ ] Dashboard
- [ ] Enquiry management
- [ ] Customer records
- [ ] Aircraft management
- [ ] Location management
- [ ] Availability calendar
- [ ] Pricing management
- [ ] Quote builder
- [ ] Booking status management

### Phase 5 — Automation

- [ ] Enquiry confirmation email
- [ ] Quote delivery email
- [ ] Quote acceptance workflow
- [ ] Booking confirmation email
- [ ] Flight reminder email
- [ ] Post-flight thank-you email
- [ ] Email delivery logging

### Phase 6 — Production Launch

- [ ] Security review
- [ ] Accessibility review
- [ ] Responsive testing
- [ ] Performance optimisation
- [ ] Database backup testing
- [ ] Email deliverability testing
- [ ] DNS configuration
- [ ] Production deployment
- [ ] Launch verification

---

## 12. Branding

Official ALITA Aviation branding uses:

- Black and dark charcoal backgrounds
- Metallic gold and champagne accents
- Elegant serif typography
- Refined sans-serif supporting text
- Cinematic helicopter photography
- Minimal, premium interface design

Official logo files are stored in:

assets/images/logos/

The existing logo assets must remain consistent
across navigation, landing and footer sections.

---

## 13. Important Notes

The Coming Soon website is a temporary static
website and is not the final charter platform.

The production website will be developed separately
using PHP, Twig and SQL.

No payment processing, live availability or
confirmed online booking functionality is currently
implemented.

Pricing, providers and infrastructure requirements
will be reviewed before purchasing services.

The public contact email must be confirmed before
the Coming Soon website is considered ready for
customer enquiries.

---

© 2026 ALITA Aviation.
All rights reserved.
