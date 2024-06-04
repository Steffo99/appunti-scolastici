# Esercizio 7.4
## Entità
**Cittadino**
- _Codice Fiscale_
- Cognome
- Nome
- Sesso
- Data di nascita
	
	[Luogo di nascita]
	**Nati nel comune**
	- Numero del registro
	- Pagina del registro

	**Nati fuori dal comune**
	- Comune di nascita

	[Residenza]
	**Residente**
	- __Capofamiglia__
	- __Appartenenza__

**Famiglia**
- _ __Capofamiglia__ _
- __Appartenenza__
- Via domicilio
- Numero civico domicilio
- Interno domicilio

__Appartenenza__
- Grado di parentela


# Relazioni
Residente <1,1 __Capofamiglia__ 0,1> Famiglia
Residente <0,N __Appartenenza__ 1,1> Famiglia

# Generalizzazioni
Cittadino <== Nati nel comune
		    = Nati fuori dal comune

Cittadino <-- Residente