---
title: 1491-Search-not-Returning-Expected-results
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: ''
ms.openlocfilehash: 881a579d7098578452c994b7ac66fe22a1d90dc2
ms.sourcegitcommit: 5182c9a73641079be59740e4524434b2e8be613a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 02/12/2019
ms.locfileid: "29964917"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="bb842-102">Turinio paieška negrįžta laukiami rezultatai</span><span class="sxs-lookup"><span data-stu-id="bb842-102">Content Search not returning expected results</span></span>

<span data-ttu-id="bb842-p101">Kai veikia turinio paieškų iš "Office 365" sauga & atitikties užtikrinimo centre, gaunate netikėtas paieškos rezultatus. Apsvarstyti šiuos dalykus, kurie gali turėti įtakos jūsų paieškos rezultatai:</span><span class="sxs-lookup"><span data-stu-id="bb842-p101">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results. Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="bb842-p102">**Turinio vietos ir ieškos sąlygų**: įsitikinkite, kad pasirinkote tinkamą turinio vietas ir paieškos sąlygas. Jei jūs paleidote didelis paieškos (daugelyje vietų) su, mano padalijant ją į keletą paieškų.</span><span class="sxs-lookup"><span data-stu-id="bb842-p102">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions. If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="bb842-p103">**Iš dalies indeksuoti elementus**: [iš dalies indeksuoti elementus](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) iš pašto dėžutės yra įtrauktos į numatomą paieškos rezultatus. Vis dėlto iš dalies indeksuoti elementus iš SharePoint ir "OneDrive" neįtraukiami į ieškos įvertinimą.</span><span class="sxs-lookup"><span data-stu-id="bb842-p103">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results. However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="bb842-p104">**Paieška gedimai**: ieškant daug pašto dėžučių (daugiau nei 100 000 pašto dėžučių), galite gauti paieškos klaidas, klaidų kodai, pvz., CS008-009 ir CS012-002). Šiuo atveju, bandykite dar kartą ieškoti tik nepavyko turinio vietas. Skaitykite [šį straipsnį](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) daugiau informacijos.</span><span class="sxs-lookup"><span data-stu-id="bb842-p104">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002). In this case, retry the search only for the failed content locations. See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>