# 🍴 Forken & Mitmachen / Fork & Contribute

**🇩🇪 [Deutsch](#-deutsch) · 🇬🇧 [English](#-english)**

> 🇩🇪 Diese Anleitung zeigt dir, wie du eine Datei änderst (z. B. eine Idee in die [IDEENLISTE.md](../IDEENLISTE.md) einträgst) und sie zurück ins Projekt gibst.
> 🇬🇧 This guide shows how to change a file (e.g. add an idea to [IDEENLISTE.md](../IDEENLISTE.md)) and send it back to the project.

---

## 🇩🇪 Deutsch

### 🟢 Der einfache Weg (direkt im Browser)

Perfekt für kleine Änderungen wie das Eintragen einer Idee – **kein Git nötig**:

1. Öffne die Datei auf GitHub (z. B. `IDEENLISTE.md`).
2. Klicke oben rechts auf das **Bleistift-Symbol** ✏️ ("Edit this file").
3. Schreibe deine Änderung rein.
4. Unten auf **"Commit changes"** klicken.
5. GitHub erstellt automatisch einen **Fork** und einen **Pull Request** für dich.
6. Fertig – das Team prüft deinen Vorschlag. 🎉

### 🔧 Der klassische Weg (mit Git)

Für größere Änderungen oder wenn du lokal arbeiten möchtest:

```bash
# 1. Repo auf GitHub forken (Button "Fork" oben rechts)

# 2. Deinen Fork lokal klonen
git clone https://github.com/DEIN-NAME/Techhelp-Support-Bot.git
cd Techhelp-Support-Bot

# 3. Einen Branch für deine Änderung anlegen
git checkout -b meine-idee

# 4. Datei ändern, dann speichern und committen
git add IDEENLISTE.md
git commit -m "docs: neue Idee ergänzt"

# 5. Zu deinem Fork pushen
git push origin meine-idee
```

Danach auf GitHub den **"Compare & pull request"**-Button klicken und den Pull Request abschicken.

### ✅ Danach

- Das Team schaut sich deinen Pull Request an.
- Vielleicht gibt es Rückfragen oder kleine Anpassungswünsche.
- Wird er gemergt, ist deine Idee Teil des Projekts. 💙

---

## 🇬🇧 English

### 🟢 The easy way (directly in the browser)

Perfect for small changes like adding an idea – **no Git needed**:

1. Open the file on GitHub (e.g. `IDEENLISTE.md`).
2. Click the **pencil icon** ✏️ at the top right ("Edit this file").
3. Type in your change.
4. Click **"Commit changes"** at the bottom.
5. GitHub automatically creates a **fork** and a **pull request** for you.
6. Done – the team reviews your suggestion. 🎉

### 🔧 The classic way (with Git)

For larger changes or if you prefer working locally:

```bash
# 1. Fork the repo on GitHub (the "Fork" button at the top right)

# 2. Clone your fork locally
git clone https://github.com/YOUR-NAME/Techhelp-Support-Bot.git
cd Techhelp-Support-Bot

# 3. Create a branch for your change
git checkout -b my-idea

# 4. Edit the file, then save and commit
git add IDEENLISTE.md
git commit -m "docs: add a new idea"

# 5. Push to your fork
git push origin my-idea
```

Then click the **"Compare & pull request"** button on GitHub and submit the pull request.

### ✅ Afterwards

- The team reviews your pull request.
- There may be follow-up questions or small change requests.
- Once merged, your idea becomes part of the project. 💙

---

**TechHelp Support Bot**
*Gemeinsam besser. Gemeinsam entwickelt. / Better together. Built together.*
