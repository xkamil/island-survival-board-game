# Gra planszowa - Island survivors

### Opis gry

Gracze (1-4) wcielają się w role rozbitków na bezludnej wyspie. 
Celem gry jest przetrwanie i ucieczka z wyspy zanim pogarszające sie warunki nie zabiją graczy. 
Gracze muszą zbierać zasoby, rozwijać obóz, zdobywać jedzenie, a także współpracować, aby zbudować tratwę i uciec z wyspy.

### Plansza i komponenty

Plansza zbudowana jest z 30 heksagonalnych pól, które reprezentują różne obszary wyspy.
Typy pól to: las, łąka, bagna, góry, plaża, jezioro, jaskinia, skaly.
Dodatkowo na planszy znajduje się 1 pole obozu oraz 1 pole plaży z miejscem na budowę tratwy.

### Właściwości pól
- las - wymaga 1 PA aby do niego wejść, pozwala na zbieranie drewna i jedzenia oraz polowanie.
- łąka - wymaga 1 PA aby do niego wejść, pozwala na zbieranie ziół i oraz polowanie
- bagna - wymaga 2 PA aby do niego wejść, pozwala na zbieranie włókna
- skały - wymaga 1 PA aby do niego wejść, pozwala na zbieranie kamienia
- góry - nie można na nie wejść
- jezioro - nie można na nie wejść, ale pozwala na łowienie ryb kiedy gracz jest na polu obok
- jaskinia: wymaga 2 PA aby explorować, pozwala na znalezienie ulepszeń, ale także zagrożeń
- pole z obozem: wymaga 1 PA aby wejść, pozwala na rozwój obozu i wytwarzanie przedmiotów
- pole z plażą: wymaga 1 PA aby wejść
- pole z plażą i miejscem na tratwę: wymaga 1 PA aby wejść, pozwala na budowę tratwy i ucieszkę z wyspy

### Zasoby
- drewno - potrzebne do rozbudowy obozu, wytwarzania przedmiotów oraz budowy tratwy
- jedzenie - potrzebne do przetrwania, można je zdobyć polując lub zbierając owoce
- kamień - potrzebny do rozbudowy obozu i wytwarzania przedmiotów
- włókno - potrzebne do rozbudowy obozu oraz budowy tratwy
- zioła - potrzebne do leczenia chorób

### Jedzenie
Każdy gracz po zakończeniu tury musi zjeść 1 jedzenia inaczej traci 1 punkt zdrowia.
Jedzenie przywraca też zdrowie - 1 jedzenie przywraca 1 punkt zdrowia, ugotowane/upieczone jedzenie przywraca 2 punkty zdrowia.
Jedzenie nie ugotowanego/upieczonego jedzenia daje ryzyko choroby. 

### Choroby
Gracze mogą zachorować na różne choroby, które wpływają na ich formę a co za tym idzie na PA.
Każda choroba zabiera 1 punkt akcji do czasu wyleczenia.
Jeśli gracz uzbiera 3 choroby, umiera.
Choroby można leczyć za pomocą ziół, które można znaleźć na polach - 1 zioło leczy 1 chorobę.
Choroby można też leczyć za pomocą lekartstwa wytwarzanego w obozie z ziół. Lekarstwo leczy wszystkie choroby naraz.

### Statystyki gracza
Każdy gracz ma 2 statystyki: zdrowie oraz punkty akcji.
Gracze zaczynają z 5 punktami zdrowia i 5 punktami akcji.
W trakcie gry te statystyki mogą być modyfkowane przez różne czynniki jak choroba (-PA) czy przedmioty (+PA, +HP).
Gracz umiera kiedy jego zdrowie spadnie do 0 lub kiedy uzbiera 3 choroby. W obu przypadkach kończy to grę dla tego gracza.

### Zbieranie zaosbów i polowanie
Gracze mogą zbierać zasoby na polach, które pozwalają na ich zbieranie oraz polować na zwierzęta.
Akcja zbierania zasobow w tym jedzenia wymaga rzutu kością 1K6 na sukces lub porażkę. Wyrzucenie 1-2 oznacza porażkę, 3-6 oznacza sukces i zdobycie zasobu.
Przedmioty znajdowane w jaskiniach lub wytwarzane mogą modykować ten rzut, np. dodając +1 do rzutu, lub rzutu wieloma koścmi i wyboru lepszego wyniku lub zebrania wielu zasobów.

Aby polować gracz musi wytworzyć broń, która pozwala na polowanie. Są 3 rodzaje broni: 
- pułapka pozwala polować na mniejszą zwierzynę na łąkach
- łuk pozwala polować na większą zwierzynę w lesie
- wędka pozwala na łowienie ryb w jeziorze

Polowanie zapewnia więcej jedzenia niż zbieranie, ale wymaga broni która zajmuje miejsce w plecaku.

Zasoby gracza są w jego plecaku, który ma ograniczoną pojemność. Gracz może mieć maksymalnie 10 zasobów w plecaku wliczając jedzenie i przedmioty.
Gracze może w dowolnym momencie przekazać zasoby lub przedmioty innemu graczowi kiedy są na tym samym polu lub sąsiadującym polu.
Po ulepszeniu obozy zasoby można też składować w obozie.

### Rozwój obozu
Gracze mogą rozwijać obóz, który pozwala na wytwarzanie przedmiotów, składowanie zasobów oraz ulepszenia.

Dostępne ulepszenia obozu to: (P = gracz. 2xP = 2 graczy, itd.)
- warsztat - pozwala na wytwarzanie przedmiotów: Wymaga 3xP drewna i 2xP kamień
- skład - pozwala na składowanie zasobów w obozie: Wymaga 2xP drewna i 2xP włókno
- palenisko - pozwala na gotowanie/pieczenia jedzenia, co zwiększa jego wartość odżywczą: Wymaga 2xP drewna i 1xP kamień
- apteczka - pozwala na wytwarzanie lekarstwa z ziół: Wymaga 1xP Kamień 1xP drewna i 1xP włókno
- schronienie - pozwala na regenerację zdrowia graczowi ktory zakończy turę w obozie : Wymaga 3xP drewna i 2xP włókno
