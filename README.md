### Hi, I'm Johandi 👋 — Senior Software Developer

I build production systems end to end — cloud architecture on AWS, and AI/ML systems including
agentic workflows (LangGraph), RAG pipelines (pgvector, Qdrant), and real-time computer vision.

**Currently:** Head of IT at Pershing Global Solution, solely architecting and running their AWS
infrastructure and AI systems.

#### What I've built

Most of my production work was built on private employer and client repositories under NDA, so it
isn't visible here directly — but the systems are real:

- **RAG & agentic AI** — built an end-to-end RAG architecture (pgvector, Qdrant) and agentic
  workflows (LangGraph) for knowledge-base search and autonomous task pipelines, at Pershing Global Solution.
- **Computer vision at scale** — led a CV video analytics platform integrating 4+ models at
  under 200ms latency, and an AI voice/caption translator at 90%+ accuracy, at Blue Silo / Sigmawave AI.
- **Manufacturing systems** — rebuilt material calculation, output counting, and traceability
  systems handling millions of components monthly, at PT. Sat Nusapersada.

The pinned repos below are original projects I built outside those constraints, to demonstrate the
same skills in the open.

#### Currently building

- **[Gesture-Controlled Claw Machine](https://github.com/johandiMIS/gesture-control)** — Play a claw
  machine with your bare hand. Real-time hand tracking drives an Arduino servo gantry: depth-invariant
  mapping in palm-radius units so the same physical movement works at any distance from the camera,
  One Euro filtering for jitter-free pointing, debounced grab detection, and multi-hand arbitration so
  a bystander can't steal control. Firmware side adds a link watchdog and slew limiting.
  *(Python, MediaPipe, OpenCV, Arduino/C++)*
- **ERP for a wholesale distributor** — Self-hosted Odoo 12 deployment with **40 custom modules**
  covering multi-warehouse stock, multi-unit conversion (pcs / dozen / box) with cascading
  denomination logic, automated restock between store and display warehouses, purchasing and sales
  workflows, Indonesian e-Faktur tax invoicing, barcode and QR operations, POS synchronisation, and
  custom COGS reporting. *(Python, Odoo, PostgreSQL, Docker Compose)* — client work, repo private.

#### Selected live projects

Repos for these are private (client/venture work), but they're live in production:

- **[Proprely](https://proprely.fr)** — Operations platform for cleaning companies (private beta, EU-hosted). Sales pipeline, clients & sites, recurring contracts, mission scheduling with SOP protocols, inventory, agent management, and automatic hour tracking that feeds payroll — replacing the spreadsheet-and-WhatsApp sprawl these firms run on. Multi-tenant, with a super-admin console for onboarding client organisations. I build the application at `app.proprely.fr`. *(Next.js, NestJS, PostgreSQL, TypeScript)*
- **[Limuda](https://limuda.net)** — IT solutions studio I co-founded, delivering tailored systems and websites. *(Next.js, Turborepo, Tailwind CSS)*
- **[Limielle](https://limielle.com)** — Full business platform for a nail art studio: company profile, CRM, loyalty card program, referral tracking, vouchers & discounts, booking system, pricelist. *(NestJS, Next.js, PostgreSQL, TypeORM, TypeScript, Turborepo, AWS S3)*
- **[Mitsutama Indo Teknik](https://mitsutama-indotek.com)** — Company profile site for an industrial calibration & testing instrumentation provider. *(Next.js, NestJS, PostgreSQL, Turborepo)* — repo is public, pinned below as `mitsutama-compro`

#### Reach me

[LinkedIn](https://linkedin.com/in/johandilim) · limjohandi@gmail.com
