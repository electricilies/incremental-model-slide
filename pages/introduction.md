---
transition: fade
---

# Giới thiệu về Incremental Model
<hr>
<div class='mt-5'>
    <span v-click class='text-4xl leading-[1.5]'>
        <span class='font-bold'>Incremental Model</span> (Mô hình tăng trưởng) là một phương pháp phát triển phần mềm trong đó:
    </span>
    <div></div>
    <ul class='text-3xl'>
        <li v-click>
            Hệ thống được chia thành các <span class='text-red-300 font-bold'>module</span> nhỏ.
        </li>
        <li v-click>
            Mỗi module được phát triển, kiểm thử và <span class='text-red-300 font-bold'>triển khai độc lập</span> với nhau.
        </li>
        <li v-click>
            Các module được tích hợp để tạo thành <span class='text-red-300 font-bold'>hệ thống hoàn chỉnh</span>.
        </li>
    </ul>
</div>

---
transition: fade-out
class: text-center
---

```mermaid
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
    style A fill:#4da6ff,stroke:#fff,color:#fff
    style B1 fill:#005f99,stroke:#fff,color:#fff
    style B2 fill:#005f99,stroke:#fff,color:#fff
    style B3 fill:#005f99,stroke:#fff,color:#fff
    style C1 fill:#cc66ff,stroke:#fff,color:#fff
    style C2 fill:#cc66ff,stroke:#fff,color:#fff
    style C3 fill:#cc66ff,stroke:#fff,color:#fff
    style D1 fill:#ffcc00,stroke:#fff,color:#000
    style D2 fill:#ffcc00,stroke:#fff,color:#000
    style D3 fill:#ffcc00,stroke:#fff,color:#000
    style E1 fill:#66cc66,stroke:#fff,color:#fff
    style E2 fill:#66cc66,stroke:#fff,color:#fff
    style E3 fill:#66cc66,stroke:#fff,color:#fff

    %% White arrows
    linkStyle default stroke:#ffffff,stroke-width:2px,color:#ffffff
```
<div class='font-bold text-xl mt--2'>
    Incremental Model
</div>

---
transition: fade
---

<!--
Partial System Delivery: The system is developed and delivered in small, manageable pieces. Each part adds new features to the previous version.
Early Functionality: Basic functionality is available early in the project. This allows users to start using and testing the system quickly.
Customer Feedback Loop: Feedback is collected after each part is delivered. This helps improve the next version of the system.
Flexible to Changes: Changes or new features can be added between increments. This makes the model flexible to evolving needs.
Combination of Linear and Iterative Approaches: Combines the structured approach of Waterfall with flexibility. Supports both planning and ongoing improvements.
-->

# **Đặc điểm chính (Characteristics)**
<hr>
<ul class='text-3xl mt-10'>
    <li>
        Partial System Delivery
    </li>
    <li>
        Early Functionality
    </li>
    <li>
        Customer Feedback Loop
    </li>
    <li>
        Flexible to Changes
    </li>
    <li>
        Combination of Linear and Iterative Approaches
    </li>
</ul>
