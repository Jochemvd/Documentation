# Clicks logfiles

Log files met prefix "clicks" bevatten informatie over de clicks die gegenereerd
zijn bij jouw berichten. Je kunt de inhoud van deze bestanden downloaden in CSV, JSON
en XML formaat via de [REST logfiles API](rest-logfiles) of via het dashboard.
Deze bestanden bevatten de volgende informatie: 

| Naam        | Beschrijving                                                                                       |
| ----------- | -------------------------------------------------------------------------------------------------- |
| id          | De unieke id van het bericht dat de klik gegeneerd heeft                                           |
| time        | Het tijdstip waarop geklikt is in het fromaat JJJJ-MM-DD uu:mm:ss                                  |
| headers     | De headers die gebruikt zijn bij het klikken, elk gedeelte van de header staat op een nieuwe regel |
| ip          | Het IP adres vanwaar geklikt is                                                                    |
| url         | De URL in het bericht waarop geklikt is                                                            |
| destination | De URL waar naar verwezen werd vanuit de klik                                                      |
| tags        | De tags van het bericht dat de klik genereerde puntkomma gescheiden                                |
| recipient   | De recipient van het bericht dat de klik genereerde                                                |
| city        | De stad waar de klik plaats vond                                                                   |
| countryname | De naam van het land waar de klik plaats vond                                                      |
| countrycode | De landencode (alpha-2) van het land waar de klik plaats vond                                      |
| regioncode  | De regiocode waar de klik plaats vond                                                              |