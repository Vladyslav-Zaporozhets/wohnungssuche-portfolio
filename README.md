# Demo: Website-Visitenkarte für die Wohnungssuche

Dies ist eine **Demo-Version (für das Portfolio)** einer einseitigen Website-Visitenkarte für eine Familie auf Wohnungssuche. Das Projekt demonstriert Fähigkeiten im Umgang mit einem modernen Frontend-Stack ohne den Einsatz von Frameworks.

Alle persönlichen Daten (Namen, Kontakte, Stadt) wurden durch **Testdaten** (z.B. "Max Mustermann") ersetzt und werden dynamisch aus der Datei `public/config.json` geladen.

**[➡️ Live-Demo ansehen](https://vladyslav-zaporozhets.github.io/wohnungssuche-portfolio/)**

---

### ✨ Technische Merkmale

* **Dynamischer Inhalt:** Alle Textdaten (Namen, Stadt, Telefon, Hobbys etc.) werden asynchron aus `public/config.json` geladen. Dies ermöglicht die Bearbeitung der Website-Inhalte ohne Änderungen am HTML-Code.
* **Modernes JavaScript:** Das Projekt ist in reinem (Vanilla) JavaScript unter Verwendung von ES Modules (ESM) geschrieben.
* **Projekt-Build:** Verwendet **Vite** für eine schnelle Entwicklung (HMR) und einen optimierten finalen Build.
* **Responsives Design:** Die Website ist vollständig responsiv für mobile Geräte, einschließlich eines funktionalen Burger-Menüs.
* **Scroll Spy:** Das Navigationsmenü hebt den aktuell sichtbaren Abschnitt der Seite beim Scrollen hervor. Dies wird performant mittels der `Intersection Observer API` umgesetzt.
* **CI/CD (Auto-Deployment):** Ein GitHub Actions Workflow ist eingerichtet, der das Projekt automatisch baut (`npm run build`) und auf GitHub Pages veröffentlicht, bei jedem Push in den `main`-Branch.
* **Code-Qualität:** Das Projekt ist für die Verwendung mit **ESLint** und **Prettier** konfiguriert, um die Code-Sauberkeit und Konsistenz zu gewährleisten.
