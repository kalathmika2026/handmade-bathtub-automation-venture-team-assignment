# Verification and Inquiry Analysis

## Three Sample Buyers Prioritization Matrix

| Priority | Buyer ID | Persona Profile | Rationale | Next Consultation Question | Lead Generation Sourcing Channel |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **1 (Highest)** | **P01** | Interior Designer (Pune) | High-intent B2B buyer managing a premium home project with a generous 60-day timeline. Looking for 2 custom basins. | "Could you share the rough plumbing blueprints or counter dimensions so we can tailor the stone cuts to your design layout?" | Premium interior architecture directories and targeted LinkedIn design networks in Maharashtra. |
| **2 (Medium)** | **P02** | Boutique Hotel Buyer | High-volume wholesale potential (12 units), but the extreme 10-day deadline makes custom stone creation tight. Open to alternative materials. | "Since stone cuts take 21 days, would you be open to our in-stock premium alternative resin composites that can ship immediately?" | Boutique hospitality procurement platforms and commercial real estate construction forums. |
| **3 (Lowest)** | **P03** | Individual Homeowner | Low-intent B2C buyer with an unrealistic budget (<INR 5,000) and delivery timeline (3 days) for artisanal stone work. | "We can explore smaller tabletop marble accessories within that budget, or would you like to view our payment structures for standard orders?" | High-end home decor hashtags on Instagram or local residential renovation forums. |

---

## Centralized Inquiry Tracker (Inquiry Logs L01 - L05)

| Inquiry ID | Source | Prospect Name | Status | Missing Details for Quote | Immediate Next Action / Response Strategy |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **L01** | Instagram | Person C001 | **In Progress** | Specific design/dimensions for the Pune bathroom basin. | Schedule a custom bathroom consultation link to lock down sizing choices. |
| **L02** | Website | Person C001 | **Duplicate** | None (Identical matching entry to L01). | Keep entry logged for volume history tracking; do not send a double message to avoid spamming. |
| **L03** | Website | Person C002 | **Awaiting Data** | Destination shipping address, delivery date, and explicit budget limits. | Send custom form link: "To build your total quote for two units, please confirm your delivery pincode and target date." |
| **L04** | Instagram | Person C003 | **Rejected / Pivot** | Alternative product flexibility. | Politely reject the 3-day turnaround: "Handmade stone requires a strict 21-day processing window. Let's look at accessories." |
| **L05** | Website | Person C004 | **Pending Verification** | Validated asset sheets. | State that the 10-year warranty certificate and instant stock counts require physical manager confirmation today. |

---

## Operational Metrics & Testing Framework

### 📊 Metric to Count
- **Lead Qualification Rate (LQR):** The exact ratio of raw inbound messages that match our production constraints (Minimum 21 days lead time, budget > INR 10,000 per basin) versus total inbound inquiries.

### 📝 Recording Method
- A simple shared cloud spreadsheet where every inbound row logs a `1` (Qualified) or `0` (Unqualified) based on automated form text parameters.

### 🧪 Proposed Micro-Test
- **Friction-Based Validation Test:** Swap out the plain "Ask for a Quote" text button on the mockup flow with a clean drop-down menu forcing the buyer to select their required delivery timeline (Options: "Under 10 days", "10-20 days", "21+ days"). If an unqualified lead clicks "Under 10 days", route them automatically to an informative page explaining artisanal curing times to protect support bandwidth.
