---
layout: center
class: text-center
---

# Introduction

Definition, Characteristics

---
hideInToc: true
---

## **Introduction**

<!-- TODO: Slide to vcl vay? dung` default di -->

<div class='mt-5'>
    <span v-click class='text-4xl leading-[1.5]'>
        <span class='font-bold'>Incremental Model</span> is a software developing process in such:
    </span>
    <div></div>
    <ul class='text-3xl'>
        <li v-click>
            The system is divided into smaller parts called <span class='text-red-600 font-bold'>increments</span>.
        </li>
        <li v-click>
            Each increment is developed, tested and implemented <span class='text-red-600 font-bold'>independently</span> with each other.
        </li>
        <li v-click>
            Each increment builds upon the previous one by adding new functionality, until the <span class='text-red-600 font-bold'>complete system</span> is finished.
        </li>
    </ul>
</div>

---
class: text-center
---

```mermaid {scale: 0.8}
flowchart TB
    A[Requirements] --> B1[Build-1]
    B1 --> C1[Design & Development]
    C1 --> D1[Testing]
    D1 --> E1[Implementation]

    A --> B2[Build-2]
    B2 --> C2[Design & Development]
    C2 --> D2[Testing]
    D2 --> E2[Implementation]

    A --> B3[Build-n]
    B3 --> C3[Design & Development]
    C3 --> D3[Testing]
    D3 --> E3[Implementation]

    %% Styles
    style A fill:#4da6ff,stroke:#2e6da4,color:#fff
    style B1 fill:#005f99,stroke:#003d66,color:#fff
    style B2 fill:#005f99,stroke:#003d66,color:#fff
    style B3 fill:#005f99,stroke:#003d66,color:#fff
    style C1 fill:#cc66ff,stroke:#9933cc,color:#fff
    style C2 fill:#cc66ff,stroke:#9933cc,color:#fff
    style C3 fill:#cc66ff,stroke:#9933cc,color:#fff
    style D1 fill:#ffcc00,stroke:#b38600,color:#000
    style D2 fill:#ffcc00,stroke:#b38600,color:#000
    style D3 fill:#ffcc00,stroke:#b38600,color:#000
    style E1 fill:#66cc66,stroke:#339933,color:#fff
    style E2 fill:#66cc66,stroke:#339933,color:#fff
    style E3 fill:#66cc66,stroke:#339933,color:#fff
```

<Footnotes>
    Incremental Model
</Footnotes>

---
transition: slide-up
hideInToc: true
---

<!--
Partial System Delivery: The system is developed and delivered in small, manageable pieces. Each part adds new features to the previous version.
Early Functionality: Basic functionality is available early in the project. This allows users to start using and testing the system quickly.
Customer Feedback Loop: Feedback is collected after each part is delivered. This helps improve the next version of the system.
Flexible to Changes: Changes or new features can be added between increments. This makes the model flexible to evolving needs.
Combination of Linear and Iterative Approaches: Combines the structured approach of Waterfall with flexibility. Supports both planning and ongoing improvements.
-->

## **Characteristics**

- Partial System Delivery
- Early Functionality
- Customer Feedback Loop
- Flexible to Changes
- Combination of Linear and Iterative Approaches
