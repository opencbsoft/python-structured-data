# python-structured-data
A project that will interpret romanian sentences and convert them to structured data.

## Recognized structures and example text
The following texts will be used as examples to be converted into structured data.

 1. Greutate (grams)
 - are 5 kilograme = 5000 grams
 - 4 kg = 4000 grams
 - 5 kile = 5000 grams
 
 2. Email
 - adresa mea este john at yahoo.com = john@yahoo.com
 - email-ul meu este john@yahoo.com = john@yahoo.com
 
 3. Website
 - website-ul meu este john.ro = http://john.ro
 - site-ul meu este john.ro = http://john.ro
 
 4. Phone number
 - numarul meu de telefon este 0723xxxxxx = +407236xxxxxx
 - telefonul meu este 0723 6xx xxx = +407236xxxxxx
 - numarul meu este 0723 6x xx xx = +407236xxxxxx
 
 5. Money value
 - costa 5 lei = 5.00 RON
 - o sa ajunga pana la 5 mii euro = 5000.00 EUR
 
 6. Ordinal
 - primul este john = 1
 - al doi-lea este vasile = 2
 - al 3-lea este gigi = 3
 
 7. Temperature
 - sunt 8 grade celsius = 8
 - maine vor fi +5 grade = 5
 
 8. Time (today is Friday 23.12.2016 hour 18:00)
 - maine la ora 5 = 24.12.2016 17:00:00
 - peste 2 ore = 23.12.2016 20:00:00
 - saptamana viitoare, luni la ora 10 = 26.12.2016 10:00:00
 - craciunul viitor = 25.12.2017
 - la anul de sf ion = 6.01.2016