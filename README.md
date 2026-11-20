# website-companyServices

Eigenes Webseiten-Projekt

Baut eine Webseite zu einem Thema, auf das ihr Lust habt. Überlegt euch, welche Inhalte ihr zeigen möchtet.

## Start

Klont das Kurs-Repository und erstellt euren eigenen Branch. Ersetzt `DEIN-PROJEKT` durch den Repository-Namen und `DEIN-BRANCH` z. B. durch euren Vornamen:

```bash
git clone git@github.com:ctf-26d/DEIN-PROJEKT.git webprojekt
cd webprojekt
git switch -c DEIN-BRANCH
```

Das HTML-Grundgerüst in [index.html](index.html) ist bereits mit [style.css](style.css) verknüpft. Baut darauf eine kleine Version, prüft sie im Browser und erweitert sie Schritt für Schritt.

Tipps zum Aufbau, Ideen und Links findet ihr unter [Hilfen und Inspiration](help/hilfen.md). Ihr dürft KI und neue Techniken als Hilfe nutzen.

## Fortschritte speichern

Arbeitet auf eurem Branch. Committet eure Zwischenschritte und pusht sie ins Kurs-Repository (`origin`):

```bash
git add .
git commit -m "Projekt erweitert"
git push origin DEIN-BRANCH
```

## Abschluss

Vor dem finalen Push könnt ihr die Hilfedateien in `help/` löschen und in der `README.md` euer Projekt kurz beschreiben. Committet diese Änderungen und pusht euren Stand wie oben zu `origin`.

## Optional: veröffentlichen

Erstellt in eurem eigenen GitHub-Account ein **öffentliches, leeres Repository** – ohne README, Lizenz oder `.gitignore`. Fügt es einmalig als Remote `deploy` hinzu und pusht euren Branch dort auf `main`. **`solution` steht im Beispiel und in der Grafik für euren eigenen Branch – ersetzt es durch euren Branchnamen.**

```bash
git remote add deploy git@github.com:DEIN-USERNAME/DEIN-REPO.git
git push deploy DEINBRANCH:main
```

Bei weiteren Änderungen wiederholt ihr nach dem Commit beide Push-Befehle mit eurem Branchnamen.

Veröffentlicht euer öffentliches Repository mit GitHub Pages aus `main` und teilt den Link im Slack. Auch unfertige und experimentelle Projekte dürfen veröffentlicht werden.

![Git-Workflow: auf dem eigenen Branch arbeiten und zu origin sowie optional deploy pushen](assets/Git-Workflow_%20Lokal%20und%20zwei%20GitHub-Repos.png)
