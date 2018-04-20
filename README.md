# Zadanie testowe React Developer

#### Opis
Czas na wykonanie zadania 3h
Aplikacja polega na wyświetleniu listy użytkowników z API wraz z detalami użytkowników.
Użytkownicy są linkami (cały komponent) i przekierowuja na kolejna stronę (użycie routingu) na której będzie wyświetlona lista ich postów.
Pod lista znajduje sie przycisk (dodaj nowy post) który otwiera modal z formularzem do dodania posta.
Każdy post ma pod soba link/przycisk (pokaż/schowaj komentarze) ktory wyswietla/chowa komentarze do danego posta.
Pod komentarzami jest też form który pozwala na dodanie własnego komentarza.
Dodatkowo każdy post zawiera przycisk usuń do usuwania postów.
Na stronie z postami musi być też przycisk do powrotu na stronę z użytkownikami.
Każde połączenie z API (pomiędzy wysłaniem żądania a odpowiedzią) musi wyświetlić loader na stronie który przy okazji zablokuje wszelką interakcję.

#### Wymagania
Własny komputer & ładowarka
Konto na GitHub
Dobra znajomość Javascript
Znajomość react + redux
Umiejętność komunikacji z API

#### Co będzie oceniane?
40% - umiejęt ności techniczne JS/React/Redux
40% - umiejętności miękkie (komunikacja)
20% - znajomość IDE oraz praca z GIT

#### Plan działania w biurze:
Pobierz repozytorium (wszelkie potrzebne paczki powinny byc zainstalowane)
Zapoznaj się z opisem i wytycznymi.
Podziel zadanie na małe etapy.
Zweryfikuj plan działania z opiekunem.
Oddawaj poszczególne etapy jako merge / pull requesty.
Uwzględniaj feedback z code review.
Po akcepcie merge / pull request zajmij się kolejnym etapem.
Działamy do momentu kiedy ukończysz zadanie lub minie czas.

#### Plan działania w trybie remote:
Limitem czasowym jest deadline określony z opiekunem
Sklonuj repozytorium (wszelkie potrzebne paczki powinny byc zainstalowane) i zainstaluj paczki
Stwórz własne repozytorium na githubie i daj dostęp opiekunowi (jeżeli będzie potrzebny)
Stwórz plan działania w punktach (bardzo ogólny) i prześlij go do opiekuna
np:
 - stworzenie store w redux i dodanie go do aplikacji
 - stworzenie podstawy routingu
 - podstrona z userami
 - dodanie akcji do userow
 - polaczenie z API strony z userami
 - ...

Wykonaj zadanie
Zgłoś zakończenie zadania oraz uzupełnij plan -> co było robione w jakiej kolejności
Dolacz listę rzeczy z ktorymi miales problem badz zajely Ci najwiecej czasu

#### Wytyczne:
 - Projekt stawiamy na starterze [create react app](https://github.com/facebook/create-react-app)
 - Do zarządzania stanem używamy [reduxa](https://github.com/reactjs/react-redux)
 - Do routingu używamy [react router [v4]](https://github.com/ReactTraining/react-router)
 - Do formularzy używamy [redux form](https://github.com/erikras/redux-form)
 - Do komunikacji z API używamy [axios](https://github.com/axios/axios)
 - Do modali użyjmy [tego](https://stackoverflow.com/questions/35623656/how-can-i-display-a-modal-dialog-in-redux-that-performs-asynchronous-actions/35641680) sposobu
 - [API](https://jsonplaceholder.typicode.com/)
 - Używamy ES6+
