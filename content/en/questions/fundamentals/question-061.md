---
title: "Question 061"
question: "Drag and drop the Azure storage redundancy option to the risk it mitigates: (A) Zone-redundant storage, (B) Geo-zone-redundant storage, (C) Read-access geo-redundant storage."
module: "Module 1: Describe Azure storage services"
domain: "Describe Cloud Concepts"
difficulty: "hard"
type: "drag-and-drop"
tags:
  - az900
  - storage
---

> https://learn.microsoft.com/azure/storage/common/storage-redundancy

- [x] A → Protects against zone failures within a region
- [x] B → Handles zone failure plus regional failover option
- [x] C → Provides cross-region replication with read access
- [ ] Any other mapping

**Explanation:**
ZRS covers intra-region zones, GZRS combines zone + geo, and RA-GRS adds readable secondary region.
