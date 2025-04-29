# custom-treasure-hunt

A custom-built digital treasure hunt system designed for live events with booth-based QR code tracking. Developed for the Antam Family Gathering 2024, this tool helps manage, track, and validate participant activity across multiple stations.

## Overview

Participants must scan a unique QR code at each of the **6 booths**. After each scan, they are required to enter their **ticket number** for validation. Only invited participants with valid ticket numbers can participate.

## Key Features

- **QR Code-Based Booth Tracking**
  - Each of the 6 booths has a unique QR code linking to its designated tracking page
  - Users must scan the QR and enter their ticket number to check in at each booth
  - Prevents unauthorized access — only valid ticket holders can participate

- **Participant Validation**
  - The system checks the provided ticket number against the event invitation database
  - Only verified attendees can log visits at the booths

- **Activity Tracking**
  - Tracks how many participants have visited each individual booth
  - Tracks how many participants have completed all 6 booths (fully participated)

- **Data Export/Import**
  - Admin can **export booth visit data** for reporting and analysis
  - Enables identification of participants who are eligible for the **lucky draw** based on complete participation

## Contributions

- Developed front-end booth pages with ticket validation form
- Created back-end logic to verify ticket numbers against the database
- Implemented booth visit logging and progress tracking
- Built export/import functions to support lucky draw eligibility checks
- Ensured mobile-first design for on-site scanning
- 
## Watch Demo
- [Antam Family Gathering 2024](https://youtu.be/VNom_31-u04)
