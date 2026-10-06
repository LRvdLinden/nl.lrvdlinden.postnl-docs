# Flow-voorbeelden

## Nieuwe post melden

**Als:** Er is nieuwe post onderweg.  
**Dan:** stuur via een Homey-notificatieactie: “Er zijn [Aantal poststukken] nieuwe poststukken gevonden.”

Gebruik eventueel de token **Afbeelding poststuk** met een actie die afbeeldingen ondersteunt, mits **Afbeelding beschikbaar** waar is.

## Bezorgvenster melden

**Als:** Er is een bezorgvenster bekend.  
**Dan:** stuur: “Je pakket van [Afzender] komt op [Bezorgdatum] tussen [Bezorgvenster vanaf] en [Bezorgvenster tot].”

## Gewijzigde bezorginformatie

**Als:** De status van een pakket is gewijzigd.  
**Dan:** stuur: “[Afzender]: [Officiële PostNL-status]. Verwacht: [Bezorgdatum] [Bezorgvenster].”

Deze Flow kan ook starten bij een gewijzigde bezorgdatum of een gewijzigd venster, zonder dat de statustekst verandert. Niet ieder pakket heeft alle velden.

## Aanmelding herstellen

**Als:** De PostNL-aanmelding is verlopen.  
**Dan:** stuur jezelf een melding om het betreffende Mijn PostNL-apparaat te repareren.

De notificatieacties komen van Homey of een andere geïnstalleerde app. Plaats de tokens via de tokenkiezer; de vierkante haken hierboven zijn uitleg.
