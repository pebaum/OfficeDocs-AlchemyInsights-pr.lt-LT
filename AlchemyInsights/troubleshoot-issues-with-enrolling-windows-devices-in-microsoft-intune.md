---
title: Šalinkite triktis naudodami werbowania į Microsoft Intune "Windows" įrenginiai
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.openlocfilehash: 8d19bbd5a5782c7793c87499baf62b2eb7de82ae
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 01/24/2019
ms.locfileid: "29480629"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="92d25-102">Šalinkite triktis naudodami werbowania į Microsoft Intune "Windows" įrenginiai</span><span class="sxs-lookup"><span data-stu-id="92d25-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="92d25-103">Peržiūrėkite žemiau siekiama išspręsti jūsų problemą dabar ištekliai.</span><span class="sxs-lookup"><span data-stu-id="92d25-103">Review the resources listed below to resolve your issue now.</span></span> 
  
<span data-ttu-id="92d25-104">Kai kurių įprastinių klaidos prane imų ir sprendimo veiksmai:</span><span class="sxs-lookup"><span data-stu-id="92d25-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="92d25-p101">**Negali būti įdiegta programinė įranga, 0x80cf4017:** Jūsų paskyros sertifikatas nebegalioja. Iš naujo atsisiųsti PC kliento programinės įrangos paketą Intune administratoriaus konsolėje. Peržiūrėti šiuos dokumentus daugiau informacijos.</span><span class="sxs-lookup"><span data-stu-id="92d25-p101">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired. Re-download the PC Client software package in the Intune Admin Console. Review this documentation for more information.</span></span> 
  
 <span data-ttu-id="92d25-108">**Klaidos kodas 0x801c0003:** Klaida gali atsirasti šie scenarijai:</span><span class="sxs-lookup"><span data-stu-id="92d25-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span> 
  
1. <span data-ttu-id="92d25-p102">Vartotojas turi daugiau įrenginius, užregistruotus nei įrenginio. Peržiūrėkite šiuos dokumentus [pašalinti įrenginį](https://docs.microsoft.com/en-us/intune/devices-wipe) arba [pakeisti įrenginio](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span><span class="sxs-lookup"><span data-stu-id="92d25-p102">The user has more devices enrolled than the device limit. Review these documents to [remove a device](https://docs.microsoft.com/en-us/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/en-us/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>
    
2. <span data-ttu-id="92d25-p103">"Vartotojai gali prisijungti prie įrenginių Azure AD" nustatykite "none". Nustatyti visiems arba pasirinkite vartotojai. Peržiūrėkite [šiuos dokumentus](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) daugiau informacijos.</span><span class="sxs-lookup"><span data-stu-id="92d25-p103">"Users may join devices to Azure AD" is set to "none". Set it to all or select users. Review [this documentation](https://docs.microsoft.com/en-us/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span> 
    
3. <span data-ttu-id="92d25-p104">Prietaisas jau mokosi kitas vartotojas. Jei tai byla, pašalinti įrenginį iš Azure Intune konsolės arba rankiniu būdu unenroll įrenginį, prieš bandydami dar kartą.</span><span class="sxs-lookup"><span data-stu-id="92d25-p104">The device is already enrolled by another user. If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>
    
4. <span data-ttu-id="92d25-p105">Prietaisas veikia Windows 10 namuose. Tik "Windows 10 Pro", švietimo ir Enterprise SKU prisijungti prie Azure Active Directory.</span><span class="sxs-lookup"><span data-stu-id="92d25-p105">The device is Windows 10 Home. Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>
    
<span data-ttu-id="92d25-118">Papildomų išteklių, kurie padės išspręsti jūsų problemą:</span><span class="sxs-lookup"><span data-stu-id="92d25-118">Additional resources to help resolve your issue:</span></span>
  
1. <span data-ttu-id="92d25-p106">Naudoti [Intune trikčių šalinimo portalas](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) diagnozuoti ir išspręsti bendras registracijos nesėkmių. Peržiūrėti daugiau informacijos [šiame dokumente](https://docs.microsoft.com/en-us/intune/help-desk-operators) .</span><span class="sxs-lookup"><span data-stu-id="92d25-p106">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures. Review [this document](https://docs.microsoft.com/en-us/intune/help-desk-operators) for more details.</span></span> 
    
2. <span data-ttu-id="92d25-121">Peržiūrėkite šiuos dokumentus bendrosios klaidos, kurios neleis registracijos ir rezoliucijas į kiekvieną sąrašą: [trikčių diagnostikos vadovas](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) ir [trikčių diagnostika doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="92d25-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/en-us/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/en-us/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).</span></span>
    
<span data-ttu-id="92d25-122">[Sužinokite, kaip įtraukti į Microsoft Intune "Windows" įrenginiuose](https://docs.microsoft.com/en-us/intune/windows-enroll).</span><span class="sxs-lookup"><span data-stu-id="92d25-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/en-us/intune/windows-enroll).</span></span>
  
