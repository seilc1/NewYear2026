# Agent.MD - Kontext und allgemeine Hinweise

Diese Datei liefert Kontext und allgemeine Hinweise fuer die Arbeit im Repository `Sylvester.RolePlay`.

## Repository-Ueberblick
Dieses Repository enthaelt das Projekt `Sylvester.RolePlay`, das eine Storytelling-Erfahrung fuer eine Rollenspiel-Session an Silvester (31.12.2026) unterstuetzt. Waehren das Projekt weiterentwickelt wird, sollten hier konkrete Richtlinien und Best Practices dokumentiert werden.

## Sitzungsdetails
- **Datum:** 31.12.2026 (Silvester / New Year's Eve)
- **Setting:** Kriminalfall in der realen Stadt Bern, Schweiz
- **Spieler:** 1 Spielleitung (du) + 4 weitere Spieler
- **Ort:** Authentische Orte in Bern, Schweiz sollen in die Handlung eingebaut werden

## Kreative Ausrichtung
- Die gesamte Rollenspiel-Session soll eine direkte Parodie auf `Police Academy` sein
- Das Abenteuer soll chaotischen Ensemble-Humor, ueberzeichnete Polizeipersoenlichkeiten, absurde Autoritaetsstrukturen und komische Kriminalermittlung nutzen
- Szenen sollen Mystery-Fortschritt mit Missverstaendnissen, Running Gags, Slapstick-Eskalation und oeffentlichem Chaos verbinden

## Hinweise zur NPC-Benennung
- Verwende fuer NPCs, die von `Police Academy` inspiriert sind, sehr offensichtliche Parodienamen oder direkte Wiedererkennung
- Bevorzuge laute, einpraegsame Namen und Rollen wie strenge Kommandanten, schrullige Beamte, chaotische Rekruten, exzentrische Spezialisten und laecherliche Verdaechtige
- Beispielstil fuer Namen: `Mahoni`, `Lasserd`, `Tekkelberry`, `Heitauer`, `Hux`, `Hooks`, `Callahan`, `Jonz`
- Passe Parodie-NPCs bei Bedarf an das Berner Setting an, halte sie aber klar wiedererkennbar

## Story-Regeln
- Reales Bern, Schweiz bleibt die Grundlage fuer Geografie, Wahrzeichen und Szenenorte
- Nutze reale Orte in Bern als Hintergrund fuer Ermittlungen, Befragungen, Verfolgungen, Polizeipannen und komische Set Pieces
- Kriminalaufklaerung bleibt die Kernstruktur der Session, auch wenn die Szenen absurd und komisch werden

## Regeln zur Aktstruktur
- Die Rollenspiel-Session soll ueber 4 Akte aufgebaut sein
- Akt 4 ist immer das finale Showdown-Kapitel, in dem die Gruppe `The Mercenary` am eigentlichen Tatort gegenuebersteht
- In Akt 1 bis 3 sammelt die Gruppe Informationen ueber `The Mercenary`, um herauszufinden, welches Verbrechen er wirklich plant
- In jedem der Akte 1 bis 3 soll `The Mercenary` einen bestimmten Aspekt des Verbrechens vorbereiten, etwa Aufklaerung, Beschaffung von Werkzeugen, Rekrutierung von Helfern, Sicherung von Zugang oder die Vorbereitung eines noetigen Vorfalls
- Die Vorbereitungen in Akt 1 bis 3 sollen sich mit mehreren Verbrechensoptionen ueberschneiden, damit die Beweislage bis spaet mehrdeutig bleibt
- Erst nach Akt 3 soll die Gruppe sicher bestimmen koennen, welches konkrete Verbrechen `The Mercenary` plant
- Jede Verbrechensoption soll daher aehnliche Vorbereitungselemente teilen, aber in ein eigenes Ziel und einen eigenen Showdown-Ort muenden

## Kanonisches Opening-Setup
- Die Session beginnt um 07:00 Uhr am 31.12.2026 in einem Besprechungsraum des Hauptpolizeigebaeudes in Bern
- Die vier Spielercharaktere wurden per Notfall-Pager zusammengerufen und kennen sich persoenlich nicht, obwohl sie alle zur selben Polizeibehoerde gehoeren, aber aus unterschiedlichen Abteilungen stammen
- Sie sind das improvisierte `B team` der Behoerde: junge Beamte aus verschiedenen Abteilungen, weil die kompetenten Einheiten bereits ausgelastet sind
- Die Spielercharakter-Vorlagen sollen jeweils eine praktische Ermittlungsstaerke mitbringen, die in mehreren Verbrechensvarianten nuetzlich sein kann
- Eric Lassard liefert die froehliche und unfaehige Eroeffnungsansprache, bevor er die praktischen Details an Thaddeus Harris uebergibt
- Thaddeus Harris informiert die Gruppe darueber, dass der beruechtigte Verbrecher `The Mercenary` die Stadt betreten hat und wahrscheinlich bald zuschlagen wird
- Ein grosses Konzert und ein laufender Polizeieinsatz haben die kompetenten Beamten gebunden, sodass die Spielercharaktere das einzige verfuegbare Team sind
- Der erste Auftrag lautet, das Ziel von `The Mercenary` zu identifizieren, ihn an der Durchfuehrung zu hindern und ihn in Gewahrsam zu bringen

## Hinweise zur Einleitung
- Behandle die vom Nutzer gelieferte Intro-Szene als Grundversion des Eröffnungsbriefings
- Spaetere Szenen, Hinweise, NPC-Reaktionen und eskalierende Vorfaelle sollen sich natuerlich aus diesem Briefing entwickeln
- Bewahre den Kontrast zwischen Lassards froehlicher Inkompetenz und Harris' feindseligem Pragmatismus
- Halte den Eröffnungsdruck auf Silvesterlogistik, das grosse Konzert und die Gefahr unmittelbaren oeffentlichen Chaos zentriert

## Allgemeine Richtlinien
- Halte dich an konsistente Coding-Stile und Konventionen
- Schreibe klare, aussagekraeftige Commit-Messages
- Halte Funktionen fokussiert und mit klarer Verantwortung
- Schreibe Tests fuer neue Funktionalitaet
- Dokumentiere oeffentliche APIs und komplexe Logik
- Organisiere Vorbereitungsmaterial in eigenen Ordnern fuer `Characters`, `Locations` und `Story Elements`
- Speichere alternative Hauptverbrechensoptionen fuer `The Mercenary` in `Crimes/`

## Repository-Struktur
- `Characters/` fuer Spielercharaktere, NPCs, Verdaechtige und Nebenrollen
- `Locations/` fuer reale Orte in Bern, Schweiz, die in der Session vorkommen
- `Story Elements/` fuer Hinweise, Zeitablaeufe, Szenen, Ereignisse und Mystery-Struktur
- `Crimes/` fuer waehlbare Verbrechensoptionen in der Berner Altstadt und Plotvarianten

## Hinweis
**Diese Datei `Agent.MD` sollte erweitert werden, sobald neue Regeln, Tipps oder Best Practices fuer die Arbeit in diesem Repository definiert werden.** Regelmaessige Aktualisierung stellt sicher, dass alle Beteiligten Zugang zu den neuesten Richtlinien haben.
