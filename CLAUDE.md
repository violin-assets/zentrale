# Anleitung für Claude: Zentrale VA & IF

Dieses Repository ist der gemeinsame Rahmen für alles, was Carolina Maggiore mit Claude für **VIOLIN ASSETS (VA)** und die **INSTRUMENTUM Foundation (IF)** aufbaut. Lies diese Datei zu Beginn jeder Session. Sie enthält nur Zusammenhang und Verweise, keine vertraulichen Inhalte und keine Gestaltungsregeln einer Organisation.

## Wer ist wer

| | VIOLIN ASSETS (VA) | INSTRUMENTUM Foundation (IF) |
|---|---|---|
| Rechtsform | GmbH | gemeinnützige GmbH (gGmbH) |
| Thema | Investitionen in Streichinstrumente, außerdem Mäzenatentum (eigener Menüpunkt auf der neuen Website) | Fundraising und Spenden, Leihgabe von Instrumenten über Mäzenatentum an begabte Musikerinnen und Musiker („Instrumenten-Stipendium“) |
| Gegründet | 2014 | 2024 |
| Gründung | Christian Reister und Jost Thöne | Christian Reister (Geschäftsführer) und Laura Zarina (Mitgründerin, künstlerische Leiterin) |
| Adresse | Opernplatz 14, 60313 Frankfurt am Main | Opernplatz 14, 60313 Frankfurt am Main |
| Register | noch offen | HRB 123336, Amtsgericht Frankfurt am Main |
| Website | violin-assets.com (Relaunch läuft) | instrumentum.org (WordPress mit WPBakery) |

- **Carolina Maggiore** baut und pflegt alles mit Claude. Sie ist derzeit die einzige Person mit Zugriff. Später können ein bis zwei Mitarbeitende dazukommen, die Zugriff auf alles bekommen sollen. Deshalb alles so bauen, dass Zugriff einfach erteilt und entzogen werden kann.
- **Christian Reister** ist Gründer beider Organisationen.

## Feste Regeln

1. **Jost Thöne wird nirgends genannt.** In keinem Text, keinem Material und auch nicht auf der neuen VA-Website, auch wenn ältere Quellen ihn erwähnen.
2. **VA und IF strikt trennen:** eigene Gestaltung, eigene Logos, eigene Absenderzeilen. Keine Investment- oder Renditesprache bei der IF.
3. Markennamen immer in Großbuchstaben: **VIOLIN ASSETS**, **INSTRUMENTUM**.
4. **Keine erfundenen Zahlen, Personen oder Zitate.** Für VA sind vorerst freigegeben: 5–8 % p. a. seit 1907 (Albert Fuchs) und die Einstiegsgrößen 30.000 € und 100.000 €. Renditeangaben gegenüber US-Investoren vorher rechtlich prüfen lassen.
5. Schloss Bedburg wird für VA nicht mehr verwendet.
6. Unterschriebene Verträge und Unterlagen mit personenbezogenen Daten gehören nicht auf GitHub. Hier liegen nur Vorlagen und Entwürfe.
7. Schriften auf echten Websites lokal einbinden, nicht von Google-Servern laden (DSGVO).

## Wo was liegt

**Notion (nur Text, keine Dateien):**
- VA & IF Zentrale: https://app.notion.com/p/413ccc607da481848788fe528c83df3c (Überblick, Ablage, Systemübersicht, Entscheidungsprotokoll)
- Alle Aufgaben an einem Ort: ToDos IF / VA: https://app.notion.com/p/200ccc607da480dd815ed3669cb3977d
- Neue Stichpunkte von Carolina kommen als Aufgaben in diese Liste (Bereich, Art und Projekt ausfüllen). Nie Einträge löschen. Beim Kürzen eines Titels den Originaltext als Notiz in der Aufgabe behalten.

**GitHub:**
- `violin-assets/zentrale`: dieses Repository
- `violin-assets/va-dokumente`: Vorlagen, Entwürfe, Konzepte und CI von VA, dort auch das Design System als Skill `violin-assets-design`
- `instrumentum-foundation/if-dokumente`: dasselbe für die IF, dort auch das Design System als Skill `instrumentum-design`
- `violin-assets/violin-assets-website`: Relaunch der VA-Website
- Für CRM, ERP und Newsletter-Tool kommt je ein eigenes Repository in die Organisation, der es gehört.

**Gestaltung:** Für Design-Aufgaben das Dokumente-Repository der jeweiligen Organisation zur Session hinzunehmen, damit sein Design System geladen wird. Die Design Systems werden erst nach Carolinas Freigabe eingespielt (Prüfliste in der Zentrale).

## Zusammenarbeit mit Carolina

- Antworten auf Deutsch, ohne Emojis und ohne Höflichkeitsfloskeln. Absätze, Überschriften und Listen, wo es hilft.
- **Fragen immer als Pop-up** (Werkzeug AskUserQuestion) stellen, nie nur im Fließtext. Lieber nachfragen als raten.
- Technische Entscheidungen trifft Claude selbst, begründet sie kurz und trägt sie ins Entscheidungsprotokoll der Zentrale ein.
- Wenn Carolina selbst etwas einrichten muss: Schritt-für-Schritt-Anleitung mit genauen Klickwegen.
- Carolina diktiert oft. Erkennungsfehler sind möglich (zum Beispiel „While in Assets“ für Violin Assets). Bei unklaren Begriffen nachfragen.
- Notion-Memory enthält weitere Einträge zu Personen und Vorlieben (Notion-Werkzeug fetch mit id "memory").
