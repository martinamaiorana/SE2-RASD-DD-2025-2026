# Best Bike Paths (BBP)

**Software Engineering 2 — A.Y. 2025-2026**
**Requirement Engineering and Design Project**

Authors: Brini, Maiorana, Lucariello

---

## The project

Best Bike Paths (BBP) is a software system that supports users in creating and
browsing bike paths. Registered users can record their cycling
trips (manually or automatically while biking), integrating statistics such as distance, average speed and weather information, and any user — registered or not — can query the system for the best bike path between an origin and a destination.

Our scope covers **all aspects of BBP**:

- Recording of personal trips.
- Insertion of publishable information in **manual mode**.
- Insertion of publishable information in **automated mode** and its confirmation
  by the user.
- **Merging** of information incoming from different users.
- Visualization of the paths between a user-specified origin and destination.

## Deliverables

This project consists of two documents to be produced:

| Document | Description |
|----------|-------------|
| **RASD** | Requirement Analysis and Specification Document |
| **DD**   | Design Document                                 |

## Repository structure

```
.
├── RASD/                          # RASD source (LaTeX) — chapters, diagrams, images
├── DD/                            # DD source (LaTeX) — chapters, images, sequence diagrams
├── DeliveryFolder/                # Submitted PDF deliverables + Alloy model
│   ├── RASD_BriniLucarielloMaiorana.pdf
│   ├── DD_BriniLucarielloMaiorana.pdf
│   └── alloy/                     # Alloy models, assertions and example worlds
├── Assignment_RDD_AY_2025_2026.pdf   # Original project assignment (problem statement)
└── README.md
```



The final PDF versions are committed and pushed to `DeliveryFolder/`.
