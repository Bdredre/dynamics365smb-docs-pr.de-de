---
title: "So geht's: Kostenbudgetposten löschen | Microsoft Docs"
description: "Sie verwenden den Batchauftrag **Kostenbudgeteinträge löschen** , um Kostenbudgetposten in der Kostenbudgeterfassung zu stornieren."
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
ms.openlocfilehash: acd8e0f25a3909ceab3dd63e04509ab48a300bb6
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="delete-cost-budget-entries"></a><span data-ttu-id="91ff1-103">Kostenbudgetposten löschen</span><span class="sxs-lookup"><span data-stu-id="91ff1-103">Delete Cost Budget Entries</span></span>
<span data-ttu-id="91ff1-104">Sie verwenden den Batchauftrag **Kostenbudgeteinträge löschen** , um Kostenbudgetposten in der Kostenbudgeterfassung zu stornieren.</span><span class="sxs-lookup"><span data-stu-id="91ff1-104">You use the **Delete Cost Budget Entries** batch job to cancel cost budget entries from the cost budget register.</span></span>  

<span data-ttu-id="91ff1-105">Um keine Lücken in den Kostenbudgetposten und den Kostenjournalposten entstehen zu lassen, können Sie einen einzelnen Posten oder eine Gruppe von Posten nicht mitten in der Liste der Journalposten löschen.</span><span class="sxs-lookup"><span data-stu-id="91ff1-105">To prevent any gaps in the cost budget entries and cost register entries, you cannot delete a single entry or a batch of entries in the middle of the list of register entries.</span></span>  

### <a name="to-delete-a-cost-budget-entry"></a><span data-ttu-id="91ff1-106">Kostenbudgetposten löschen:</span><span class="sxs-lookup"><span data-stu-id="91ff1-106">To delete a cost budget entry</span></span>  

1.  <span data-ttu-id="91ff1-107">Wählen Sie das Symbol ![Nach Seite oder Bericht suchen](media/ui-search/search_small.png "Symbol Nach Seite oder Bericht suchen"), geben **Kostenbudgetposten löschen** ein und wählen dann den zugehörigen Link aus.</span><span class="sxs-lookup"><span data-stu-id="91ff1-107">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Delete Cost Budget Entries**, and then choose the related link.</span></span>  

    <span data-ttu-id="91ff1-108">Die **Zu-Register-Nr.**</span><span class="sxs-lookup"><span data-stu-id="91ff1-108">The **To Register No.**</span></span> <span data-ttu-id="91ff1-109">Das Feld  enthält die letzte Journalpostennummer und kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="91ff1-109">field contains the last register entry number and cannot be changed.</span></span>  

    <span data-ttu-id="91ff1-110">Sie können **Von Journalnr.** verwenden</span><span class="sxs-lookup"><span data-stu-id="91ff1-110">You can use the **From Register No.**</span></span> <span data-ttu-id="91ff1-111">Sie können das Feld  verwenden, um eine Journalpostennummer auszuwählen, ab der der Löschvorgang beginnen soll.</span><span class="sxs-lookup"><span data-stu-id="91ff1-111">field to select a register entry number from which the deletion should begin.</span></span>  
2.  <span data-ttu-id="91ff1-112">Wählen Sie die Schaltfläche **OK** aus, um die ausgewählten Kostenbudgetposten zu löschen.</span><span class="sxs-lookup"><span data-stu-id="91ff1-112">Choose the **OK** button to delete the selected cost budget entries.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="91ff1-113">Um ein versehentliches Löschen von Kostenbudgetposten zu vermeiden, können Sie Journalposten schließen, indem Sie die Zeilen als **Abgeschlossen** im Feld **Abgeschlossen** im Fenster **Kostenbudget-Register**markieren.</span><span class="sxs-lookup"><span data-stu-id="91ff1-113">To avoid an accidental deletion of cost budget entries, you can close register entries by marking the lines as **Closed** in the **Closed** field in the **Cost Budget Registers** window.</span></span>  

## <a name="see-also"></a><span data-ttu-id="91ff1-114">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="91ff1-114">See Also</span></span>  
<span data-ttu-id="91ff1-115">[Kostenrechnung](finance-manage-cost-accounting.md)
[Erstellen von Kostenbudgets](finance-create-cost-budgets.md)</span><span class="sxs-lookup"><span data-stu-id="91ff1-115">[Accounting for Costs](finance-manage-cost-accounting.md)
[Creating Cost Budgets](finance-create-cost-budgets.md)</span></span>  
<span data-ttu-id="91ff1-116">[Arbeiten mit [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="91ff1-116">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>
