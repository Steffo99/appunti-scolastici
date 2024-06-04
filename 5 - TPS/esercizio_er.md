I lettori che frequentano la biblioteca hanno una tessera su cui è scritto il nome e l'indirizzo ed effettuano richieste di prestito per i libri che sono catalogati nella biblioteca.
I libri hanno un titolo, una lista di autori e possono esistere in diverse copie.
Tutti i libri contenuti nella biblioteca sono identificati da un codice.
A seguito di una richiesta viene dapprima consultato l'archivio dei libri disponibili (cioè non in prestito).
Se il libro è disponibile, si procede alla ricerca del volume negli scaffali; il testo viene poi classificato come in prestito.
Acquisito il volume, viene consegnato al lettore, che procede alla consultazione.
Terminata la consultazione, il libro viene restituito, reinserito in biblioteca e nuovamente classificato come disponibile.
Per un prestito si tiene nota degli orari e delle date di acquisizione e di riconsegna.

**Lettore**
- Nome
- Indirizzo

**Libro**
- Codice
- Titolo

**Copia**
- In prestito

**Autore**
- Nome

__Prestito__
- Data prestito
- Data riconsegna

Libro <1;N __Copyright__ 1;N> Autore
Libro <1;N __Unità__ 1;N> Copia
Lettore <1;N __Prestito__ 1;N> Copia