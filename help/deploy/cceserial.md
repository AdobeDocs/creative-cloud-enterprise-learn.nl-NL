---
title: Werken met verlopen van Creatives Cloud voor ondernemingen en Acrobat-serienummers
description: Werken met het verlopen van serienummers voor Creatives Cloud voor ondernemingen en Acrobat
role: Admin
level: Beginner, Intermediate
feature: Deploy
exl-id: bc457be0-86dc-4e8a-b6b2-34bc76af2d21
source-git-commit: c57212d39b2e613964bc15d2967a1958dc0c8c8e
workflow-type: tm+mt
source-wordcount: '844'
ht-degree: 3%

---

# Werken met verlopen van Creatives Cloud voor ondernemingen en Acrobat-serienummers

Adobe heeft serienummers met onze apps (d.w.z. Creative Suite, Creative Cloud voor ondernemingen, Acrobat XI, Acrobat DC) uitgegeven aan klanten met Enterprise Term License Agreements (ETLA). Deze serienummers hebben een vervaldatum. Nadat de vervaldatum is verstreken, werkt het product niet meer. Het is daarom belangrijk dat u de migratie plant voordat uw serienummers verlopen. Op deze pagina worden de stappen beschreven die nodig zijn om ervoor te zorgen dat uw eindgebruikers toegang kunnen blijven houden tot hun Adobe-apps en -services.

## De vervaldatum van uw serienummers controleren

### Serienummer(s) zoeken

De serienummerlicenties voor uw ETLA-overeenkomst zijn beschikbaar via de [Licentiewebsite Adobe](https://licensing.adobe.com/) (LWS). Volg deze instructies om weer te geven en te downloaden:

1. Aanmelden bij [Licentiewebsite Adobe](https://licensing.adobe.com/) (LWS) met uw Adobe ID en wachtwoord.
1. Kies **Licenties > Serienummers ophalen**.
1. Voer uw **Eindgebruiker-id** of **Distribueren naar id**.
1. (Optioneel) Selecteer een **Productnaam**, **Productversie**, of **Platform** om resultaten te filteren.
1. Klik op Zoeken.
1. De productnaam en serienummers worden weergegeven.
1. (Optioneel) Selecteer &quot;EXPORTEREN NAAR CSV&quot; om de lijst met serienummers te downloaden.

![Serienummers zoeken](assets/retrieveserialnumbers.png)

### Controleer de vervaldatum

De [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) is een opdrachtregelprogramma voor IT-beheerders om te controleren of Adobe-producten op een computer serienummers gebruiken die zijn verlopen of verlopen. De tool geeft informatie weer zoals de product-id (LEID), het gecodeerde serienummer en de vervaldatum. Dit [pagina](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) bevat instructies voor het downloaden en gebruiken van het gereedschap op Mac- of Windows-computers.

## De ervaring van eindgebruikers voor en na het verlopen van het serienummer

Zowel Acrobat- als Creative Cloud-voor-ondernemingen-apps geven vanaf 60 dagen voor het verlopen berichten weer (in de apps). Zodra het serienummer is verlopen, stoppen de producten met werken en vragen de gebruiker om actie te ondernemen.

### Creative Cloud voor bedrijfservaring

De volgende informatie geeft een overzicht van de gebruikerservaring. Hieronder volgt een korte video, gevolgd door een overzicht van de gebruikerservaring.

>[!VIDEO](https://video.tv.adobe.com/v/331746?hidetitle=true)

**Voor vervaldatum**

Vanaf 60 dagen voordat het serienummer verloopt, wordt bij alle Creatives Cloud voor bedrijfs-apps een dialoogvenster met het product in weergegeven voor de eindgebruiker. Dit bericht verschijnt wekelijks, tot 30 dagen voor het verlopen, en verschijnt dan dagelijks tot de vervaldatum die *Uw licentie verloopt. Voor dit product van de Adobe wordt een licentie gebruikt die op 29 november 2020 verstrijkt. Neem contact op met uw beheerder om ervoor te zorgen dat u altijd toegang hebt*.

![CCE vóór vervaldatum](assets/cceexpiring.png)

**Na vervaldatum**

Zodra het serienummer is verlopen, hebben de gebruikers geen toegang meer tot het Creative Cloud voor bedrijfs-apps. Bij de eerste keer dat de toepassing wordt gestart na het verlopen, wordt een dialoogvenster weergegeven waarin *Het ingevoerde serienummer is verlopen. Er kan geen licentie voor dit product worden verleend. Neem contact op met de klantenondersteuning*.

![CCE na vervaldatum](assets/cceafterexpire.png)

Voor alle volgende pogingen om de toepassingen te starten, wordt de eindgebruiker gevraagd om **Nu aanmelden** gevolgd door de optie om een eigen Adobe ID te maken en de proefmodus te activeren. Nieuwe Adobe ID die door de eindgebruiker is gemaakt, is echter niet gekoppeld aan de licenties van uw organisatie en veroorzaakt extra verwarring voor uw gebruikers. Migreer uw gebruikers naar gebruikerslicenties op naam voordat uw serienummers verlopen, om bedrijfsonderbrekingen en/of onnodige verwarring te voorkomen.

![CCE aanmelden, dialoogvenster 1](assets/ccesignin1.png)

![CCE in dialoogvenster 2](assets/ccesignin2.png)

### Acrobat Experience

De volgende informatie geeft een overzicht van de gebruikerservaring. Hieronder volgt een korte video, gevolgd door een overzicht van de gebruikerservaring.

>[!VIDEO](https://video.tv.adobe.com/v/331749?hidetitle=true)


**Voor vervaldatum**

Vanaf 60 dagen voordat het serienummer verloopt, geeft Acrobat een pop-upbericht in het product weer voor de eindgebruiker. Dit zal eenmaal per week tot 7 dagen voor het verlopen verschijnen. Het zal dan dagelijks verschijnen met een *Uw Adobe Acrobat-licentie verloopt op 30-11-2020. Neem contact op met uw beheerder om Acrobat zonder onderbreking te blijven gebruiken.*

![Acrobat-verloopbericht](assets/acrobatexpiring.png)

**Na vervaldatum**

Zodra het serienummer is verlopen, hebben de gebruikers geen toegang meer tot Acrobat. Bij de eerste keer dat de toepassing wordt gestart na het verlopen, wordt een dialoogvenster weergegeven waarin *Het ingevoerde serienummer is verlopen. Er kan geen licentie voor dit product worden verleend. Neem contact op met de klantenondersteuning.*

![Acrobat na vervaldatum](assets/acrobatafterexpire.png)

Voor alle volgende pogingen om Acrobat te starten, wordt de eindgebruiker gevraagd: **Nu aanmelden** gevolgd door de optie om een eigen Adobe ID te maken en de proefmodus te activeren. Nieuwe Adobe ID die door de eindgebruiker is gemaakt, is echter niet gekoppeld aan de licenties van uw organisatie en veroorzaakt extra verwarring voor uw gebruikers.

![Acrobat Sign in dialoogvenster 1](assets/acrobatsignin1.png)

![Acrobat Sign in dialoogvenster 2](assets/acrobatsignin2.png)

## Neem contact met ons op voor hulp

Als u vragen hebt over het gebruik van de [AdobeExpiryCheck](https://helpx.adobe.com/enterprise/kb/volume-license-expiration-check.html) of hebt u hulp nodig bij het migreren van serienummerimplementatie naar een benoemde gebruiker. U hebt een aantal opties:
* Stuur een e-mail naar het Enterprise Onboarding-team van de Adobe - **entonb@adobe.com**
* Open een ondersteuningsticket in [Admin Console](https://adminconsole.adobe.com/support)
* Bereik uw accountteam voor Adoben
