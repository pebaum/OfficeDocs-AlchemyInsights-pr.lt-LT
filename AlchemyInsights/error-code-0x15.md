---
title: Klaidos kodas 0x15
ms.author: pebaum
author: pebaum
ms.date: 10/31/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Jei gaunate Klaida aktyvinant Office 2013 nuotolinio darbalaukio tarnybų (RDS) dislokavimo, patariame įjungti Alma redaguodami registrą.
ms.openlocfilehash: 89f9270169e13fd7706f7826c624ef8ae4d47b3f
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: lt-LT
ms.lasthandoff: 01/15/2019
ms.locfileid: "28301761"
---
<span data-ttu-id="dd961-103">Jei gaunate Klaida aktyvinant Office 2013 nuotolinio darbalaukio tarnybų (RDS) dislokavimo, patariame įjungti Alma redaguodami registrą.</span><span class="sxs-lookup"><span data-stu-id="dd961-103">If you're receiving an error while activating Office 2013 on Remote Desktop Services (RDS) deployments, consider enabling ADAL by editing the registry.</span></span> 
  
|<span data-ttu-id="dd961-104">**Registro raktas**</span><span class="sxs-lookup"><span data-stu-id="dd961-104">**Registry key**</span></span>|<span data-ttu-id="dd961-105">**Tipas**</span><span class="sxs-lookup"><span data-stu-id="dd961-105">**Type**</span></span>|<span data-ttu-id="dd961-106">**Reikšmė**</span><span class="sxs-lookup"><span data-stu-id="dd961-106">**Value**</span></span>|
|:-----|:-----|:-----|
|<span data-ttu-id="dd961-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span><span class="sxs-lookup"><span data-stu-id="dd961-107">HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\EnableADAL</span></span>  <br/> |<span data-ttu-id="dd961-108">REG_DWORD</span><span class="sxs-lookup"><span data-stu-id="dd961-108">REG_DWORD</span></span>  <br/> |<span data-ttu-id="dd961-109">1</span><span class="sxs-lookup"><span data-stu-id="dd961-109">1</span></span>  <br/> |
   
<span data-ttu-id="dd961-110">Daugiau informacijos ieškokite [Įjungti šiuolaikinės autentifikavimas Office 2013 m. "Windows" įrenginiuose](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span><span class="sxs-lookup"><span data-stu-id="dd961-110">For more information, see [Enable Modern Authentication for Office 2013 on Windows devices](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="dd961-p101">Alma yra įjungta pagal nutylėjimą "Office 365 ProPlus" ir Office 2016. > Nuotolinio darbalaukio tarnybos (RDS) anksčiau buvo pavadintas Terminal Services.</span><span class="sxs-lookup"><span data-stu-id="dd961-p101">ADAL is enabled by default in Office 365 ProPlus and Office 2016. >  Remote Desktop Services (RDS) was previously named Terminal Services.</span></span> 
  
