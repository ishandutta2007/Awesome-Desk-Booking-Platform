# Awesome-Desk-Booking-Platform

## Top Desk Booking Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Hot Desking, Workspace Reservation, Floor Plan Visualization & Hybrid Work Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Desk Booking**. These tools help organizations manage hybrid workplaces, allowing employees to reserve desks, rooms, and parking spaces while providing facilities teams with utilization analytics.



**Examples** include Envoy Desks, Robin, OfficeSpace, Kadence, Skedda, Condeco, Deskbird, Officely, Tactic, and Eden Workplace (the category leaders).



**Open-source emphasis**: Desk booking has a **focused but developing open-source ecosystem**. **Seatsurfing** is the leading open-source solution with **313 stars and 98 forks**, actively maintained with recent commits as of September 2026 . **WARP** (Workspace Autonomous Reservation Program) provides a comprehensive hybrid office management system with production-grade Docker deployment . **LibreBooking** is a mature community fork of Booked Scheduler used by organizations for resource reservations . **Roomer** is a self-hosted platform for desk and asset reservations without SaaS dependency . **OpenDesk** is an early-stage project focused on desk optimization . This section documents these solutions honestly.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Envoy Desks](https://envoy.com/desks/)**  

  Desk booking integrated with Envoy's workplace platform. Provides desk reservations, floor plan visualization, and occupancy analytics with visitor management integration.



- **[Robin](https://robinpowered.com/)**  

  Workplace experience platform for hybrid teams. Provides desk and room booking, workplace analytics, and integrations with Google Calendar and Microsoft 365.



- **[OfficeSpace](https://www.officespacesoftware.com/)**  

  Workplace management platform with desk booking, room scheduling, and space utilization analytics. Helps organizations optimize office footprint.



- **[Kadence](https://kadence.co/)**  

  Hybrid workplace management platform. Provides desk, room, and parking booking, visitor management, and workplace analytics.



- **[Skedda](https://www.skedda.com/)**  

  Cloud-based space scheduling platform for meeting rooms, desks, and shared resources. Known for ease of use and flexible booking rules.



- **[Condeco](https://www.condeco.com/)**  

  Workplace management platform with desk booking, meeting room scheduling, and occupancy analytics. Used by enterprises worldwide for hybrid workplace optimization.



- **[Deskbird](https://www.deskbird.com/)**  

  European desk booking platform with strong DACH market presence. Provides desk and room booking, team coordination, and analytics .



- **[Officely](https://officely.app/)**  

  Desk booking platform integrated with Slack and Microsoft Teams. Enables team coordination and office attendance planning.



- **[Tactic](https://tactic.io/)**  

  Hybrid workplace platform with desk booking, room reservations, and team scheduling.



- **[Eden Workplace](https://edendenworkplace.com/)**  

  Workplace management platform with desk booking, visitor management, and maintenance ticketing.



## Open-Source GitHub Projects



### Comprehensive Desk Booking Systems



- **[Seatsurfing](https://github.com/seatsurfing/backend)**  

  **The leading open-source desk and room booking system.** **313 stars, 98 forks**, GPL-3.0 licensed, **actively maintained** (last commit September 3, 2026) . **Key features**: Core REST API backend in **Go**; booking PWA (TypeScript/React) for end users; separate Admin UI for configuration; **floor plan visualization** with drag-and-drop layout tools; multi-language support; PostgreSQL persistence; **Docker and Kubernetes deployment** with multi-architecture images (amd64, arm64) . Integrations include Microsoft Teams and Confluence. Optional hosted SaaS with free tier for small teams . **Best for**: Organizations wanting a complete self-hosted desk booking solution with modern web UI.



- **[WARP (Workspace Autonomous Reservation Program)](https://github.com/sebo-b/warp)**  

  **Comprehensive open-source system for managing hybrid office space.** **Key features**: Support for **assigned desks, hot-desks, parking stalls**; mobile PWA; admin interface for **maps, zones, groups**; per-zone booking constraints; assigned seats; disabled seats; auto-book; **iCal feed subscriptions**; per-zone reminders; configurable booking windows; **SAML/LDAP/Azure AD/OIDC authentication**; translations (English, German, French, Spanish, Polish) . **Tech stack**: Python/Flask with PostgreSQL. **Deployment**: `docker run --rm -p 5000:5000 ghcr.io/sebo-b/warp:debug` for demo; production via `ghcr.io/sebo-b/warp:latest` with uWSGI . **Best for**: Organizations needing comprehensive hybrid workplace management with authentication integrations.



### Resource Scheduling Platforms



- **[LibreBooking](https://github.com/LibreBooking/librebooking)**  

  **Mature open-source resource scheduling and reservation system.** Community-driven fork of Booked Scheduler. **Key features**: **Resource reservations** (rooms, equipment, shared assets); calendar-style views (day, week, month); **recurring bookings** with conflict detection; **approval workflows** with email notifications; **groups and permissions**; **accessories and add-ons** (projectors, microphones); REST API and reports . **Self-hosting** keeps data under your control with no per-user fees . **Best for**: Organizations needing flexible resource scheduling beyond just desks.



- **[Roomer](https://github.com/topics/hotdesk-booking)**  

  **Self-hosted platform for managing desk and asset reservations across offices, buildings, and floors.** **Key features**: Upload floor plans, place bookable assets on a canvas, team booking without SaaS dependency. **TypeScript-based**, updated September 2026 . **Best for**: Teams wanting visual floor plan-based booking with self-hosting.



- **[OpenDesk](https://github.com/kanwalnainsingh/OpenDesk)**  

  **Open-source system for optimizing office desk utilization.** **Key features**: Organization setup with sites/buildings and desk capacity; employee desk reservation for planned office days; reservation modification and cancellation; booking history; confirmation alerts . **Future roadmap**: SSO with roles, notification channels (email), department segregation, desk map configurations, real-time organization dashboard . **Best for**: Early adopters wanting a simple, extensible desk booking foundation.



### Additional Strong Open-Source Options



- **Comprehensive Systems**: **Seatsurfing** (Go/React, floor plans, Docker/K8s) , **WARP** (Python/Flask, hybrid office, SSO) .

- **Resource Scheduling**: **LibreBooking** (PHP, recurring bookings, approval workflows) , **Roomer** (TypeScript, visual floor plans) .

- **Early-Stage**: **OpenDesk** (simple desk optimization) .

- **Note**: **Booked Scheduler** (original, now succeeded by LibreBooking) and **MRBS** (Meeting Room Booking System) are legacy options, though LibreBooking is the actively maintained fork .



**Frameworks for building custom systems**: Combine **Seatsurfing** for a complete desk booking solution with floor plans and Docker deployment, **WARP** for hybrid office management with SSO authentication, **LibreBooking** for resource scheduling with approval workflows, and **Roomer** for visual floor plan-based booking. Add **PostgreSQL** for persistence and **Docker/Kubernetes** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Desk booking platforms handle potentially sensitive employee location and occupancy data; ensure compliance with GDPR, CCPA, and applicable workplace monitoring regulations.

- **Open-source reality**: The open-source ecosystem for desk booking is **developing but production-capable**. **Seatsurfing** is the standout—actively maintained with 313 stars, Go/React stack, floor plan visualization, and Docker/Kubernetes deployment . **WARP** provides comprehensive hybrid office management with SSO integrations . **LibreBooking** offers mature resource scheduling with approval workflows . **Roomer** delivers visual floor plan-based booking . However, **commercial platforms** (Envoy, Robin, OfficeSpace, Condeco) provide **enterprise-grade analytics, native mobile apps, visitor management integration, and dedicated support** that open-source alternatives require additional tooling to match. The open-source path is **genuinely viable** for organizations with strong IT capacity seeking full data ownership and zero per-user fees.



---



**Made for facilities managers, workplace experience teams, HR leaders, and hybrid workplace strategists.**

Let's make desk booking more open, transparent, and flexible.
