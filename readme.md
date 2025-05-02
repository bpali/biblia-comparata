# EN

## Working with source (src) images

Image resizing is done through following command in order to achieve a readable yet under 1MB image

`mogrify -monitor -quality 30 -resize 50% *.jpg`

## Check number of lines in files

Each chapter is in a sepparate [markdown](https://en.wikipedia.org/wiki/Markdown) file (.md). The file is structured (from a line perspective) as follows:
 - line 1: chapter title
 - line 2: source image links
 - line 3: chapter summary
 - line 4+: blank line + verse on a new line

So a chapter with 17 verses will have 3 + 17x2 = 37 lines

Command to count number of lines in files is:

`wc -l *.md`

---

# RO

## Lucrul cu imaginile sursa (src)

Redimensionarea imaginilor se face prin comanda urmatoare pentru a obține imagini lizibile insă cu o dimensiune mai mica de 1MB

`mogrify -monitor -quality 30 -resize 50% *.jpg`

## Verificare numar de linii din fișiere

Fiecare capitol se gasește într-un fișier de tip [markdown](https://en.wikipedia.org/wiki/Markdown) (.md). Fișierele, din perspectiva liniilor, sunt organizate după cum urmează:
 - linia 1: titlul capitolului
 - linia 2: legatura la imaginile sursa
 - linia 3: sumarul capitolului
 - linia 4+: linie goala + verset pe linie noua

Deci un capitorl cu 17 versete va avea 3 + 17x2 = 37 linii

Comanda pentru numararea liniilor din fisiere este:

`wc -l *.md`