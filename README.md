# Odoo ERP Customization — PassionTech

**Odoo Community Customization • Business Systems Integration • PostgreSQL & Linux Deployment Preparation**

A case study of Odoo 19 Community customization for Passion Technologies PLC, covering connected Sales, Purchase, Inventory and Finance workflows, organization-specific addons, access controls, financial reporting and a reproducible deployment baseline.

**Contributor:** Muluneh Tarekegn  
**Scope:** Odoo customization, addon integration, role configuration, reporting and deployment documentation.

> Public portfolio documentation only. The development repository, source code, operational configuration, database backups and filestore artifacts are maintained separately. This portfolio contains no credentials, private records or production configuration.

## Business context

The project adapts an Odoo Community foundation to company workflows while coordinating business applications, role-based access and deployment requirements. It packages approved dependencies into a single bootstrap module so a fresh environment can install a consistent application baseline.

## Customization work

| Area | Documented work |
|---|---|
| Business applications | Coordinated Sales, Purchase, Inventory, invoicing and Finance dependencies |
| Bootstrap | Single-module installation through the custom ERP bootstrap addon |
| Company customization | Organization-specific defaults, branding and interface customization |
| Access control | Custom role hierarchy, ACLs, record rules, menu restrictions and server-side controls |
| Financial reporting | P&L, Balance Sheet and Cash Flow templates, comparison periods and report access controls |
| Addon integration | Vendored and pinned OCA dependencies for reporting, assets, reconciliation and statement import |
| Deployment preparation | Docker and native Linux runbooks, dependency installation and release checks |
| Recovery preparation | Coordinated PostgreSQL database and Odoo filestore backups, restore procedures and rollback documentation |

## Custom addons and upstream components

The development project includes organization-specific addons for the ERP bootstrap, core customization, branding, security and financial reports. They extend and configure the Odoo Community platform and integrate selected OCA components.

The upstream Odoo and OCA modules are dependencies; they are not presented as software authored from scratch for this project.

## Logical architecture

| Component | Responsibility |
|---|---|
| Authorized business users | Access the application through assigned roles and permissions |
| Odoo 19 Community | Provides the business application and ORM framework |
| Company-specific addons | Apply customization, bootstrap dependencies, access controls, branding and reports |
| PostgreSQL | Stores application records and configuration |
| Odoo filestore | Stores attachments associated with the database |
| Docker or native Linux environment | Hosts the application and its dependencies |
| Deployment and recovery runbooks | Coordinate release installation, verification, backup, restore and rollback |

## Reporting and controlled access

The project documentation describes P&L, Balance Sheet and Cash Flow templates with comparison periods, report security and default posted-entry filtering. Roles and record rules restrict access to business operations; menu restrictions are complemented by server-side controls.

Financial reporting configuration is subject to finance and accountant validation before production use. No statutory-compliance certification or accountant-approved tax implementation is claimed here.

## Reproducible installation and release baseline

The release documentation records a successful installation of the approved no-demo application set on a fresh Odoo 19 Community database using the tracked addons and standard Community platform.

The baseline coordinates:

1. An approved source revision and pinned dependencies.
2. A PostgreSQL custom-format database backup.
3. The matching Odoo filestore backup.
4. Module upgrade, application health checks and workflow verification.

Production-only company details, named users, opening balances and stock, email credentials and infrastructure settings remain separate controlled configuration tasks.

## Deployment and recovery preparation

The development repository contains Docker, native Linux and cPanel/WHM deployment documentation, production prechecks, a release gate, backup/restore instructions and update/rollback procedures.

Database and filestore backups are treated as a matched pair. Restore validation uses a separate target database rather than overwriting the source environment. These are documented operational procedures; this portfolio does not claim an independently verified live production rollout.

## Technology focus

| Area | Technology or practice |
|---|---|
| ERP | Odoo 19 Community |
| Customization | Python-based Odoo addons and module configuration |
| Data | PostgreSQL and Odoo ORM |
| Interface | Odoo views, branding and business menus |
| Reporting | MIS templates and OCA reporting components |
| Infrastructure | Docker, Linux and deployment runbooks |
| Access | Roles, ACLs, record rules and server-side checks |
| Operations | Dependency pinning, release checks, backup, restore and rollback |

## Scope and evidence

This case study is based on the existing customization repository, module inventory and deployment/release documentation. It demonstrates ERP customization and operational preparation without publishing the development source or private deployment artifacts.

Future or optional scope such as Fleet, M-PESA, advanced Projects, commissions, territories and broader HR functionality is excluded from the documented bootstrap and is not claimed as completed work.

## Portfolio focus

Odoo customization, business module integration, access control, financial reporting configuration, PostgreSQL-backed ERP systems and Linux deployment preparation.
