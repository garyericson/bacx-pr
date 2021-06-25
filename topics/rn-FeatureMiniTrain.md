---
title: "Feature: Holdback plans"
ms.date: 06/14/2021
ms.service: 
ms.topic: "conceptual"
author: "Chitra"
ms.author: "Chitra"
manager: "Chitra"
---

# Feature: Mini train capturing date and status changes 

**Persona:** Program Managers, Release Managers, Release POCs, and Content Publishing Team 

**Why this feature:**

When the PMs changes the GA or Public Preview status as planned or shipped or the public preview or GA dates, the changes will not be published in the external release plans until after the next publishing cycle (~2 to 3 weeks) and our external customers will have to wait for these changes to reflect in the plan. 

**How does it work:**

Mini train approach automatically runs every week (Sundays) to capture the date and status changes done by the PMs without disturbing any content updates such as feature details, business value, metadata, or images. The date and status changes made will be reflected in article, planned features and in change history in the external plans for both Dynamics 365 and Powerplatform. The date and status changes will be picked up by this feature only when the “Include in selected release wave” option is set to “Yes”. 
