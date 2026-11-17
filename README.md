# Eseményhorizont

Egyfájlos böngészős játék – az `index.html` megnyitásával fut.

Relativisztikus pilótagyakorlat egy fekete lyuk körül: időtágulás, árapály, ergoszféra, gravitációs hullámok, Alcubierre-hajtómű és egy négydimenziós tér a horizont mögött.

## Küldetések

| Küldetés | Cél |
|---|---|
| Jeladók | Gyűjtsd be az öt jeladót a lyuk körül. |
| Ikerparadoxon | Térj haza a Föld-kapuhoz: a Földön ≥ 2 év teljen el, és ≥ 4× annyi, mint a hajón. |
| Csillagközi körút | Keresd fel mind a hét távoli helyet a Proximától az Andromedáig. |
| Ugrás a jövőbe | A Földön teljen el 1 millió év, a hajón legfeljebb 30 nap. |
| Elmélet-vadász | Fedezd fel mind a hat elméletet a 4D térben, és juss ki egy fehér lyukon. |
| Hullámvadász | Légy 3000 egységen belül a kettős lyuktól, amikor az összeolvadás hulláma eléri a hajót. |
| Penrose-bánya | Öt rakományból háromszor nyerj energiát az ergoszférában, aztán szökj el 30 rs-en túlra. |

A játék küldetésenként megjegyzi az öt legjobb (legrövidebb hajóidejű) teljesítést. A rekordtábla a böngészőben tárolódik, ezért eszközönként külön van.

## Változások

### 1.6 – 2026. november 17.
- Interstellar-szerű fekete lyuk valódi fénypálya-követéssel: a játék induláskor 1300 fénysugár pályáját számolja ki Schwarzschild-téridőben (u'' = 3Mu² − u), és minden képpontnál megkeresi, hol metszi a sugár a korong síkját. Így áll elő a filmből ismert kép: a korong túloldala a lyuk fölé és alá hajlik, a közeli oldal előtte halad el, a lyuk körül vékony fotongyűrű.
- A korong fizikája: vékony korong a legbelső stabil pályától (6M) 20M-ig, differenciális (Kepler-) forgással; a gravitációs vöröseltolódás és a keringés Doppler-hatása színezi és fényesíti (a felénk keringő oldal sokkal fényesebb – a film ezt művészi okból kihagyta, itt benne van).
- Felülnézetben ugyanez a számolás felülről nézve.
- A háttércsillagok képe is ugyanebből a pályakészletből jön, vékonylencse-közelítés nélkül: pontos Schwarzschild-elhajlás a hajó tényleges távolságából. Minden csillagnak van elsődleges képe, a lyuk túloldalán másodlagos képe, és a fotongyűrű mellett (erősen összenyomott) harmadrendű képe; a képek a lyuk körül Einstein-gyűrűvé sűrűsödnek. Gyenge térben a számolás visszaadja a klasszikus 4M/b elhajlást.
- Filmes utómunka: ragyogás (bloom), anamorf lencsecsillanás, finom filmszemcse; halványabb jetek.

### 1.5 – 2026. november 17.
- A féreglyuk-átkelés a film jelenete alapján újrarajzolva: belépéskor a tér összetörik (sötét szakadás izzó, töredezett peremmel, sugárirányú csillagcsíkok); a torokban sötét, üveges, hullámzó fal, átlátszó buborékgömbök, vibráló villámszerű repedés, kék lencsefoltok; kilépéskor újabb csíkok, meleg, tűzszerű fénykitörés és felfehéredés. Az átkelés 8 másodperc.

### 1.4 – 2026. november 17.
- Féreglyuk (H): a lyuk mellett egy kapu, amely bármelyik távoli helyre hangolható; minden helyen ott a visszavezető száj. Az Interstellar mintájára gömbként látszik, benne a túloldal egével és a peremén lencsézett háttérrel.
- Átkelés a film mintájára: a gömb kitágul, amíg betölti a képet; a torokban textúrázott „tájak” suhannak el a falon (az indulás színeiből a cél színeibe), a torok kanyarog, a hajó rázkódik, a cél fénye egyre gyorsabban közeledik, a végén felfehéredés.
- A Csillagközi körútban a kapu csak a már felkeresett helyekre hangolható, hogy a küldetést továbbra is repülve kelljen teljesíteni.
- Az értesítések nem írják felül a nyitott kártyák szövegét.

### 1.3 – 2026. november 17.
- Irányítópultosabb kezelőfelület: MFD-kijelző kerettel, nyolclámpás hibajelző sor (GRAV, ÁRAPÁLY, ERGO, GW, AUTOP, BUBORÉK, EGZOT, 4D), radar iránylépték és pásztázó sugár, fizikai gombok LED-del, részletesebb pilótafülke-konzol.
- Új térhajtómű-nézet a pilótafülkében: csillagcsíkok, hullámzó téridő-gyűrűk, buborékfal, haladásjelző a szélvédőn.
- Sötétebb lyukbelső és négy új jelenség: beeső anyag-szálak (spagettifikáció), a kinti ég (tévhit-cáfolattal), BKL-káosz a szingularitás közelében, Penrose-diagram a műszerfalon.

### 1.2 – 2026. november 17.
- Új küldetés: Hullámvadász – a GW150914 mintájára összeolvadó kettős lyuk hullámát kell közelről elkapni.
- Rekordtábla: küldetésenként az öt legjobb teljesítés a záró kártyán.
- Penrose-bánya: 5 rakomány (3 sikeres ledobás kell), mert egy menetbe csak egy ledobás fér bele; a bukás már akkor kiderül, ha nem maradt elég rakomány.
- Javítás: a G billentyű az ergoszférán kívül nem pazarol rakományt.
- Javítás: a záró kártya alatt nem látszik át az utolsó értesítés.

### 1.1 – 2026. november 17.
- Négy új küldetés: Csillagközi körút, Ugrás a jövőbe, Elmélet-vadász, Penrose-bánya.
- Küldetésválasztó a menüben, küldetésenkénti rekord (legjobb hajóidő).
- Az Alcubierre-hajtómű egzotikus anyaga már nem fogy el: a Casimir-gyűjtő 12 másodpercenként pótol egy töltetet (legfeljebb 3).
- Javítások: a záró kártya számai egyeznek a szöveggel; nagy γ tudományos alakban; a menü kis kijelzőn is görgethető.

### 1.0 – 2026. október 27.
- Első kiadás: Jeladó-küldetés és Ikerparadoxon.
