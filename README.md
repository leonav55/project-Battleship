# project-Battleship

Ovo je projekt rada igre Battleship(Potapljanje brodova) koja je napravljena u programskom jeziku C++ uz korištenje raylib grafičke biblioteke.

Igra sadrži 2 moda: 
- PvP(Player vs Player)
- PvAI(Player vs AI)

## Kontrole u igri

Kada se igra pokrene vidi se Menu za biranje moda igre:
- Kliknite '1' za pokretanje moda PvP
- -Kliknite '2' za pokretanje moda PvAI

Brodove postavljate sa klikom na određeni kvadratić na ploči. Kada kliknete ENTER potvrdili ste da ste postavili svoje brodove i prelazi se u sljedeću fazu.

Pucanje na tuđu ploču radi se na način da kliknete na kvadratič na ploči protivnika. Ako ste brod pogodili, točkica će se pojaviti u crvenoj boji. Ako niste pogodili onda će se pojaviti točkica u sivoj boji. 
Igrači ne mogu pucati na isto polje vise puta.
U PvAI modu AI puca na nasumičan način.

Nakon što su svi brodovi jednog igrača potopljeni, igra završava i ispisuje se:

GAME OVER
Winner: <Igrac#>

