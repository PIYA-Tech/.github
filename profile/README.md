# PIYA (Pharmaceuticals In Your Area)

## Description

PIYA helps people find medicines and healthcare nearby, starting in **Baku, Azerbaijan**. Users can search for medicines, explore pharmacies on a map, and compare stock and prices reported by participating pharmacies.

Building on that original idea, PIYA now brings medicine discovery, appointments, personal health information and professional care workflows into one connected platform. Patients use **PIYA**, doctors and pharmacists use **PIYA Care**, and managers and administrators use the web workspace to manage their organisations.

The goal remains simple: make it easier to find the care you need and keep the information from that care connected.

[Visit PIYA](https://piya.life)

## Features

### Find medicines and nearby care

- Search the medicine catalogue and find pharmacies with reported stock.
- View available pharmacy prices and explore nearby options on a map.
- Use location and distance-based discovery to find care nearby.
- Browse doctors, clinics, hospitals and pharmacies in Baku.
- Scan medicine packaging barcodes in the mobile apps, with manual search available.
- Book and manage appointments with participating doctors.

Stock, prices and booking availability depend on connected providers and their data. A directory listing does not necessarily mean a facility has joined PIYA or supplies live inventory.

### Manage personal health — PIYA

- Keep recorded appointments, prescriptions, referrals, lab results and medical documents together.
- Track personal medications and use supported refill and prescription-pickup workflows.
- Set medication reminders, log doses and view supported Apple Health measurements in the iOS app.
- Follow care plans, consultation summaries and follow-up recommendations in supported clients.
- View admission summaries and attending-doctor information through Hospital stays on iOS.
- Set up an emergency profile with allergies, conditions, medicines and emergency contacts.
- Share an expiring emergency QR/token and review or revoke access through supported workflows.

PIYA contains information entered into or shared with the platform; it does not automatically have a patient's complete medical history from every provider.

### Support doctors and pharmacists — PIYA Care

- Review assigned visits and authorised patient information.
- Record consultations and create prescriptions.
- Request time-limited, audited emergency access using a patient-provided token and a clinical reason.
- Admit patients from an eligible consultation or authorised emergency-QR workflow in iOS Care.
- Manage active cases, add chart notes and append corrections without replacing the original note, then record discharge outcomes.
- Review pharmacy inventory and refill requests.
- Scan prescription pickup tokens and explicitly confirm authorised dispensing.

### Manage participating organisations

- Manage facilities, pharmacies, staff assignments, users and permissions through role-specific web workspaces.
- Review audit records and control access to organisational resources.
- Import and synchronise pharmacy inventory using the desktop **PIYA Sync Agent**.

### Platform and access

- Separate native **PIYA** and **PIYA Care** apps for iOS and Android.
- A React-based web application for patient, professional and management workflows.
- English, Azerbaijani and Russian localisation in the web application; translation coverage varies across clients.
- Two-factor authentication, role- and relationship-based permissions, and controlled emergency sharing.

**Development status:** these features describe the current implementation, not a guarantee of deployment or equal coverage across every app. Clinical case management is currently implemented in the backend and iOS Care. Mobile distribution, external integrations and provider coverage depend on release and partner readiness. Case vital-sign charts and alerts are currently demonstration simulations, not live clinical monitoring. PIYA is not an emergency response service.

## Technologies

- **Backend:** C#, ASP.NET Core, Entity Framework Core
- **Database and caching:** PostgreSQL, Redis
- **Web:** React, TypeScript, JavaScript, Vite, Tailwind CSS, HTML and CSS
- **iOS:** Swift, SwiftUI, MapKit and HealthKit
- **Android:** Kotlin and Jetpack Compose
- **Desktop inventory sync:** Electron and TypeScript
- **Infrastructure and development tools:** Docker and Postman

<div align="center">
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/_net_core.png" alt=".NET Core" title=".NET Core"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/c%23.png" alt="C#" title="C#"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/redis.png" alt="Redis" title="Redis"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postgresql.png" alt="PostgreSQL" title="PostgreSQL"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/postman.png" alt="Postman" title="Postman"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/react.png" alt="React" title="React"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/typescript.png" alt="TypeScript" title="TypeScript"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/javascript.png" alt="JavaScript" title="JavaScript"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/html.png" alt="HTML" title="HTML"/></code>
  <code><img width="50" src="https://raw.githubusercontent.com/marwin1991/profile-technology-icons/refs/heads/main/icons/css.png" alt="CSS" title="CSS"/></code>
</div>
