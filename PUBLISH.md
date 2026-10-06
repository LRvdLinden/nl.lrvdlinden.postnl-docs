# PostNL GitBook publiceren

Dit pakket bevat twee complete Markdown-handleidingen, elk met een SUMMARY.md en lokale afbeeldingen. Nederlands is standaard. Het pakket is voorbereid voor GitBook, maar nog niet in een GitBook-account geplaatst of gepubliceerd.

## Via Git Sync

1. Pak de ZIP uit en plaats de inhoud in een documentatierepository op GitHub, inclusief het verborgen bestand `.gitbook.yaml`.
2. Maak een space in GitBook en kies **Set up Git Sync**.
3. Koppel de repository en de gewenste branch.
4. Kies bij de eerste synchronisatie **GitHub → GitBook**, zodat GitBook de aangeleverde bestanden importeert.
5. Controleer de pagina's, navigatie en afbeeldingen in GitBook en publiceer de site vanuit jouw account.

De configuratie wijst naar `./nl/`. Voor uitsluitend Engels wijzig je dit naar `./en/`. Voor beide talen met losse spaces kun je per taal een afzonderlijke repository gebruiken: kopieer de inhoud van die taalmap naar de repositoryroot en gebruik `root: ./` in de configuratie. Koppel iedere repository aan de bijbehorende space. De precieze meertalige site-indeling hangt af van je GitBook-inrichting.

Gebruik je dezelfde repository als de app, plaats deze documentatie dan bijvoorbeeld in een map `docs` en pas `root` aan naar `./docs/nl/`. Overschrijf geen bestaande appbestanden of GitBook-configuratie zonder deze eerst te vergelijken.

## Vormgeving

Gebruik PostNL-oranje als accent, de busafbeelding op de startpagina en de bestaande widgetpreviews bij de afzonderlijke widgetpagina's. De daadwerkelijke navigatie, zoekfunctie en themaweergave worden door GitBook verzorgd.

## Bronnen en afbakening

- Inhoud: PostNL-for-Homey-v1.2.1.zip, appmanifest en implementatie; onderzocht op 6 oktober 2026.
- Afbeeldingen: ongewijzigde assets en lichte/donkere widgetpreviews uit dezelfde ZIP. De Homey Store bevat ook de previews voor Mijn Post, Mijn Pakketten en Mijn Bezorging.
- Homey Store: https://homey.app/nl-nl/app/nl.lrvdlinden.postnl/PostNL/ — opgehaalde pagina vermeldde 1.1.12; deze handleiding beschrijft 1.2.1.
- Community: https://community.homey.app/t/app-pro-postnl-for-homey/159674
- GitBook Git Sync: https://gitbook.com/docs/guides/editing-and-publishing-documentation/import-or-migrate-your-content-to-gitbook-with-git-sync
- GitBook quickstart: https://gitbook.com/docs/getting-started/quickstart

Het RDW-voorbeeld was niet bereikbaar via de gebruikte webzoektool. Dit pakket gebruikt een eigen indeling voor PostNL; het is geen kopie van die documentatie.
