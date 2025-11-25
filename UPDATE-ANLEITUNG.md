# 🚀 GitHub Update Anleitung

## ✅ Was ist neu?

### **1. Logo**
- Echtes Hoffmann Metallbau Logo (Haus mit Solarpanel)
- In Header, als App-Icon, im PDF

### **2. Speichersystem - KOMPLETT NEU**

#### **Fenecon Home:**
- Basis: 8,4 kWh
- Slider: 0-20 Batterie Module
- +2,8 kWh pro Modul
- Automatische Berechnung

#### **Sigenergy:**
- Basis-Auswahl: 6 kWh oder 9 kWh
- Slider 1: Anzahl 6 kWh Module (0-10)
- Slider 2: Anzahl 9 kWh Module (0-10)
- Automatische Gesamt-Berechnung

### **3. kWp-Rechner - NEU**
- Standard Modul: AIKO-A475-MCE54Db Neostar 3S+
- Fest: 475 Wp pro Modul
- Slider: 0-50 Module
- Automatische kWp-Berechnung

### **4. Foto-Upload**
- Mehrere Fotos gleichzeitig
- Live-Vorschau
- Im PDF integriert

### **5. Design**
- Blaues Corporate Design (#0066cc)
- Moderne Slider
- Responsive für Mobile

---

## 📦 Dateien im ZIP

```
github-upload-final.zip
├── index.html              ← Haupt-App
├── manifest.json           ← PWA Manifest
├── service-worker.js       ← Offline-Funktionalität
├── vercel.json             ← Vercel Config
├── logo.svg                ← Logo SVG
├── logo.png                ← Logo 512x512
├── logo-192.png            ← Logo 192x192
├── logo-header.png         ← Logo für Header
├── apple-touch-icon.png    ← iOS Icon
├── README.md               ← Dokumentation
├── DEPLOYMENT.md           ← Deploy-Anleitung
└── .gitignore              ← Git Ignore
```

---

## 🔧 GitHub Update Schritt-für-Schritt

### **Option 1: GitHub Desktop (Empfohlen)**

1. **ZIP entpacken**
   - Entpacke `github-upload-final.zip`
   - In einen Ordner deiner Wahl

2. **Dateien ersetzen**
   - Öffne deinen lokalen Git-Repository-Ordner
   - **ALLE alten Dateien löschen**
   - **ALLE neuen Dateien aus dem entpackten Ordner kopieren**

3. **GitHub Desktop öffnen**
   - Repository auswählen
   - Alle Änderungen werden angezeigt

4. **Commit**
   - Commit Message:
   ```
   Major update: New storage systems, AIKO module, photo upload
   ```
   - Klick auf **"Commit to main"**

5. **Push**
   - Klick auf **"Push origin"**
   - Warte 10 Sekunden

6. **Vercel Check**
   - Gehe zu vercel.com
   - Dein Projekt → Deployments
   - Neuer Build sollte starten (30 Sekunden)

7. **Fertig!** ✅
   - Öffne deine URL
   - Hard Refresh (Strg+F5)
   - Alle neuen Features sollten sichtbar sein

---

### **Option 2: GitHub Web-Interface**

1. **ZIP entpacken**
   - Entpacke alle Dateien

2. **GitHub.com aufrufen**
   - Gehe zu deinem Repository
   - Klick auf "Add file" → "Upload files"

3. **Dateien hochladen**
   - Ziehe ALLE Dateien ins Fenster
   - Oder klicke "choose your files"

4. **Commit**
   - Commit message:
   ```
   Major update: New storage systems, AIKO module, photo upload
   ```
   - Klick auf **"Commit changes"**

5. **Warten**
   - GitHub: 10 Sekunden
   - Vercel: 30 Sekunden

6. **Fertig!** ✅

---

### **Option 3: Git Command Line**

```bash
# In deinem lokalen Repository-Ordner:

# Alte Dateien löschen (außer .git/)
rm -rf *.html *.json *.js *.md *.svg *.png

# Neue Dateien hineinkopieren
cp /pfad/zum/entpackten/ordner/* .

# Git Status prüfen
git status

# Alle Änderungen hinzufügen
git add .

# Commit
git commit -m "Major update: New storage systems, AIKO module, photo upload"

# Push
git push origin main

# Fertig!
```

---

## ✅ Erfolgreich? Prüfe:

1. **GitHub:**
   - Alle neuen Dateien sichtbar
   - Commit ist da

2. **Vercel:**
   - Neues Deployment (grüner Haken)
   - "Ready" Status

3. **Live-Site:**
   - Öffne URL
   - Hard Refresh (Strg+F5 / Cmd+Shift+R)
   - Logo oben links sichtbar
   - Neue Speicher-Auswahl funktioniert
   - AIKO Modul im kWp-Rechner

---

## 🆘 Probleme?

### **Logo nicht sichtbar:**
- Browser-Cache leeren (Strg+F5)
- Inkognito-Modus testen
- Auf Handy: Safari/Chrome Cache löschen

### **Alte Version wird angezeigt:**
- Warte 2-3 Minuten
- Hard Refresh mehrmals
- Browser-Cache komplett leeren

### **Vercel deployed nicht:**
- GitHub verbunden? (Settings → Git)
- Branch richtig? (sollte "main" sein)
- Manuell in Vercel: "Redeploy"

---

## 📱 Als App installieren

Nach dem Update:

**iPhone:**
1. Safari öffnen
2. Teilen → "Zum Home-Bildschirm"
3. Fertig!

**Android:**
1. Chrome öffnen
2. Menü (⋮) → "App installieren"
3. Fertig!

---

## 🎉 Das wars!

Nach dem Push zu GitHub ist alles automatisch:
- ✅ GitHub hat die neuen Dateien
- ✅ Vercel deployed automatisch
- ✅ App ist in 1 Minute live
- ✅ Alle neuen Features funktionieren

**Viel Erfolg!** 🚀