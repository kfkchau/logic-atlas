# coremd-termmap

## Term Hierarchy Map (Canonical)

### Activity (activity)
- **Types**
  - Requirement (req) [REQ]
  - Event Record (event) [EVT]
  - Capability (cap) [CAP]
- **Elements**
  - Actor (actor)
  - Action (action)
  - Object (object)
  - Target (target)
- **Temporal states**
  - Start (start)
  - End (end)

### Action – Types (action)
- Movement (move) [MV]
- Static (static) [NM]
- Transformation (trans) [TF]
- Lock (lock) [NF]
- Not Applicable (na) [NA]
- ↪ used in: Action (activity)

### Resource – Types (resource)
- Consumable (consumable) [CO]
- Durable (durable) [NC]
- Physical (phys) [PH]
- Virtual (virt) [VI]
- ↪ used in: Object (activity), Target (activity), Actor (activity)

### Measurement – Types (measure)
- Length (length) [LN]
- Width (width) [WD]
- Height (height) [HT]
- ↪ used in: Resource (resource), Action (action), Enforcement Strength (enforce)

### Relationship Architecture – Types (rel_arch)
- Hierarchical (hierarchy) [HR]
- Network (network) [NT]
- System (system) [SY]

### Spatial Relationship – Types (spatial)
- Unrelated (unrelated) [UR]
- Adjacent (adjacent) [AD]
- Intersecting (intersect) [IN]
- Nested (nested) [NS]
- Embedded (embedded) [EM]
- ↪ used in: Start x Resource (activity), End x Resource (activity) 

### Enforcement (enforce)
- Scope (scope) [SCP]
  - Blanket (blanket) [BL]
  - Targeted (targeted) [TG]
- Mechanism (mechanism) [MCH]
  - Incentive (incentive) [IC]
  - Deterrent (deterrent) [DT]
- Strength (strength) [STR]
  - Absolute (absolute) [AB]
  - Significant (significant) [SG]
  - Fair (fair) [FR]
  - Minor (minor) [MN]
  - Zero (zero) [ZR]
  - ↪ used in: Mechanism (mechanism)
- ↪ used in: Connection Logic (connect)

### Composition – Types (composition)
- Whole (whole) [WH]
- Component (component) [CP]
- Surface (surface) [SF]
- Inside (inside) [IN]
- Wireframe (wireframe) [WF]
- Content (content) [CT]
- ↪ used in: Start x Resource (activity), End x Resource (activity)

### Connection Logic (connect)
- Structural (structural) [STR]
  - One-to-One (1→1) [11]
  - One-to-Many (1→N) [1N]
  - Many-to-One (N→1) [N1]
  - Many-to-Many (N→N) [NN]
- Temporal (temporal) [TMP]
  - Finish-to-Start (FS) [FS]
  - Start-to-Start (SS) [SS]
  - Finish-to-Finish (FF) [FF]
  - Start-to-Finish (SF) [SF]
- Logical (logical) [LOG]
  - AND (and) [AND]
  - OR (or) [OR]
  - XOR (xor) [XOR]
  - NAND (nand) [NAND]
  - NOR (nor) [NOR]
- ↪ used in: Start (activity), End (activity)


