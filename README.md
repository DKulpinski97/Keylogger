Jest to jeden z pięciu programów które tworzą całość. Pozostałe programy znajdują się na tym githabie. Nazwy pozostałych programów to:

*	Analiza
*	Tłumacz
*	Analiza-czasu
*	Nadzorujący

Zadaniem tego programu jest pobieranie wszystkich sygnałów z klawiatury i dodawanie ich do pliku csv. 
Ponadto ma on  dodać informacje do jakiego procesu został wysłany sygnał.  Jest on  reprezentowany przez fokus.
Pliki są tworzone automatycznie i zawiera informacje o dacie jego stworzenia oraz identyfikator użytkownika i komputera. 
Można manipulować informacjami o użytkowniku oraz numerze komputera poprzez edytowanie pliku Conf.txt znajdującym się w folderze debugującym. 
W wypadku jeżeli plik nie będzie istnieć w tym folderze zostanie on automatycznie wygenerowany. 
W tym pliku ustala się również czas do uznania że zaszła przerwa w pisaniu  oraz czas do restartu programu po czym zostanie stworzony nowy plik z nową datą. 
Należy podawać parametry w milisekundach. Parametry zostają pobrane na podstawie numeru linijki oraz wartościami znajdującymi się po znaku „=”. 
Bardzo ważne jest że terminal został ukryty. Wytworzone pliki csv są gromadzone w folderze debugującym. 
