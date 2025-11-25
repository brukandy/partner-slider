# Partner Slider - Leone Master School

Slider orizzontale infinito con card espandibili per mostrare i partner della Leone Master School.

## 🎯 Caratteristiche

- **Card Espandibili**: Hover su desktop, tap su mobile per vedere la bio completa
- **Scroll Infinito**: Animazione automatica continua
- **Pausa on Hover**: Lo slider si ferma quando passi sopra
- **Responsive**: Ottimizzato per desktop, tablet e mobile
- **14 Partner**: Con foto, nome, ruolo e biografia

## 📁 Struttura File

```
partner-slider/
├── index.html          # Struttura HTML
├── styles.css          # Stili e animazioni
├── script.js           # Interattività
├── images/             # Cartella per le immagini
│   ├── adriana-volpe.jpg
│   ├── annalisa-minetti.jpg
│   ├── pino-insegno.jpg
│   ├── sonia-peronaci.jpg
│   ├── alviero-martini.jpg
│   ├── danilo-iervolino.jpg
│   ├── stefania-logatto.jpg
│   ├── jacopo-mele.jpg
│   ├── bruno-mascarenhas.jpg
│   ├── giampaolo-grossi.jpg
│   ├── francesco-magro.jpg
│   ├── michele-montesano.jpg
│   ├── marco-landi.jpg
└── README.md
```

## 📸 Image Requirements

Place 14 partner images in the `images/` folder with these exact filenames:

1. `adrianavolpe.png`
2. `annalisaminetti.png`
3. `pinoinsegno.png`
4. `soniaperonaci.png`
5. `alvieromartini.png`
6. `daniloiervolino.png`
7. `stefanialogatto.png`
8. `jacopomele.png`
9. `brunomascarenhas.png`
10. `giampaologrossi.png`
11. `francescomagro.png`
12. `michelemontesano.png`
13. `marcolandi.png`
14. `claudiorossi.png`

**Formato consigliato**: JPG o PNG, dimensioni 600x800px (proporzione 3:4)

## 🎨 Comportamento

### Desktop
- **Hover sulla card**: Si espande verticalmente mostrando la biografia
- **Hover sullo slider**: Pausa l'animazione
- **Animazione smooth**: Transizioni fluide

### Mobile
- **Tap sulla card**: Toggle espansione (si apre/chiude)
- **Tap fuori**: Chiude tutte le card espanse
- **Scroll**: Previene espansione accidentale durante lo scroll

## 🚀 Come Usare

1. Inserisci le immagini nella cartella `images/`
2. Apri `index.html` nel browser
3. Per embeddare su LearnWorlds, usa iframe:

```html
<iframe 
    src="URL_GITHUB_PAGES" 
    width="100%" 
    height="700px" 
    frameborder="0" 
    scrolling="no"
    style="border: none; overflow: hidden;">
</iframe>
```

## 📱 Dimensioni Responsive

- **Desktop (>1024px)**: Card 280x420px
- **Tablet (768-1024px)**: Card 240x380px
- **Mobile (480-768px)**: Card 200x340px
- **Mobile Small (<480px)**: Card 180x300px

## 🎯 Partner Inclusi

1. **Adriana Volpe** - Il volto della Leone Master School
2. **Annalisa Minetti** - La madrina della Leone Master School
3. **Pino Insegno** - Ospite d'onore MMS 1ª e 2ª edizione
4. **Sonia Peronaci** - Ospite d'onore MMS 4ª edizione
5. **Alviero Martini** - Ospite d'onore MMS 4ª edizione
6. **Danilo Iervolino** - Ospite d'onore MMS 4ª edizione
7. **Stefania Lo gatto** - Ospite d'onore Donna Leader 1ª edizione
8. **Jacopo Mele** - Ospite d'onore MMS 3ª edizione
9. **Bruno Mascarenhas** - Ospite d'onore
10. **Giampaolo Grossi** - Docente Leone Master School
11. **Francesco Magro** - Docente Leone Master School
12. **Michele Montesano** - Docente Leone Master School
13. **Marco Landi** - Ospite d'onore MMS 4ª edizione
14. **Claudio Rossi** - Docente Leone Master School

## 🔧 Personalizzazione

### Modificare i colori
Modifica le variabili in `styles.css`:
- Background: `#f8f9fa`
- Testo principale: `#1a1a1a`
- Testo secondario: `#666`

### Modificare la velocità
In `styles.css`, cambia la durata dell'animazione:
```css
animation: scroll 80s linear infinite; /* 80s = velocità attuale */
```

### Aggiungere/Rimuovere partner
1. Duplica un blocco `.partner-card` in `index.html`
2. Aggiorna il numero totale nell'animazione CSS
3. Aggiungi l'immagine nella cartella `images/`

## 📄 Licenza

Progetto per Leone Master School - Tutti i diritti riservati
