---
title: Tvarkyti sinchronizuotą vartotoją
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000609"
- "2444"
ms.openlocfilehash: 84e337a7224fdd3c3ab7ad0f61240692fe007d5a
ms.sourcegitcommit: 82af227ac6d075e748e27c4ce6bdcf56628559cb
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 05/28/2020
ms.locfileid: "44407358"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Neįmanoma nustatyti pagrindinio el. pašto adreso, keisti vartotojo atributų arba pašalinti / panaikinti sinchronizuoto vartotojo

Jei katalogų sinchronizavimas įgalintas jūsų aplinkoje, kai kurių vartotojo arba objekto atributų negalima keisti naudojant "Microsoft 365" administravimo centrą.

Norėdami visiškai valdyti sinchronizuotus naudotojus ir visus jų atributus, naudokite vietinius active directory naudotojus ir grupių valdymo konsolę (adsiedit.msc).  

Taip pat galite keisti atskirus vartotojus arba atributus sinchronizuotiems vartotojams naudodami "PowerShell", pvz., parodyta šiuose bendruosiuose pavyzdžiuose: 
- `Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

- `Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

- `Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
