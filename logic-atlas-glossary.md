# 📚 Shared Glossary & Typing Schema

This glossary defines all formal terms, tags, and typing logic used across the framework system. It supports semantic consistency, tagging interoperability, and onboarding clarity.

---

## 🧾 Formal Framework Names

| Framework Name | Description |
|----------------|-------------|
| Activity Relationship Framework | Models activities using Actor, Action, Object, Target |
| Verb Action Tagging Framework | Tags verbs using Movement × Transformation logic |
| Resource Classification Framework | Classifies resources by Consumability × Physicality |
| Enforcement Logic Framework | Models enforcement as structural nodes with scope, mechanism, source, and strength |
| Universal Measurement Framework | Measures entities and activities using Length, Width, Height |
| Universal Relationship Architecture | Maps influence and flow using Hierarchical, Network, System logic |
| Relational Geometry Framework | Classifies spatial relationships using five categories |
| Resource Part Typology | Classifies parts of a resource (Whole, Component, Surface, Inside, Wireframe, Content) |
| Logic Atlas | Meta-framework governing all logic |
| Documentation Strategy & Governance | Defines naming conventions and documentation structure |
| Gap & Task Tracker | Tracks missing logic and resolution tasks |
| Shared Glossary & Typing Schema | Centralized term definitions and tag meanings |
| Change Log & Version History | Records all framework updates and refinements |
| Integration Schema | Maps how frameworks connect and share logic |
| Unified Visual Schema Repository | Centralizes all visual logic and diagrams |
| Chat Logic Rule Base | Governs chat behavior, rule enforcement, and compliance logic |

---

## 🧠 Activity Relationship Framework

| Term | Definition |
|------|------------|
| Actor | Entity capable of initiating an action (e.g. person, team, system) |
| Action | Verb or behavior initiated by the actor. Not an activity itself, but a component of one. |
| Object | Entity affected or manipulated by the action |
| Target | Destination or endpoint of the action |
| RQ | Requirement-type activity |
| EV | Event record-type activity |
| CP | Capability-type activity |

---

## 🏷️ Verb Action Tagging Framework

| Tag | Meaning |
|-----|--------|
| MV | Movement occurs |
| NM | No movement occurs |
| N/A (Movement) | Movement is irrelevant |
| TF | Transformation occurs |
| NF | No transformation occurs |
| N/A (Transformation) | Transformation is irrelevant |

**Note**: Every verb/action must be tagged with both dimensions, even if one is N/A.

---

## 📦 Resource Classification Framework

| Tag | Meaning |
|-----|--------|
| Consumable | Resource is depleted or transformed by use |
| Non-Consumable | Resource retains utility after use |
| Physical | Tangible, spatially located |
| Virtual | Intangible, digitally represented |

**Clarification**: Rights, licenses, and digital identities are non-consumable & virtual. Human attention and water are consumable.

---

## 🧩 Resource Part Typology

| Tag | Meaning |
|-----|--------|
| whole | Entire entity |
| component | Sub-unit or part |
| surface | Outer boundary |
| inside | Internal volume excluding surface |
| wireframe | Structural frame or skeleton |
| content | Non-frame material including surface |

**Grouped Dimensions**:
- **Structural Scope**: whole, component
- **Boundary Logic**: surface, inside
- **Structural Composition**: wireframe, content

**Combinability**: Tags can be combined using logical operations (∩, ∪, −) for precision modeling.

---

## 📐 Relational Geometry Framework

| Tag | Meaning |
|-----|--------|
| Unrelated | Entities have spatial separation |
| Adjacent | Entities touch at boundary (zero gap) |
| Intersecting | Entities share partial volume |
| Nested | One entity enclosed, touching boundary |
| Embedded | One entity enclosed, not touching boundary |

**Clarification**: Surface contact = Adjacent; volume overlap = Intersecting.

---

## 🧮 Universal Measurement Framework

| Dimension | Meaning |
|-----------|--------|
| Length | Time-related measure (e.g. duration, delay) |
| Width | Distribution-related measure (e.g. quantity, spread) |
| Height | Effect-related measure (e.g. strength, impact) |

**Usage**: Each tagged item (e.g. activity, resource) can carry a [L, W, H] vector.

---

## 🛡️ Enforcement Logic Framework

| Tag | Meaning |
|-----|--------|
| Blanket | Applies to all entities in scope |
| Targeted | Applies to specific entities |
| Incentive | Positive reinforcement |
| Deterrent | Negative consequence |
| Legal | Statutory source |
| Policy | Internal or public policy |
| Contractual | Agreement-based source |
| Systemic | Automated enforcement |
| Discretionary | Case-by-case enforcement |
| Absolute | E = ∞ (non-negotiable enforcement) |
| Significant | E > C |
| Fair | E ≈ C |
| Minor | E < C |
| Zero | E = 0 |

**Clarification**: Enforcement is a structural node linking condition activities to contingent outcomes.

---

## 🔗 Universal Relationship Architecture

| Type | Meaning |
|------|--------|
| Hierarchical | Top-down authority flow |
| Network | Peer-to-peer connectivity |
| System | Cyclical flow with feedback loops |

**Resource Flow Types**: Trust, authority, information, feedback.

---

## 🧭 Integration & Meta Logic

| Term | Meaning |
|------|--------|
| Universal Relationship Mapper | Visual tool for mapping relationships across architectures |
| Logic Atlas | Meta-framework governing all logic and integration |
| Gap & Task Tracker | Tracks missing logic and resolution tasks |
| Change Log & Version History | Records all framework updates and refinements |
| Integration Schema | Maps how frameworks connect and share logic |
| Unified Visual Schema Repository | Centralizes all visual logic and diagrams |
| Documentation Strategy & Governance | Defines naming conventions and documentation structure |
| Chat Logic Rule Base | Governs chat behavior, rule enforcement, and compliance logic |

---

© Kelvin Chau, 2025  
This work is part of the [Logic Atlas Framework](https://github.com/kfkchau/logic-atlas/).  
For attribution, citation, or inquiries, please refer to:  
🔗 [https://au.linkedin.com/in/kfkchau](https://au.linkedin.com/in/kfkchau)
