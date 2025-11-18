🌿 Garden Shop – Moderne E-Commerce Frontend-Applikation

Dieses Projekt wurde im Rahmen einer Teamarbeit mit insgesamt fünf Entwickler:innen realisiert.
Ich übernahm dabei die Rolle des Team Leads und war verantwortlich für technische Architektur, Aufgabenverteilung, Code-Qualität, Reviews sowie die finale Integration der einzelnen Module.

Der Fokus des Projekts lag darauf, eine performante, benutzerfreundliche und skalierbare E-Commerce-Oberfläche zu entwickeln, basierend auf React und Redux Toolkit.


🔗 Live-Demo:
https://garden-products-gamma.vercel.app/

⸻

📘 Projektübersicht

Garden Shop ist eine vollständig clientseitige E-Commerce-Applikation, entwickelt mit React, Redux Toolkit und React Router.
Der Fokus lag auf:
	•	sauberer und skalierbarer Code-Struktur
	•	optimaler User Experience
	•	stabiler globaler State-Verwaltung
	•	responsivem UI nach Figma-Design
	•	performantem Rendering und Skeleton-Loading

Die Anwendung ermöglicht es Nutzer:innen, Produkte zu durchsuchen, zu filtern, zu sortieren, als Favoriten zu markieren und in den Warenkorb zu legen.

⸻

🛠 Tech-Stack

Technologie:                  Einsatzgebiet
React:                        Komponenten-Architektur, UI-Logik
Redux Toolkit:                Zentraler globaler State, Async Thunks
React Router:                 Client-seitiges Routing
SCSS Modules:                 Strukturierte, komponentenbasierte Styles
React Loading Skeleton:       Skeleton-Loader für bessere UX
Vercel:                       Deployment der Produktivversion
Git & GitHub:                 Versionskontrolle, Team-Workflow

⸻

🚀 Hauptfunktionen

🏠 Startseite
	•	Anzeige von vier Hauptkategorien
	•	Formular für 5-%-Rabatt
	•	„Produkt des Tages“ (Modal, 50 % Rabatt)
	•	Vier zufällige rabattierte Produkte

🗂 Kategorien & Produkte
	•	Kategorienliste
	•	Gefilterte Produktansicht pro Kategorie
	•	Sortierung (Preis ↑ / Preis ↓)
	•	Filter nach Rabatt und Preisrange

❤️ Favoriten
	•	Hinzufügen/Entfernen von Favoriten
	•	Sortierung und Filterung
	•	Persistenz im Client-State

🛒 Warenkorb
	•	Mengenanpassung
	•	Entfernen einzelner Artikel
	•	Berechnung der Gesamtsumme
	•	Formular zur Bestellbestätigung

📄 Produktdetails
	•	Mehrbild-Gallerie
	•	Preis, Beschreibung, Rabatte
	•	Direktes Hinzufügen zum Warenkorb

🌙 Dark Mode
	•	Umschaltbar
	•	Speicherung im LocalStorage

📱 Responsiveness
	•	Vollständig responsives UI nach Figma-Vorlage
	•	Optimiert für Mobile, Tablet und Desktop

🧩 Skeleton-Loader
	•	Skeleton-Layouts für Produktlisten und Detailseiten

❌ 404-Seite
	•	Benutzerfreundliche Fehlerseite

⸻

⚙️ Installation & Lokale Ausführung

git clone https://github.com/Dzhabrai1/Garden-Shop.git

cd Garden-Shop
npm install
npm run dev


⸻

📁 Projektstruktur

src/
├── assets/          # Bilder, Icons
├── components/      # Wiederverwendbare UI-Komponenten
├── features/        # Redux slices (cart, products, categories, etc.)
├── pages/           # Hauptseiten
├── store/           # Redux Store
├── styles/          # SCSS-Module und globale Styles
└── App.jsx          # Hauptrouting & Layout


⸻


👥 Team & Rolle

Dieses Projekt entstand zusammen mit vier weiteren Entwickler:innen.
Ich übernahm folgende Aufgaben:
	•	Teamleitung & Projektplanung
	•	Architekturentscheidungen und Aufbau der Code-Struktur
	•	Review-Prozesse & Qualitätssicherung
	•	Integration der Teilkomponenten
	•	Aufsetzen und Deployment auf Vercel
