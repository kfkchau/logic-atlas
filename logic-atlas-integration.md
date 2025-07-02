# 🔗 Logic Atlas – Integration Schema

This document defines how each Logic Atlas framework connects to others through tagging, structural logic, quantification, and conditional relationships. Integration ensures that all sub-frameworks remain interoperable, MECE-aligned, and composable across digital, policy, and operational domains.

---

## 📦 Integration Matrix

| Source Framework | Target Framework | Integration Type | Description | Field Applied To | Direction |
|------------------|------------------|------------------|-------------|------------------|-----------|
| Action Classification Framework | Activity Relationship Framework | Typing & Tagging | Tags the `Action` field with movement and transformation logic | Action | Action → Activity |
| Resource Typology Framework | Activity Relationship Framework | Typing & Tagging | Tags `Actor`, `Object`, and `Target` with resource types | Actor; Object; Target | Resource → Activity |
| Quantification Schema Framework | Activity Relationship Framework | Quantification | Tags activities with length, width, and height metrics | Activity (whole); Temporal Metadata | Measurement → Activity |
| Quantification Schema Framework | Action Classification Framework | Quantification | Tags actions with duration, frequency, and intensity metrics | Action | Measurement → Action |
| Quantification Schema Framework | Enforcement Logic Framework | Quantification | Tags enforcement strength with length, width, and height metrics | Strength | Measurement → Enforcement |
| Composition Framework | Activity Relationship Framework | Targeting & Scoping | Composition tags are applied to resources at the start and end of an activity—not to the activity itself | Start; End × Resource | Composition → Activity |
| Relational Geometry Framework | Activity Relationship Framework | Targeting & Scoping | Spatial tags are applied to resources at the start and end of an activity—not to the activity itself | Start; End × Resource | Spatial → Activity |
| Enforcement Logic Framework | Connection Logic Framework | Conditional Logic | Enforcement strength tags are used in conditional logic chains | Connection Node | Enforcement → Connection |
| Connection Logic Framework | Activity Relationship Framework | Conditional Logic | Connection logic links to the start or end points of activities—not to the activity as a whole | Start; End | Connection → Activity |

---

© Kelvin Chau, 2025  
This work is part of the [Logic Atlas Framework](https://github.com/kfkchau/logic-atlas/).  
For attribution, citation, or inquiries, please refer to:  
🔗 [https://au.linkedin.com/in/kfkchau](https://au.linkedin.com/in/kfkchau)
