Laboratorium z sieci komputerowych

Trzecie zadanie zaliczeniowe

Termin włożenia rozwiązania do repozytorium:
13 czerwca 2016, godzina 10.00 (czas na serwerze SVN)

Zaprojektować sieć IPv4 dla małej firmy.

Założenia

1. Firma X połączyła się z firmą Y. Mieści się obecnie w dwóch budynkach: A i B.
2. W budynku A planowane jest umieszczenie zarządu firmy, działu handlowego
oraz księgowości itp. Oprócz tego działa tam również dział rozwojowy byłej firmy X.
3. W budynku B mieści się dział serwisu i dział rozwojowy byłej firmy Y.
4. Między budynkami położono kabel światłowodowy.
5. W budynku A jest kablowy (Ethernet) dostęp do publicznego Internetu
i operator przyznał stały adres 193.1.42.121/24, a domyślnym ruterem
jest 193.1.42.1.
5. W budynku B również jest kablowy (Ethernet) dostęp do publicznego Internetu
i operator przyznał stały adres 201.1.21.21/28, a domyślnym ruterem
jest 201.1.21.30.
6. W każdym budynku powinna być zainstalowana sieć przewodowa zbudowana
na bazie Ethernetu i sieć bezprzewodowa zbudowana na bazie WiFi.
7. Powinien być zapewniony dostęp do Internetu w obu budynkach również 
w przypadku awarii kabla łączącego budynek B z dostawcą Internetu.
8. Fragmenty sieci przewodowej używane przez programistów z działów
rozwojowych powininny być szczególnie chronione przed dostępem z zewnątrz.
9. Firma będzie chciała udostępniać własny serwis WWW.
10. Poszczególne działy firmy potrzebują serwerów z różnego rodzaju
oprogramowaniem: system finansowo-księgowy, baza danych, repozytorium
oprogramowania itp.
11. Wszystkie maszyny, które nie muszą mieć stałego adresu IP, powinny
dostawać go za pomocą DHCP.
12. Przewidujemy, że w każdym z budynków będzie działało około 50
maszyn stacjonarnych i około 50 maszyn z kartami WiFi.
13. W każdym budynku przewidziano jedno pomieszczenie na sprzęt
sieciowy, tzw. serwerownię.

Oczekiwana zawartość projektu

1. Określenie rodzaju i liczby urządzeń sieciowych, które będą
potrzebne, czyli np. przełączniki, rutery, maszyny serwerowe itp.
2. Rysunek ze schematycznym projektem fizycznego połączenia urządzeń
sieciowych
3. Rysunek przedstawiający logiczną konfigurację sieci, czyli schemat
połączenia ruterów, zapór ogniowych, serwerów i agentów poszczególnych
usług, wirtualnych interfejsów sieciowych itd.
4. Przydział nazw interfejsów sieciowych, które takiej nazwy wymagają.
5. Przydział adresów IP dla interfejsów sieciowych, które tego wymagają.
6. Przydział nazw hostów, które tego wymagają.
7. Dla każdego rutera jego tablica tras, gdy wszystkie połączenia działają
oraz zmodyfikowane tablice dla sytuacji awaryjnej.
8. Reguły NAT
9. Schemat przydzielania adresów IP i wewnętrznych nazw domenowych

Wszelkie wątpliwości należy uzupełnić zgodnie ze zdrowym rozsądkiem.
Zdrowy rozsądek też punktujemy.

Projekt należy wykonać w formacie PDF. Na pierwszej stronie powinno się
znaleźć imię i nazwisko autora projektu. Plik z rozwiązaniem zadania
o nazwie projekt-sieci.pdf należy umieścić w repozytorium SVN

https://svn.mimuw.edu.pl/repos/SIK/

w katalogu

students/ab123456/zadanie3/

gdzie ab123456 to standardowy login wg schematu: inicjały, nr indeksu,
używany na maszynach wydziału.
