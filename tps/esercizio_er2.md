# Entità
**Officina**
- _Nome_
- Indirizzo
- Telefono
- __Locazione__

**Automobile**
- _Targa_
- Modello
- __Proprietà__
- __Oggetto__

**Cliente**
`Proprietario`
- _Codice fiscale_
- Cognome
- Nome
- Telefono
- __Proprietà__

**Intervento**
- _ID_
- _Officina_
- Data inizio
- Data fine
- Ore manodopera
- __Utilizzo__
- __Locazione__
- __Oggetto__

**Pezzo**
- _Codice_
- Nome
- Costo unitario
- __Utilizzo__

__Utilizzo__
- Quantità

# Relazioni
Cliente <1,1 __Proprietà__ 1,N> Automobile
Intervento <0,N __Utilizzo__ 0,N> Pezzo
Intervento <0,N __Locazione__ 0,1> Officina
Intervento <1,N __Oggetto__ 1,1> Automobile