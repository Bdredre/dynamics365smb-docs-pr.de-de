---
title: Info zu Kosten des beendeten Produktionsauftrags | Microsoft Docs
description: "Das Beenden eines Fertigungsauftrages ist eine wichtige Aufgabe beim Abschließen der Gesamtkostenbewertung des Artikels, der gefertigt wird. Endeinstandspreise (Abweichungen in einer Einstandspreisumgebung; Ist-Kosten in einer FIFO-, Durchschnitt- oder LIFO-Einstandspreisumgebung) werden mit der Stapelverarbeitung  **Kosten anpassen Lagerreg. fakt** berechnet."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: ea69f3c8af84e92f09f4b2046530c9b935905ebe
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="about-finished-production-order-costs"></a><span data-ttu-id="f3cf9-104">Info zu Kosten des beendeten FA</span><span class="sxs-lookup"><span data-stu-id="f3cf9-104">About Finished Production Order Costs</span></span>
<span data-ttu-id="f3cf9-105">Das Beenden eines Fertigungsauftrages ist eine wichtige Aufgabe beim Abschließen der Gesamtkostenbewertung des Artikels, der gefertigt wird.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-105">Finishing the production order is an important task in completing the costing lifecycle of the item that is being produced.</span></span> <span data-ttu-id="f3cf9-106">Endeinstandspreise einschließlich Abweichungen in einer Einstandspreisumgebung; Ist-Kosten in einer FIFO-, Durchschnitt- oder LIFO-Einstandspreisumgebung, werden mit der Stapelverarbeitung **Artikelkosteneinträge anpassen** berechnet, die eine finanzielle Abstimmung der Kosten der Artikelfertigung ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-106">Final costs, including variances in a standard cost environment, actuals in a FIFO, Average, or LIFO cost environment, are calculated using the **Adjust Cost - Item Entries** batch job, which allows for financial reconciliation of the costs of item production.</span></span> <span data-ttu-id="f3cf9-107">Damit ein Fertigungsauftrag für die Einstandspreisregulierung berücksichtigt wird, muss er den Status **Beendet** haben.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-107">For a production order to be considered for cost adjustment, the status must be **Finished**.</span></span> <span data-ttu-id="f3cf9-108">Es ist daher unbedingt erforderlich, dass nach Beendigung die Änderung des Status eines Fertigungsauftrags in **Beendet** erfolgt.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-108">It is therefore critical that upon completion, the status of a production order is changed to **Finished**.</span></span>  

## <a name="example"></a><span data-ttu-id="f3cf9-109">Beispiel</span><span class="sxs-lookup"><span data-stu-id="f3cf9-109">Example</span></span>  
 <span data-ttu-id="f3cf9-110">Wenn Sie z. B. in einer Einstandspreis-Umgebungen Material verbrauchen, um einen Artikel zu fertigen, gehen, einfach gesagt, der Einstandspreis des Artikels sowie die Bearbeitungs- und die Gemeinkosten in die WIP ein.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-110">In a standard cost environment, when you consume material to produce an item, stated simply, the cost of the item plus labor and overhead go into WIP.</span></span> <span data-ttu-id="f3cf9-111">Wenn der Artikel gefertigt wird, wird WIP um den Betrag Einstandspreises des Artikels verringert.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-111">When the item is produced, WIP is reduced by the amount of the standard cost of the item.</span></span> <span data-ttu-id="f3cf9-112">Normalerweise sind diese Kosten nicht gleich Null.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-112">Typically, these costs do not net to zero.</span></span> <span data-ttu-id="f3cf9-113">Damit diese Kosten sich zu Null saldieren können, müssen Sie die Stapelverarbeitung **Artikelkosteneinträge anpassen**, wobei zu beachten ist, dass nur Fertigungsaufträge mit dem Status **Beendet** für die Regulierung berücksichtigt werden.</span><span class="sxs-lookup"><span data-stu-id="f3cf9-113">So that these costs can net to zero, you must run the **Adjust Cost - Item Entries** batch job, noting that only production orders with the status of **Finished** will be considered for adjustment.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f3cf9-114">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="f3cf9-114">See Also</span></span>  
[<span data-ttu-id="f3cf9-115">Verwalten der Lagerregulierung</span><span class="sxs-lookup"><span data-stu-id="f3cf9-115">Managing Inventory Costs</span></span>](finance-manage-inventory-costs.md)  
[<span data-ttu-id="f3cf9-116">Produktion</span><span class="sxs-lookup"><span data-stu-id="f3cf9-116">Manufacturing</span></span>](production-manage-manufacturing.md)  
<span data-ttu-id="f3cf9-117">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="f3cf9-117">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
