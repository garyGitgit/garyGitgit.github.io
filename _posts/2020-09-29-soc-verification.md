---
title: What is SoC design verification?
tags: [SoC, Verification]
style: fill
color: warning
description: SoC (System On Chip) design verification is a process that the product works correctly in a variety of scenarios. It is also a process of finding out a bug hiding in the hardware design.
<!-- external_url: https://blog.usejournal.com/how-to-undo-your-git-failure-b76e31ecac74 -->
---

SoC (System On Chip) design verification is a process that a hardware (physical) design works correctly in a variety of scenarios. It is also a process of finding out a bug hiding in the hardware design. <br>

## Overall Flow
![overall flow](https://drive.google.com/uc?id=19uEBxrxZEhszDdGEZ_lvyWdA-YFsaQnR) <br>
1. Design: SoC design flow is a process of creating a physical design and architecture. This stage includes C modeling and hardware design with HDL (Hardware Description Language).  <br>
2. Verification: <br>
  (1) IP / Block: IP (Intellectual Property) and block is a basic component in SoC. Tests for each IP and block are performed in this stage.<br>
  (2) SoC: SoC is integrated IPs and blocks. Full tests are performed in this stage.<br>
3. Tape out: This stage is a process of producing the chip from the factory. <br>
4. Software development <br>
  (1) Software development and validation: Software that enables the chip is developed in this stage. It includes setting tuning parameters for the chip, developing software working on the chip, etc.<br>
  (2) System integration: Both hardware chip and software are integrated in this stage.<br>

## Cost
![verification cost](https://community.cadence.com/resized-image/__size/500x0/__key/communityserver-blogs-components-weblogfiles/00-00-00-01-06/michal2.png) <br>