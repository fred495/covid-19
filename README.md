# covid-19
Dataset e grafici sull'emergenza covid

I dataset sono presi dalla [protezione civile](https://github.com/pcm-dpc/COVID-19) e modificati da me per aggiungere altre variabili. 
I grafici sono fatti con la funzione ggplot di R.

I data set sono aggiornati al giorno indicato e sono complessivi dei giorni precedenti.

Il dato nuovi_casi(totale_casi ieri meno totale_casi di oggi)non presente sui dataset della [protezione civile](https://github.com/pcm-dpc/COVID-19), è il dato utilizzato dall'[OMS](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports) nei suoi rapporti. Il totale_casi è la somma di totali_attulmente_positivi, dimessi_guariti e deceduti. 
Diverso invece il dato nuovi_attualemnete_positivi che è la semplice differenza tra totali_attualmente_positivi di oggi con totali_attualmente positivi di ieri. Quest'ultimo potrebbe avere valore negativo, quando accadrà vorrà dire che i positivi sono in diminuzione. 


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
