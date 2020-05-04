# ls-autocomplete-comuni
Domanda per selezione dei Comuni Italiani con autocomplete, per versioni 3 e superiori di LimeSurvey. Comuni al 1.1.2020

Importare autocomplete_comuni_ita.lsq sulla propria survey.
Senza modifiche viene caricato il csv del sito https://www.cervelletta.it/ls-ita/data/comuni_ita.csv di cui una copia qui
Per modifiche allo script della domanda:
- Modificare la var url per puntare a altro path o altro path. Se si vuole caricare il file csv sulla cartella "files" della survey (con il pannello delle risorse di LimeSurvey, modificare così:
var url = surveyRoot+"upload/surveys/"+{SID}+"/files/comuni_ita.csv";
- 3 è il numero minimo di caratteri per iniziare la ricerca. Per modificare questo parametro, assegna la variabile minLength dello script
