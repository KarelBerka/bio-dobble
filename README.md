# 🧬 BioDobble Portal

Vítejte v biochemickém portálu výukových karetních her **BioDobble**.

🌐 **Živá aplikace (GitHub Pages):** [https://karelberka.github.io/bio-dobble](https://karelberka.github.io/bio-dobble)

---

## 🚀 Nabídka aplikací

### 🧬 [AA-Dobble](https://karelberka.github.io/amino-acid-dobble)
- **Oblast:** Biogenní aminokyseliny
- **Řád Dobble:** $q = 4$
- **Parametry:** 21 aminokyselin, 21 karet, 5 symbolů na kartě
- **Reprezentace:** České/Anglické/Německé/Francouzské názvy, 3D PyMOL modely, 2D strukturní vzorce, 3-písmenné a 1-písmenné zkratky.

### 🍬 [Glyco-Dobble](https://karelberka.github.io/glyco-dobble)
- **Oblast:** Glykonomika a sacharidy
- **Verze:**
  - **Základní lidský glykom ($q = 3$):** 13 cukrů, 13 karet, 4 symboly/karta
  - **Rozšířený glykom ($q = 4$):** 21 cukrů, 21 karet, 5 symbolů/karta
  - **SNFG Atlas ($q = 7$):** 57 cukrů, 57 karet, 8 symbolů/karta
- **Reprezentace:** Vícenásobné jazyky, 2D Haworthovy projekce, sumární vzorce a **oficiální barevné SNFG symboly** (Symbol Nomenclature for Glycans).

### 🧈 [Lipido-Dobble](https://karelberka.github.io/lipido-dobble)
- **Oblast:** Lipidomika a mastné kyseliny
- **Verze:**
  - **Základní membrána ($q = 3$):** 13 lipidů, 13 karet, 4 symboly/karta
  - **Signalizační a metabolická ($q = 5$):** 31 lipidů, 31 karet, 6 symbolů/karta
  - **LIPID MAPS Atlas ($q = 7$):** 57 lipidů, 57 karet, 8 symbolů/karta
  - **Mass Spec Nightmare ($q = 8$):** 73 molekulárních druhů nad tělesem $\text{GF}(8)$, 9 symbolů/karta
- **Reprezentace:** Názvy, zkratky LIPID MAPS, 2D schémata, třídy lipidů.

### 🔬 [NA-Dobble (NucleicAcid-Dobble)](https://karelberka.github.io/nucleic-acid-dobble)
- **Oblast:** Nukleové kyseliny a nukleotidy
- **Verze:**
  - **NADobbleMini ($q = 2$):** 7 symbolů (báze A, T, U, C, G + cukry Rib, dRib), 3 symboly/karta
  - **Plná verze ($q = 4$):** 21 symbolů (báze, nukleosidy, nukleotidy, ATP, GTP, cAMP, tRNA speciality jako pseudouridin), 5 symbolů/karta
- **Reprezentace:** Názvy, zkratky, 2D purinové/pyrimidinové kruhy, sumární vzorce.

---

## 🧮 Matematické pozadí

Aplikace BioDobble jsou generovány pomocí konečných projektivních rovin $PG(2,q)$:
- Počet karet = Počet symbolů = $q^2 + q + 1$
- Počet symbolů na kartě = $q + 1$
- Každé dvě karty sdílejí **přesně jeden** společný prvek.

---

## 👨‍💻 Autor & Licenční ujednání

- **Autor:** [Karel Berka](https://karelberka.github.io)
- Určeno pro výuku biochemie, molekulární biologie a glykobiologie.
