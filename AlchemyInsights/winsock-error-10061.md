---
title: 1554 Winsock klaida 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e8f62d97efc937518ef766b45e1747e83b7f99c3
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 04/22/2020
ms.locfileid: "43766177"
---
# <a name="winsock-error-10061"></a>Winsock klaida 10061

Šis klaidos kodas reiškia, kad "Microsoft" nepavyko nustatyti TCP lizdas (ryšys) su paskirties pagrindinio kompiuterio. Labiausiai tikėtina šios klaidos priežastis yra užkardos konfigūracijos problema. Norėdami išspręsti šią problemą, patikrinkite šiuos parametrus:

- Patikrinkite užkardos konfigūraciją naudodami ["Microsoft 365" URL ir IP adresų diapazonų informaciją](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)

- Jei klaida būdinga "Exchange Online Protection" (EOP), jums turėjo būti anksčiau pranešta apie ["Exchange Online Protection" IP adresų](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)pakeitimą .

- Patikrinkite, ar jūsų interneto paslaugų teikėjas (ISP) neblokuoja prievado.

- Patikrinkite išmaniojo pagrindinio kompiuterio ir paskirties serverio parametrus savo jungtyse.

Atkreipkite dėmesį, kad "Microsoft 365" neblokuoja *gaunamų* ryšių tokiu būdu.
