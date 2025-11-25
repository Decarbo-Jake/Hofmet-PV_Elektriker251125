# PV Daten für Elektriker Partner

Eine Progressive Web App (PWA) zur Erfassung von PV-Anlagen-Daten für Elektriker Partner von Hoffmann Metallbau GmbH & CO. KG.

## 🌟 Features

- ✅ **Responsive Design** - Funktioniert auf allen Geräten
- ✅ **Offline-fähig** - Als PWA auf dem Smartphone installierbar
- ✅ **Automatische kWp-Berechnung** - Modulanzahl × Leistung
- ✅ **Zerez ID Integration** - Automatische Anzeige für Wechselrichter
- ✅ **PDF-Export** - Professionelle PDF-Erstellung mit jsPDF
- ✅ **E-Mail-Integration** - Direkter Versand an info@hofmet.de
- ✅ **Moderne UI** - Im Corporate Design von Hoffmann Metallbau

## 📱 Installation als App

### Auf iPhone/iPad:
1. Öffne die App in **Safari**
2. Tippe auf das **Teilen-Symbol** 📤
3. Wähle **"Zum Home-Bildschirm"**
4. Tippe auf **"Hinzufügen"**

### Auf Android:
1. Öffne die App in **Chrome**
2. Tippe auf die **drei Punkte** ⋮
3. Wähle **"App installieren"** oder **"Zum Startbildschirm hinzufügen"**
4. Tippe auf **"Installieren"**

## 🚀 Deployment

### GitHub Pages
1. Repository auf GitHub erstellen
2. Alle Dateien hochladen
3. In Repository Settings → Pages:
   - Source: `main` Branch
   - Folder: `/ (root)`
4. Nach wenigen Minuten ist die App live unter:
   `https://username.github.io/repository-name/`

### Vercel
1. Repository auf GitHub pushen
2. Vercel Account erstellen (vercel.com)
3. "New Project" → GitHub Repository verbinden
4. Deploy - fertig!

## 📁 Projektstruktur

```
.
├── index.html              # Haupt-HTML-Datei mit App
├── manifest.json           # PWA Manifest
├── service-worker.js       # Service Worker für Offline-Funktionalität
├── logo.svg                # Logo im SVG-Format
├── logo.png                # Logo als PNG (512x512)
└── README.md               # Diese Datei
```

## 🛠️ Technologien

- **HTML5** - Struktur
- **CSS3** - Styling (Corporate Design)
- **Vanilla JavaScript** - Funktionalität
- **jsPDF** - PDF-Generierung
- **PWA** - Progressive Web App Features
- **Service Worker** - Offline-Funktionalität

## 📋 Verwendete Komponenten

### Wechselrichter
- **FENECON**: home 6 V2, home 10 V2, home 15, home 20
- **SIGEN**: Hybrid 5.0 TP, Hybrid 8.0 TP, Hybrid 10.0 TP, Stor EC 15.0 TP

### Speichersysteme
- **FENECON**: Home 10 Gen2, Home 10 kW, Home 20 kW, Home 15
- **SIGEN**: SigenStor BAT 10.0, BAT 8.0, 16 kWh, 6 kWh, Stack Battery, Battery 9 kWh, EC 25.0 TP, Hybrid 5.0 TP

## 🎨 Design

Das Design orientiert sich am Corporate Design von Hoffmann Metallbau:
- **Primärfarbe**: Orange (#ff9500)
- **Sekundärfarbe**: Dunkelgrau (#1a1a1a)
- **Akzentfarbe**: Orange-Rot (#ff6600)

## 📧 Kontakt

**Hoffmann Metallbau GmbH & CO. KG**
- E-Mail: info@hofmet.de
- Website: www.hofmet.de
- Standort: Meerbusch

## 📄 Lizenz

© 2024 Hoffmann Metallbau GmbH & CO. KG. Alle Rechte vorbehalten.

---

Entwickelt für Elektriker Partner zur einfachen Erfassung von PV-Anlagen-Daten.