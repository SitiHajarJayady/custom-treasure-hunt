# custom-treasure-hunt

This repository showcases **event-specific treasure hunt systems** built to meet unique client requirements. Each system was tailored with custom rules, validation logic, booth tracking, and data export tools to support real-time engagement and post-event reporting.

## Implementation 1 : Antam Family Gathering 2024

Participants must scan a unique QR code at each of the **6 booths**. After each scan, they are required to enter their **ticket number** for validation. Only invited participants with valid ticket numbers can participate.

### Key Features

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

### Contributions

- Developed front-end booth pages with ticket validation form
- Created back-end logic to verify ticket numbers against the database
- Implemented booth visit logging and progress tracking
- Built export/import functions to support lucky draw eligibility checks
- Ensured mobile-first design for on-site scanning
  
## Watch Demo
- [Antam Family Gathering 2024](https://youtu.be/VNom_31-u04)

## Implementation 2 : Capital Market Summit & Expo 2024 – Aku Investor Saham
A point-based treasure hunt system categorized by booth types, built for a large-scale expo event.  
Participants scanned QR codes across categories and accumulated points — all accessible to registered users only.

### Category & Point Structure

| Category           | Points per QR  | Total QR Codes |
|--------------------|----------------|----------------|
| General Booth      | 1              | 76             |
| Investor Upgrade   | 10             | 1              |
| Seminar            | 5              | 9              |
| Survey Event       | 1              | 1              |
| IDX Mobile         | 5              | 1              |

### Key Features

- Validation of registered participants before access
- QR scans assigned points based on booth category
- Real-time logging and point accumulation
- Excel export of participant data with category filters

### Contributions

- Built multi-category point logic based on QR scans
- Designed validation and tracking logic for registered users
- Implemented export functionality with filters by category
- Created UI optimized for mobile event participation

  
## Watch Demo
- [Capital Market Summit & Expo 2024 – Aku Investor Saham](https://youtu.be/c5SbqkWRiw0)
