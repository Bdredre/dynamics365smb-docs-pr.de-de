---
title: Wie Sie Power BI mit Finance and Operations, Business edition | Microsoft Docs verbinden
description: "Insight, Business Intelligence und KPIs können mit dem Power BI und dem Finance and Operations, Business edition einfach von den Finance and Operations, Business edition Daten abgerufen werden."
author: SusanneWindfeldPedersen
ms.service: dynamics365-financials
ms.topic: get-started-article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: account schedule, analysis, reporting, financial report, business intelligence, KPI
ms.date: 02/05/2018
ms.author: solsen
ms.translationtype: HT
ms.sourcegitcommit: b4e2e7bc1c2622d329c73ae5bf47b4accff10aa8
ms.openlocfilehash: aff8d95b13f795fa12d3146e5613712fb3baf9b4
ms.contentlocale: de-de
ms.lasthandoff: 03/22/2018

---
# <a name="connecting-power-bi-to-finance-and-operations-business-edition-content-packs"></a><span data-ttu-id="ff460-103">Wie Sie Power BI mit den Finance and Operations, Business edition Inhaltspaketen verbinden</span><span class="sxs-lookup"><span data-stu-id="ff460-103">Connecting Power BI to Finance and Operations, Business edition Content Packs</span></span>
<span data-ttu-id="ff460-104">Einblicke in Ihre Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Daten zu erhalten ist mit Power BI und dem Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Inhaltspaket sehr einfach.</span><span class="sxs-lookup"><span data-stu-id="ff460-104">Getting insights into your Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] data is easy with Power BI and the Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] content packs.</span></span> <span data-ttu-id="ff460-105">Power BI ruft die Daten ab und erstellt ein Standarddashboard und Berichte auf Grundlage der Daten.</span><span class="sxs-lookup"><span data-stu-id="ff460-105">Power BI retrieves your data then builds an out-of-the-box dashboard and reports based on that data.</span></span>

> [!NOTE]  
>  <span data-ttu-id="ff460-106">Sie müssen ein gültiges Konto mit Dynamics 365 und Power BI haben.</span><span class="sxs-lookup"><span data-stu-id="ff460-106">You must have a valid account with Dynamics 365 and with Power BI.</span></span> <span data-ttu-id="ff460-107">Zudem müssen Sie [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) herunterladen.</span><span class="sxs-lookup"><span data-stu-id="ff460-107">Also, you must download [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/).</span></span>  
>  <span data-ttu-id="ff460-108">Power BI Inhaltpakete benötigen Berechtigungen für die Tabellen, aus denen Daten abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="ff460-108">Power BI content packs require permissions to the tables where data is retrieved from.</span></span> <span data-ttu-id="ff460-109">Weitere Einzelheiten auf den Anforderungen werden im Folgenden beschrieben.</span><span class="sxs-lookup"><span data-stu-id="ff460-109">More details on the requirements are described below.</span></span>  

## <a name="how-to-connect"></a><span data-ttu-id="ff460-110">So stellen Sie die Verbindung her</span><span class="sxs-lookup"><span data-stu-id="ff460-110">How to Connect</span></span>
1. <span data-ttu-id="ff460-111">Wählen Sie **Daten abrufen** am unteren Rand des linken Navigationsbereich aus.</span><span class="sxs-lookup"><span data-stu-id="ff460-111">Select **Get Data** at the bottom of the left navigation pane.</span></span>  
<span data-ttu-id="ff460-112">![Navigieren, um die Daten zu erhalten](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-get-data.png)</span><span class="sxs-lookup"><span data-stu-id="ff460-112">![Navigating to Get Data](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-get-data.png)</span></span>
2. <span data-ttu-id="ff460-113">Im Feld **Dienste** wählen Sie **Abrufen** aus.</span><span class="sxs-lookup"><span data-stu-id="ff460-113">In the **Services** box, select **Get**.</span></span> <span data-ttu-id="ff460-114">Dadurch wird ein Fenster mit **AppSource** und **Apps für Power BI Apps** geöffnet.</span><span class="sxs-lookup"><span data-stu-id="ff460-114">This will open a window with the **AppSource** and **Apps for Power BI apps**.</span></span>  
<span data-ttu-id="ff460-115">![Wählen Sie Inhaltspakete von Onlinediensten aus](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-online-services-get.png)</span><span class="sxs-lookup"><span data-stu-id="ff460-115">![Choose content packs from online services](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-online-services-get.png)</span></span>
3. <span data-ttu-id="ff460-116">Wählen Sie **Apps** auf der Registerkarte **Apps für Power BI Apps**, und wählen Sie das Feld **Microsoft Dynamics 365 for Finance and Operations** Inhaltspakete, die Sie verwenden möchten, und wählen Sie dann **jetzt abrufen**.</span><span class="sxs-lookup"><span data-stu-id="ff460-116">Select **Apps** from the **Apps for Power BI apps** tab, and choose the **Microsoft Dynamics 365 for Finance and Operations** content pack that you want to use, and then select **Get it now**.</span></span>  
<span data-ttu-id="ff460-117">![Wählen Sie Dynamics 365 for Finance and Operations, Business edition. Wählen Sie jetzt abrufen](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-dynamics365-for-financials-get-it-now.png)</span><span class="sxs-lookup"><span data-stu-id="ff460-117">![Select Dynamics 365 for Finance and Operations, Business edition and select Get it now](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-dynamics365-for-financials-get-it-now.png)</span></span>
4. <span data-ttu-id="ff460-118">Wenn Sie dazu aufgefordert werden, geben Sie in [!INCLUDE[d365fin_md](includes/d365fin_long_md.md)] den Namen des *Unternehmens* ein.</span><span class="sxs-lookup"><span data-stu-id="ff460-118">When prompted, enter the name of *your company* in [!INCLUDE[d365fin_md](includes/d365fin_long_md.md)].</span></span> <span data-ttu-id="ff460-119">Dies ist nicht der Anzeigename.</span><span class="sxs-lookup"><span data-stu-id="ff460-119">This is not the display name.</span></span>  
<span data-ttu-id="ff460-120">![Wählen Sie Dynamics 365 for Finance and Operations, Business edition. Wählen Sie jetzt abrufen](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-connect-to-d365-finance-and-operations-crm.png)</span><span class="sxs-lookup"><span data-stu-id="ff460-120">![Select Dynamics 365 for Finance and Operations, Business edition and select Get it now](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-connect-to-d365-finance-and-operations-crm.png)</span></span>
5. <span data-ttu-id="ff460-121">Sobald verbunden, werden ein Dashboard, ein Bericht und ein Datensatz automatisch in Ihren Power BI Arbeitsbereich geladen.</span><span class="sxs-lookup"><span data-stu-id="ff460-121">Once connected, a dashboard, report and dataset will automatically be loaded into your Power BI workspace.</span></span> <span data-ttu-id="ff460-122">Wenn abgeschlossen werden die Kacheln die Daten aus dem Konto aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ff460-122">When completed, the tiles will update with data from your account.</span></span>
<span data-ttu-id="ff460-123">![Wählen Sie Dynamics 365 for Finance and Operations, Business edition. Wählen Sie jetzt abrufen](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-workspace-dashboard-report-dataset.png)</span><span class="sxs-lookup"><span data-stu-id="ff460-123">![Select Dynamics 365 for Finance and Operations, Business edition  and select Get it now](./media/across-how-to-connect-powerbi-d365-content-packs/powerbi-workspace-dashboard-report-dataset.png)</span></span>

## <a name="what-now"></a><span data-ttu-id="ff460-124">Was jetzt?</span><span class="sxs-lookup"><span data-stu-id="ff460-124">What Now?</span></span>

- <span data-ttu-id="ff460-125">Versuchen Sie im [Erstellen eine Frage im Q&A-Feld](https://docs.microsoft.com/en-us/power-bi/service-q-and-a) im oberen Bereich des Dashboards.</span><span class="sxs-lookup"><span data-stu-id="ff460-125">Try [asking a question in the Q&A box](https://docs.microsoft.com/en-us/power-bi/service-q-and-a) at the top of the dashboard.</span></span>  
- <span data-ttu-id="ff460-126">[Ändern Sie die Kacheln](https://docs.microsoft.com/en-us/power-bi/service-dashboard-edit-tile) im Dashboard.</span><span class="sxs-lookup"><span data-stu-id="ff460-126">[Change the tiles](https://docs.microsoft.com/en-us/power-bi/service-dashboard-edit-tile) in the dashboard.</span></span>  
- <span data-ttu-id="ff460-127">[Wählen Sie eine Kachel aus](https://docs.microsoft.com/en-us/power-bi/service-dashboard-tiles), um den zu Grunde liegenden Bericht zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="ff460-127">[Select a tile](https://docs.microsoft.com/en-us/power-bi/service-dashboard-tiles) to open the underlying report.</span></span>  
- <span data-ttu-id="ff460-128">Während Ihr Dataset täglich aktualisiert wird, können Sie den Aktualisierungsplan ändern oder ihn mithilfe von **jetzt aktualisieren** bei Bedarf aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="ff460-128">While your dataset will be scheduled to refreshed daily, you can change the refresh schedule or try refreshing it on demand using **Refresh Now**.</span></span>

## <a name="system-requirements"></a><span data-ttu-id="ff460-129">Systemanforderungen</span><span class="sxs-lookup"><span data-stu-id="ff460-129">System Requirements</span></span>
<span data-ttu-id="ff460-130">Um die Daten [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] in Power BI zu importieren, müssen Sie Berechtigungen für den Webdiensten haben, um die Daten abzurufen.</span><span class="sxs-lookup"><span data-stu-id="ff460-130">To import your [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] data into Power BI, you need to have permissions to the web services used to retrieve data.</span></span> <span data-ttu-id="ff460-131">Die Web Services, die für jedes Inhaltspakete erforderlich sind:</span><span class="sxs-lookup"><span data-stu-id="ff460-131">The web services required for each content pack include:</span></span>

<span data-ttu-id="ff460-132">**Microsoft Dynamics 365 for Finance and Operations, Business edition – CRM**</span><span class="sxs-lookup"><span data-stu-id="ff460-132">**Microsoft Dynamics 365 for Finance and Operations, Business edition – CRM**</span></span>
- <span data-ttu-id="ff460-133">SalesOpportunities</span><span class="sxs-lookup"><span data-stu-id="ff460-133">SalesOpportunities</span></span>
- <span data-ttu-id="ff460-134">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-134">ExcelTemplateViewCompany</span></span>

<span data-ttu-id="ff460-135">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Sales**</span><span class="sxs-lookup"><span data-stu-id="ff460-135">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Sales**</span></span>
- <span data-ttu-id="ff460-136">ItemSalesbyCustomer</span><span class="sxs-lookup"><span data-stu-id="ff460-136">ItemSalesbyCustomer</span></span>
- <span data-ttu-id="ff460-137">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="ff460-137">SalesDashboard</span></span>
- <span data-ttu-id="ff460-138">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-138">ExcelTemplateViewCompany</span></span>

<span data-ttu-id="ff460-139">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Finance**</span><span class="sxs-lookup"><span data-stu-id="ff460-139">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Finance**</span></span>
- <span data-ttu-id="ff460-140">PowerBIFinance</span><span class="sxs-lookup"><span data-stu-id="ff460-140">PowerBIFinance</span></span>
- <span data-ttu-id="ff460-141">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-141">ExcelTemplateViewCompany</span></span>

<span data-ttu-id="ff460-142">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Jobs**</span><span class="sxs-lookup"><span data-stu-id="ff460-142">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Jobs**</span></span>
- <span data-ttu-id="ff460-143">Projektübersicht</span><span class="sxs-lookup"><span data-stu-id="ff460-143">Job List</span></span>
- <span data-ttu-id="ff460-144">Projektplanzeilen</span><span class="sxs-lookup"><span data-stu-id="ff460-144">Job Planning Lines</span></span>
- <span data-ttu-id="ff460-145">Projektaufgabenzeilen</span><span class="sxs-lookup"><span data-stu-id="ff460-145">Job Task Lines</span></span>

<span data-ttu-id="ff460-146">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Customers List**</span><span class="sxs-lookup"><span data-stu-id="ff460-146">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Customers List**</span></span>
- <span data-ttu-id="ff460-147">ItemSalesbyCustomer</span><span class="sxs-lookup"><span data-stu-id="ff460-147">ItemSalesbyCustomer</span></span>
- <span data-ttu-id="ff460-148">Power_BI_Item_Purchase_List</span><span class="sxs-lookup"><span data-stu-id="ff460-148">Power_BI_Item_Purchase_List</span></span>
- <span data-ttu-id="ff460-149">Power_BI_Item_Sales_List</span><span class="sxs-lookup"><span data-stu-id="ff460-149">Power_BI_Item_Sales_List</span></span>
- <span data-ttu-id="ff460-150">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="ff460-150">SalesDashboard</span></span>
- <span data-ttu-id="ff460-151">Power_BI_Customer_List</span><span class="sxs-lookup"><span data-stu-id="ff460-151">Power_BI_Customer_List</span></span>
- <span data-ttu-id="ff460-152">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-152">ExcelTemplateViewCompany</span></span>

<span data-ttu-id="ff460-153">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Items List**</span><span class="sxs-lookup"><span data-stu-id="ff460-153">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Items List**</span></span>
- <span data-ttu-id="ff460-154">ItemSalesbyCustomer</span><span class="sxs-lookup"><span data-stu-id="ff460-154">ItemSalesbyCustomer</span></span>
- <span data-ttu-id="ff460-155">Power_BI_Item_Purchase_List</span><span class="sxs-lookup"><span data-stu-id="ff460-155">Power_BI_Item_Purchase_List</span></span>
- <span data-ttu-id="ff460-156">Power_BI_Item_Sales_List</span><span class="sxs-lookup"><span data-stu-id="ff460-156">Power_BI_Item_Sales_List</span></span>
- <span data-ttu-id="ff460-157">Artikel</span><span class="sxs-lookup"><span data-stu-id="ff460-157">Items</span></span>
- <span data-ttu-id="ff460-158">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="ff460-158">SalesDashboard</span></span>
- <span data-ttu-id="ff460-159">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-159">ExcelTemplateViewCompany</span></span>

<span data-ttu-id="ff460-160">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Vendors List**</span><span class="sxs-lookup"><span data-stu-id="ff460-160">**Microsoft Dynamics 365 for Finance and Operations, Business edition – Vendors List**</span></span>
- <span data-ttu-id="ff460-161">ItemSalesbyCustomer</span><span class="sxs-lookup"><span data-stu-id="ff460-161">ItemSalesbyCustomer</span></span>
- <span data-ttu-id="ff460-162">Power_BI_Item_Purchase_List</span><span class="sxs-lookup"><span data-stu-id="ff460-162">Power_BI_Item_Purchase_List</span></span>
- <span data-ttu-id="ff460-163">Power_BI_Item_Sales_List</span><span class="sxs-lookup"><span data-stu-id="ff460-163">Power_BI_Item_Sales_List</span></span>
- <span data-ttu-id="ff460-164">Artikel</span><span class="sxs-lookup"><span data-stu-id="ff460-164">Items</span></span>
- <span data-ttu-id="ff460-165">SalesDashboard</span><span class="sxs-lookup"><span data-stu-id="ff460-165">SalesDashboard</span></span>
- <span data-ttu-id="ff460-166">Power_BI_Customer_List</span><span class="sxs-lookup"><span data-stu-id="ff460-166">Power_BI_Customer_List</span></span>
- <span data-ttu-id="ff460-167">ItemSalesbyCustomer</span><span class="sxs-lookup"><span data-stu-id="ff460-167">ItemSalesbyCustomer</span></span>
- <span data-ttu-id="ff460-168">Power_BI_Vendor_List</span><span class="sxs-lookup"><span data-stu-id="ff460-168">Power_BI_Vendor_List</span></span>
- <span data-ttu-id="ff460-169">ExcelTemplateViewCompany</span><span class="sxs-lookup"><span data-stu-id="ff460-169">ExcelTemplateViewCompany</span></span>

## <a name="web-services"></a><span data-ttu-id="ff460-170">Webdienste</span><span class="sxs-lookup"><span data-stu-id="ff460-170">Web Services</span></span>
<span data-ttu-id="ff460-171">Eine einfache Methode, die Webdienste zu finden ist, in [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] nach Webdiensten zu suchen.</span><span class="sxs-lookup"><span data-stu-id="ff460-171">An easy way to find the web services is to search for web services in [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)].</span></span> <span data-ttu-id="ff460-172">In der Übersicht stellen Sie sicher, dass das Veröffentlichungsfeld für die oben aufgeführten Webdienste markiert wird.</span><span class="sxs-lookup"><span data-stu-id="ff460-172">In the list make sure the Publish box is marked for the web services listed above.</span></span>

## <a name="troubleshooting"></a><span data-ttu-id="ff460-173">Problembehebung</span><span class="sxs-lookup"><span data-stu-id="ff460-173">Troubleshooting</span></span>
<span data-ttu-id="ff460-174">Das Power BI-Dashboard beruht auf den veröffentlichten Webdiensten, die oben erwähnten werden. Es enthält Daten vom Demomandanten oder von Ihrem eigenen Unternehmen wenn Sie Daten aus der aktuellen Finanzlösung importieren.</span><span class="sxs-lookup"><span data-stu-id="ff460-174">The Power BI dashboard relies on the published web services that are listed above, and it will show data from the demonstration company or your own company if you import data from your current finance solution.</span></span> <span data-ttu-id="ff460-175">Wenn etwas schief geht, stellt dieser Abschnitt eine Problemumgehung für die häufigsten Probleme bereit.</span><span class="sxs-lookup"><span data-stu-id="ff460-175">However, if something goes wrong, this section provides a workaround for the most typical issues.</span></span>

### <a name="incorrect-company-name"></a><span data-ttu-id="ff460-176">Ungültiger Unternehmensnamen</span><span class="sxs-lookup"><span data-stu-id="ff460-176">Incorrect Company Name</span></span>  
<span data-ttu-id="ff460-177">Ein häufiger Fehler ist, den Unternehmensanzeigenamen anstelle des Unternehmensnamens einzugeben.</span><span class="sxs-lookup"><span data-stu-id="ff460-177">A common mistake is to enter the company display name instead of the company name.</span></span> <span data-ttu-id="ff460-178">Unternehmensnamensuche für **Unternehmen** zu suchen.</span><span class="sxs-lookup"><span data-stu-id="ff460-178">To find the company name search for **Companies**.</span></span> <span data-ttu-id="ff460-179">Verwenden Sie das Feld **Name**, wenn Sie den Unternehmensnamen eingeben.</span><span class="sxs-lookup"><span data-stu-id="ff460-179">Then use the **Name** field when entering your company name.</span></span>

### <a name="incorrect-user-name-and-password"></a><span data-ttu-id="ff460-180">Falscher Benutzername und Kennwort</span><span class="sxs-lookup"><span data-stu-id="ff460-180">Incorrect User Name and Password</span></span>  
<span data-ttu-id="ff460-181">Der Benutzername und das Kennwort, die zum Verbinden verwendet werden, sind dieselben, die verwendet werden, um die Verbindung mit Ihrem  Microsoft Office 365 Konto herzustellen.</span><span class="sxs-lookup"><span data-stu-id="ff460-181">The user name and password used to connect will be the same as what is used to connect to your Microsoft Office 365 account.</span></span>  

<span data-ttu-id="ff460-182">Die Inhaltspakete erfordern, dass Sie ein Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Konto haben.</span><span class="sxs-lookup"><span data-stu-id="ff460-182">The content packs also require that you have a Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] account.</span></span> <span data-ttu-id="ff460-183">Nachdem Sie Ihre Anmeldeinformationen eingeben haben, erkennen wir sämtliche Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Tenants, auf die Sie Zugriff haben.</span><span class="sxs-lookup"><span data-stu-id="ff460-183">Once you enter your credentials, we will auto discover any Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] tenants you have access to.</span></span> <span data-ttu-id="ff460-184">Wenn Sie kein lizenziertes oder Probe-Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] Konto haben, erhalten Sie eine Fehlermeldung.</span><span class="sxs-lookup"><span data-stu-id="ff460-184">If you do not have a licensed or trial Microsoft [!INCLUDE[d365fin_long_md](includes/d365fin_long_md.md)] account, you will receive an error message.</span></span>

### <a name="the-key-didnt-match-any-rows-in-the-table"></a><span data-ttu-id="ff460-185">Der Schlüssel glich keinen Zeilen in der Tabelle</span><span class="sxs-lookup"><span data-stu-id="ff460-185">The Key Didn't Match Any Rows in the Table</span></span>
<span data-ttu-id="ff460-186">Wenn Sie einen nicht gültigen Unternehmensnamen während des Verbindungsvorgangs eingeben, erhalten Sie möglicherweise die Fehlermeldung, "der Schlüssel entsprach keinen Zeilen in der Tabelle".</span><span class="sxs-lookup"><span data-stu-id="ff460-186">If you enter a non valid company name during the connection process, you may get the error message "The key didn't match any rows in the table".</span></span> <span data-ttu-id="ff460-187">Geben Sie den korrekten Unternehmensnamen an und versuchen Sie die Verbindung erneut.</span><span class="sxs-lookup"><span data-stu-id="ff460-187">Provide the correct company name and try connecting again.</span></span>

## <a name="see-also"></a><span data-ttu-id="ff460-188">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="ff460-188">See Also</span></span>
[<span data-ttu-id="ff460-189">Erste Schritte mit Power BI</span><span class="sxs-lookup"><span data-stu-id="ff460-189">Get started with Power BI</span></span>](https://docs.microsoft.com/en-us/power-bi/service-get-started)  
<span data-ttu-id="ff460-190">[Power BI - Grundmodelle](https://docs.microsoft.com/en-us/power-bi/service-basic-concepts)
[Business Intelligence](bi.md)</span><span class="sxs-lookup"><span data-stu-id="ff460-190">[Power BI - Basic Concepts](https://docs.microsoft.com/en-us/power-bi/service-basic-concepts)
[Business Intelligence](bi.md)</span></span>  
<span data-ttu-id="ff460-191">[Willkommen bei [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="ff460-191">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
[<span data-ttu-id="ff460-192">Geschäftsdaten aus anderen Finanzsystemen importieren</span><span class="sxs-lookup"><span data-stu-id="ff460-192">Importing Business Data from Other Finance Systems</span></span>](upload-data.md)  
<span data-ttu-id="ff460-193">[Einrichten [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)</span><span class="sxs-lookup"><span data-stu-id="ff460-193">[Setting Up [!INCLUDE[d365fin](includes/d365fin_md.md)]](setup.md)</span></span>  
[<span data-ttu-id="ff460-194">Finanzen</span><span class="sxs-lookup"><span data-stu-id="ff460-194">Finance</span></span>](finance.md)  
<span data-ttu-id="ff460-195">[Einrichtungs-Berichterstellugn für [!INCLUDE[d365fin](includes/d365fin_md.md)] in Power BI](across-how-use-financials-data-source-powerbi.md)</span><span class="sxs-lookup"><span data-stu-id="ff460-195">[Setup Reporting for [!INCLUDE[d365fin](includes/d365fin_md.md)] in Power BI](across-how-use-financials-data-source-powerbi.md)</span></span>  
