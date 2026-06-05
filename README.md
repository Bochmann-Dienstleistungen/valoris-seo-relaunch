# VALORIS – SEO-Relaunch (Staging)

Staging-/Preview-Version von **valoris-auftragsstruktur.de** mit umgesetzten SEO-Maßnahmen aus der Notion-Analyse von Philipp Hollmann.
**Die Live-Website wird hierdurch nicht verändert** — dies ist ein separates Repository zur Abnahme.

## Umgesetzte Maßnahmen (Stand 05.06.2026)

### M1 – Startseite auf „Webdesign Zwickau" ausgerichtet
- Title mit Hauptkeyword nach vorn, H1 enthält jetzt „Webdesign aus Zwickau"
- Intro + Zwischenüberschriften mit lokalem Bezug und semantischen Begriffen
- Meta-Description, Canonical, OpenGraph auf allen Seiten
- **LocalBusiness-Schema (JSON-LD)** neu auf der Startseite (Adresse, Geo, areaServed, Offer)

### M2 – Bilder & Ladezeit
- Alle Hero-/Inhaltsbilder von Pexels-Hotlink → **lokal als WebP** (`assets/img/`), ~40 % kleiner
- DSGVO-Fix: kein IP-Leak an Pexels mehr, Preconnect entfernt
- `width`/`height` + sprechende, lokale `alt`-Texte

### M3 – Content vor dem Preisbereich
- Neue Section „Für lokale Betriebe" (Problem/Hook, Zielgruppe, Nutzen, 4 Benefit-Karten) vor den Preisen

### M4 – Cluster → Seite + Wettbewerbslogik
- Pro Unterseite eigenes Cluster-Keyword im Title (preise = „Festpreis ohne Abo", leistungen = „Webdesign/Local SEO/Google Ads" usw.)
- Service-, AboutPage-, ContactPage-, FAQPage-Schema je Seite

### M5 – Ratgeberbereich
- Hub `ratgeber.html` mit Content-Kategorien
- 3 Cornerstone-Artikel (eigene Texte) mit Article- + BreadcrumbList-Schema:
  - Was kostet eine Website?
  - Bei Google gefunden werden (Local SEO)
  - Webdesign für Handwerker in Zwickau

### Weitere Maßnahmen
- **FAQ + FAQPage-Schema** auf Startseite, Preise, Leistungen, Kontakt (Fragen aus der Notion-Analyse)
- **Leistungs-Kacheln klickbar** und intern verlinkt (Money Pages)
- **Interne Verlinkung**: Ratgeber in Haupt-Nav + Footer aller Seiten, 2–4 Links/Artikel auf Money Pages
- **Socials/LinkedIn** auf „Über uns" (URLs noch zu bestätigen — siehe unten)
- **sitemap.xml** + **robots.txt**
- Paket-Dropdown im Kontaktformular an echte Pakete angeglichen (Starter/Premium/Individual)

## Noch offen / extern (nicht im Code umsetzbar)
- **Google-Unternehmensprofil** einrichten/optimieren (Local-SEO-Top-Hebel)
- **Backlinks**: Footer-Links bei Kunden (Gasthaus 1470, Scholz, Seiler, Goldhaus24, Renner, Lack Design, Minolo …) + trustlocal
- **LinkedIn/Instagram-URLs** auf „Über uns" sind Platzhalter → echte Profil-URLs einsetzen
- Wettbewerber-Detailanalyse (werbefranz, cm design) — Philipps leere Felder

## Hinweis
Canonical-Tags zeigen auf die Produktionsdomain `valoris-auftragsstruktur.de`, damit die Staging-Preview nicht mit der Live-Seite um Rankings konkurriert.
