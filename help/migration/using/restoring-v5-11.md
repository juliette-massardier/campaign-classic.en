---
title: Restoring v5.11
seo-title: Restoring v5.11
description: Restoring v5.11
seo-description: 
page-status-flag: never-activated
uuid: d2e7a8e2-003f-4047-bf6a-548fe7bd2a76
contentOwner: sauviat
products: SG_CAMPAIGN/CLASSIC
content-type: reference
discoiquuid: be1d524f-2591-4afd-886b-5f59d5d99cff
index: y
internal: n
snippet: y
---

# Restoring v5.11{#restoring-v}

Here is the procedure to restore a v5.11 from a v7.

1. Recover the backup of the database and restore it.
1. Recover the **Neolane v5.back** folder (**nl5.back** in Linux), rename it to **Neolane v5** (**nl5** in Linux) and restore it to its original location.
1. Re-configure IIS by re-assigning the listen ports to re-establish the integration of Neolane v5 at IIS Website level.
1. Stop the Adobe Campaign v7 service.
1. Re-start IIS.
1. Re-start the Adobe Campaign v5 service.
