## Szintaxis

Változó létrehozás: !prefix! !változó neve! = !érték!
Mi az a prefix? Milyen típusai vannak?

A prefix megadja hogy az adott érték szám vagy szöveg alapú-e a változó.
Prefixek:
- sz: Szám megadása
- b: Szöveg megadása

Kiírás a konzolba: Kiírás(!tartalom!)
A kiírás lehet változó vagy szöveg.

Szöveg megadása: Kiírás("szöveg")
Változó megadása: Kiírás(változó)
Mindkettő egyszerre: Kírás("Szöveg %Változó%")

Ismétlés: AMEDDIG !feltétel! {!utasítások!}
Példa:
sz X = 0
AMEDDIG X < 0 {
    Kiírás("A jelenlegi ismétlés száma: %X%")
    sz += 1
}

Fontos: az örök ismétléshez a feltétel "true" legyen

If szerkezet: HA !feltétel! {!utasítások!}

Alapműveletek között nem kell space, példa:
sz X = 1
sz Y = 6
sz eredmeny = X+Y

## Ismert hibák

- Egyszerre változó és szöveg kiírása kicsit furán működik még.
- A GYÖK() és a hatvány rendszer nem működik helyesen.

# NEMSOKÁRA A NYELV PUBLIKUS LESZ :D