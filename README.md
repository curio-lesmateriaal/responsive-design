# Responsive Web Design Leeropdrachten

Een complete leeromgeving voor het oefenen van responsive web design met HTML en CSS. Dit project bevat een voorbeeldsite (TechNieuws nieuwswebsite) en uitgebreide opdrachten om je vaardigheden met responsive design te verbeteren.

## 📚 Over dit project

Dit project is ontwikkeld om je te helpen bij het leren van responsive web design. Het bestaat uit:

- **Een voorbeeldsite** (`index.html`) - Een realistische nieuwswebsite (TechNieuws) die dient als basis voor de opdrachten
- **Opdrachtenpagina** (`opdrachten.html`) - Uitgebreide opdrachten verdeeld over verschillende categorieën
- **Stylesheet** (`styles.css`) - Eenvoudige, beginnervriendelijke CSS zonder frameworks

## 🎯 Wat leer je?

Na het voltooien van deze opdrachten ben je in staat om:

- ✅ Responsive layouts te bouwen met CSS Grid en Flexbox
- ✅ Media queries te gebruiken voor verschillende schermgroottes
- ✅ Moderne CSS-technieken toe te passen in een realistische website
- ✅ Mobile-first en desktop-first benaderingen te begrijpen
- ✅ Responsive typography en spacing te implementeren
- ✅ Touch-vriendelijke interfaces te ontwerpen

## 📁 Projectstructuur

```
html-css/
│
├── index.html          # Voorbeeldsite (TechNieuws nieuwswebsite)
├── opdrachten.html     # Opdrachtenpagina met alle opdrachten
├── styles.css          # Hoofdstylesheet (eenvoudige CSS voor beginners)
└── README.md           # Dit bestand
```

## 🚀 Aan de slag

### Vereisten

Je hebt alleen nodig:
- Een moderne webbrowser (Chrome, Firefox, Safari, Edge)
- Een code editor (VS Code, Sublime Text, etc.)
- Een lokale webserver (optioneel, maar aanbevolen)

### Installatie

1. **Clone of download dit project**
   ```bash
   git clone [repository-url]
   cd html-css
   ```

2. **Start een lokale server** (optioneel maar aanbevolen)

   **Met Python:**
   ```bash
   # Python 3
   python -m http.server 8000
   ```

   **Met PHP:**
   ```bash
   php -S localhost:8000
   ```

   **Met Node.js (http-server):**
   ```bash
   npx http-server
   ```

   Of open de HTML-bestanden direct in je browser (let op: sommige features werken mogelijk niet zonder server).

3. **Open de site**
   - Navigeer naar `http://localhost:8000` (of het poortnummer dat je gebruikt)
   - Of open `index.html` direct in je browser

## 📖 Gebruik

### Voorbeeldsite bekijken

1. Open `index.html` in je browser
2. Verken de TechNieuws nieuwswebsite
3. Test de responsive design door je browser venster te verkleinen of vergroten
4. Gebruik de Developer Tools (F12) om te zien hoe de layout verandert bij verschillende schermgroottes

### Opdrachten uitvoeren

1. Klik op de **"Opdrachten"** knop in de navigatie (links naast het logo)
2. Je ziet 4 tabs:
   - **Meerkeuzeopdrachten** - Test je kennis met 10 multiple choice vragen
   - **Uitzoekopdrachten** - 10 open vragen waarbij je de code moet bestuderen (antwoorden worden automatisch opgeslagen)
   - **Doe-opdrachten** - 6 praktische opdrachten om aan de code te werken
   - **Finale Opdracht** - Een complete opdracht die alles combineert

3. Werk door de opdrachten heen en test je oplossingen in de browser

## 🎓 Opdrachttypen

### 1. Meerkeuzeopdrachten
- 10 vragen over responsive web design concepten
- Directe feedback met confetti bij goede antwoorden! 🎉
- Algemene kennis over CSS, Flexbox, Grid, media queries, etc.

### 2. Uitzoekopdrachten
- 10 open vragen die code-reading vereisen
- Antwoorden worden automatisch opgeslagen in localStorage
- Leer door code te analyseren en te begrijpen hoe het werkt

### 3. Doe-opdrachten
- 6 praktische opdrachten
- Pas de code aan en test je wijzigingen
- Leer door te doen: breakpoints toevoegen, navigatie verbeteren, etc.

### 4. Finale Opdracht
- Complete opdracht: maak een volledig responsive contact pagina
- Combineert alle geleerde concepten
- Optionele extra uitdagingen voor gevorderden

## 🛠️ Technologieën

- **HTML5** - Semantische HTML structuur
- **CSS3** - Pure CSS, geen frameworks
  - Flexbox
  - CSS Grid
  - Media Queries
  - CSS Custom Properties (basis)
  - Responsive Typography
- **JavaScript** - Minimale JS voor interactiviteit
  - Quiz functionaliteit
  - LocalStorage voor opslag
  - Tab navigatie

## 📱 Responsive Breakpoints

De site gebruikt de volgende breakpoints:

- **Desktop**: > 900px
- **Tablet**: 700px - 900px
- **Mobiel**: ≤ 700px

## 💡 Tips

1. **Gebruik Developer Tools**
   - Open met F12
   - Test verschillende schermgroottes met Device Mode
   - Inspecteer elementen om CSS te begrijpen

2. **Test regelmatig**
   - Test je wijzigingen op verschillende schermgroottes
   - Controleer op horizontale scroll
   - Zorg dat tekst leesbaar blijft

3. **Experimenteer**
   - Probeer verschillende waarden uit
   - Wijzig kleuren, spacing, en layout
   - Bekijk wat er gebeurt

4. **Code lezen**
   - Bestudeer `styles.css` aandachtig
   - Begrijp hoe media queries werken
   - Zie hoe Flexbox en Grid worden gebruikt

## 🐛 Problemen oplossen

### De site ziet er niet goed uit
- Controleer of `styles.css` correct geladen wordt
- Zorg dat je browser up-to-date is
- Probeer hard refresh (Ctrl+F5 of Cmd+Shift+R)

### Opdrachten worden niet opgeslagen
- Controleer of JavaScript ingeschakeld is
- Zorg dat localStorage beschikbaar is (geen private/incognito mode)
- Check de browser console voor errors (F12)

### Media queries werken niet
- Controleer of de viewport meta tag aanwezig is in `index.html`
- Test met Developer Tools Device Mode
- Zorg dat je een lokale server gebruikt

## 📝 Best practices in dit project

- **Semantische HTML** - Gebruik van `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, etc.
- **Mobile-first thinking** - Responsive design vanaf het begin
- **Accessibility** - Toegankelijke code structuur
- **Clean CSS** - Eenvoudige, leesbare CSS zonder overbodige complexiteit
- **Geen frameworks** - Pure CSS om de basis te leren

## 🤝 Contribueren

Dit is een leerproject. Voel je vrij om:
- Issues te melden
- Verbeteringen voor te stellen
- Jouw oplossingen te delen

## 📄 Licentie

Dit project is gemaakt voor educatieve doeleinden. Vrij te gebruiken en aan te passen voor leerdoeleinden.

## 🎯 Volgende stappen

Na het voltooien van deze opdrachten kun je:
- Meer geavanceerde CSS-technieken leren (CSS Variables, Animations, etc.)
- Een CSS framework leren (Bootstrap, Tailwind, etc.)
- JavaScript interactiviteit toevoegen
- Je eigen responsive websites bouwen!

## 📞 Hulp nodig?

- Check de browser console voor errors (F12)
- Gebruik de Developer Tools om code te inspecteren
- Experimenteer met verschillende waarden
- Test op verschillende apparaten

---

**Veel succes met leren! 🚀**
