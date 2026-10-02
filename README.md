# Webentwicklung & E-Commerce (WS 2026/27)

Die Lehrveranstaltung wird auf Deutsch abgehalten und ist als **Live-in-Progress-LV** aufgebaut: Inhalte, Beispiele und Projektanforderungen entwickeln sich entlang des tatsächlichen Fortschritts der Gruppe.

Diese README begleitet die Lehrveranstaltung als **Living Document**. Nach jeder Einheit wird festgehalten, was tatsächlich behandelt wurde, welche Zusammenhänge hergestellt wurden, welche Beispiele entstanden sind und welche nächsten Schritte daraus folgen.

Der Schwerpunkt liegt nicht darauf, möglichst viele Technologien isoliert kennenzulernen, sondern den Weg von einer einfachen lokalen Webseite bis zu einer öffentlich erreichbaren Webanwendung nachvollziehbar aufzubauen: **HTML → CSS → JavaScript → Browser → Live Server → Hosting → Domain/Subdomain → Upload → Deployment**.

## LV-Termine

| Datum | Zeit | Raum | Status | Wichtig |
|:------|:-----|:-----|:-------|:--------|
| 01.10.2026 | 13:00–17:05 | L-218 | Abgeschlossen | Einführung, Web-Grundlagen und erstes Deployment |
| 08.10.2026 | 13:00–17:05 | L-219 | Offen | Fortsetzung auf Basis von Einheit 01 |
| 22.10.2026 | 13:00–17:05 | – | Offen | Vertiefung und Weiterentwicklung der Projektarbeit |

Der Status wird nach jedem Termin aktualisiert. Die Beschreibung bildet dabei den **tatsächlich erreichten Stand** der Lehrveranstaltung ab und wird laufend ergänzt.

---

## Bisherige Inhalte

### Einheit 01 – 01.10.2026

**Status:** Abgeschlossen · **Schwerpunkt:** Vom lokalen HTML-Dokument zur ersten veröffentlichten Webseite

Die erste Einheit startete bewusst nicht mit einem fertigen Framework oder einem komplexen Projekt. Stattdessen wurde zunächst geklärt, **was eine Webseite technisch eigentlich ist**, welche Komponenten zusammenspielen und wie aus einigen lokalen Dateien eine öffentlich erreichbare Website wird.

| Thema | Behandelt | Stand und nächste Schritte |
|:------|:----------|:---------------------------|
| Organisation der Lehrveranstaltung | Ablauf, Arbeitsweise, Projektorientierung und dynamischer Aufbau der LV wurden besprochen. | Der organisatorische Rahmen steht; Inhalte und Projektumfang werden entlang des tatsächlichen Fortschritts weiterentwickelt. |
| Zusammenspiel von HTML, CSS und JavaScript | Die drei zentralen Bausteine klassischer Webentwicklung wurden voneinander abgegrenzt und in ihrem Zusammenspiel erklärt: HTML für Struktur/Inhalt, CSS für Darstellung und JavaScript für Verhalten/Interaktion. | Grundlagen sind gelegt; alle drei Bereiche werden in den nächsten Einheiten praktisch erweitert. |
| Grundbegriffe des Webs | Begriffe wie Website, Webseite, Browser, Webserver, Hosting, Domain, Subdomain, FTP, SFTP, CMS und WordPress wurden eingeordnet. | Die Begriffe werden nicht isoliert gelernt, sondern in den kommenden Deployments und CMS-Einheiten praktisch verwendet. |
| Hosting und Veröffentlichung | Es wurde gezeigt, warum lokale Dateien allein noch keine öffentliche Website sind und welche Rolle ein Webhoster übernimmt. | Der Weg lokal → Server → Browser wurde erstmals praktisch umgesetzt. |
| Domain und Subdomain | Aufbau und Zweck von Domains und Subdomains wurden besprochen. Eine Subdomain wurde als eigener Bereich für eine Website angelegt. | Subdomains dienen in der LV als klar abgegrenzte Veröffentlichungsbereiche für Projekte. |
| FTP und SFTP | Dateiübertragung zwischen lokalem Rechner und Webspace wurde erklärt; FTP und SFTP wurden funktional eingeordnet. | Upload und Aktualisierung von Webdateien werden im weiteren Verlauf regelmäßig verwendet. |
| Live Server | Live Server wurde als Entwicklungswerkzeug thematisiert: lokale Website über einen kleinen Entwicklungsserver öffnen, Änderungen schneller kontrollieren und typische Browser-/Pfadprobleme realistischer testen. | Wird als einfacher Workflow für lokale Entwicklung weiterverwendet. |
| Browser Developer Tools | Erste Begegnung mit den Browser-Entwicklertools: HTML-Struktur ansehen, CSS-Regeln prüfen und verstehen, was der Browser tatsächlich verarbeitet. | Die Developer Tools werden in späteren Einheiten für Fehlersuche, Layout und Responsiveness vertieft. |
| HTML-Basics | Eine minimale Seite mit Überschriften, Button, CSS-Verknüpfung und JavaScript-Verknüpfung wurde aufgebaut. | Die bestehende Seite wird schrittweise um semantische Elemente, Navigation, Formulare, Daten und dynamische Inhalte erweitert. |
| CSS-Basics | Erste Regeln für Hintergrund, Textfarbe, Schriftgröße und Schriftart wurden verwendet. | Selektoren, Box-Modell, Layout und Responsive Design folgen schrittweise. |
| Drei Arten der CSS-Einbindung | Inline-CSS, CSS innerhalb des HTML-Dokuments und eine externe globale CSS-Datei wurden gegenübergestellt. | Für wiederverwendbare und wartbare Projekte wird die externe CSS-Datei als Standard weitergeführt. |
| JavaScript-Basics | Ein HTML-Element wurde über seine ID angesprochen und ein Click-Event registriert. | DOM-Manipulation, Eingaben, dynamisches HTML und Datenverarbeitung folgen in den nächsten Einheiten. |
| Deployment einer Mini-Website | Eine rudimentäre Website aus HTML, CSS und JavaScript wurde lokal erstellt und anschließend auf den Webspace übertragen. | Das Grundmuster „entwickeln → lokal testen → hochladen → öffentlich prüfen“ ist damit erstmals vollständig durchlaufen. |
| Kundenanforderung vs. technische Umsetzung | An einfachen Fallbeispielen wurde erläutert, dass eine fachliche Anforderung nicht automatisch eine konkrete technische Implementierung vorgibt. | Anforderungen sollen künftig bewusst in Struktur, Design, Verhalten und Testfälle übersetzt werden. |
| AI Coding und Best Practices | KI-gestützte Codeerzeugung wurde parallel zur manuellen Umsetzung eingeordnet. Entscheidend bleibt, erzeugten Code zu verstehen, prüfen, anpassen und testen zu können. | KI kann als Assistent verwendet werden; Struktur, Nachvollziehbarkeit und eigene Lernleistung bleiben Teil der Projektarbeit. |
| Barrierefreiheit | Kurzer Exkurs zu Accessibility: Webseiten sollen nicht nur optisch funktionieren, sondern grundsätzlich auch für unterschiedliche Nutzergruppen zugänglich sein. | Accessibility wird später bei Struktur, Responsiveness und Testing erneut aufgegriffen. |
| Projektarbeit | Anspruch, Grundidee und Arbeitsweise der Projektleistung wurden vorgestellt. Die Projekte wachsen mit dem Lernfortschritt. | Umfang und Komplexität werden an den tatsächlich behandelten Stoff angepasst. |
| Zusammenspiel mit Co-Lektor Rudolf Grötz | Die Rolle des späteren Testing-Schwerpunkts und das Zusammenspiel zwischen Entwicklung und Qualitätssicherung wurden angekündigt. | Die in den Entwicklungsblöcken entstehenden Projekte bilden später die Grundlage für systematisches Testen. |

### Die Story der ersten Einheit

Zu Beginn stand eine einfache Frage: **Was braucht es eigentlich, damit etwas, das wir lokal programmieren, im Web sichtbar wird?**

Daraus entstand Schritt für Schritt die technische Kette:

**HTML** liefert den Inhalt und die Struktur → **CSS** gestaltet diese Struktur → **JavaScript** ergänzt Verhalten → der **Browser** interpretiert die Dateien → ein **Live Server** unterstützt die lokale Entwicklung → ein **Webhoster** stellt Speicher und Server bereit → über **FTP/SFTP** gelangen die Dateien auf den Webspace → eine **Domain bzw. Subdomain** macht die Seite erreichbar.

Damit wurden viele Begriffe nicht nur theoretisch erklärt, sondern unmittelbar miteinander verbunden.

### Praktisches Beispiel aus der Einheit

Die erste Mini-Website besteht bewusst nur aus wenigen Dateien:

```text
projekt/
├── index.html
├── zweiteSeite.html
├── design.css
└── main.js
```

`index.html` bindet die globale CSS-Datei `design.css` ein, enthält mehrere HTML-Elemente sowie einen Button mit der ID `click` und lädt am Ende `main.js`.

`main.js` greift den Button über `document.getElementById("click")` ab und registriert einen Click-Handler. Beim Klick wird eine einfache Meldung ausgegeben.

`design.css` verändert unter anderem Hintergrundfarbe und Darstellung der `h1`-Überschriften. Damit wurde sichtbar, dass **Inhalt, Gestaltung und Verhalten in getrennten Dateien organisiert werden können**.

Eine zweite HTML-Seite zeigte zusätzlich, dass mehrere Seiten dieselbe globale CSS-Datei verwenden können. Gleichzeitig wurde Bootstrap über ein CDN eingebunden und damit erstmals angedeutet, dass externe Webressourcen und Bibliotheken später zusätzliche Möglichkeiten eröffnen können.

### Warum drei Arten von CSS gezeigt wurden

Die drei Varianten wurden nicht nur syntaktisch gezeigt, sondern anhand ihrer praktischen Auswirkungen eingeordnet:

- **Inline-CSS:** schnell für einen einzelnen Sonderfall, aber schlecht wartbar und kaum wiederverwendbar.
- **CSS im HTML-Dokument:** für kleine Einzelbeispiele übersichtlich, bei größeren Projekten aber schnell unpraktisch.
- **Externe CSS-Datei:** zentral, wiederverwendbar und für mehrere Seiten geeignet – daher der bevorzugte Weg für die weitere Projektarbeit.

Die zentrale Idee dahinter: **Eine Kundenanforderung kann kurzfristig mit vielen technischen Wegen erfüllt werden – Best Practice entscheidet darüber, welche Lösung langfristig verständlich, wartbar und erweiterbar bleibt.**

### Minimale Abfolge der ersten Einheit

Organisation und Projektidee klären → HTML, CSS und JavaScript als drei Grundbausteine einordnen → lokale Mini-Webseite erstellen → CSS und JavaScript auslagern → Live Server verwenden → Browser Developer Tools kennenlernen → Hosting, Domain und Subdomain erklären → Dateien per FTP/SFTP auf den Webspace übertragen → veröffentlichte Seite im Browser prüfen → technische Umsetzung mit Best Practices und AI Coding reflektieren.

### Was aus Einheit 01 bereits mitgenommen werden sollte

Nach der ersten Einheit sollte nachvollziehbar sein,

- warum eine Website aus mehreren technischen Ebenen besteht,
- welche Aufgabe HTML, CSS und JavaScript jeweils übernehmen,
- warum lokale Dateien und öffentliches Hosting zwei unterschiedliche Dinge sind,
- was Domain, Subdomain, Hosting, FTP/SFTP und CMS grundsätzlich bedeuten,
- wie eine minimale Website lokal getestet und anschließend veröffentlicht werden kann,
- warum eine zentrale CSS-Datei gegenüber vielen Einzeldefinitionen Vorteile hat,
- wie Browser Developer Tools bei der Fehlersuche helfen,
- und warum auch bei AI-generiertem Code Verständnis, Prüfung und Test unverzichtbar bleiben.

---

## Nächster Stand

### Einheit 02 – 08.10.2026

**Status:** Offen

Die nächste Einheit setzt direkt auf dem bestehenden Mini-Projekt auf. Neue Inhalte werden nicht als isolierte Beispiele begonnen, sondern möglichst in die bestehende Struktur integriert. Dadurch soll sichtbar werden, wie aus einem sehr kleinen Ausgangspunkt schrittweise eine vollständigere Website entsteht.

*Dieser Abschnitt wird nach der Einheit mit dem tatsächlich behandelten Stand ergänzt.*

### Einheit 03 – 22.10.2026

**Status:** Offen

Die dritte Einheit führt die bisherige Entwicklung weiter und richtet den Blick zunehmend auf den Projektcharakter der Lehrveranstaltung sowie die Vorbereitung jener Artefakte, die später auch für den Testing-Block mit Rudolf Grötz relevant werden.

*Dieser Abschnitt wird nach der Einheit mit dem tatsächlich behandelten Stand ergänzt.*

---

## Grundidee der Lehrveranstaltung

Die Lehrveranstaltung folgt keinem starren „Feature-Katalog“. Der Inhalt wächst entlang eines realistischen Entwicklungsprozesses:

**verstehen → klein umsetzen → lokal testen → Fehler analysieren → veröffentlichen → erweitern → prüfen → verbessern**

Der Umfang der Projektarbeit orientiert sich daher am tatsächlich erreichten Lernstand. Zusätzliche Funktionen sind willkommen, sollen aber nicht auf Kosten von Verständnis, sauberer Struktur und nachvollziehbarer Umsetzung entstehen.

Diese README dokumentiert diesen Weg fortlaufend.
