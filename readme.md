# Google SERP snelheids test


### Onderzoeksvraag
Is aan te tonen dat de snelheid van een website een directe correlatie heeft met de positie in Google?

### Bestanden
- serp_onderzoek.ipynb 
- lg_export.csv
- lighthouse.csv

### Opzet onderzoek
Via de website PageSpeed Insights geeft Google websites een snelheidsscore. Aangenomen wordt dat deze snelheidsscore invloed heeft op de positie in Google.

Om dit te onderzoeken hebben we van 7 categorieen 692 zoekvragen ingevoerd in Google en de eerste 20 positites genoteerd.

| Categprie     | Nr queries    | Nr Urls  |
| ------------- |:-------------:| :-------:|
| Recht         | 42            | 726      |
| Lokaal        | 350           | 6834     |
| It            | 50            | 1122     |
| Ecommerce     | 100           | 2069     |
| Ondernemen    | 50            | 995      |
| Financieel    | 50            | 936      |
| Medisch       | 50            | 892      |

De genoteerde urls zijn door eerst met de Lightspeed tool in de Chrome browser getest. De scores verschilde erg veel van [Google PageSpeed](https://developers.google.com/speed/pagespeed/insights/?hl=nl). Daarom zijn alle urls uiteindelijk direct met deze tool getest.

De uitkomt van dit onderzoek is terug te vinden in de bijlage lg_export.csv.

In de bijlage serp_onderzoek.ipynb is de uitwerking van het onderzoek te vinden. 

### Conclusie

In veld 43 van het Notebook wordr over alle posities de mediaan, gemiddelde, standaarddeviatie, minimum en maximum getoond.

Wat erg opvallend is dat er over alle posities heen geen verschil in snelheid gemeten wordt. Lagere posities hebben zelf nog een wat betere score dan de hoogste posities. Op is de deviatie over de gehele range bijna gelijk. 

Tevens vind ik opvallend dat de gemiddelde score helemaal niet zo hoog is.

### Nog toe te voegen

Absolute snelheidsscores.
