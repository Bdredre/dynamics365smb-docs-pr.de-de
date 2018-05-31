---
title: 'So gehts: Eingehende Lagerhaltungseinheiten einrichten| Microsoft Docs'
description: "Sie können Lagerhaltungsdaten verwenden, um Informationen über Ihre Artikel für einen bestimmten Lagerortcode und/oder einen bestimmten Variantencode zu speichern."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 4870e82d4390e0a96a137579d035fee0e54b19eb
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="set-up-stockkeeping-units"></a><span data-ttu-id="da859-103">Lagerhaltungsdaten einrichten</span><span class="sxs-lookup"><span data-stu-id="da859-103">Set Up Stockkeeping Units</span></span>
<span data-ttu-id="da859-104">Sie können Lagerhaltungsdaten verwenden, um Informationen über Ihre Artikel für einen bestimmten Lagerortcode und/oder einen bestimmten Variantencode zu speichern.</span><span class="sxs-lookup"><span data-stu-id="da859-104">You can use stockkeeping units to record information about your items for a specific location or a specific variant code.</span></span>  

 <span data-ttu-id="da859-105">Lagerhaltungsdaten sind eine Ergänzung zu Artikelkarten.</span><span class="sxs-lookup"><span data-stu-id="da859-105">Stockkeeping units are a supplement to item cards.</span></span> <span data-ttu-id="da859-106">Sie ersetzen sie nicht, obwohl sie mit ihnen verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="da859-106">They do not replace them, although they are related to them.</span></span> <span data-ttu-id="da859-107">Lagerhaltungsdaten ermöglichen Ihnen, Informationen über Artikel nach Lagerorten (wie z. B. Lagerhäuser und Vertriebsstellen) oder Varianten (wie z. B. unterschiedliche Regalnummern oder Informationen zur Wiederbestellung) zu unterscheiden.</span><span class="sxs-lookup"><span data-stu-id="da859-107">Stockkeeping units allow you to differentiate information about an item for a specific location, such as a warehouse or distribution center, or a specific variant, such as different shelf numbers and different replenishment information, for the same item.</span></span>  

## <a name="to-set-up-a-stockkeeping-unit"></a><span data-ttu-id="da859-108">Lagerhaltungsdaten einrichten:</span><span class="sxs-lookup"><span data-stu-id="da859-108">To set up a stockkeeping unit</span></span>  

1.  <span data-ttu-id="da859-109">Wählen Sie ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol nach Seite oder Bericht suchen") aus und geben Sie **Lagerhaltungsdaten** ein und wählen Sie den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="da859-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Stockkeeping Units**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="da859-110">Wählen Sie die Aktion **Neu** aus.</span><span class="sxs-lookup"><span data-stu-id="da859-110">Choose the **New** action.</span></span>  
3.  <span data-ttu-id="da859-111">Füllen Sie die Felder der Karte aus.</span><span class="sxs-lookup"><span data-stu-id="da859-111">Fill in the fields on the card.</span></span> <span data-ttu-id="da859-112">Die folgenden Felder sind obligatorisch: **Artikelnr.**, **Lagerortcode** und/oder **Variantencode**.</span><span class="sxs-lookup"><span data-stu-id="da859-112">The following fields are required: **Item No.**, **Location Code**, and/or **Variant Code**.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

<span data-ttu-id="da859-113">Nachdem Sie die ersten Lagerhaltungsdaten für einen Artikel eingerichtet haben, ist das Feld **Lagerhaltungsdaten vorhanden** auf der **Artikel**-Karte ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="da859-113">When you have set up the first stockkeeping unit for an item, the **Stockkeeping Unit Exists** check box on the **Item** card is selected.</span></span>  

<span data-ttu-id="da859-114">Um mehrere Lagerhaltungsdaten für einen Artikel anzulegen, verwenden Sie die Stapelverarbeitung **Lagerhaltungsdaten erstellen**.</span><span class="sxs-lookup"><span data-stu-id="da859-114">To create several stockkeeping units for an item, use the **Create Stockkeeping Unit** batch job.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="da859-115">Die Informationen auf der **Lagerhaltungsdatenkarte** haben eine höhere Priorität als die auf der **Artikelkarte**.</span><span class="sxs-lookup"><span data-stu-id="da859-115">The information on the **Stockkeeping Unit** card has priority over the **Item** card.</span></span>  

## <a name="see-also"></a><span data-ttu-id="da859-116">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="da859-116">See Also</span></span>  
[<span data-ttu-id="da859-117">Neue Artikel registrieren</span><span class="sxs-lookup"><span data-stu-id="da859-117">Register New Items</span></span>](inventory-how-register-new-items.md)  
[<span data-ttu-id="da859-118">Lagerortverwaltung einrichten</span><span class="sxs-lookup"><span data-stu-id="da859-118">Setting Up Warehouse Management</span></span>](warehouse-setup-warehouse.md)  
[<span data-ttu-id="da859-119">Logistik</span><span class="sxs-lookup"><span data-stu-id="da859-119">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="da859-120">Lagerbest</span><span class="sxs-lookup"><span data-stu-id="da859-120">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="da859-121">[Montageverwaltung](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="da859-121">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="da859-122">Designdetails: Logistik</span><span class="sxs-lookup"><span data-stu-id="da859-122">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="da859-123">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="da859-123">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
