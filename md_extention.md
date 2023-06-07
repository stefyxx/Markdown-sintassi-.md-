Markdown:= .md

maiuscolo := **  **
corsivo:= _  _
barrato:= ~~ ~~

ogni carattere speciale, che é usato anche in Html, per far si' che venga letto come tale, si scrive avanti il backslash \
es: \<

 ...................
paragrafo in grigio rientrante:= tab tab   opp ```    ```
per delineare una parte rientrante é suff il tab opp 4 spazi

nuovo paragrafo:= linea vuota

 ....................

Capitoli:=
# cap1
## cap2
###-> ###### Cap6

 ..................

Citazioni:= >scrivo attaccato!!

>Questa è un’**area rientrata**.
>L’area prosegue anche qui.

>Questa è un‘altra **area rientrata**.
Anche quest’area continua nella riga successiva.

Questa riga invece non è più rientrata, perché ho chiuso il paragrafo con una linea bianca

 ..................
Elenco non numerico:= - e spazio
- Punto 1 della lista
- Punto 2 della lista
- Punto 3 della lista

Elenco numerico:= n°. spazio
1. Punto 1 della lista
2. Punto 2 della lista
3. Punto 3 della lista

 .................
checklist:= [ ] ( --> [ spazio ])
checklist spuntata:= [x]

 ................

Inserire del CODE :=  ` `

Se il backtick appare piu' volte nel vostro ex di codice, allora é meglio cosi':= `` `` (il singolo ` sarà letto come accento)
``Questo è tutto `code`.``

 ................

Links:=  [Link](https://example.com/ "Titolo del link opzionale").

 ................

Immagini:= ![Ecco un’immagine di esempio](https://example.com/immagine.jpg) 
non dimenticare il pt eclamativo!

Immagine da un link:= [![Ecco un’immagine di esempio](https://example.com/immagine.jpg)](https://example.com)

 ................

Tabelle:= |Cella 1|Cella 2|

|Cella 1|Cella 2|
|-------|-------|  (linea orizzontale)
|  A    |  B    |  allineare i pipers | serve solo a noi x la leggibilità


 ..................
Note a pié pagina:= [^n°]:   (non dimenticare i due punti :)

La posizione della nota nel testo non è rilevante. Markdown la visualizzerà sempre alla fine del documento.

Nel corpo del testo [^1] potete facilmente inserire [^2] note a piè di pagina.
[^1]: qui c’è il testo delle note a piè di pagina.
[^2]: Anche le **note a piè di pagina** possono essere *formattate*.
E queste includono anche diverse linee.