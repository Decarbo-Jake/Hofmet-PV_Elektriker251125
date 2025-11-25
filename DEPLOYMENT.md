# 🚀 Deployment Anleitung

Schritt-für-Schritt Anleitung zum Deployment der PV Elektriker App.

---

## Option 1: GitHub Pages (Kostenlos & Einfach)

### Schritt 1: GitHub Repository erstellen
1. Gehe zu [github.com](https://github.com) und melde dich an
2. Klicke auf **"New repository"** (grüner Button)
3. Repository Name: `pv-elektriker-app` (oder ein anderer Name)
4. Beschreibung: `PV Daten App für Elektriker Partner`
5. **Public** auswählen (für GitHub Pages kostenlos)
6. ✅ "Add a README file" **NICHT** anklicken (wir haben schon eins)
7. Klicke auf **"Create repository"**

### Schritt 2: Dateien hochladen
**Option A: Via Web-Interface (Einfach)**
1. Auf der Repository-Seite: Klicke **"uploading an existing file"**
2. Ziehe alle Dateien in das Fenster:
   - `index.html`
   - `manifest.json`
   - `service-worker.js`
   - `logo.svg`
   - `logo.png`
   - `vercel.json`
   - `README.md`
   - `.gitignore`
3. Commit message: `Initial commit - PV Elektriker App`
4. Klicke **"Commit changes"**

**Option B: Via Git Command Line (Fortgeschritten)**
```bash
# In dem Ordner mit den Dateien:
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/DEIN-USERNAME/pv-elektriker-app.git
git push -u origin main
```

### Schritt 3: GitHub Pages aktivieren
1. Gehe zu deinem Repository
2. Klicke auf **"Settings"** (Zahnrad-Symbol)
3. Scrolle in der linken Sidebar zu **"Pages"**
4. Unter "Source":
   - Branch: **`main`**
   - Folder: **`/ (root)`**
5. Klicke **"Save"**
6. ⏳ Warte 2-3 Minuten

### Schritt 4: App aufrufen
Deine App ist jetzt live unter:
```
https://DEIN-USERNAME.github.io/pv-elektriker-app/
```

🎉 **Fertig!** Die App ist nun online.

---

## Option 2: Vercel (Schneller & Professioneller)

### Schritt 1: Vercel Account erstellen
1. Gehe zu [vercel.com](https://vercel.com)
2. Klicke **"Sign Up"**
3. Wähle **"Continue with GitHub"**
4. Autorisiere Vercel

### Schritt 2: Repository verbinden
1. Klicke **"New Project"**
2. Klicke **"Import Git Repository"**
3. Wähle dein `pv-elektriker-app` Repository
4. Klicke **"Import"**

### Schritt 3: Deploy Settings
- **Framework Preset**: Other
- **Root Directory**: `./`
- Klicke **"Deploy"**

### Schritt 4: Warten
⏳ Deployment dauert ca. 30 Sekunden

### Schritt 5: Fertig!
Deine App ist live unter:
```
https://pv-elektriker-app.vercel.app
```

### Bonus: Custom Domain
1. Gehe zu Project Settings → Domains
2. Füge deine Domain hinzu (z.B. `pv.hofmet.de`)
3. Folge den DNS-Anweisungen

---

## 📱 Als App auf Smartphone installieren

### iPhone/iPad (Safari):
```
1. Öffne die URL in Safari
2. Tippe auf Teilen-Symbol 📤 (unten)
3. Scrolle runter → "Zum Home-Bildschirm"
4. Tippe "Hinzufügen"
```

### Android (Chrome):
```
1. Öffne die URL in Chrome
2. Tippe auf Menü ⋮ (oben rechts)
3. Wähle "App installieren"
4. Tippe "Installieren"
```

---

## 🔄 Updates deployen

### Bei GitHub Pages:
1. Bearbeite die Dateien lokal
2. Lade die geänderten Dateien hoch (oder git push)
3. GitHub Pages aktualisiert automatisch (1-2 Minuten)

### Bei Vercel:
1. Push zu GitHub: `git push`
2. Vercel deployed automatisch (30 Sekunden)
3. Fertig!

---

## ⚙️ Troubleshooting

### Problem: "404 Page Not Found"
**Lösung:** 
- Prüfe ob `index.html` im Root-Verzeichnis liegt
- Bei GitHub Pages: Prüfe Settings → Pages → Branch ist `main`

### Problem: "Service Worker funktioniert nicht"
**Lösung:**
- HTTPS erforderlich (GitHub Pages/Vercel haben das automatisch)
- Browser-Cache leeren
- Prüfe Browser Console (F12) für Fehler

### Problem: "App installiert sich nicht"
**Lösung:**
- Muss über HTTPS sein
- `manifest.json` muss korrekt verlinkt sein
- Icons müssen erreichbar sein
- Safari nur für iOS, Chrome für Android

### Problem: "PDF wird nicht erstellt"
**Lösung:**
- Prüfe ob jsPDF CDN erreichbar ist
- Browser Console checken (F12)
- Popup-Blocker deaktivieren

---

## 📞 Support

Bei Fragen oder Problemen:
- **E-Mail**: info@hofmet.de
- **GitHub Issues**: Im Repository "Issues" öffnen

---

## ✅ Checkliste vor dem Deployment

- [ ] Alle 8 Dateien vorhanden
- [ ] `index.html` funktioniert lokal
- [ ] E-Mail-Adresse korrekt (info@hofmet.de)
- [ ] Logo-Dateien vorhanden
- [ ] README.md angepasst (optional)
- [ ] GitHub Repository erstellt
- [ ] Files hochgeladen
- [ ] GitHub Pages aktiviert
- [ ] URL funktioniert
- [ ] Als App installierbar

---

**Viel Erfolg beim Deployment! 🚀**