## Tworzenia bazy danych SQL serwer
Ekran towrzenia bazy danyc. Nalezy wybrac nazwem, grupe zasobów oraz serwer bazy danych. Jeśli któryś z parametrów nie istnieje nalezy go utworzyć.

![Initial Setup](https://github.com/user-attachments/assets/f6527055-1b04-4f8a-a962-99bd52947637)

## Tworzenie serwera bazodanowego
Przy tworzeniu serwera nalezy podac nazwe oraz wybrac sposób logowania. Wybrano autentkykacje za pomocą SQL.

![Creating Server](https://github.com/user-attachments/assets/0509de5a-1026-4579-8dca-264f1ba800db)

## Ustawienia sieciowe
Aby połączyć sie z bazą za pomocą Azure Data Studio niezbedne jest ustawienie dostepu na public.

![Network Settings](https://github.com/user-attachments/assets/79104a0b-8a1a-491f-9a88-1394088cba15)

## Wybór bazy danych
Do celów testowania bazy wybrano predefiniowana przykładową baze.

![Select Database](https://github.com/user-attachments/assets/9e601c48-fa17-4527-ae47-95a9d0068793)

## Połączenie z bazą w Azure Data Studio
Ekran nawiązywania połączenia z utworzona baza danych w aplikacji Azure Data Studio

![Connecting to Database](https://github.com/user-attachments/assets/cb9dab30-c8dd-4021-a52c-05e5507abf84)

## Screen z konsoli - pobieranie danych ze stworzonej bazy danych
Na terminalu wyświetlono rekordy pobrane z bazy przez aplikacje w C# 

![Data Retrieval](https://github.com/user-attachments/assets/dc129dd4-47e7-453c-89e6-a719622797ea)

## Setup wirtualnej maszyny
SPecyfikacj utworzsonej wirtualnej maszyny

![VM Setup 1](https://github.com/user-attachments/assets/c9a36460-25dd-45e1-b41a-baa3273f5dae)
![VM Setup 2](https://github.com/user-attachments/assets/490b4f9f-93ca-4870-a92e-c3b668832d1e)
![VM Setup 3](https://github.com/user-attachments/assets/50c98f3b-b35a-440e-85fd-9c3073902fc9)

## Tworzenie storage account
W celu utowrzenia Azure Table Storage niezbedne jest utworzenie storage account

![Storage Account](https://github.com/user-attachments/assets/484c0948-8780-46c1-bbc6-24c63a0748ef)

## Dodawanie danych do bazy
Po utworzeniu bazy mozna dodawac do niej dane z poziomu GUI

![Adding Data 1](https://github.com/user-attachments/assets/5d0bedf6-4e21-4446-a7bc-75d3af3bba99)
![Adding Data 2](https://github.com/user-attachments/assets/56fc24f2-8297-40f5-823e-9e2d92f07494)

## Screen z konsoli programu łączącego się z bazą danych
Screeny z konsoli programu w C# który dodaje nowy rekord, edytuje go oraz usuwa rekord którey był wczesniej w bazie. Na drugim screenie widac stan bazy po wykonaniu programu

![Program Connection 1](https://github.com/user-attachments/assets/938fe958-b04a-46b8-9ca9-b00db59cf28f)
![Program Connection 2](https://github.com/user-attachments/assets/d594ae92-ae92-4aec-a13e-b67c767d474b)

## Dodanie zasad do firewall
DO firewalla dodano adres uzytkownika. 

![Firewall Rules](https://github.com/user-attachments/assets/81a0f196-f56b-422e-92fb-96cb74cad540)

## Stworzenie konta cosmos db
Do uzycia cosmos db niezbedne jest utowrzenie konta Cosmos DB 

![Cosmos DB Account](https://github.com/user-attachments/assets/c5b0961d-32f0-48d8-abcf-3f332914549e)

## Przykładowe zapytania do bazy

![Query Example 1](https://github.com/user-attachments/assets/033cc04a-d972-446b-8ba8-16c7675dc4ad)
![Query Example 2](https://github.com/user-attachments/assets/828f33ad-9f84-4ecd-8218-59f80194cfcc)

## Aplikacja łącząca się z bazą
Screen z konsoliu aplikacji łączącej sie z baza danych


![App Connection 3](https://github.com/user-attachments/assets/076608b3-2b1d-4034-9326-87369054622a)

## Zmiana limitu RU
Zmiana limitu RU's na 10

![Change RU Limit](https://github.com/user-attachments/assets/562ec70b-f397-42e5-964c-863df7c5d7ea)


## Monitorowanie 
Widać ze po zmniejszeniu RU's napisana aplikacja nie moze zostac obsluzona przez baze ponieaz wymaga zbyt wiele RU.

![App Connection 1](https://github.com/user-attachments/assets/c5fb33d1-6f7b-4ed7-9ce9-aaedb62bdfd0)
![App Connection 2](https://github.com/user-attachments/assets/85674e2d-28f5-497c-9863-7bb4db354c8b)

