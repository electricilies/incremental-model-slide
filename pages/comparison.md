---
layout: center
class: text-center
---

# Compare Incremental to Waterfall

## Graphs, Differences

---
hideInToc: true
---

## Graphs

<br>

### Waterfall

```mermaid
flowchart LR
    A[Requirements] --> B[Design]
    B --> C[Development]
    C --> D[Testing]
    D --> E[Deployment]
    E --> F[Maintenance]
```

### Incremental

```mermaid
flowchart LR
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
```

---
transition: slide-up
hideInToc: true
---

## Differences

|      **Waterfall**      |       **Incremental**        |
| :---------------------: | :--------------------------: |
|         Simple          |           Complex            |
|      Inflexibility      | Flexibility and Adaptability |
| High Risk, Late Testing |  Early Detection of Defects  |
|     Small Projects      |      Suitable for both       |
