---
title: Azure, Entra ID, Microsoft 365 || Office 365
date: 2026-03-05 20:14 +0100
categories: [Blogging, Cloud, Microsoft, ]
tags: [ blog, personal blog, layer 5]
author: jonaxethan
description: "Microsoft Azure, Entra und Office einfach erklärt"
---

<span style="background-color:yellow; color:black; padding:3px 6px; border-radius:4px; font-weight:bold;">
  Status: In Bearbeitung
</span>

# Azure, Entra ID, Microsoft365 oder Office 365

Während meiner Zeit bei [IQSolutions]{https://iq-solutions.de} und [Bechtle]{https://Bechtle.com} waren Kunden immer wieder an den Cloud Lösungen von Microsoft interessiert. Auch wenn die Office Suite mit Word, Excel, Powerpoint usw. noch eine Kauflizenz besitzt, wechselten mehere Kunden zu den Onlinediensten mit jeweiligen Produkten als Onlineversion bzw. in das Abomodell.

Immer wieder stolperten wir bei Gesprächen über die Nomenklatur wie Azure, Azure Active Directory, Entra ID, Microsoft 365, Office 365, Intune, Endpoint Manager usw. Viele Begriffe wurden als Synoyme für einander verwendet, aber das sind sie nicht. Leider tauchen auch bei Recherche immer wieder die "alten" Begriffe auf und eine klare Trennung zwischen den Begriffen bleibt aus.

Für alle wissbegierigen möchte ich versuchen hier meine Definition der einzelenen Begriffe näherzubringen. Diese entspricht nicht der offiziellen Definition seitens Microsoft.
Ich sehe hier den großen Vorteil, dass präzise die verschieden Produkte bzw. Sammlungen an Diensten unterschieden werden. Zur Unterstützung dient folgende Grafik.


![Overview](/assets/img/posts/2026-03-03-Azure-Entra-M365/2026-03-03-Azureoverview.png)

### Entra ID
Entra ID ehmals. Azure Active Directory ist der Verzeichnisdienst in der Cloud von Microsoft. Ich glaube hier hat schon der Verwirrung begonnen. Active Directory sollte einigen bekannt sein aus der OnPrem Umgebung. Mit dem Präfix Azure, meine ich, wollte Microsoft damals aussagen, dass dies die Cloudvariante des ADs ist. Durch die Umbennenung zu Entra wollte Mircrosoft klar machen, dass auch anderen Plattformen an den Identity Provider angebungen werden können.[^1]{https://learn.microsoft.com/de-de/entra/fundamentals/how-to-rename-azure-ad}
Der Entra Dienst wird benötigt zur Authentifizierung der Benutzer für alle andere Suites somit auch notwendig für Azure, Microsoft 365 und Office 365. Deswegen merke ich mir Entra mit dem Wort Entry als Eingang in die Cloud.

### Azure
Azure ist die Cloudcomputing Plattform vom Micosoft. Hier sinden sich virtuellen Computer, virt. Speicher, virt. Netzwerk und weitere Cloudservices im Bereich von Infrastructure as a Service und Plattform as a Service.  Azure merke ich mir mit der Farbe Azurblau für das Thema Cloud.

### Microsoft 365
Unter Microsoft 365 verstehe ich die SaaS Anwendungen wie Intune, Defender, Purview usw. Hier steht die Verwaltung von Assets (Personen, Geräte, Gruppe) zur Verfügung. 

### Office 365
Eigentlich ist der Begriff Office 365 durch Microsoft 365 abgelöst worden. Ich finde hier aber eigentlich, dass der Begriff weitherin bestehen bleiben sollte, weil die Office Suite mit Office, Teams, Excel, Powerpoint, Clipchamp, Places, Outlook, To Do auch immer größer wird und während bei Microsoft 365 die Adminportalte und somit die Verwaltung in Vordergrund steht, steht bei Office 365 der Anwender mit seinen Programmen im Vordergrund. Hier eine inhaltliche Unterscheidung zu machen, empfinde ich für sinnvoll.

