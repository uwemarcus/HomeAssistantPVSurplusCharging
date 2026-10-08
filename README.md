  PV-Laderegelung anhand der SoC-Entwicklung der BYD-Batterie:
  
  PV-Anlage mit 6,5 kWp
  
  BYD Akku HVS mit 10,24 kWh
  
  Fronius Symo Gen24 6.0 Plus
  
  Fronius Smart Meter 65A 3 TS und Enwitec Box

  Batteriekapazitaet: 9800 Wh. 1 Prozentpunkt SoC entspricht 98 Wh.

  Regeln: 
  Regelung alle 10 Minuten - Einschalten nur bei SoC > 80 %
  
  Einschalten nur zwischen 07:00 und vor 17:00 - um 17:00 zwingend Sollstrom 6 A
  und Ladefreigabe AUS
  
  Laufende Ladung darf unter 80 % weiterlaufen
  
  SoC < 60 %: Sollstrom 6 A und Ladefreigabe AUS
  
  SoC > 98 %: 16 A
  
  SoC-Trend innerhalb +/-0,2 Prozentpunkten: keine Stromaenderung
  
  ausserhalb der Totzone: energetisch berechnete Stromkorrektur
  
  Ladestrom 6 bis 16 A
  
  PV-Ueberschussladen AUS: 6 A und Ladefreigabe AUS
  
  Fahrzeugstatusaenderungen beeinflussen die Ladefreigabe nicht
  
  STOP-SOC wird nur protokolliert, wenn wirklich abgeschaltet wird
