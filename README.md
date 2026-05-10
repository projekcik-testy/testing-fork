# testing-fork
lets play

repo do testów i zabawy z gałeziami, wspólnymi commitami itp. mOże też wspólne projekciki, idee i pomysły.
Kto chętny to zapraszam.

Nie bój się, że coś zepsujesz!
Główna gałąź (main) jest zablokowana i chroniona. Nikt nie może przypadkowo nadpisać naszego głównego kodu. Każda zmiana musi przejść przez tzw. Pull Request
Do pracy w tym projekcie używamy uv – ultraszybkiego menedżera pakietów, który zastępuje tradycyjnego pipa i dba o to, żebyśmy wszyscy mieli dokładnie te same wersje bibliotek 

Krok 1
Jeśli jeszcze nie masz uv na swoim komputerze, otwórz terminal i zainstaluj go.

Krok 2
Otwórz terminal (lub terminal w VS Code), wejdź do folderu, w którym trzymasz projekty, i wpisz
git clone https://github.com/projekcik-testy/testing-fork.git
cd testing-fork


Krok 3
Mamy w projekcie plik pyproject.toml, który zawiera listę wszystkich naszych bibliotek. Aby je pobrać i stworzyć wirtualne środowisko wpisz w terminalu:

uv sync

Krok 4 Współpraca

Zasada numer 1: Nigdy nie pracujemy bezpośrednio na gałęzi main!

Za każdym razem, gdy chcesz dodać nowy model, analizę lub plik, wykonuj te kroki:
1. Zaktualizuj swój kod (żeby mieć to, co zrobili inni):
git pull origin main
2. Stwórz nową gałąź:
git checkout -b nowa-galaz
3. Pisz kod, ucz się, baw
4. Zapisz i wyślij swoje zmiany
git add .
git commit -m "Dodano nowy notatnik - cokolwiek piszesz"
git push -u origin nazwa-twojej-galezi


Krok 5. pull request i code review
** Ponieważ gałąź main jest chroniona, Twój kod nie połączy się z nią automatycznie.

1. Wejdź na stronę naszego repozytorium na GitHubie.

2. Powinien pojawić się żółty/zielony baner z Twoją gałęzią – kliknij "Compare & pull request".

3. Opisz krótko, co zrobiłeś/aś, i utwórz Pull Request.

4. Teraz uwaga: Musisz poprosić kogoś z zespołu o sprawdzenie kodu! Zgodnie z naszymi zasadami, przynajmniej jedna osoba z grupy musi wejść w Twój kod, przejrzeć go i kliknąć "Approve" (Zatwierdź)
   
5.Dopiero wtedy przycisk Merge zaświeci się na zielono i Twój kod oficjalnie znajdzie się w głównym projekcie. Sprawdzajcie sobie nawzajem kod – to najlepsza metoda nauki! **

W razie konfliktów lub problemów z gitem – piszcie śmiało na dyskusji - zakładka discussion


