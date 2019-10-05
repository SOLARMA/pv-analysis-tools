# Sample data from Danfoss Comlynx Weblogger

(2019-10-05 12:18 CEST)

Connect to SOLPEV weblogger through a SSH tunnel

```bash
solpev-tunnel.sh
```

Browse <http://localhost:5080/> to access the weblogger web interface

Click "Login"

Click "Download"

> **Download - Dati impianto**
>
> Riepilogo impianto
>
> * Dati: Orario di rilevazione, Numero registratore di dati, Potenza,
>   Energia di oggi, Rendimento conteggiato, Intensità di irradiamento,
>   Energia di irradiamento odierna
> * Periodo: 10.01.2013 fino a: 05.10.2019
> * Dimensioni protocollo: 16.8 MB
>
> Dettagli inverter
>
> * Dati: Orario di rilevazione, Numero dispositivo, Numero di serie, Potenza,
>   Energia di oggi, Temperatura, Tensione griglia, Corrente griglia,
>   Frequenza di rete, Tens. Fotov. 1, Corr. fotov. 1, Tens. Fotov. 2,
>   Corr. fotov. 2, Tens. Fotov. 3, Corr. fotov. 3, Stato, Moduli C.C.,
>   Errore, Pannello fotovoltaico, Limite di potenza, Posizione di fase, CosPhi
> * Periodo: 10.01.2013 fino a: 05.10.2019
> * Dimensioni protocollo: 605.9 MB
> 
> Eventi impianto
>
> * Dati: Orario di rilevazione, Tipologia eventi, Evento
> * Periodo: 10.01.2013 fino a: 05.10.2019
> * Dimensioni protocollo:	44.7 MB


#### Download Riepilogo impianto

(2019-10-05 12:20 CEST)

Click "Riepilogo impianto >> Download"

> * Dati: Orario di rilevazione, Numero registratore di dati, Potenza,
>   Energia di oggi, Rendimento conteggiato, Intensità di irradiamento,
>   Energia di irradiamento odierna
> * Periodo: 10.01.2013 fino a: 05.10.2019
> * Dimensioni protocollo: 16.8 MB

Select

* da: 01.07.2019
* fino a: 05.10.2019
* Tipo di file: .txt
* GZIP compresso: No

then click "Download"

Result: File [`summary.txt`](summary.txt) (153 KB) downloaded


#### Download Dettagli inverter

(2019-10-05 12:24 CEST)

Click "Dettagli inverter >> Download"

> * Periodo:	10.01.2013 fino a: 05.10.2019
> * Dimensioni protocollo:	605.9 MB
> * Colonne dati:
>   - Orario di rilevazione
>   - Numero dispositivo
>   - Numero di serie
>   - Potenza
>   - Energia di oggi
>   - Temperatura
>   - Tensione griglia
>   - Corrente griglia
>   - Frequenza di rete
>   - Tens. Fotov. 1
>   - Corr. fotov. 1
>   - Tens. Fotov. 2
>   - Corr. fotov. 2
>   - Tens. Fotov. 3
>   - Corr. fotov. 3
>   - Stato
>   - Moduli C.C.
>   - Errore
>   - Pannello fotovoltaico
>   - Limite di potenza
>   - Posizione di fase
>   - CosPhi
> * da:	04.10.2019
> * fino a: 05.10.2019
> * Tipo di file: .txt
> * GZIP compresso: No

Select

* da: 01.07.2019
* fino a: 05.10.2019
* Tipo di file: .txt
* GZIP compresso: No

then click "Download"

> **Download - Dettagli inverter**
>
> * Elenco dati:
>   - Orario di rilevazione
>   - Numero dispositivo
>   - Numero di serie
>   - Potenza
>   - Energia di oggi
>   - Temperatura
>   - Tensione griglia
>   - Corrente griglia
>   - Frequenza di rete
>   - Tens. Fotov. 1
>   - Corr. fotov. 1
>   - Tens. Fotov. 2
>   - Corr. fotov. 2
>   - Tens. Fotov. 3
>   - Corr. fotov. 3
>   - Stato
>   - Moduli C.C.
>   - Errore
>   - Pannello fotovoltaico
>   - Limite di potenza
>   - Posizione di fase
>   - CosPhi
> * da:	01.07.2019
> * fino a: 05.10.2019
> * Tipo di file: txt
>
> Il download dei dati avrà inizio tra qualche secondo.

Result: File [`details.txt`](details.txt) (5831 KB) downloaded


#### Download Eventi impianto

(2019-10-05 12:59 CEST)

Click "Eventi impianto >> Download"

> **Download - Eventi impianto**
>
> * Periodo: 10.01.2013 fino a: 05.10.2019
> * Grandezza protocollo: 44.7 MB
> * Eventi:
>   - [x] Informazioni
>   - [x] Avvertenze
>   - [x] Disturbi
> * da:	07.09.2019
> * fino a: 25.09.2019
> * Grandezza protocollo: .txt
> * GZIP compresso: No

Select

* da: 01.09.2019
* fino a: 25.09.2019
* Tipo di file: .txt
* GZIP compresso: No

then click "Download"

> **Download - Eventi impianto**
>
> * Evento:
>   - [x] Informazioni
>   - [x] Avvertenze
>   - [x] Disturbi
> * da:	01.07.2019
> * fino a: 05.10.2019
> * Tipo di file: txt
>
> Il download dei dati avrà inizio tra qualche secondo.

Result: File [`events.txt`](events.txt) (1810 KB) downloaded

<!-- EOF -->
