# 🚌 TransportOps — Transport Trip Management System

> A web application that helps transport companies plan, record, and manage trips — streamlining resource assignment, operational tracking, and performance reporting.

---

## Table of Contents

- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Architecture](#architecture)
- [Repository Tree](#repository-tree)
- [Prerequisites](#prerequisites)
- [Environment Setup](#environment-setup)
- [Usage](#usage)
- [Testing](#testing)
- [Roadmap](#roadmap)
- [License](#license)
- [Contact](#contact)

---

## About the Project

**TransportOps** (P15) is a web-based management system designed for transport companies that need to coordinate their daily operations. The platform allows operators to plan and register trips with full detail — origin, destination, date, time, client, and service type — while keeping track of each trip's lifecycle from *scheduled* all the way to *completed* or *cancelled*.

Beyond trip management, the system handles the full roster of vehicles and drivers, provides an operational dashboard for monitoring active and past trips, and generates reports and KPIs to support decision-making.

Key features:
- Trip planning and status tracking (scheduled → in progress → finished / cancelled)
- Vehicle and driver registry with availability control
- Operational log per trip (departure time, arrival, delays, incidents)
- Reports on trip history, vehicle utilization, and driver performance
- Metrics dashboard for operational planning

---

## Tech Stack

| Layer | Technology |
|---|---|
| Runtime | Bun (latest) |
| Testing | Bun test |
| Version Control | Git + GitHub |

---

## Architecture

>  To be defined during Sprint 1 once the base structure is set up.

---

## Repository Tree

```
S1C-P15-BMVV/
├── src/
│   ├── modules/                  # Feature-based modules
│   │   ├── trips/
│   │   │   ├── trips.routes.ts
│   │   │   ├── trips.controller.ts
│   │   │   └── trips.service.ts
│   │   ├── vehicles/
│   │   │   ├── vehicles.routes.ts
│   │   │   ├── vehicles.controller.ts
│   │   │   └── vehicles.service.ts
│   │   ├── drivers/
│   │   │   ├── drivers.routes.ts
│   │   │   ├── drivers.controller.ts
│   │   │   └── drivers.service.ts
│   │   └── reports/
│   │       ├── reports.routes.ts
│   │       ├── reports.controller.ts
│   │       └── reports.service.ts
│   ├── middlewares/              # Auth, error handling, validation
│   └── utils/                    # Utility functions and helpers
├── tests/                        # Test files
├── dist/                         # Build output
├── package.json
├── bunfig.toml
├── .gitignore
└── README.md
```

---

## Prerequisites

- [Bun](https://bun.sh/) (latest)
- [Git](https://git-scm.com/)

---

## Environment Setup

```bash
# Clone the repository
git clone https://github.com/uai-cl-tics420/S1C-P15-BMVV.git
cd S1C-P15-BMVV

# Install dependencies
bun install

# Run development server
bun run dev

# Build for production
bun run build

# Run tests
bun test
```

---

## Usage

> To be documented as features are implemented throughout the sprints.

---

## Testing

```bash
# Run all tests
bun test
```

---

## Roadmap

| Sprint | Epic | Status |
|---|---|---|
| S1–S2 | Setup & base configuration | 🔲 Todo |
| S2–S4 | Trip planning & registration | 🔲 Todo |
| S3–S5 | Vehicle & driver management | 🔲 Todo |
| S5–S8 | Operational control & tracking | 🔲 Todo |
| S8–S11 | Reports & KPI dashboard | 🔲 Todo |
| S12 | Buffer, bug fixes & final delivery | 🔲 Todo |

See the [open issues](https://github.com/uai-cl-tics420/S1C-P15-BMVV/issues) for the full list of planned features.

---

## License

> To be defined.

---

## Contact

Project developed by students of **UAI — TICS420** as part of the Software Engineering course.

| Name | GitHub |
|---|---|
| <!-- Student 1 Vicente Concha --> | <!-- @Vice-CG --> |
| <!-- Student 2 Martin Gonzalez --> | <!-- @Coaffy --> |
| <!-- Student 3 Benjamin Henriquez --> | <!-- @BenHenriquez --> |
| <!-- Student 4 Vicente Pulgar --> | <!-- @Vicenlol09 --> |

Repository: [https://github.com/uai-cl-tics420/S1C-P15-BMVV](https://github.com/uai-cl-tics420/S1C-P15-BMVV)
