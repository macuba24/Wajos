# Kundenapp Wajos

Eine Seite für das Handy. Name, Kundenkode, Buchung, Foto und Nachricht bleiben auf diesem Gerät.

## Start

Im Ordner `D:\Einzelhandel App\Wajos`:

```
python -m http.server 8773
```

Dann im Browser `http://127.0.0.1:8773/` öffnen.

Die SQLite-Fassung (älterer Stand der Blaupause, Ordner `static/`) startet mit:

```
python server.py
```

Sie lauscht auf `http://127.0.0.1:8765/`. Dafür braucht es keine Zusatzpakete.

## Am Handy

Die Adresse in Chrome öffnen und zum Startbildschirm hinzufügen. Kunde und Kasse liegen auf demselben Handy.

## Kontakt laut Website

Wajos Feinkost Koblenz, Löhr Center, Hohenfelder Str. 22, 56068 Koblenz. Telefon 49 261 2935646, E-Mail koblenz@wajos.de, Website https://koblenz.wajos.de/

Öffnungszeiten im Kontaktblock der Website: Mo - Sa: 10:00 - 19:00, So: Geschlossen.

Sortiment laut Website: Essig, Öl, Kräuter & Gewürzmischungen, Senf & Saucen, Pralinen, Schokolade, Liköre & Spirituosen, Whisky, Rum, Grappa, Brände, Geschenksets, Präsentkörbe.

Die Vorteilssätze (1/2/3/5 Prozent) sind die Kartenlogik dieser App und keine Preise der Website. An der Kasse lassen sie sich ändern.
