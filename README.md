# **Spis treści**
1. [Task 1](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#task-1)
2. [Subtask 1](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#subtask-1)
3. [Subtask 3](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#subtask-3) - kim jestem, co tu robię. 
4. [Subtask 4](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#subtask-4)
   * [Na czym polega aplikacja? Do czego służy?](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#1-na-czym-polega-ta-aplikacja-do-czego-s%C5%82u%C5%BCy)
   * [Jakie funkcje znajdują się w aplikacji?](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#2-jakie-funkcje-znajduj%C4%85-si%C4%99-w-aplikacji)
   * [Interfejs aplikacji](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#3-interfejs-aplikacji)
   * [Intuicyjność aplikacji](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#4-intuicyjno%C5%9B%C4%87-aplikacji)
   * [Błędy](https://github.com/AnnaMatysiak91/challenge_portfolio_AniaMatysiak/edit/main/README.md#5-b%C5%82%C4%99dy)

# **TASK 1**
### _SUBTASK 1_
10 
### _SUBTASK 3_

<p align="justify">
Cześć, nazywam się Ania :smiley: wzięłam udział w projekcie, ponieważ myślę o przebranżowieniu. Projekt da mi szansę zobaczyć "z czym się je" testowanie,  dzięki czemu podejmę decyzję czy chciałabym iść w tym kierunku. Liczę na to, że dzięki Wam poznam podstawy testowania, co będę mogła później rozwijać 
( o ile to jest to :blush:)</p>

Ponieważ jestem totalnym komputerowym laikiem, traktuję też projekt jak wyzwanie i ruszenie szarych komórek do pracy	:upside_down_face:

### _SUBTASK 4_ [Testowanie aplikacji dla skautów piłki nożnej.](https://scouts-test.futbolkolektyw.pl/pl)

#### 1. Na czym polega ta aplikacja? Do czego służy?
Jest to aplikacja służąca do zarządzania graczami, meczami i do tworzenia raportów. Ułatwia śledzenie postepów danych zawodników, drużyn czy przebieg meczów. 

#### 2. Jakie funkcje znajdują się w aplikacji:
W aplikacji znajdują się takie funkcje jak:
  * Możliwość charakterystyki poszczególnych zawodników, drużyn, meczy. 
  
    <p align="justify">Intuicyjnie weszłam w zakładkę "gracze" i przeklikałam się przez opcje mecze i raporty. Uważam, że opcja "dodaj gracza" powinna być również możliwa z poziomu "gracz", nie tylko ze strony startowej.</p> 
    
  * Możliwość tworzenia raportów dla danego zawodnika, drużyn.
  
    <p align="justify">Tworzenie raportów jest możliwe jedynie z poziomu "gracze", żeby stworzyć raport dla danego zawodnika, należy odpowiednio wyfiltrować dane. Łatwiej by było, gdyby raport można było stworzyć z poziomu zawodnika. Dodatkowo przy kolumnach dodałabym znaczek sortowania, jest mniej estetyczny, ale można nie zauważyć tej opcji. Dodatkowo dodałabym możliwość filtrowania i sortowania w zakładce mecze i raporty.</p> 
    
  * Na podstawie wprowadzonych danych, można odtworzyć przebieg meczu i na jego podstawie stworzyć statystyki i raport.
  
    Szczerze mówiąc zgaduję, że tak to działa, ta część strony jest dla mnie niezrozumiała. 
    
  * Funkcja szukaj pozwala na wyszukanie interesującego nas zagadnienia. 

#### 3. Interfejs aplikacji:
<p align="justify">Aplikacja jest prosta, dzięki czemu przejrzysta. Jednak na pierwszy rzut oka strona główna wygląda mało profesjonalnie, raczej na potrzeby małej drużyny sportowej :blush: Mimo wszystko działa szybko.</p>  

#### 4. Intuicyjność aplikacji:
<p align="justify">Dla mnie aplikacja była dość intuicyjna, nie jestem jednak pewna czy każdy by wiedział, że po kliknięciu dwa razy w zawodnika, odkryje się przed nim wieęcej opcji, jak raporty czy możliwość dodawania meczy. Podobało mi się za to, że po najechaniu na ikonki, pojawiają się ich opisy, co ułatwia korzystanie z aplikacji.Intuicyjnie klikałam w logo strony, żeby przekierowała mnie na stronę startową, myślę, że byłoby to sporym ułatwieniem, mimo że "strona główna" znajduje się zaraz pod nim. Na plus dodałabym również wyraźnie widoczną opcję zmiany języka na angielski.</p> 

##### 5. Błędy:
Myślę, że wyłapałam kilka błędów, nie jestem jednak pewna czy wszystkie powinny znaleźć się akurat w tym podpunkcie :sweat_smile:
  * Przy wprowadzaniu danych gracza, w polach w których można wproadzić treść, nie ma ograniczenia liczby znaków. Może to powodować błędu oraz psuje to czytelność
    tabeli z graczami przy filtrowaniu po imieniu. Sprawia też, że do odczytywania tabeli konieczny jest suwak - można nie zauważyć przez to opcji akcji w zakładce
    "mecze".
  * Treści dodane w polach przy wprowadzaniu danych nie mają żadnych ograniczeń - waga może być na minusie, a rocznik gracza z XIII wieku :upside_down_face:
  * Po ściągnięciu tabeli z graczami, excel nie jest poprawnie sformatowany. 
  * Opcja "dodaj raport" w zakładce "raporty" przekierowuje do "dodaj mecz".
  * W "edycja gracza" w linku do YT można dodać jakąkolwiek treść, nie musi to być link.
  * Na stronie głównej w słowie "Aktywnosć" jest błąd - "s" zamiast "ś". 
  * Nie działa opcja "wróć do raportu" przy niezapisanym meczu na stronie głównej - devtools pokazuje błąd:
    >Uncaught (in promise) Error: The provided f542032078bbadf019700308e0ffe503d5056449.e5058d62b3c6fbb81936.js:1 `as` value  (/pl/players/6026b48956c79737b3f3c624/reports/start) is incompatible with the `href` value (/players/[id]/reports/start).
  * Nie można tworzyć ani ściągnąć raportu z poziomu gracza.
  * Opcja "clear" w edycji meczu nie działa, jeżeli jest niepotrzebna, powinna być usunięta. 

No to chyba na tyle :smiley: Pozdrawiam, Ania :blush:
