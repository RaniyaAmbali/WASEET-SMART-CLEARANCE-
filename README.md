# WASEET (وسيط) – Smart Customs Accelerated Clearance

Working wireframe prototype for the **TDRA UAE Hackathon 2026**, **Challenge 21: Smart Customs Accelerated Clearance** (Abu Dhabi Customs).

**Live demo:** https://raniyaambali.github.io/WASEET-SMART-CLEARANCE-/

> Prototype with mock data. All names, numbers and thresholds are illustrative, not real customs rules.

## The problem

Cargo clearance is slow because each authority checks the same documents separately, nobody owns the gaps between them, and problems are often found when the cargo has already arrived. Think of ordering a package from abroad that gets delayed for weeks over a document issue nobody flagged in time.

## Our idea

WASEET is a shared rulebook plus a web platform that puts it into practice. It is designed to **complement** the existing Abu Dhabi trade platform, not replace it.

- **Verified once:** a document checked by one party is not asked for again
- **Clear owner and deadline** for every open problem
- **Early warning:** problems show up days before arrival
- **People decide:** the app suggests; officers and receiving agencies confirm

## What the prototype shows

Demo shipment: dairy cargo whose lab certificate expires before arrival.

1. **Broker:** sees what is blocking the shipment, who must fix it and by when, then uploads and confirms a new certificate
2. **Customs officer:** sees a suggested lane with reasons, then confirms or overrides it
3. **Food Safety:** accepts the handoff, and ownership moves
4. **Port operator:** sees the shipment released for handling

## Run it

Open the live demo link above, or download `index.html` and open it in any browser. No installation needed.

## 90-day pilot idea

| Days | Phase | What happens |
|---|---|---|
| 1 to 30 | Learn | Interview 5 to 10 brokers, agree a one-page rulebook |
| 31 to 60 | Build | Test on past shipments with sample data |
| 61 to 90 | Measure | Run in shadow mode on live shipments, then decide |

Scope: fresh food, one port, two authorities to start. The pilot only suggests and measures; no authority's decision or legal mandate is replaced.

## Limitations

- Mock data only, with no real integrations
- Document field reading and the "request from exporter" action are simulated
- Savings are not claimed; they would be measured in the pilot

## Team WASEET

Built by:

- **Raniya Ambali**
- **Anastasia Kajalic**
- **Linah Fathima**
- **Hana Mundambra**
- **Aima Wasif**

Thank you to every teammate who helped build, test and shape this project.
