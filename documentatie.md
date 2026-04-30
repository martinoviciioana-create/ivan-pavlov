# LUCRARE DE ATESTAT

## Informatică

---

**Tema:** Prezentarea orașului Roma — pagină web

**Elev:** Martinovici Ioana Alexandra

**Clasa:** a XII-a B

**Profesor coordonator:** Prof. Soare Daniela

**Liceul:** Colegiul Național Spiru Haret București

**An școlar:** 2025 - 2026

---

## Cuprins

1. Argument
2. Descrierea proiectului
3. Tehnologii folosite
   - 3.1. HTML
   - 3.2. CSS
4. Structura aplicației
   - 4.1. Organizarea fișierelor
   - 4.2. Pagina principală (index.html)
   - 4.3. Pagina de atracții (atractii.html)
   - 4.4. Fișierul de stil (stil.css)
5. Detalii de implementare
   - 5.1. Structura HTML
   - 5.2. Stilizare CSS
   - 5.3. Design responsive
   - 5.4. Galeria de imagini
6. Mod de utilizare
7. Concluzii
8. Bibliografie

---

## 1. Argument

Am ales ca temă pentru lucrarea de atestat realizarea unei pagini web de
prezentare a orașului Roma, capitala Italiei. Am ales acest subiect deoarece
Roma este unul dintre cele mai importante orașe din istoria omenirii și are
o legătură strânsă cu cultura românească — chiar și numele "România" provine
de la cuvântul "roman".

Realizarea unui site web mi-a permis să aplic cunoștințele de informatică
acumulate în timpul liceului, în special cele legate de limbajele HTML și
CSS, dar și să îmi dezvolt creativitatea prin alegerea culorilor, a imaginilor
și a modului de organizare a informației.

Proiectul îmbină astfel **tehnologia** cu **istoria** și **cultura**, fiind
util atât din punct de vedere educațional, cât și informativ pentru orice
persoană care dorește să afle mai multe despre Orașul Etern.

---

## 2. Descrierea proiectului

Proiectul constă într-un site web format din **două pagini HTML**, conectate
între ele printr-un meniu de navigare. Site-ul prezintă orașul Roma sub
diferite aspecte:

- **Pagina principală** conține informații generale despre oraș, istoria
  Romei împărțită pe perioade, geografia și clima, precum și un tabel cu
  date utile.
- **Pagina de atracții** prezintă cele mai cunoscute monumente ale Romei,
  o galerie foto, bucătăria tradițională romană și diverse curiozități.

Site-ul este realizat **integral în limba română** și folosește un design
inspirat din culorile clasice ale Romei antice (roșu închis și auriu), cu
o tipografie serif (Georgia) care amintește de inscripțiile romane.

---

## 3. Tehnologii folosite

### 3.1. HTML (HyperText Markup Language)

HTML este limbajul standard folosit pentru crearea paginilor web. El
definește **structura** unei pagini, prin elemente numite *tag-uri*
(de exemplu: `<h1>`, `<p>`, `<img>`).

Fiecare pagină a site-ului este un fișier `.html` care conține:
- antetul `<head>` cu informații despre pagină (titlu, codificare)
- corpul `<body>` cu conținutul vizibil de utilizator

În proiectul meu am folosit **HTML5**, varianta modernă a limbajului, care
introduce elemente semantice utile precum `<header>`, `<nav>`, `<main>`,
`<section>` și `<footer>`.

### 3.2. CSS (Cascading Style Sheets)

CSS este limbajul folosit pentru a **stiliza** o pagină web — culori,
fonturi, dimensiuni, poziționare etc. Practic, dacă HTML stabilește
*ce* afișăm, CSS stabilește *cum arată* ceea ce afișăm.

Am folosit un fișier CSS extern (`stil.css`) care este aplicat ambelor
pagini. Avantajul acestei metode este că, dacă vreau să schimb un stil
(de exemplu culoarea meniului), îl modific într-un singur loc și
schimbarea apare automat pe toate paginile.

În stilizarea proiectului am folosit:
- **CSS Grid** — pentru afișarea galeriei de imagini
- **Flexbox** și **box model** — pentru aranjarea elementelor
- **Media queries** — pentru ca site-ul să arate bine și pe telefoane
- **Pseudo-clase** (`:hover`) — pentru efecte la trecerea mouse-ului
- **Tranziții** — pentru animații line

---

## 4. Structura aplicației

### 4.1. Organizarea fișierelor

Proiectul este compus din **3 fișiere** plasate în același folder:

```
prezentare-roma/
├── index.html       (pagina principală)
├── atractii.html    (pagina de atracții și cultură)
└── stil.css         (fișierul cu stiluri, comun ambelor pagini)
```

### 4.2. Pagina principală (index.html)

Pagina de start a site-ului conține următoarele secțiuni:

1. **Antet** — un banner mare cu o imagine de fundal cu Colosseum-ul,
   peste care apare titlul "Roma — Orașul Etern".
2. **Meniu de navigare** — două butoane pentru a comuta între cele
   două pagini ale site-ului.
3. **Despre Roma** — informații generale: poziție geografică,
   populație, supranume.
4. **Istoria Romei** — prezentată cronologic în 5 perioade:
   - Fondarea (753 î.Hr.)
   - Republica Romană
   - Imperiul Roman
   - Roma papală
   - Roma modernă
5. **Geografie și climă** — cele 7 coline, râul Tibru, clima mediteraneană.
6. **Tabel cu informații rapide** — date utile (populație, suprafață,
   limbă, monedă etc.).
7. **Subsol** — informații despre proiect și surse.

### 4.3. Pagina de atracții (atractii.html)

A doua pagină a site-ului are următoarele secțiuni:

1. **Antet** — banner cu o imagine de fundal cu Fontana di Trevi.
2. **Meniu de navigare** — identic cu prima pagină.
3. **Atracții turistice** — descrieri detaliate pentru 9 monumente:
   - Colosseum, Forul Roman, Vaticanul, Capela Sixtină,
   - Fontana di Trevi, Panteonul, Piazza Navona,
   - Treptele Spaniole, Castel Sant'Angelo.
4. **Galerie foto** — 8 imagini ale celor mai importante monumente,
   cu un efect de mărire la trecerea mouse-ului.
5. **Bucătărie romană** — împărțită pe categorii: paste, preparate
   tradiționale, deserturi.
6. **Curiozități** — 7 fapte interesante, prezentate în cutii
   evidențiate.
7. **Subsol** — identic cu prima pagină.

### 4.4. Fișierul de stil (stil.css)

Acest fișier conține toate regulile de stilizare aplicate ambelor
pagini. Principalele reguli definite sunt:

- stiluri generale pentru `body`, `header`, `nav`, `main`, `footer`
- stiluri pentru secțiuni și titluri
- stiluri pentru galeria de imagini (grid + efect hover)
- stiluri pentru tabel
- stiluri pentru cutia de curiozități
- reguli responsive pentru ecrane mici

---

## 5. Detalii de implementare

### 5.1. Structura HTML

Fiecare pagină HTML respectă structura standard:

```html
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roma - Orașul Etern</title>
    <link rel="stylesheet" href="stil.css">
</head>
<body>
    <header>...</header>
    <nav>...</nav>
    <main>
        <section>...</section>
        ...
    </main>
    <footer>...</footer>
</body>
</html>
```

Atributul `lang="ro"` indică faptul că pagina este în limba română, iar
`<meta charset="UTF-8">` permite afișarea corectă a diacriticelor
(ă, â, î, ș, ț).

### 5.2. Stilizare CSS

Pentru a obține un aspect plăcut, am folosit o paletă de culori
inspirată din Roma antică:

| Culoare | Cod hex   | Utilizare              |
|---------|-----------|------------------------|
| Roșu închis | `#8b0000` | meniul, titlurile, subsol |
| Auriu | `#ffd700` | accente, link-uri active |
| Crem | `#f9f5ec` | fundalul paginii |
| Galben pal | `#fff8dc` | cutiile de curiozități |

Am folosit fontul **Georgia** (sau "Times New Roman" ca alternativă),
un font cu serife care amintește de inscripțiile romane antice.

### 5.3. Design responsive

Pentru ca site-ul să arate bine atât pe calculator, cât și pe telefon,
am folosit *media queries*:

```css
@media (max-width: 600px) {
    header h1 {
        font-size: 2em;
    }
    nav a {
        display: block;
        margin: 5px 0;
    }
}
```

Pe telefoane, link-urile din meniu sunt așezate unul sub altul, iar
titlul antetului devine mai mic, pentru a încăpea bine pe ecran.

### 5.4. Galeria de imagini

Galeria foto folosește **CSS Grid**, care aranjează automat imaginile
într-un număr potrivit de coloane, în funcție de lățimea ecranului:

```css
.galerie {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 15px;
}
```

Funcția `repeat(auto-fit, minmax(250px, 1fr))` înseamnă: "umple linia
cu cât mai multe coloane care au cel puțin 250px lățime". Astfel,
pe un ecran lat vom vedea 4 imagini pe rând, iar pe telefon doar una
sau două.

Imaginile au și un efect de mărire la *hover*:

```css
.galerie img:hover {
    transform: scale(1.05);
}
```

Imaginile folosite sunt preluate de pe **Wikimedia Commons**, sursă
liberă de imagini cu licență Creative Commons.

---

## 6. Mod de utilizare

Pentru a rula proiectul nu este nevoie de niciun program special — doar
de un browser web (Google Chrome, Firefox, Safari, Edge etc.).

Pașii de utilizare:

1. Se deschide folderul `prezentare-roma`.
2. Se face dublu-click pe fișierul `index.html`.
3. Pagina se va deschide automat în browserul implicit.
4. Se folosește meniul de sus pentru a naviga între cele două pagini.

Fiind realizat doar cu HTML și CSS, site-ul **nu necesită conexiune la
internet**, cu excepția afișării imaginilor (care sunt încărcate de pe
Wikimedia Commons).

---

## 7. Concluzii

Realizarea acestui proiect a fost o experiență utilă din mai multe
puncte de vedere:

- Mi-a permis să aplic în practică cunoștințele de **HTML** și **CSS**
  acumulate în orele de informatică.
- Am învățat să organizez informația într-un mod clar, atât pentru
  utilizator (prin secțiuni și meniu), cât și pentru programator
  (prin separarea HTML-ului de CSS).
- Am descoperit conceptul de **design responsive**, foarte important
  în prezent, când majoritatea oamenilor folosesc telefonul pentru
  a accesa internetul.
- Am exersat scrierea unui cod **curat și comentat**, care poate fi
  înțeles ușor și de o altă persoană.

Pe viitor, proiectul ar putea fi îmbunătățit prin:
- adăugarea unei pagini de **contact** sau **harta** orașului;
- folosirea **JavaScript** pentru a adăuga interactivitate (de exemplu,
  un slider de imagini sau un quiz despre Roma);
- traducerea site-ului și în alte limbi (engleză, italiană).

---

## 8. Bibliografie

1. **Wikipedia** — articolul despre Roma:
   https://ro.wikipedia.org/wiki/Roma

2. **Wikipedia** — articolul în limba engleză despre Rome:
   https://en.wikipedia.org/wiki/Rome

3. **Wikimedia Commons** — sursa imaginilor folosite:
   https://commons.wikimedia.org/wiki/Rome

4. **MDN Web Docs** — documentația oficială pentru HTML și CSS:
   https://developer.mozilla.org/

5. **W3Schools** — tutoriale HTML și CSS:
   https://www.w3schools.com/

6. Manualul de Informatică pentru clasa a XII-a.
