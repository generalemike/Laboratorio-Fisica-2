
### Prima esperienza sui circuiti RC CR.

Scopo dell'esperienza:

1. verificare le proprietà filtranti dei due circuiti:

- RC -> fa passare le frequenze basse (filtro passa-basso);
- CR -> fa passare le frequenze alte (filtro passa-alto);

2. raccogliere un campione di dati per ogni circuito che comprenda:

- tensione in entrata:  $V_{in}$;
- tensione in uscita:  $V_{out}$;
- frequenza / pulsazione:  $f /\omega$;
- sfasamento dei segnali: $\delta$;

3. ricavare il guadagno usando la definizione e plottare i valori ottenuti in funzione della frequenza/pulsazione ;

$\hspace{4cm} G(w) = \frac{V_{out}(\omega)}{V_{in}(\omega)}$

4. fare il fit dei dati usando le due equazioni del guadagno ricavate a lezione per estrapolare il valore della costante $\tau$ da cui poi sarà possibile ricavare la capacità del condensatore, essendo la resistenza nota;

$\hspace{1cm} G_{RC}(w) = \frac{1}{\sqrt{1 + (\omega \tau)^2}} 
\hspace{2cm}
 G_{CR}(w) = \frac{1}{\sqrt{1 + (\frac{1}{\omega \tau})^2}}$
 
$\hspace{4cm} \tau = RC$

5. verificare i valori delle frequenze (pulsazioni) di taglio $\omega_{RC }$, $\omega_{CR}$ e visualizzare sull'oscilloscopio che effettivamente:

- per frequenze molto più alte della frequenza di taglio, nei circuiti RC, la tensione in uscita integra la tensione in entrata;

$\hspace{3cm} \omega >> \omega_{RC} \Rightarrow V_{out}(w) = \int{V_{in}(w)dt}$

- per frequenze molto più basse della frequenza di taglio, nei circuiti CR, la tensione in uscita deriva la tensione in entrata;

$\hspace{3cm} \omega << \omega_{CR} \Rightarrow V_{out}(w) = \frac{ dV_{in}(w)}{dt}$
