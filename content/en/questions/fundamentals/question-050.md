---
title: "Question 050"
question: "A logistics firm needs to replicate data to another Azure region with minimal management overhead. Which service fits best?"
module: "Module 1: Describe Azure storage services"
domain: "Describe Cloud Concepts"
difficulty: "medium"
type: "multiple-choice"
tags:
  - az900
  - storage
---

> https://learn.microsoft.com/azure/storage/common/storage-redundancy

- [ ] Locally redundant storage (LRS)
- [x] Geo-redundant storage (GRS)
- [ ] Zone-redundant storage (ZRS)
- [ ] Azure Files

**Explanation:**
GRS asynchronously replicates to a paired region automatically; LRS and ZRS stay within a region.
