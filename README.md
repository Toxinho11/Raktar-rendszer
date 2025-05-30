# 📦 Raktározási rendszer

Ez a projekt egy egyszerű raktározási rendszert valósít meg Python nyelven.

## Fájlok

- `raktar.py` – a fő program
- `adatok.txt` – készítő adatai (Tárkányi Márk, Mérnökinformatikus, HG7RS8)
- `raktar_mentes.json` – mentett foglalások (automatikusan jön létre)
- `.gitignore` – segéd fájl GitHub-hoz

## Funkciók

- Termék foglalása név + e-mail alapján
- Foglalás lemondása azonosítóval
- Foglalt termékek listázása
- Szabad készlet listázása
- Összes foglalás listázása
- Állapot mentése fájlba

## Elérhető termékek

- tej
- víz
- cukor
- liszt
- kávé
- csirkemell
- paradicsom

## Áru fogadók

- Tesco
- Penny
- Lidl
- Aldi
- Spar

## Foglalás adatkezelés

- Foglalási dátum: a foglalás pillanatában rögzül
- Várható kiszállítás: foglalás + 3 nap
- Minden foglalás egyedi azonosítóval rendelkezik

## Használat

A program futtatása:

```bash
python raktar.py
