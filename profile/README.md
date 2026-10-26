# Cannabrokers

Canna Brokers is the brokerage for growers, buyers, shops, and doctors. Restricted supply stays broker-managed. The clinical track is separate from the brokerage. The product is PHP 8.4 and Laravel 12.

## Staging

- Plan: Hostinger KVM 2
- Location: France, Paris
- OS: Ubuntu 24.04 with Docker
- Hostname: srv1128122.hstgr.cloud
- IPv4: 72.61.108.146
- Backups: Weekly

A push to `main` on [cannabrokers](https://github.com/Cannabrokers/cannabrokers) deploys to this VPS.

## The build bible

This is the build programme. Show each milestone on staging before the next one merges.

- M0 Ground. Sign in on the staging URL, over TLS, with the nav shell.
- M1 Identity. Invite a user, put them in an organisation, and refuse a role they do not hold.
- M2 Catalogue. Browse grower supply, regional products, and a listing. A pending listing is invisible.
- M3 Cases. Submit a request and see it under My enquiries.
- M4 Broker. Qualify, block, match, and quote. The buyer still sees only the supplier code.
- M5 Files and money records. Upload evidence, issue a quote, accept it, and refuse an expired one.
- M6 Directory and stores. Public shops on a map. Grower sites stay off the map. Introductions become cases.
- M7 Practitioners. A consultation request stores no symptoms and creates no prescription.
- M8 Pathway. Six stages, the right role on each. Broker read is refused.
- M9 Operate. Backups restored onto a scratch VPS. Production opened to invited organisations only.
