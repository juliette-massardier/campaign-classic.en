---
title: Image display issues
seo-title: Image display issues
description: Image display issues
seo-description: 
page-status-flag: never-activated
uuid: 8fc51459-ee46-4c05-8011-f0651e6b451b
contentOwner: sauviat
products: SG_CAMPAIGN/CLASSIC
audience: production
content-type: reference
topic-tags: troubleshooting
discoiquuid: dfccfe8c-b826-4648-9a0b-23d7e6a4808a
index: y
internal: n
snippet: y
---

# Image display issues{#image-display-issues}

If you face image display issues in a sent message, reasons may be linked to bad location:

* locations may not match, or images may not have been correctly pushed to duplicate tracking server: check your configuration.
* images may not reside in the public resource folder on the marketing instance: upload the images into your resource folder to solve the issue.
* if you work in a mid-sourcing architecture: check images are uploading without errors when proofs are sent (information is displayed in the analysis logs).

How to troubleshoot:

1. Send a proof that will show the images.
1. Validate the resources configuration in the instance setup is correct. 
1. Check the public resources folder, or - if it is not in the public resources folder - the folder referenced in the delivery.

