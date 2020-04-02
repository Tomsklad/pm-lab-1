# Parametry projektu
Nazwa:  pm-lab-1  
Autor:  Tomasz Składanek (tomasz.skladanek@student.wat.edu.pl)  
Opis:   Projekt bazowy repozytorium na pierwsze spotkanie laboratoryjne z przedmiotu *Programowanie mikrokontrolerów*.  
Wersja: v1.0  
Data:   02.04.2020 r.  

# Informacje o studencie
Imię i nazwisko studenta:   Tomasz Składanek  
Numer albumu:               72021  
Grupa studencka:            WEL18EQ5S1  

# Pytania do zadań z instrukcji
## Zadanie 2-2-1a:
Pytanie:    *Jaki jest efekt działania programu?*  
Odpowiedź:  Uruchomienie symulacji powoduje świecenie wbudowanej żółtej diody oznaczonej na płytce symbolem L. Przytrzymanie przycisku powoduje jej wyłączenie. Po zwolnieniu przycisku dioda znów się zapala.

Po dodaniu funkcji delay() z parametrem 500. Dioda LED zapala się zgodnie z założeniem na 0,5 sekundy, co 1 sekundę.

## Zadanie 2-2-2:
Pytanie:    *Czy zamienienie kolejności podłączenia diody LED i rezystora ma znaczenie?*  
Odpowiedź:  Nie ma znaczenia.

## Zadanie 2-2-3:
Pytanie:    *Czy każdy rodzaj pętli jest wymienny (zawsze można zastąpić jedną konstrukcję drugą)?*  
Odpowiedź:  Nie. Niektóre instrukcje wymagają chociaż jednokrotnego uruchomienia. W takim przypadku można użyć pętli konstrukcji "do {} while {}". Pętla "while" wykonywana jest zawsze gdy spełniony jest zadany warunek. Do wyjścia z niej można sterować warunkiem lub poleceniem "break". Natomiast pętla "for" uwzględnia możliwość zadeklarowania zmiennej wewnątrz jej struktury, zadania warunku, oraz inkrementacji/dekrementacji tej zmiennej np. for(int i = 0; i<3; i++). 

## Zadanie 2-2-4:
Pytanie:    *Jak wpływa na działanie układu zwiększenie wartości stałej LED_T (np. do 100 ms)?*  
Odpowiedź:  Dioda LED będzie świeciła przez 100 ms.

## Zadanie 2-3-1:
Pytanie:    *Jakie niedogodności z punktu widzenia kierowców są obecne w programie sterującym światłami?*  
Odpowiedź:  Przycisk zmiany świateł dla pieszych zmienia natychmiastowo na światło czerwone sygnalizator przeznaczony dla kierowców. Nie ma również odstępu pomiędzy ponownym użyciem przycisku dla pieszych co umożliwia całkowite wstrzymanie ruchu przez złośliwego pieszego. 

## Zadanie 2-3-2:
Pytanie:    *Czy możliwe jest sterowanie stanem niskim (LOW) diod LED?*  
Odpowiedź:  Tak jest ono możliwe.

# Zadania rozszerzajace
## Zadanie 3-1:
Pytanie:    *Określić wady i zalety operowania na rejestrach mikrokontrolera.*  
Odpowiedź:  Rejestr pozwala na szybkie przechowywanie w pamięci zmiennych. Jest to szybka operacja jednakże skomplikowana do wykorzystania.

## Zadanie 3-2:
Pytanie:    *Jaka jest treść nadawnaego tekstu? Proszę zapisać postać jawną i zakodowaną.*  
Odpowiedź:  ...

## Zadanie 3-3:
Pytanie:    *Kiedy programowe generowanie sygnału PWM ma zastosowanie i jakie pociąga to za sobą konsekwencje.*  
Odpowiedź:  ...


