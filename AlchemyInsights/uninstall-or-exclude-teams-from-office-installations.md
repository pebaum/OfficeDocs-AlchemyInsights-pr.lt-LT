---
title: Pašalinti arba pašalinti komandas iš Office įrenginių
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2662"
- "9000660"
ms.openlocfilehash: 6fc5645028c9fb9df2606c0d03b67e87ae15087c
ms.sourcegitcommit: 1e5de64e34e9ba16185b3a895b3152ca61718f4b
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 10/01/2019
ms.locfileid: "37344245"
---
# <a name="uninstall-or-exclude-teams-from-new-or-existing-office-installations"></a><span data-ttu-id="b1546-102">Pašalinti arba išskirti komandas iš naujų ar esamų Office diegimų</span><span class="sxs-lookup"><span data-stu-id="b1546-102">Uninstall or exclude Teams from new or existing Office installations</span></span>

<span data-ttu-id="b1546-103">"Microsoft teams" dabar įtraukta kaip "Office 365 ProPlus", "Office 365 Business" ir "Office for Mac" dalis.</span><span class="sxs-lookup"><span data-stu-id="b1546-103">Microsoft Teams is now included as part of Office 365 ProPlus, Office 365 Business, and Office for Mac.</span></span>

- <span data-ttu-id="b1546-104">Norėdami neįtraukti komandų į naujus "Office" diegimus, naudokite " [Office" visuotinio diegimo įrankį](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) .</span><span class="sxs-lookup"><span data-stu-id="b1546-104">Use the [Office Deployment Tool](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) to exclude Teams from new installations of Office.</span></span>
- <span data-ttu-id="b1546-105">Norėdami *pašalinti* komandas iš įrenginio, kuriame veikia "Windows", peržiūrėkite ["Microsoft teams" pašalinimas](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span><span class="sxs-lookup"><span data-stu-id="b1546-105">To *uninstall* Teams from a device running Windows, see [Uninstall Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span></span> <span data-ttu-id="b1546-106">Norėdami išvalyti "Microsoft teams" iš kelių tikslinių įrenginių arba vartotojų, peržiūrėkite ["Microsoft teams" diegimas išvalyti](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span><span class="sxs-lookup"><span data-stu-id="b1546-106">To clean up Microsoft Teams from multiple target machines or users, see [Microsoft Teams deployment clean up](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span></span>
- <span data-ttu-id="b1546-107">Naudokite parinktį [Preventteamsinstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) , kad Microsoft komandos negalėtų automatiškai įdiegti Office.</span><span class="sxs-lookup"><span data-stu-id="b1546-107">Use the [PreventTeamsInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams
) option to prevent Microsoft Teams from installing automatically with Office.</span></span>
- <span data-ttu-id="b1546-108">Naudokite pasirinktį [Preventfirstlaunchafterinstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) prieš diegiant *komandas*, kad "Microsoft teams" nebūtų paleidžiama automatiškai po įdiegimo.</span><span class="sxs-lookup"><span data-stu-id="b1546-108">Use the [PreventFirstLaunchAfterInstall](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation) option, *before Teams is installed*, to prevent Microsoft Teams from starting automatically after installation.</span></span>

<span data-ttu-id="b1546-109">Jei naudojate "Office for Mac", peržiūrėkite ["Microsoft teams" diegimus "Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac)".</span><span class="sxs-lookup"><span data-stu-id="b1546-109">If you're using Office for Mac, see [Microsoft Teams installations on a Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span></span>