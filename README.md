# Zadanie: klasa Trojkat

* Krzysztof Molenda, ver. 0.1

Utwórz klasę Trojkat spełniającą następujące założenia:

1. Obiekt klasy Trojkat reprezentuje figurę geometryczną trójkąt, opisaną długościami trzech jej boków.

1. Obiekty klasy Trojkat są niezmiennicze.

1. Trójkąt domyślny, to taki, o bokach o długościach 1.

1. Należy dostarczyć funkcjonalności:
    * Wyliczenie pola powierzchni
    * Wyliczenie obwodu
    * Zwrócenie informacji, czy trójkąt jest prostokątny, rozwartokątny, ostrokątny
    * Zwrócenie informacji, czy trójkąt jest równoboczny, czy jest równoramienny
    * Eksport do postaci tekstowej

1. UWAGA:
    * W sytuacji podania niedodatnich długości boków, obiekt nie może powstać - zgłoszenie wyjątku ArgumentOutOfRangeException
    * Nie dla każdych podanych długości trzech boków można utworzyć trójkąt - muszą spełniać tzw. warunek trójkąta. W takiej sytuacji zgłoszenie wyjątku ArgumentException
    * Pole powierzchni trójkąta, przy zadanych długościach boków, można obliczyć ze wzoru Herona.

Napisz interaktywny program konsolowy weryfikujący funkcjonalność klasy Trojkat.

Przykładowy scenariusz:
1. Program prosi o podanie trzech długości boków.
2. Jeśli podane dane nie są numeryczne, zgłasza wyjątek i kończy pracę.
3. Tworzony jest obiekt typu Trojkat o zadanych bokach.
4. Wypisywane są na konsolę parametry trójkąta (obwód, pole, czy prostokątny, ostrokątny lub rozwartokątny).
5. Jeśli trójkąt jest równoramienny lub równoboczny, stosowna informacja wypisywana jest na konsolę.
  
