LT-Spice handleiding m.b.t. ad633

- Maak nieuwe schakeling in LT-spice en sla deze ergens op
- Plaats deze bestanden in de zelfde directory als jouw LT-spice schakeling.
- Voeg nieuw component toe (F2)
- Verander "Top Directory" naar jouw gekozen map

De ad633 zou nu moeten verschijnen.
Om convergentie problemen te voorkomen kan je het volgende statement toevoegen in je schakeling.
- Druk op 's' en plak dit in het veld : ".OPTIONS CSHUNT=1e-13"

Dit plaatst een kleine condensator van elke node naar aarde en voorkomt enige simulatie problemen.
