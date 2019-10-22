# Nutzungsplanung Kanton Solothurn - Nachführung und Fehlerkorrektur

## Workflow

 1. Ticketeingang beim Büro per Mail
 2. [Download](https://geo.so.ch/geodata/ch.so.arp.nutzungsplanung/) der Daten vom Kanton (zwingend - Masterdaten liegen beim Kanton)
 3. Import der Daten in lokale Umgebung
 4. Anpassen der Daten, fehlerfrei  Validierung [geo.so.ch/ilivalidator-nplso](https://geo.so.ch/ilivalidator-nplso) mit strengem Validator  
 5. .xtf und .log exportieren im GitHub anhängen
 6. Ticket von `To Do (Planungsbüro)` nach `Validation (Kanton)` verschieben
 7. Kontrolle der neuen Daten - ev. zurück zu 4.
 8. Daten Aufschalten, Ticket schliessen und nach `Done` verschieben

![alt text](https://github.com/bjdarp/nplso-nf/blob/master/workflow.png)
