  Anlage:
  PV-Anlage mit 6,5 kWp
  
  BYD Akku HVS mit 10,24 kWh
  Batteriekapazitaet: 9800 Wh. 1 Prozentpunkt SoC entspricht 98 Wh.
  
  Fronius Symo Gen24 6.0 Plus
  
  Fronius Smart Meter 65A 3 TS und Enwitec Box
  

  
  PV-Laderegelung anhand der SoC-Entwicklung der BYD-Batterie:
  
  Regeln: 
  Regelung alle 10 Minuten - Einschalten nur bei SoC > 80 %
  
  Einschalten nur zwischen 07:00 und vor 17:00 - um 17:00 zwingend Sollstrom 6 A
  und Ladefreigabe AUS
  
  Laufende Ladung darf unter 80 % weiterlaufen
  
  SoC < 60 %: Sollstrom 6 A und Ladefreigabe AUS
  
  SoC > 98 %: 16 A
  
  SoC-Trend innerhalb +/-0,2 Prozentpunkten: keine Stromaenderung
  
  Ausserhalb der Totzone: energetisch berechnete Stromkorrektur: Ladestrom 6 bis 16 A
  
  PV-Ueberschussladen AUS: 6 A und Ladefreigabe AUS
  
  Fahrzeugstatusaenderungen beeinflussen die Ladefreigabe nicht
  
  STOP-SOC wird nur protokolliert, wenn wirklich abgeschaltet wird

Anmerkungen:
Momentaufnahme Regelungen (egal wie komplex aufgebaut haben bei mir einfach nicht funktioniert. Wenn bei einer kleinen Wolke 500 Watt gefördert werden und dann 10 Sekunden später wieder 5000 Watt und immer wieder große Verbraucher wie Herde oder Warmwasserbereiter kurz laufen funktionieren sie einfach nicht oder regeln sich und die Wallbox und das Auto mit dauernden Änderungen und Ein/Aus Schaltungen zu Tode.
Eine sehr einfache Regelung (basierend auf diesem Ansatz: Alle 10 Minuten wird einfach nur die SOC Änderung des Hausakkus überprüft mit ein paar wenigen Tageszeit und Hausakkumindestladung Regeln) hat sich bei mir hingegen sehr bewährt.

Ich habe mich halt nur auf meinen begrenzten Anwendungsfall konzentriert:
6,5 kWp PV mit 10kwh Akku, Fronius WR mit Smartmeter und goecharger mit einphasigem Kabel da das für diese kleine PV genügt.
Ampere von 6 bis 16 und Laden Ein/Aus werden gesteuert.
