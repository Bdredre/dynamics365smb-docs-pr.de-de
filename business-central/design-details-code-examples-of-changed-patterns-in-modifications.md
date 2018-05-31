---
title: 'Designdetails: Bedarf und Vorrat | Microsoft Docs'
description: "Wenn die Zubehör-Ausgleichsverfahren ausgeführt wurden, gibt es drei mögliche Schlusssituationen."
services: project-madeira
documentationcenter: 
author: SorenGP
ms.service: dynamics365-business-central
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: d7fb34e1c9428a64c71ff47be8bcff174649c00d
ms.openlocfilehash: 2be48e11d562f469ab9ef5ac156fdeb46ea51107
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="design-details-closing-demand-and-supply"></a><span data-ttu-id="30b6e-103">Designdetails: Abschluss von Bedarf und Vorrat</span><span class="sxs-lookup"><span data-stu-id="30b6e-103">Design Details: Closing Demand and Supply</span></span>
<span data-ttu-id="30b6e-104">Wenn die Zubehör-Ausgleichsverfahren ausgeführt wurden, gibt es drei mögliche Schlusssituationen:</span><span class="sxs-lookup"><span data-stu-id="30b6e-104">When the supply balancing procedures have been performed, there are three possible end situations:</span></span>  

-   <span data-ttu-id="30b6e-105">Die benötigte Menge und das Datum der Bedarfsereignisse wurden erfüllt, und die Planung für den Artikel kann geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="30b6e-105">The required quantity and date of the demand events have been met and the planning for them can be closed.</span></span> <span data-ttu-id="30b6e-106">Das Vorratsereignis ist noch offen und kann möglicherweise den nächsten Bedarf decken, der Ausgleichsvorgang kann daher erneut mit dem aktuellen Vorratsereignis und dem nächsten Bedarf starten.</span><span class="sxs-lookup"><span data-stu-id="30b6e-106">The supply event is still open and may be able to cover the next demand, so the balancing procedure can start over with the current supply event and the next demand.</span></span>  

-   <span data-ttu-id="30b6e-107">Der Beschaffungsauftrag kann nicht geändert werden, um den gesamten Bedarf zu decken.</span><span class="sxs-lookup"><span data-stu-id="30b6e-107">The supply order cannot be modified to cover all of the demand.</span></span> <span data-ttu-id="30b6e-108">Das Bedarfsereignis ist noch offen, mit einigen nicht abgedeckten Mengen, die möglicherweise vom nächsten Bedarfsereignis abgedeckt werden.</span><span class="sxs-lookup"><span data-stu-id="30b6e-108">The demand event is still open, with some uncovered quantity that may be covered by the next supply event.</span></span> <span data-ttu-id="30b6e-109">Daher wird das aktuelle Vorratsereignis geschlossen, sodass der Ausgleichsvorgang mit dem aktuellen Bedarfs- und dem nächsten Vorratsereignis erneut beginnen kann.</span><span class="sxs-lookup"><span data-stu-id="30b6e-109">Thus the current supply event is closed, so the balancing act can start over with the current demand and the next supply event.</span></span>  

-   <span data-ttu-id="30b6e-110">Der gesamte Bedarf ist abgedeckt; es gibt keinen folgenden Bedarf (oder es gab überhaupt keinen Bedarf).</span><span class="sxs-lookup"><span data-stu-id="30b6e-110">All of the demand has been covered; there is no subsequent demand (or there has been no demand at all).</span></span> <span data-ttu-id="30b6e-111">Wenn überschüssiger Vorrat vorhanden ist, kann dieser vermindert (oder storniert) und dann geschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="30b6e-111">If there is any surplus supply, it may be decreased (or canceled) and then closed.</span></span> <span data-ttu-id="30b6e-112">Es ist möglich, dass zusätzliche Zubehörereignisse weiter entlang der Kette vorhanden sind, und diese sollten ebenfalls annulliert werden.</span><span class="sxs-lookup"><span data-stu-id="30b6e-112">It is possible that additional supply events exist further along in the chain, and they should also be canceled.</span></span>  

 <span data-ttu-id="30b6e-113">Schließlich erstellt das Planungssystem ein Auftragsnachverfolgungslink zwischen dem Vorrat und dem Bedarf.</span><span class="sxs-lookup"><span data-stu-id="30b6e-113">Last, the planning system will create an order tracking link between the supply and the demand.</span></span>  

## <a name="creating-the-planning-line-suggested-action"></a><span data-ttu-id="30b6e-114">Die Planungszeile (vorgeschlagene Aktion) erstellen</span><span class="sxs-lookup"><span data-stu-id="30b6e-114">Creating the Planning Line (Suggested Action)</span></span>  
 <span data-ttu-id="30b6e-115">Wenn eine Aktion – Neu, Menge ändern, Neuplanen, Neuplanen und Menge ändern oder Stornieren – für die Revision des Beschaffungsauftrags vorgeschlagen wird, erstellt das Planungssystem, eine Planung auf dem Planungsvorschlag.</span><span class="sxs-lookup"><span data-stu-id="30b6e-115">If any action – New, Change Quantity, Reschedule, Reschedule and Change Quantity, or Cancel – is suggested to revise the supply order, the planning system creates a planning line in the planning worksheet.</span></span> <span data-ttu-id="30b6e-116">Aufgrund der Auftragsnachverfolgung wird die Planungszeile nicht nur erstellt, wenn das Vorratsereignis geschlossen wird, sondern auch, wenn das Nachfrageereignis geschlossen wird, auch wenn das Vorratsereignis möglicherweise noch offen und abhängig von zusätzlichen Änderungen ist, wenn das nächste Nachfrageereignis verarbeitet wird.</span><span class="sxs-lookup"><span data-stu-id="30b6e-116">Due to order tracking, the planning line is created not only when the supply event is closed, but also if the demand event is closed, even though the supply event is still open and may be subject to additional changes when the next demand event is processed.</span></span> <span data-ttu-id="30b6e-117">Dies bedeutet, dass die Planungszeile, wenn sie zuerst erstellt wird, möglicherweise erneut geändert wird.</span><span class="sxs-lookup"><span data-stu-id="30b6e-117">This means that when first created, the planning line may be changed again.</span></span>  

 <span data-ttu-id="30b6e-118">Um Datenbankzugriff zu minimieren, wenn Sie Fertigungsaufträge bearbeiten, können Sie die Planungszeile in drei Ebenen verwalten, mit dem Ziel, das am wenigsten anspruchsvolle Bestanderhaltungsniveau auszuführen:</span><span class="sxs-lookup"><span data-stu-id="30b6e-118">To minimize database access when handling production orders, the planning line can be maintained in three levels, while aiming to perform the least demanding maintenance level:</span></span>  

-   <span data-ttu-id="30b6e-119">Erstellen Sie nur die Planungszeile mit dem aktuellen Fälligkeitsdatum und der Menge, aber ohne Arbeitsplan und Komponenten.</span><span class="sxs-lookup"><span data-stu-id="30b6e-119">Create only the planning line with the current due date and quantity but without the routing and components.</span></span>  

-   <span data-ttu-id="30b6e-120">Arbeitsplan einschließen: Der geplante Arbeitsplan wird einschließlich Berechnung des Start- und Enddatum und -Zeiten ausgebreitet.</span><span class="sxs-lookup"><span data-stu-id="30b6e-120">Include routing: the planned routing is laid out including calculation of starting and ending dates and times.</span></span> <span data-ttu-id="30b6e-121">Dieses ist anspruchvoll in Bezug auf Datenbankzugriffe.</span><span class="sxs-lookup"><span data-stu-id="30b6e-121">This is demanding in terms of database accesses.</span></span> <span data-ttu-id="30b6e-122">Um das End- und die Fälligkeitsdatum zu bestimmen, kann es notwendig sein, dies zu berechnen, auch wenn das Vorratsereignis nicht abgeschlossen wurde (im Fall der Vorwärtsterminierung).</span><span class="sxs-lookup"><span data-stu-id="30b6e-122">To determine the ending and due dates, it may be necessary to calculate this even if the supply event has not been closed (in the case of forward scheduling).</span></span>  

-   <span data-ttu-id="30b6e-123">Strukturstückliste einschließen: Dies kann warten bis kurz vor dem Abschluss des Vorratsereignisses.</span><span class="sxs-lookup"><span data-stu-id="30b6e-123">Include BOM explosion: this can wait until just before the supply event is closed.</span></span>  

 <span data-ttu-id="30b6e-124">Damit sind die Beschreibungen dazu, wie Bedarf und Vorrat vom Planungssystem geladen, priorisiert und ausgeglichen werden, abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="30b6e-124">This concludes the descriptions of how demand and supply is loaded, prioritized, and balanced by the planning system.</span></span> <span data-ttu-id="30b6e-125">In der Integration mit dieser Beschaffungsplanungsaktivität muss das System sicherstellen, dass der erforderliche Lagerbestand jedes geplanten Artikels entsprechend den jeweiligen Wiederbeschaffungsverfahren verwaltet wird.</span><span class="sxs-lookup"><span data-stu-id="30b6e-125">In integration with this supply planning activity, the system must ensure that the required inventory level of each planned item is maintained according to its reordering policies.</span></span>  

## <a name="see-also"></a><span data-ttu-id="30b6e-126">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="30b6e-126">See Also</span></span>  
 <span data-ttu-id="30b6e-127">[Designdetails: Ausgleich von Bedarf und Vorrat](design-details-balancing-demand-and-supply.md) </span><span class="sxs-lookup"><span data-stu-id="30b6e-127">[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md) </span></span>  
 <span data-ttu-id="30b6e-128">[Designdetails: Zentrale Konzepte des Planungssystems](design-details-central-concepts-of-the-planning-system.md) </span><span class="sxs-lookup"><span data-stu-id="30b6e-128">[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md) </span></span>  
 [<span data-ttu-id="30b6e-129">Designdetails: Vorratsplanung</span><span class="sxs-lookup"><span data-stu-id="30b6e-129">Design Details: Supply Planning</span></span>](design-details-supply-planning.md)
