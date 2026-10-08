# MONO routecheck

Formulier op de vloer (QR per wand), antwoorden in een Google Sheet, dashboard voor het team. Zelfde opzet als de Highball-verklaring: GitHub Pages plus Apps Script.

## Bestanden

index.html is het formulier. dashboard.html is het teamdashboard. Code.gs is de koppeling met de Google Sheet.

## Installeren

1. Maak in MONO Drive een Google Sheet "MONO routecheck".
2. Extensies > Apps Script, plak Code.gs, verander DASHBOARD_SLEUTEL in een lange willekeurige tekst.
3. Voer één keer de functie setup uit. Die maakt de tabs Antwoorden en Sets.
4. Implementeren > Nieuwe implementatie > Web-app. Uitvoeren als: ik. Toegang: iedereen. Kopieer de URL.
5. Plak die URL als ENDPOINT in index.html en dashboard.html.
6. Pas in beide bestanden WANDEN aan naar de echte wandnamen. De id's moeten in beide gelijk zijn.
7. Zet index.html en dashboard.html in een GitHub-repo met Pages aan, bijvoorbeeld op feedback.monoboulder.nl.

## QR-codes

Eén QR per wand, met de wand-id in de link:
https://feedback.monoboulder.nl/?wand=overhang

Zonder ?wand= kiest de klimmer zelf de wand. Een algemene QR bij de balie of in de chalkbar kan dus ook.

## Dashboard delen

Deel deze link in Slack, alleen met het team:
https://feedback.monoboulder.nl/dashboard.html#key=JOUW_SLEUTEL

Zonder sleutel geen data. De antwoorden zijn anoniem, maar de sleutel hoort niet op Instagram.

## Sets bijhouden (belangrijk)

Draait er een nieuwe set in, zet dan een regel in de tab Sets: wand, setdatum, naam, setters. Alleen zo kan het dashboard een set vergelijken met de vorige. Leg dit bij de routesetters neer als vast onderdeel van het indraaien.

## Van signaal naar actie

Elke maandag (of bij de Weekstart) opent de hoofdsetter het dashboard, filter Huidige set. Met "Kopieer alles" neem je de actiepunten mee naar Asana of Slack; zet er per punt een eigenaar en deadline bij. Geen signaal is ook een uitkomst.

## Trainingsplanning

De trainers zetten hun planning in de tab Trainingen: van (startdatum), tot (einddatum), groep (regulier of selectie), thema en een notitie. Het dashboard toont wat nu loopt en wat eraan komt, zodat de routesetters er rekening mee kunnen houden.
