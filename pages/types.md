---
layout: center
class: text-center
transition: slide-up
---

# **Types of Incremental Model**

Staged Delivery Model/Parallel Development Model

---
hideInToc: true
---

## **Staged Delivery Model**

- Develops software in a sequence of planned stages, each stage delivers a functional part of the system.
- Each release brings the product closer to completion.
- Working versions are delivered at regular intervals -> visible and manageable progress.

---
class: text-center
---
```mermaid {scale: 0.8}
flowchart TD
    A[Requirements Definition] --> B[Architecture Design]
    B --> C[Subsystem 1 Construction]
    C --> D[Subsystem n Construction]
    D --> E[Verification Test]
    E --> F[Validation Test]
```

<Footnotes>
    Staged Delivery Model
</Footnotes>

---
hideInToc: true
---
## **Parallel Development Model**

- Divides the system into multiple modules that are developed simultaneously at the same time by different teams -> faster and more efficient development process.
- Reduces overall project time, allows teams to focus on specific functionalities concurrently.

---
class: text-center
---

```mermaid {scale: 0.8}
flowchart TD
    A[Requirements Definition] --> B[Architecture Design]
    B --> C1[Team 1; Subsystem 1 Construction]
    B --> C2[Team 2; Subsystem 2 Construction]
    B --> Cn[Team n; Subsystem n Construction]
    C1 --> D[Verification Test]
    Cn --> D
    D --> E[Validation Test]
```

<Footnotes>
    Staged Delivery Model
</Footnotes>