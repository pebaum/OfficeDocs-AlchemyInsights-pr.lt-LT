---
title: Komandos, įdiegtos naudojant "Office" naujinimus
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2599"
- "9000140"
- "9000660"
- "2509"
ms.openlocfilehash: d523ab51852cf771fb260d0050fbe92d4578ff76
ms.sourcegitcommit: 123e9fe46e99719dd271e75a66555861e968f4a2
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 12/30/2019
ms.locfileid: "40908752"
---
# <a name="microsoft-teams-installed-with-office-updates"></a><span data-ttu-id="72870-102">"Microsoft teams" įdiegiama su "Office" naujinimais</span><span class="sxs-lookup"><span data-stu-id="72870-102">Microsoft Teams installed with Office updates</span></span>

<span data-ttu-id="72870-103">"Microsoft teams" įtraukta į naujų "Office 365 ProPlus", "Office 365 Business" ir "Office for Mac" ***diegimų*** dalį.</span><span class="sxs-lookup"><span data-stu-id="72870-103">Microsoft Teams is included as part of ***new installations*** of Office 365 ProPlus, Office 365 Business, and Office for Mac.</span></span> <span data-ttu-id="72870-104">Daugiau informacijos rasite [Kada "Microsoft teams" pradės būti įtraukta į naujus "Office" diegimus?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)</span><span class="sxs-lookup"><span data-stu-id="72870-104">For more information, see [When will Microsoft Teams start being included with new installations of Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)</span></span>

<span data-ttu-id="72870-105">Be to, pradedant nuo versijos 1906 kas mėnesį kanalas, komandos bus palaipsniui įtraukti į ***esamus įrenginius*** , Office 365 ProPlus (ir Office 365 Business) įrenginiuose, kuriuose veikia Windows, kai atnaujinate savo esamą diegimą į naujausią versiją.</span><span class="sxs-lookup"><span data-stu-id="72870-105">Additionally, starting with Version 1906 in Monthly Channel, Teams will gradually be added to ***existing installations*** of Office 365 ProPlus (and Office 365 Business) on devices running Windows when you update your existing installation to the latest version.</span></span> <span data-ttu-id="72870-106">Daugiau informacijos [apie esamus "Office" diegimus](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus) žr.</span><span class="sxs-lookup"><span data-stu-id="72870-106">For more information, see [What about existing installations of Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)</span></span>

<span data-ttu-id="72870-107">**Pastaba:** Jei nenorite laukti šio diegimo tvarkaraščio, galite visuotinai diegti "teams" kaip atskirus vartotojus [vadovaudamiesi šiomis instrukcijomis](https://docs.microsoft.com/MicrosoftTeams/msi-deployment)arba galite nustatyti, kad naudotojai patys įdiegtų "teams" https://teams.microsoft.com/downloads.</span><span class="sxs-lookup"><span data-stu-id="72870-107">**Note:** If you don't want to wait for this rollout schedule, you can deploy Teams as standalone for your users by [following these instructions](https://docs.microsoft.com/MicrosoftTeams/msi-deployment), or you can have your users install Teams for themselves from https://teams.microsoft.com/downloads.</span></span>

<span data-ttu-id="72870-108">Jei jūsų organizacija nėra pasirengusi įdiegti komandas, galite ***pašalinti komandas*** iš [naujų](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) arba [esamų](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) įrenginių biure.</span><span class="sxs-lookup"><span data-stu-id="72870-108">If your organization isn't ready to deploy Teams, you can ***exclude Teams*** from [new](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) or [existing](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) installations of Office.</span></span> <span data-ttu-id="72870-109">Jei norite, kad būtų įdiegtos komandos, bet nenorite, kad ją įdiegus komandos būtų automatiškai paleistos, žiūrėkite [neleisti "Microsoft teams" paleisti automatiškai po įdiegimo](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).</span><span class="sxs-lookup"><span data-stu-id="72870-109">If you want Teams to be installed, but don't want Teams to start automatically for the user after it's installed, see [Prevent Microsoft Teams from starting automatically after installation](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).</span></span>

<span data-ttu-id="72870-110">Norėdami ***pašalinti komandas*** iš įrenginio, kuriame veikia "Windows", peržiūrėkite ["Microsoft teams" pašalinimas](https://support.office.com/article/uninstall-microsoft-teams-3b159754-3c26-4952-abe7-57d27f5f4c81).</span><span class="sxs-lookup"><span data-stu-id="72870-110">To ***uninstall Teams*** from a device running Windows, see [Uninstall Microsoft Teams](https://support.office.com/article/uninstall-microsoft-teams-3b159754-3c26-4952-abe7-57d27f5f4c81).</span></span> <span data-ttu-id="72870-111">Norėdami išvalyti "Microsoft teams" iš kelių tikslinių įrenginių arba vartotojų, peržiūrėkite ["Microsoft teams" visuotinio diegimo valymą](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span><span class="sxs-lookup"><span data-stu-id="72870-111">To clean up Microsoft Teams from multiple target machines or users, see [Microsoft Teams deployment cleanup](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span></span>

<span data-ttu-id="72870-112">Jei naudojate bendrai naudojamus kompiuterius, nuotolinio darbalaukio tarnybas (RDS) arba virtualiojo darbalaukio infrastruktūrą (VDI), peržiūrėkite [bendrai naudojamą kompiuterį ir VDI aplinkas su "Microsoft teams"](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).</span><span class="sxs-lookup"><span data-stu-id="72870-112">If you're using shared computers, Remote Desktop Services (RDS), or Virtual Desktop Infrastructure (VDI), see [Shared computer and VDI environments with Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).</span></span> <span data-ttu-id="72870-113">Jei naudojate "Office for Mac", peržiūrėkite ["Microsoft teams" diegimus "Mac](https://docs.microsoft.com/en-us/deployoffice/teams-install#microsoft-teams-installations-on-a-mac)".</span><span class="sxs-lookup"><span data-stu-id="72870-113">If you're using Office for Mac, see [Microsoft Teams installations on a Mac](https://docs.microsoft.com/en-us/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span></span>

<span data-ttu-id="72870-114">**Pastaba:** Įdiegus "teams", ji [automatiškai atnaujinama](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) maždaug kas dvi savaites, naudojant naujas funkcijas ir kokybės naujinimus.</span><span class="sxs-lookup"><span data-stu-id="72870-114">**Note:** After Teams is installed, it's [automatically updated](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) approximately every two weeks with new features and quality updates.</span></span> 