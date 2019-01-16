---
title: Stebėsenos sąlyginės prieigos
ms.author: pebaum
author: pebaum
ms.date: 8/1/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: dcb86c54-769e-4832-9f88-bc45f1e5f36c
ms.openlocfilehash: 06307b57475e8828e6d4e5e01625d5100576f12b
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 01/15/2019
ms.locfileid: "28302346"
---
# <a name="monitoring-conditional-access"></a><span data-ttu-id="86662-102">Stebėsenos sąlyginės prieigos</span><span class="sxs-lookup"><span data-stu-id="86662-102">Monitoring Conditional Access</span></span>

<span data-ttu-id="86662-p101">Vartotojams skirta su sąlygine prieiga gausite pranešimas el. paštu, jei jie neatitinka jūsų organizacijos suteikiant prieigą keliami reikalavimai. Norėdami išspręsti, rekomenduojame vieną ar kelis iš šių sprendimų:</span><span class="sxs-lookup"><span data-stu-id="86662-p101">Users targeted with conditional access will receive a notification email if they do not meet your organization's access requirements. To resolve, we recommend one or more of the following solutions:</span></span>
  
- <span data-ttu-id="86662-p102">Jei prietaisas yra preziumuojamas, gautų, patarti vartotojui eiti į programėlę įmonės portalą ir patikrinkite, ar rodomas įmonės portale. Jei ne, vartotojas turėtų registruotis įrenginį.</span><span class="sxs-lookup"><span data-stu-id="86662-p102">If the device is presumed to be enrolled, advise the user to go to the Company Portal app and verify that it appears in the Company Portal. If it doesn't, the user should enroll the device.</span></span>
    
- <span data-ttu-id="86662-p103">Azure portale rasite apsilankę **Intune \> prietaiso atitikties**. Po **monitoriumi** spustelėkite **įrenginio atitiktį**. Rodyti jūsų prietaiso atitikties ataskaitą, kad patikrinti, kad vartotojo įrenginys pažymimas kaip suderinamas.</span><span class="sxs-lookup"><span data-stu-id="86662-p103">In the Azure portal go to **Intune \> Device compliance**. Under **Monitor** click **Device compliance**. View your device compliance report to verify that the user's device is marked as compliant.</span></span> 
    
- <span data-ttu-id="86662-p104">Azure portale rasite apsilankę **Intune \> prietaiso atitikties**. Dalyje **tvarkyti**spustelėkite **strategijos**. Atitikties strategijos sąraše, patikrinkite, kad profilis yra priskirtas jūsų vartotojo įrenginio. Jei nėra Vartotojo profilis yra priskirtas, tada Intune nebus galima patvirtinti įrenginio atitikties būklę.</span><span class="sxs-lookup"><span data-stu-id="86662-p104">In the Azure portal go to **Intune \> Device compliance**. Under **Manage**, click **Policies**. In the list of compliance policies, verify that a profile is assigned to your user's device. If no profile is assigned, then Intune will not be able to confirm the device's compliance status.</span></span> 
    
- <span data-ttu-id="86662-114">Redaguoti vartotojo sąlyginės prieigos priskyrimo.</span><span class="sxs-lookup"><span data-stu-id="86662-114">Edit the user's conditional access assignment.</span></span>
    
1. <span data-ttu-id="86662-115">Azure portale rasite apsilankę **Intune \> sąlyginės prieigos \> politika**</span><span class="sxs-lookup"><span data-stu-id="86662-115">In the Azure portal go to **Intune \> Conditional access \> Policies**</span></span>
    
2. <span data-ttu-id="86662-116">Iš sąrašo pasirinkite politiką</span><span class="sxs-lookup"><span data-stu-id="86662-116">Select a policy from the list</span></span>
    
3. <span data-ttu-id="86662-117">Spustelėkite **vartotojai ir grupės**</span><span class="sxs-lookup"><span data-stu-id="86662-117">Click **Users and groups**</span></span>
    
4. <span data-ttu-id="86662-p105">Nukreipti tam tikrą politiką kažkas, įtraukti juos į sąrašus **įtraukti** . Siekiant užtikrinti, kad asmuo yra praleista politiką, įtraukti juos į sąrašą **neįtraukti** .</span><span class="sxs-lookup"><span data-stu-id="86662-p105">To target a certain policy at someone, add them to the **Include** list. To ensure that a person is omitted from the policy, add them to the **Exclude** list.</span></span> 
    
<span data-ttu-id="86662-120">Skaityti daugiau: [kaip stebėti sąlyginės prieigos priemonės](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span><span class="sxs-lookup"><span data-stu-id="86662-120">Read more: [How to Monitor Conditional Access devices](https://docs.microsoft.com/en-us/intune/conditional-access-exchange-monitor)</span></span>
  
