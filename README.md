Link https://playground.wordpress.net/?zip=https://github.com/elbsegler63/TT5-Child/

<img src="https://r2cdn.perplexity.ai/pplx-full-logo-primary-dark%402x.png" class="logo" width="120"/>

## Anleitung: WordPress Playground-Export in GitHub speichern und Link zum Öffnen erzeugen

**1. Export aus WordPress Playground als ZIP-Datei**

- Öffne deine WordPress Playground-Instanz.
- Klicke oben links auf das kleine Quadrat-Symbol.
- Gehe im Menü auf das Drei-Punkte-Menü neben „Homepage“.
- Wähle „Herunterladen als .zip“ – die ZIP-Datei wird auf deinen Computer geladen[^1].

**2. ZIP-Datei zu GitHub hochladen**

- Erstelle ein neues Repository auf GitHub (z.B. „mein-playground-export“)[^5].
- Klone das Repository auf deinen Computer oder öffne es im Browser.
- Lade die ZIP-Datei in das Repository hoch (per Drag \& Drop oder über „Add file“ → „Upload files“)[^5].
- Führe einen Commit durch, um die Datei zu speichern.

**3. Link zum Öffnen in WordPress Playground erzeugen**

- Kopiere den direkten Link zur ZIP-Datei im GitHub-Repository (Rechtsklick auf die Datei → „Link kopieren“).
- Um den Playground mit deiner ZIP zu starten, verwende folgende URL-Struktur:

```
https://playground.wordpress.net/?zip=https://github.com/USERNAME/REPOSITORY/raw/main/DATEINAME.zip
```

Ersetze `USERNAME`, `REPOSITORY` und `DATEINAME.zip` entsprechend[^2].

**4. Beispiel-Link**

Angenommen, dein Benutzername ist `maxmuster`, das Repository heißt `mein-playground-export` und die Datei `export.zip`, dann lautet der Link:

```
https://playground.wordpress.net/?zip=https://github.com/maxmuster/mein-playground-export/raw/main/export.zip
```

Diesen Link kannst du teilen oder selbst in deinem Browser öffnen, um die ZIP direkt im WordPress Playground zu laden[^2].

---

**Tipp:** Achte darauf, dass das Repository und die ZIP-Datei öffentlich sind, damit der Playground darauf zugreifen kann.

<div style="text-align: center">⁂</div>

[^1]: https://www.wpbeginner.com/de/wp-tutorials/wordpress-playground-how-to-use-wordpress-in-your-browser/

[^2]: https://wpmet.com/de/was-ist-wordpress-playground-wordpress-playground-erklart/

[^3]: https://www.wpbeginner.com/de/beginners-guide/beginners-guide-to-using-git-with-wordpress/

[^4]: https://www.dreamhost.com/blog/de/wie-man-wp-mit-github-verwendet/

[^5]: https://www.ionos.de/digitalguide/hosting/blogs/wordpress-github/

[^6]: https://kinsta.com/de/wissensdatenbank/wordpress-seite-exportiert/

[^7]: https://wordpress.github.io/wordpress-playground/quick-start-guide/

[^8]: https://github.com/WordPress/wordpress-playground/discussions/1814
