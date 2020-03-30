# covid-19
Dataset e grafici sull'emergenza covid

I dataset sono presi dalla [protezione civile](https://github.com/pcm-dpc/COVID-19) e modificati da me per aggiungere altre variabili. 
I grafici sono fatti con la funzione ggplot di R.

I data set sono aggiornati al giorno indicato e sono complessivi dei giorni precedenti.

Il dato nuovi_casi,non presente sui dataset della [protezione civile](https://github.com/pcm-dpc/COVID-19), è il dato utilizzato dall'[OMS](https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports) nei suoi raporti. E' diverso da nuovi_attualemnete_positivi perchè considera tutti i casi, sia guariti che deceduti, e non solamente quelli risultati positivi al tampone. 
nuovi_attualemnete_positivi ci da invece il dato del numero dei risultati positivi ogni giorno, la somma con la riduzione dei decuduti e guariti è totale_attualmente_positivi. Invece una sommatoria semplice dei nuovi postivi potrebbe darci un valore indicativo del numero di persone contagiate fino a questo momento tramite tampone, sono ovviamente esclusi i deceduti rislutati positivi dopo la morte. 
C'è in realtà il bisogno di costruitre un indice migliore di quelli attuali, che poco cambia la sostanza delle vittime e dei contagi attuali ma che potrebbe essere utile a fini statistici.


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
