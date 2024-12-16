# Netzwerk & Linux Grundlagen Zusammenfassung

## VPC und Subnet
Ein Virtual Private Cloud (VPC) ist ein isoliertes virtuelles Netzwerk innerhalb der Cloud. Subnets sind Unterteilungen dieses VPCs in kleinere Netzwerksegmente, die zur besseren Organisation und Sicherheit dienen. Dies ermöglicht eine logische Trennung von Ressourcen.

## IP-Adressen
- **Private IPs**: Nur innerhalb eines Netzwerks gültig (z.B. 192.168.1.x, 10.0.x.x)
- **Öffentliche IPs**: Weltweit eindeutige Adressen für Kommunikation über das Internet
- **Statische IPs**: Fest zugewiesene Adressen die sich nicht ändern, wichtig für konstante Erreichbarkeit von Diensten

## Ports
Ports sind numerische Identifikatoren (0-65535), die verschiedene Dienste auf einem System unterscheiden. Beispielsweise nutzt HTTP Port 80, HTTPS Port 443 und SSH Port 22. Dies ermöglicht mehrere gleichzeitige Verbindungen zu unterschiedlichen Services auf einem System.

## Sicherheitsgruppen/Firewall
Sicherheitsgruppen fungieren als virtuelle Firewall für Cloud-Ressourcen. Sie kontrollieren ein- und ausgehenden Netzwerkverkehr durch Regeln, die definieren:
- Erlaubte IP-Adressen/Bereiche
- Zugelassene Ports
- Protokolle (TCP/UDP)
- Richtung des Verkehrs (Inbound/Outbound)

## Der sed-Befehl
`sed` (Stream Editor) ist ein mächtiges Werkzeug zur Textmanipulation in Linux. Haupteinsatzgebiet ist das Suchen und Ersetzen von Text. Grundlegende Syntax:
```bash
sed 's/alter_text/neuer_text/g' dateiname
```
Der Befehl unterstützt reguläre Ausdrücke und kann Änderungen direkt in Dateien vornehmen mit der Option `-i`.
