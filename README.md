# 🎮 4 CULORI sau UNO cu buget redus 🙂



Un joc clasic de cărți, adaptat pentru browser, construit cu **HTML5 Canvas** și **JavaScript**.  
Proiectul include logica jocului, meniuri interactive, efecte audio și suport pentru mai mulți jucători.  

## 🚀 Funcționalități
- Joc de tip **UNO** direct în browser
- Suport pentru **2–4 jucători**
- Interfață grafică animată (Canvas + CreateJS)
- Sunete integrate cu [Howler.js](https://howlerjs.com/)
- Mod **fullscreen** și verificare orientare pe mobil
- Panouri dedicate pentru:
  - Selectare jucători
  - Explicații funcții cărți speciale
  - Alegere culoare
  - Final de joc
  - Credite
- Compatibil cu **desktop și dispozitive mobile**

## 🛠️ Tehnologii folosite
- **HTML5** & **Canvas API**
- **JavaScript (ES5/ES6)**  
- [jQuery 3.2.1](https://jquery.com/)  
- [CreateJS](https://createjs.com/)  
- [Howler.js](https://howlerjs.com/) – pentru audio
- CSS custom pentru interfață și fullscreen

## 📂 Structura proiectului
```
/
├── index.html           # Punctul de start al jocului
├── css/                 # Stiluri (reset, main, fullscreen, orientare)
├── js/                  # Logica jocului și librăriile necesare
│   ├── CMain.js         # Punctul central al aplicației
│   ├── CGame.js         # Logica jocului
│   ├── CMenu.js         # Meniu principal
│   ├── CCard.js         # Obiectele de tip carte
│   ├── CInterface.js    # Interfața grafică
│   └── ... (alte module)
└── favicon.ico
```

## ▶️ Cum rulezi proiectul
1. Clonează repository-ul:
   ```bash
   git clone https://github.com/neurici/4-culori.git
   ```
2. Intră în folderul proiectului:
   ```bash
   cd 4-culori
   ```
3. Rulează un server local (exemple):
   ```bash
   # Python 3
   python -m http.server 8080

   # Node.js (http-server)
   npx http-server .
   ```
4. Accesează în browser:
   ```
   http://localhost:8080
   ```

## 📱 Suport pentru dispozitive mobile
- Jocul detectează orientarea dispozitivului și afișează un mesaj dacă nu este în modul **landscape**
- Compatibil cu **iOS și Android**

## 📜 Licență
Acest proiect este publicat sub licența [**MIT**](LICENSE.md).

Poți folosi, modifica și distribui liber codul, cu menționarea **autorului**!

---

🎨 *Creat cu pasiune pentru jocuri, direct în browser.*
