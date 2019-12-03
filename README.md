# Nutzungsplanung Kanton Solothurn - Nachführung und Fehlerkorrektur

## Workflow
 1. Eröffnung Ticket durch Amt für Geoinformation (AGI) oder Amt für Raumplanung (ARP)
 2. Zuweisung Ticket durch Alex (ARP) `Bearbeitung (Planer)`
  3. Bearbeitung des Ticket durch zugewiesenes Planungsbüro
 - [Download](https://geo.so.ch/geodata/ch.so.arp.nutzungsplanung/) der Daten vom Kanton (zwingend - Masterdaten liegen beim Kanton)
 - Import der Daten in lokale Umgebung
 - Anpassen der Daten, fehlerfrei  Validierung [geo.so.ch/ilivalidator-nplso](https://geo.so.ch/ilivalidator-nplso) mit strengem Validator  
 - exportieren .xtf und .log und in GitHub anhängen
 
 4. Ticket von `Bearbeitung (Planer)` nach `Validation (ARP)` verschieben
 

 5. Kontrolle der neuen Daten - ev. zurück zu 3.
 6. Zusweisen Ticket an AGI von `Validation (ARP)` nach `Freischalten (AGI)` verschieben
 7. Daten Aufschalten, Ticket schliessen und nach `Done` verschieben

![alt text](https://github.com/bjdarp/nplso-nf/blob/master/workflow.png)
