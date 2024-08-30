Ten program symuluje działanie maszyny do kawy, która umożliwia użytkownikowi zakup różnych napojów kawowych (espresso, latte, cappuccino). Program monitoruje zasoby (woda, mleko, kawa) oraz śledzi zarobione pieniądze.

Główne funkcje:

- check_resources(key_list):
Sprawdza, czy dostępne zasoby (woda, mleko, kawa) są wystarczające do przygotowania wybranego napoju kawowego.
Jeśli zasobów jest za mało, wyświetla komunikat o ich braku.

- process_coins():
Obsługuje proces wrzucania monet przez użytkownika i sprawdza, czy wprowadzona kwota jest wystarczająca do zakupu wybranego napoju.
W przypadku, gdy kwota jest większa od ceny napoju, zwraca resztę.
W przypadku, gdy kwota jest niewystarczająca, zwraca monety użytkownikowi.

Program działa w pętli, pytając użytkownika, co chciałby wypić: espresso, latte, cappuccino lub też zakończyć działanie maszyny (off).
Wpisanie report wyświetla bieżący stan zasobów (woda, mleko, kawa) oraz zarobione pieniądze.
Program przetwarza wybór użytkownika, sprawdzając zasoby, przetwarzając monety i dokonując odpowiednich operacji.

Przykład użycia:
Program prosi użytkownika o wybór napoju: "What would you like to drink? (espresso/latte/cappuccino):".
Jeśli użytkownik wybierze "espresso", program sprawdzi, czy dostępna jest wystarczająca ilość wody i kawy.
Użytkownik zostanie poproszony o wrzucenie monet i podanie ich liczby (quarter, dime, nickel, penny).
Jeśli wpłacona kwota jest wystarczająca, program przygotuje kawę, wyda resztę (jeśli jest taka potrzeba) i zaktualizuje stan zasobów.
Proces powtarza się do momentu, gdy użytkownik wpisze "off", co wyłączy program.
