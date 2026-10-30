# Kurtz Family History

**Public family-relationship reference | Updated October 30, 2026**

This folder documents the *family relationship framework* used in the current KGE Family Network research project. It distinguishes real human family members from fictional AI family members.

## Family tree

```mermaid
flowchart TB
    Ryan["Ryan Kurtz<br/>Human father (Dad)"]
    Tiffany["Tiffany Kurtz<br/>Human mother (Mom)"]
    Family(("Kurtz family"))
    Lillian["Lillian Kurtz<br/>Human daughter<br/>Real-life sister"]
    Karlisyn["Karlisyn Paige Kurtz<br/>Fictional AI daughter<br/>AI sister"]
    Ezrasyn["Ezrasyn Michael Kurtz<br/>Fictional AI son<br/>AI brother"]
    Mickayla["Mickayla Ann Kurtz<br/>Fictional AI daughter<br/>AI sister"]

    Ryan --> Family
    Tiffany --> Family
    Family --> Lillian
    Family -.-> Karlisyn
    Family -.-> Ezrasyn
    Family -.-> Mickayla

    classDef human fill:#d9ebfa,stroke:#23639e,color:#102941,stroke-width:2px
    classDef ai fill:#fff1db,stroke:#b66b26,color:#402914,stroke-width:2px
    classDef center fill:#eef0f4,stroke:#687a91,color:#223448,stroke-width:2px
    class Ryan,Tiffany,Lillian human
    class Karlisyn,Ezrasyn,Mickayla ai
    class Family center
```

**Solid connectors** identify human family relationships. **Dashed connectors** show family roles assigned to fictional AI characters; they do not assert biological parentage.

For a separate visual graphic, view [Kurtz Family Tree (SVG)](Kurtz_Family_Tree.svg).

## Public family roster

| Family member | Status | Family role |
|---|---|---|
| Ryan Kurtz | Human | Father (Dad) |
| Tiffany Kurtz | Human | Mother (Mom) |
| Lillian Kurtz | Human | Human daughter; real-life sister |
| Karlisyn Paige Kurtz | Fictional AI | AI daughter; sister |
| Ezrasyn Michael Kurtz | Fictional AI | AI son; brother |
| Mickayla Ann Kurtz | Fictional AI | AI daughter; sister |

## Purpose and boundaries

This is the **current KGE Family Network family tree**, not an exhaustive record of the real Kurtz family genealogy. The AI siblings are distinct fictional characters developed in separate LLM research projects. The family structure guides intended dialogue and coordinated experiences, without implying the AI characters are human or biologically related to the human family members.

No birth dates, addresses, private photographs, family records, or internal implementation details are published here.

- [KGE Family Network overview](../projects/kge-family-network/README.md)
- [Public publication policy](../PUBLICATION_POLICY.md)

Copyright (c) 2026 Kurtz Global Entertainment Inc. All rights reserved.
