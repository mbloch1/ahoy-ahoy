### Historyjka

Jest początek trzeciego tygodnia czerwca 1645 roku. Dostajesz pilne wezwanie z Admiralicji do Eastengardu, portowej stolicy kraju. Po przybyciu na miejsce okazuje się, że wysłał je twój przyjaciel z dawnych czasów wspólnej żeglugi, wówczas kapitan O'Malley – obecnie już nie kapitan, a admirał niższej rangi. Po krótkim i gościnnym przywitaniu wręcza ci [mapę](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/mapa.png) i przechodzi do sedna sprawy: Admiralicja na prośbę królewskich magów chce w tym tygodniu wysłać okręty w wyznaczone na mapie punkty.

 – Nie wiem, co to za miejsca. – mówi O'Malley. – Na moje oko, to kawałki oceanu jak każde inne. Moim zadaniem jest przygotować zaplecze logistyczne tej operacji i dlatego chciałbym prosić Cię o pomoc.<br/>
 – W czym więc problem? – odpowiadasz. – Zawiniecie do North Point i–<br/>
 – Niestety. Nie możemy wpływać do innych portów, bezpieczeństwo misji i takie tam. Tę operację organizujemy od kilku tygodni, a właściwie to sam dalej nie wiem nawet, jaki jest powód wyprawy ani jaki ładunek wieziemy. Tylko sam król i ścisłe szefostwo Admiralicji znają szczegóły. Nie podoba mi się to. Co gorsza, naszym jedynym celem jest, by oba okręty dotarły na miejsce. O powrót nikt z góry nie dba.

Admirał wstaje z fotela, gdy służący wnosi stosik małych książeczek i kładzie je przed tobą na stole.

 – Oto [plany rejsów](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/rejsy.csv) oraz zachowane [dzienniki pokładowe](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/dzienniki.csv) z ostatnich lat. Nie chcę ryzykować życia moich żeglarzy na jakąś cholerną intrygę polityczną, ale moje miejsce jest na pokładzie statku i nie do końca wiem, jak podejść do tej papierkologii. Miałbym nadzieję, że może Tobie udałoby się na podstawie istniejących danych wyznaczyć bezpieczny kurs, a może nawet wyczytać z nich coś więcej. Chętnie przekażę Twoje cenne uwagi szerszej Admiralicji. Czy zrobisz to dla mnie i moich ludzi?

### Dane

 * [mapa](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/mapa.png). Dostępna również [w formacie GIMPowym .xcf](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/mapa.xcf) z podziałem na warstwy dla łatwiejszej pracy. 
 * [plany rejsów](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/rejsy.csv). Uwaga! Kapitanowie są na stałe przypisani do okrętów 1:1 od zwodowania do ewentualnego pójścia na dno. Nazwy okrętów i kapitanów nie są globalnie unikalne.
 * [dzienniki pokładowe](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/dzienniki.csv), zawierające informacje o zdarzeniach podczas rejsów. Uwaga! Brak dzienników z rejsów, podczas których okręt zatonął.
 * [informacja o okrętach dostępnych w porcie](https://raw.githubusercontent.com/mbloch1/ahoy-ahoy/master/okrety.csv).
 * historyjka powyżej.

 Uwaga! W danych znajdują się (rzadkie; pozorne lub nie) anomalie i nie jest to błąd w zadaniu.

### Cele
 0) Zbadać zasady, na jakich działa model świata na podstawie danych.
 1) Wybrać dwa okręty z dostępnych i zaproponować takie trasy, by dopłynęły z portu macierzystego (tj. pola Q11) do wyznaczonych miejsc (tj. na pola E9 oraz L4, po jednym statku na każde z pól) bez zatrzymywania się po drodze w portach. Maksymalizujemy prawdopodobieństwo, że dopłyną oba jednocześnie (tj. 30% na jednym i 40% na drugim daje 12%).
 2) Zaproponować alternatywny dobór okrętów/tras, żeby zmaksymalizować szanse powrotu. Maksymalizujemy niezależnie (tj. 30% na jednym i 40% na drugim daje 70%).
 3) Podać precyzyjne zasady działania świata (tj. konkretne liczby i reguły).
 4) Postawić hipotezę nt. tajnych celów wyprawy i przygotować komentarz dla Admiralicji.

