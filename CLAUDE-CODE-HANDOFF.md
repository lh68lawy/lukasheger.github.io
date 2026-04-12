# Übergabe-Prompt für Claude Code

Kopiere den folgenden Text als Prompt in Claude Code:

---

Ich habe eine fertige statische Portfolio-Website unter `~/Documents/Model:Kleindarsteller/Modeljob/Kleindarsteller Portfolio & Webpräsenz/website/`. Die Struktur ist:

```
website/
├── index.html          (komplette Seite, Single-File HTML/CSS/JS)
└── images/
    ├── portrait.jpeg
    ├── front.jpeg
    ├── fullbody.jpeg
    ├── profile-left.jpeg
    ├── profile-right.jpeg
    ├── torso.jpeg
    ├── editorial-01.jpg bis editorial-06.jpg
```

Ich möchte diese Website jetzt auf GitHub Pages deployen. Bitte hilf mir dabei:

1. **Git-Repo initialisieren** im `website/`-Ordner
2. **GitHub-Repository erstellen** via `gh` CLI (Repo-Name: `lukasheger.github.io`, public)
3. **Commit & Push** aller Dateien
4. **GitHub Pages aktivieren** (deploy from branch `main`, root `/`)
5. **Prüfen** ob die Seite unter `lukasheger.github.io` erreichbar ist

Falls `gh` CLI nicht installiert ist, installiere es via `brew install gh` und führe `gh auth login` durch.

Die Website ist eine Actor/Model-Portfolio-Seite für Lukas Heger (Berlin). Single-File HTML mit eingebettetem CSS/JS, Google Fonts (Inter + Playfair Display), Lightbox-Galerie, responsive Design. Alle Bilder sind bereits weboptimiert (insgesamt ~2.7MB).

Kontakt-E-Mail auf der Seite: p.fiedler@posteo.de

---
