ADHSync — Website (adhsync.de)
==============================

Seiten:
  index.html         — Startseite (ruhiges, editoriales Design)
  datenschutz.html   — Datenschutzerklärung (DSGVO-Vorlage)
  impressum.html     — Impressum (§5 DDG-Vorlage)
  fachpersonen.html  — Für Ärzt:innen/Therapeut:innen/Kliniken (Sie-Ansprache)

DSGVO-Konformität der Website selbst:
  - Schriften sind LOKAL eingebettet (kein Google-Fonts-Aufruf, keine IP-Übertragung an Dritte).
  - Kein Tracking, keine Analyse, keine Marketing-Cookies, kein localStorage.
  - Die HTML-Dateien sind eigenständig und machen KEINE externen Requests.

Optional schlankere Variante:
  Wer kleinere HTML-Dateien möchte, kann die eingebetteten Fonts entfernen
  und stattdessen die mitgelieferte fonts.css + den /fonts-Ordner einbinden:
      <link rel="stylesheet" href="fonts.css">

NOCH ZU TUN vor dem Livegang:
  [ ] Alle orange markierten Platzhalterfelder in datenschutz.html & impressum.html ausfüllen
  [ ] Echten App-Store-Link einsetzen (im Code: data-appstore="1")
  [ ] Datenschutz/Impressum rechtlich prüfen lassen (kein Ersatz für Rechtsberatung)
  [ ] Weitere App-Screenshots ergänzen (aktuell 1 Device im Hero)
