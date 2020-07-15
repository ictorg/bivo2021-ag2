# Verteilte Systeme

## Kompetenz
Client-Server-Konzepte verstehen, planen oder erweitern und applikatorisch anwenden. Monolitische (Silo-)Applikationen in ein verteiltes System aufteilen. Bestehende verteilte Systeme analysieren, ergänzen und weiterentwickeln. 

Zweiter Vorschlag:
Verwendung und Entwicklung von verteilten Softwarekomponenten für voneinander entfernte Rechnerressourcen.

## Handlungsziele und handlungsnotwendige Kenntnisse
1. Komponenten von Datenübertragungssystemen
   1. Kennt die Gründe für Rechnerverbünde (z.B. Lasten-, Betriebsmittel-, Daten-, Software-, Kommunikationsverbund)
   1. Kennt Vertreter der Netzwerktopologien (Bus, Stern, Netz, Peer-to-peer, Client-Server) .
      /* Kommentar H.Mü 15.7.2020: --> kann man voraussetzen aus Modul M117, müsste im Unterricht sicher wiederholt/aufgefrischt werden  ==> evtl. streichen ? */
   1. Kennt übersichtsmässig die drahtgebundenen und drahtlosen Übertragungstechniken (z.B. CSMA/CD, Ethernet, Bus, Tokenring/-bus, ISDN, ADSL, ATM, PowerLine, Infrarot, Bluetooth, WLAN, UMTS, GPRS, LTE) und deren Austauschbarkeit aus Sicht von Anwendung und Applikationen.
      /* Kommentar H.Mü 15.7.2020: --> kann man voraussetzen aus Modul M117, müsste im Unterricht sicher wiederholt/aufgefrischt werden  ==> evtl. streichen ? */
   1. Kennt übersichtsmässig die grundsätzliche Funktionsweise von Netzen und ihren Subnetzen, Gateways, Routers sowie das Adresssystem (IP-Adressen) und die Adressierungsarten (z.B. URI, URL sowie DNS) im Internet.
   1. Kennt Protokolle aktueller Datenübertragungsarten (z.B. http, smtp, imap, pop3, ftp, telnet/ssh) und kennt genauer das HTTProtokoll samt dessen Methoden (z.B. GET, POST, PUT, DELETE, ..) und Statuscode(-gruppen).
   1. Kennt Schichten und Modelle (OSI-7-Schichtenmodell, TCP/IP-Architektur), insbesondere der Anwendungsschicht im Hinblick auf die Nutzung für die Softwareentwicklung (Client-Server). 
      /* Kommentar H.Mü 15.7.2020: --> kann man voraussetzen aus Modul M117, müsste im Unterricht sicher wiederholt/aufgefrischt werden  ==> evtl. streichen ? */
   1. Kennt die Softwareverteilungs- und Mehrschichtenkonzepte für die Datenhaltung, die Anwendung und die Darstellung (DB-Layer, Business-Layer, Presentation-Layer).
1. Anwendung von Webtechnologien, -diensten und -sprachen und die Implementierung von Systemkomponenten in einem verteilten System.
   1. Kennt die Verbindungsarten um einzelne Systemteile über wohl definierte Schnittstellen zusammenzuschliessen.
   1. Kennt Hilfsmittel zum serialisieren und de-serialisieren von auszutauschenden Daten innerhalb und ausserhalb einer Applikationskomponente (z.B. Session-Handling, protobuf, ...)
   1. Kennt die gängigen Sprachen für zur Datenübertragung für Applikationen (z.B. HTML, XML, JSON)
   1. Kennt die gängigen Nutzungsarten von entfernten Ressourcen (z.B. Webservices, SOAP, RMI, CGI) und die Architekturen (z.B. REST, RESTful, GraphQL).
   1. Kennt die Implementation von Dienstaufrufen als Client(-Komponente).
      /* Kommentar H.Mü 15.7.2020: 
      Vorbereitung/Übergang zu ÜK-Pflicht-Modul "Webentwicklung Frontend"
      Vorbereitung/Übergang zu BFS-Modul M120 "Benutzerschnittstellen implementieren" */
   1. Kennt die Implementation von Dienstanbietung als Server(-Komponente).
      /* Kommentar H.Mü 15.7.2020: 
      Vorbereitung/Übergang in ÜK-Pflicht-Modul "Webentwicklung Backend" 
      Vorbereitung/Übergang zu BFS-Modul M120 "Benutzerschnittstellen implementieren" */
   1. Kennt Möglichkeiten, eigene Systemkomponenten an bestehende Systemkomponenten anzubinden.
   1. Kennt unterschiedliche Methoden zur Skalierung von verteilten Systemkomponenten.
   1. Kennt das Bedürfnis von Sicherheitsmechanismen für Authentifizierung und Autorisierung.
      /* Kommentar H.Mü 15.7.2020: 
      Vorbereitung/Übergang in BFS-Modul M183 "Applikationssicherheit implementieren" --> Umsetzung dann dort */
1. Analysieren von unterschiedlich strukturierten Softwaresysteme und überführen in verteilte Systeme.
   /* Kommentar H.Mü 15.7.2020: Geht wohl zu weit für das 2. Lehrjahr). Ist eher etwas für HF oder FH  --> Antrag: streichen*/
   1. Kennt Vorgehensweisen um Softwaresysteme zu migrieren (z. B. Strangler, Big Bang, ...)
   1. Kennt Methoden, um die Fehler bei der Überführung zu vermeiden (z. B. automatisiertes Testen, ...).
1. Publizieren von verteilten Systemkomponenten und Funktionsüberwachung.
   /* Kommentar H.Mü 15.7.2020: 
   Geht wohl zu weit für "Applikationsentwickler" im 2. Lehrjahr). Ist eher etwas für Systemtechniker HF oder FH --> Antrag: streichen */
   1. Kennt Werkzeuge um einzelne Systemteile in einem verteilten System verfügbar zu machen.
   1. Kennt Systemkomponenten zur Identitätsverwaltung (z. B. LDAP, KeyCloak), zum Verwalten von Ereignissen (z. B. LogStash, ...)
   1. Kennt Mittel um eigene Systemteile zu dokumentieren.
   1. Kennt Möglichkeiten, den unterbruchsfreien Betrieb zu überwachen. (z. B. Prometheus, ...).  

## Kompetenzfeld
Applikationsentwicklung

## Objekt
Entwickeln von Systemkomponenten in verteilten (Client-Server-)Systemen.

## Niveau
3

## Voraussetzungen
M117 "Grundlagen Netzinfrastruktur" , Mxxx "Einstieg in Webentwicklung")

M120, M183, Grundlagen Cloud und Services ,...
/* Kommentar H.Mü 15.7.2020:   --> Antrag: streichen*/

## Anzahl Lektionen
40

## Anerkennung
Eidg. Fähigkeitszeugnis
