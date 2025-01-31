# Modelowanie Biznesowe

Perspektywa modelowania systemu. Zapewnienie komunikacji i lepsze zrozumienie między biznesem, a IT.
W jaki sposób opisać organizację, procesy, role systemu.

# Model biznesowy

Plan określający relacje między elementami systemu i wartość jaką dostarcza. Składa się z

-   cele
-   procesy
-   reguły biznesowe
-   strategia
-   zasoby

# Obszary modelowania biznesowego

-   analityka deskryptywna - na podstawie danych historycznych, statystyki, np. raport sprzedaży z ostatniego roku
-   analityka preskryptywna - optymalizacja, symulacja, prognozowanie, np. obliczanie co lepiej sprzedawać w danym momencie
-   analityka predyktywna - prognozowanie w czasie, np. prognozowanie sprzedaży na przyszły rok

# Proces

Składa się z nazwy, wejścia, wyjścia i ograniczeń. Prowadzi do wytworzenia jakiejś wartości.

# Typy procesów

-   jak działa (AS-IS),
-   jak mógłby działać (SHOULD-BE),
-   jak ma działać (TO-BE).

# Ilościowe miary procesów

-   czas wykonania (CW) - cały czas realizacji
-   czas oczekiwania (CO) - czas kiedy nic się nie dzieje bo czekamy na coś (np. podwykonawcę)
-   czas transportu (CT) - czas od końca jednego procesu, do rozpoczęcia kolejnego
-   koszty (K) - cały koszt procesu

# Jakościowe miary procesów

-   satysfakcja klienta
-   zmniejszenie kroków w procesie
-   zmniejszenie użycia zasobów (np. papieru)
-   zmniejszenie liczby osób w procesie
-   elastyczność procesu (możliwość zmiany i adaptacji)
-   jakość procesu (liczba błędów, terminowość)

# Materialne miary procesów

-   efektywna alokacja zasobów
-   racjonalność inwestycji
-   optymalizacja procesów
-   spójność podejmowanych decyzji
-   efektywna ocena ilościowa zdarzeń przeszłych
-   poziom kosztów
-   poziom zapasów
-   wielkość sprzedaży
-   poziom zysku
-   zwrot z zaangażowanego kapitały
-   zwrot z akcji
-   udział w rynku
-   zaspokojenie potrzeb różnych grup interesariuszy

# Niematerialne miary procesów

-   przekonanie i motywacja
-   wiedza, umiejętności, doświadczenie
-   zrozumienie i akceptacja misji, i celów strategicznych
-   kultura organizacji
-   komunikacja wewnętrzna
-   ocena jakościowa zdarzeń przeszłych
-   elastyczność organizacji
-   jakościowe uwarunkowania zewnętrzne
-   marka produktu (usługi)
-   wizerunek przedsiębiorstwa
-   reputacja i prestiż
-   jakość produktów i usług
-   motywacja
-   satysfakcja zainteresowanych stron

# Strategia departamentowa

Klient składa i kończy zamówienie, a proces idą po kolei przez różne departamenty.
Pracownicy przekazują zadania przez przełożonych.

# Strategia procesowa

Pracownicy bezpośrednio przekazują sobie zadania.

# Poziomy dojrzałości procesowej

-   chaos
-   powtarzalność
-   standaryzacja
-   zarządzanie procesami
-   ciągłe doskonalenie

# Business Process Reengineering (BPR)

Fundamentalne i radykalne przeprojektowanie procesów. Stosujemy gdy

-   problemy z jakością, kosztami
-   zmieniające się cechy klientów i warunki ekonomiczne
-   ambitne cele biznesowe

# Cel modelowania biznesowego

-   optymalizacja procesów
-   czas i koszty
-   przygotowuje do zmian do wdrożenia
-   pomaga zrozumieć specyfikę firmy

# Dlaczego warto modelować

-   sprawniejsza komunikacja
-   efektywniejsze szkolenia
-   sprawniejsza perswazja i sprzedaż
-   sprawniejsza analiza
-   zarządzanie zgodnością
-   zarządzanie wymaganiami
-   automatyzacja
-   zarządzanie wiedzą

# Unified Modeling Language (UML)

-   notacja - czytelny i jednoznaczny
-   metamodel (semantynka) - ściśle określone znaczenie

Rodzaje diagramów

-   strukturalne (komponenty, obiekty, elementy procesu)
    -   pakietów
    -   klas i obiektów
    -   struktur złożonych
    -   komponentów
    -   wdrożenia
-   behawioralne (kroki, przepływ procesu)
    -   przypadków użycia
    -   czynności
    -   maszyny stanowej
    -   interakcji (sekwencji, komunikacji)
    -   uwarunkowań czasowych

# Perspektywy UML

-   zewnętrzna - opisuje interakcje systemu z klientami i partnerami od zewnątrz
-   wewnętrzna - opisuje wewnętrzny proces

# Elementy biznesowe UML

-   aktor biznesowy - ktokolwiek powiązany z systemem
-   pracownik biznesowy - pracownik organizacji
-   klasa przechowująca - fizyczny używany i przetwarzany byt
-   pracownik kontaktu - pracownik w bezpośrednim kontakcie z aktorami
-   przypadek użycia - proces biznesowy
-   jednostka organizacyjna - zgrupowanie obiektów
-   czynność biznesowa - określa zachowanie złożone z wielu kroków

# Diagram kontekstowy

Przedstawia ogólny kontekst przedsiębiorstwa z otoczeniem.

# Mapa procesów

Diagram kontekstowy ale z pracownikami i procesami.

# Diagram przypadków użycia

Przedstawia związki między aktorami, a przypadkami użycia.

# Diagram klas

Opisuje związki między pracownikami, a obiektami biznesowymi.

# Rozszerzalność UML

-   stereotypy - nadaje dodatkowe znaczenie, np. `<<actor>>`, `<<rozkazuje>>`
-   tagi/metki/tagowanie - specyficzne dla zastosowania dodatkowe dane, np. `{wersja = 1.1}`
-   ograniczenia - warunki i ograniczenia

# Rozszerzenia Erikksona-Penkera

Przydatne dla systemów informatycznych. Wprowadza

-   role
-   jednostki organizacyjne
-   zasoby
-   bardziej szczegółowe przedstawienie procesów

# Poziomy modelowania

Używamy taki jaki jest potrzebny poziom szczegółowości.

-   model poglądowy - ogólny, bez zagadnień technicznych. Dla menadżerów, zarządu
-   model analityczny - ocena rozmiaru prac do wykonania, bez definicji. Dla analityków
-   model wykonalny - precyzyjny, wszystko jest. Dla wdrażających procesy w firmie
