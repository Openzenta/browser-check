# Browser-Check (lokal & datenschutzfreundlich)

🔗 **Live-Version:**  
https://sicherheits-tools.de/werkzeuge/browser-check/

## Kurzbeschreibung
Der Browser-Check führt eine lokale Analyse deines Browsers durch
um grundlegende Datenschutz- und Sicherheitsmerkmale sichtbar zu machen.
Die Ausführung erfolgt vollständig clientseitig im Browser.

## Technische Funktionsweise
- Clientseitige Ausführung (JavaScript im Browser)
- Keine Netzwerk-Requests
- Keine Datenübertragung an Server
- Nutzung von Browser-APIs zur Informationssammlung
- Einfache, verständliche Ergebnisse ohne Tracking

## Datenschutz
- Keine Speicherung von Daten
- Kein Tracking
- Keine Analyse-Tools
- Keine Verbindung zu externen Servern

## Hinweise für Entwickler
Die Funktionsweise kann direkt über die Browser-Entwicklertools
überprüft werden (Netzwerk-Tab bleibt leer).

## Quellcode & Offenlegung

Der vollständige produktive Quellcode dieses Tools ist bewusst
nicht öffentlich verfügbar.

**Gründe:**
- Schutz vor ungeprüfter Weiterverbreitung
- Vermeidung manipulierte Kopien
- Sicherstellung, dass Nutzer stets die Originalversion verwenden

Die technische Funktionsweise ist oben beschrieben und
klar clientseitig überprüfbar.

## Beispiel (vereinfachtes Prinzip)

```js
// Clientseitige Feature-Abfrage (Beispiel)
const isSecureContext = window.isSecureContext;
console.log(isSecureContext);
```

## Rechtlicher Hinweis

© 2026 [sicherheits-tools.de](https://sicherheits-tools.de)  
Alle Rechte vorbehalten.

Dieses Repository dient ausschließlich der technischen
Dokumentation und Referenz.
