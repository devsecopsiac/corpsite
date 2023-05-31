---
title: "About"
date: 2021-08-11
description: "A theme for Hugo built with Tailwind CSS."
topics: ["Hugo", "Web", "Tailwind"]
---

{{< mermaid >}}
flowchart LR
    A(GitOps導入)
    A --> B{Platform<br>製品選択}
    B -->|GitLab選択| C[GitLab Runner<br>導入サービス]
    B -->|GitHub選択| D[GitHub Actions<br>導入サービス]
    C --> E[Terraform<br>導入サービス]
    D --> E[Terraform<br>導入サービス]
    E --> F[Ansible<br>導入サービス]
    style A fill:#CCE5FF,stroke:#333,stroke-width:4px
    style B fill:#CCFFE6,stroke:#333,stroke-width:4px
    style C fill:#FF8000,stroke:#333,stroke-width:4px
    style D fill:#E6E6E6,stroke:#333,stroke-width:4px
    style E fill:#E8CFFF,stroke:#333,stroke-width:4px
    style F fill:#FFB3B3,stroke:#333,stroke-width:4px
{{< /mermaid >}} 
