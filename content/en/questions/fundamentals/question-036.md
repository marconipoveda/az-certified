---
title: "Question 036"
question: "Drag and drop the Azure load-balancing option to its use case: (A) Azure Load Balancer, (B) Application Gateway, (C) Traffic Manager."
module: "Module 1: Describe Azure networking services"
domain: "Describe Cloud Concepts"
difficulty: "medium"
type: "drag-and-drop"
tags:
  - az900
  - load-balancing
---

> https://learn.microsoft.com/azure/architecture/guide/technology-choices/load-balancing-overview

- [x] A → Distribute TCP/UDP traffic within a VNet
- [x] B → Layer 7 routing with SSL termination
- [x] C → Global DNS-based routing across regions
- [ ] Any other mapping

**Explanation:**
Load Balancer handles Layer 4 internal/external traffic, Application Gateway manages HTTP(S) features, Traffic Manager selects the best endpoint via DNS.
