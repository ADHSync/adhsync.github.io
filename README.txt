ADHSync — Website (adhsync.com)
==============================

Seiten:
  index.html         — Startseite (ruhiges, editoriales Design)
  datenschutz.html   — Datenschutzerklärung (DSGVO)
  impressum.html     — Impressum (§ 5 DDG)
  fachpersonen.html  — Für Ärzt:innen/Therapeut:innen/Kliniken (Sie-Ansprache)

DSGVO-Konformität der Website selbst:
  - Schriften sind LOKAL eingebettet (kein Google-Fonts-Aufruf, keine IP-Übertragung an Dritte).
  - Kein Tracking, keine Analyse, keine Marketing-Cookies, kein localStorage.
  - Die HTML-Dateien sind eigenständig und machen beim Seitenaufruf KEINE externen Requests.
  - Externe Links (z. B. Apple App Store) werden erst nach Nutzerinteraktion geöffnet.

Aktueller Stand:
  [x] Domain und Canonicals auf adhsync.com vereinheitlicht
  [x] Kontaktadresse vereinheitlicht und im HTML gegen einfache Spam-Bots verschleiert
  [x] Impressum finalisiert und Platzhalter entfernt
  [x] Navigation über alle Seiten konsistent aufgebaut
  [x] App-Store-Link eingesetzt (im Code: data-appstore="1")
  [x] SEO-Basics ergänzt: Canonical, Open Graph, Twitter Card, Robots, App-Name

Optional schlankere Variante:
  Wer kleinere HTML-Dateien möchte, kann die eingebetteten Fonts entfernen
  und stattdessen die mitgelieferte fonts.css + den /fonts-Ordner einbinden:
      <link rel="stylesheet" href="fonts.css">

NOCH ZU TUN vor dem Livegang:
  [ ] Datenschutz/Impressum rechtlich prüfen lassen (kein Ersatz für Rechtsberatung)
  [ ] GitHub-Pages-Custom-Domain adhsync.com, DNS und SSL nach Livegang prüfen
  [ ] Optional ein eigenes Social-Preview-Bild für Open Graph/Twitter ergänzen
  [ ] Weitere App-Screenshots ergänzen (aktuell 1 Device im Hero)
