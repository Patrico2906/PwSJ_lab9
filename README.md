# PwSJ_lab9 ====== PYTHON (1)
Treści zadań : 
Laboratorium 7
UWAGA: Utwórz plik `mojeklasy.py` a w nim zrealizuj kody z zadania 1-3. Wpisz w pliku następujące
instrukcje:
def testy():
 pass
if __name__ == "__main__":
 testy()
W funkcji testy() będzie znajdował się program testowy, w którym będą deklaracje obiektów oraz
czynności wykonywane na obiektach. W Python nie potrzebna jest funkcja startowa, ale dobra
praktyka wskazuje, aby takiej funkcji używać (u nas to jest właśnie testy())
Zadanie 1. Napisz klasę Punkt2D zawierającą dwa pola x, y definiujące współrzędne punktu. Zrealizuj
metodę Drukuj(), która wydrukuje współrzędne. Zrealizuj metodę Zeruj(), która wyzeruje
współrzędne. Pokaż w przykładowym kodzie jak działają utworzone metody na egzemplarzu klasy
(obiekcie).
Zadanie 2. Napisz klasę Punkt3D, która dziedziczy po klasie Punkt2D. Klasa Punkt3D powinna mieć
dodatkowe pole (względem klasy Punkt2D), które określa trzecią współrzędną z. Sprawdź jak działają
metody Drukuj() i Zeruj()? Popraw metody tak aby drukowały i zerowały wszystkie współrzędne.
Pokaż w przykładowym kodzie jak działają utworzone metody na egzemplarzu klasy (obiekcie).
Zadanie 3. Utwórz klasę Odcinek() i wykorzystaj w niej do określenia współrzędnych odcinka
Punkt2D. Napisz metodę zwracającą długość odcinka. Pokaż w przykładowym kodzie jak działają
utworzone metody na egzemplarzu klasy (obiekcie).
Zadanie 4. Utwórz plik program.py w tym samym katalogu co mojeklasy.py. W pliku tym umieść taką
samą zawartość jak w UWAGA. Wykonaj import biblioteki z utworzonymi klasami: import mojeklasy.
Spróbuj uruchomić zadania 1-3 posługując się odniesieniami tylko do samych obiektów z biblioteki
mojeklasy. Uwaga: jeżeli w bibliotece `mojeklasy` jest klasa o nazwie `Pilka` to przykładowo można
stworzyć obiekt na zasadzie p1 = mojeklasy.Pilka(). W tym zadaniu chodzi o przetestowanie takiej
konwencji.
