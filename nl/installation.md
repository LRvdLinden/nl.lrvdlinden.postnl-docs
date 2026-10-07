# Installeren en koppelen

## App installeren

[**Installeer de PostNL-app voor Homey (testversie)**](https://homey.app/a/nl.lrvdlinden.postnl/test/)

Via deze link installeer je de testversie. Deze kan nieuwer zijn dan de reguliere App Store-versie.

## Wat heb je nodig?

- Een compatibele Homey met versie 12.3.0 of nieuwer. De app gebruikt het lokale Homey-platform.
- Een PostNL-account waarin je post en/of pakketten zichtbaar zijn.
- Chrome met de PostNL Chrome Login Helper voor het overnemen van de aanmeldcallback. Download de helper hieronder. Aanvullende instructies vind je in het communitytopic.

## Login Helper downloaden

[**Download hier de PostNL Homey Login Helper**](https://lrvdlinden.app/Extentions/PostNL-Homey-Login-Helper.zip)

Pak het ZIP-bestand uit voordat je de extensie in Chrome installeert.

## Account toevoegen

1. [Installeer de PostNL-testversie](https://homey.app/a/nl.lrvdlinden.postnl/test/) op je Homey.
2. Kies in Homey **Apparaat toevoegen → PostNL → Mijn PostNL**.
3. Kopieer of open de PostNL-aanmeld-URL die het koppelvenster toont.
4. Open deze URL in Chrome en meld je aan bij PostNL.
5. Kopieer de volledige callback-URL met de Chrome Login Helper. Deze begint met `postnl://login?code=…`.
6. Plak deze in **Callback-URL** en kies **Account koppelen**.
7. Wacht op de eerste synchronisatie en controleer het apparaat.

Gebruik de aanmeld-URL uit dezelfde koppelprocedure. Begin opnieuw als de autorisatiecode niet meer geldig is.

## Meerdere accounts en opnieuw verbinden

Accounts worden per apparaat beheerd. Voeg voor een ander account een nieuw Mijn PostNL-apparaat toe. Gebruik **Repareren** bij het betreffende apparaat als de aanmelding verloopt. De algemene appinstellingen verwijzen naar deze apparaatgebonden werkwijze.

De eerste succesvolle synchronisatie stelt een uitgangssituatie vast: bestaande post en pakketten worden dan niet allemaal als nieuw gemeld.

[Homey App Store](https://homey.app/nl-nl/app/nl.lrvdlinden.postnl/PostNL/) · [Login Helper & support](https://community.homey.app/t/app-pro-postnl-for-homey/159674)
