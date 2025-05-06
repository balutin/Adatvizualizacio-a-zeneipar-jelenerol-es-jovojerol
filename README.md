# Spotify Előadók – Adatvizualizációs Projekt

## Miről szól a projekt?

Ez a vizualizációs projekt a Spotify zenei streaming platform legnépszerűbb előadóit mutatja be adatvezérelt módon. A cél az, hogy különböző nézőpontokból elemezzük a zenei előadók jelenlegi és korábbi népszerűségét, megfigyeljük a trendeket (növekedés, visszaesés, stabilitás), és ezeket vizuálisan érthető módon mutassuk be.

## Milyen adatokat használsz?

Az adatforrás a **Spotify Top Artists by Monthly Listeners** dataset, amely az alábbi főbb mezőket tartalmazza:

- **Artist**: Előadó neve  
- **Listeners**: Jelenlegi havi hallgatók száma  
- **Daily Trend**: Napi növekedés/csökkenés a hallgatók számában  
- **Peak**: Az elért legjobb helyezés a ranglistán (1 a legjobb)  
- **PkListeners**: A valaha elért legmagasabb hallgatószám  

További számított mezők is szerepelnek, például:

- **Loss** = PkListeners - Listeners

## Miért érdekesek az adatok?

A zeneipar rendkívül dinamikus – a napi trendek és hallgatottsági számok értékes betekintést adnak a valós időben változó népszerűségi mintákba. Az adatok segítségével felismerhetők üzleti és kulturális trendek, valamint feltörekvő vagy visszaeső előadók.

## Ki a cél-felhasználó?

- Zenerajongók  
- Zenei menedzserek és producerek  
- Marketingesek  
- Adatelemzők és hallgatók  
- Tartalomgyártók (YouTube, TikTok)

## Mit szeretnél, hogy a felhasználó tanuljon ebből?

- A népszerűség dinamikusan változik, nem állandó  
- A napi trendek és történeti csúcsok együtt adnak teljes képet  
- Az adatvizualizáció képes összetett összefüggéseket egyszerűen bemutatni

## Mennyire skálázható a megoldásod?

- Könnyen bővíthető több előadóra  
- Alkalmazható más platformokra (YouTube, Apple Music)  
- Más adatsorokon is újrahasznosítható

## Mennyire automatizálható a megoldásod?

- Adatelőkészítés fél-automatizálható (Excel, Python)  
- Flourish vizualizációk frissíthetők új adatokkal  
- Automatizálható API-alapú Spotify-adatlekéréssel

## Mivel lenne még hasznos bővíteni?

- Idősoros adatok gyűjtése és vizualizálása  
- Előadók csoportosítása stílus, célcsoport szerint  
- Interaktív szűrők alkalmazása a dashboardon  
- Események idővonalhoz kötése (albummegjelenés, díjak)  
- Valós idejű adatfrissítés
