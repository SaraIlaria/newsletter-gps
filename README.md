# Immagini delle newsletter GPS

Le grafiche delle venti email del portale commerciale GPS (rete È ORA — Eurocedibe S.r.l.).

Stanno qui perché le email non possono portarsi le immagini dentro: i programmi di
posta, Gmail per primo, non le mostrano, e il messaggio supera il limite oltre il quale
viene troncato. Le immagini vanno quindi richiamate da un indirizzo pubblico, ed è
questo.

## Come sono fatti i nomi

| file | cos'è |
|---|---|
| `titolari-01-banner.jpg` | la fascia illustrata in testa all'email 01 della serie ai titolari |
| `titolari-01-foto.jpg` | la scena fotografica dentro il corpo |
| `titolari-01-manifesto.jpg` | la scena grande della riga-manifesto |
| `venditori-…` | le stesse tre, per la serie ai venditori |
| `logo-gps-bianco.png` | il marchio in testa, uguale per tutte |
| `tr-*.png` | le strisce di carta strappata fra un fondo e l'altro |

## Non si modificano a mano

Le rigenera la skill `postino` (`02 - Strumenti/serie.js`) insieme alle email: il nome
del file è quello che l'HTML si aspetta, cambiarlo rompe l'email. Per sostituire una
grafica si rifà la scena e si rilancia la catena.
