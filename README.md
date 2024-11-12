# Gra konsolowa w zgadywanie liczb przez komputer

## Opis

W tej grze użytkownik wybiera sobie liczbę z zakresu 1–1000, a zadaniem komputera jest jej odgadnięcie. Komputer zgaduje liczbę w maksymalnie 10 próbach, zakładając, że użytkownik udziela poprawnych wskazówek.

### Zasady gry

1. **Wybór liczby:** Użytkownik myśli o liczbie z zakresu 1–1000.
2. **Próby zgadywania:** Komputer zgaduje liczbę, a użytkownik odpowiada, czy liczba jest:
   - `"Too small"` – gdy liczba podana przez komputer jest za mała,
   - `"Too big"` – gdy liczba jest za duża,
   - `"You won"` – gdy komputer trafił poprawną liczbę.
3. **Limit prób:** Komputer odgadnie liczbę maksymalnie w 10 krokach, jeśli gracz odpowiada zgodnie z prawdą.

### Jak uruchomić program

1. Upewnij się, że masz zainstalowanego Python 3.x
2. Pobierz repozytorium Gra_w_zgadywanie-_liczb_2
3. W terminalu przejdź do lokalizacji pliku i uruchom program poleceniem:
   python3 app.py