---

title: Conditional Statements
author: soew
version: 1.0
date: 2025-06-17
topic: C-Programming, AIIT, AINF, FI
theme: beige
handout: true

---

# Verzweigungen

C-Programmierung - Kapitel 5

---

## Verzweigungen - Intro

- Siehe Kapitel [Verzweigungen](https://www.c-howto.de/tutorial/verzweigungen/) im C-[Tutorial](https://www.c-howto.de/tutorial) von C-HowTo.

![image](./_img/05-conditionals.png)

---

## `if`-`else`-Anweisung

- Siehe Unterkapitel [if und else](https://www.c-howto.de/tutorial/verzweigungen/if-und-else/).

![image](./_img/05-if-else-statement.png)

---

## Übungsaufgabe

- Erstelle ein Programm, das das Volumen eines Würfels berechnet und am Bildschirm ausgibt.

- Die Kantenlänge wird über die Tastatur eingegeben.

- **Falls** eine positive Kantenlänge eingegeben wird, soll das richtige Ergebnis berechnet und am Bildschirm ausgegeben werden, **ansonsten** soll die Ausgabe einer Fehlermeldung erfolgen und das Programm mit einem Fehlercode 1 schließen.

- [&rarr; Lösung](./c05_if-else-xrcs.md)

---

## Vergleichsoperatoren

- Siehe Unterkapitel [Vergleichsoperatoren](http://www.c-howto.de/tutorial/verzweigungen/vergleichsoperatoren/)

| Vergleich           | Operator |
| :------------------ | :------: |
| ungleich	          | `!=`     |
|    gleich           | `==`     |
| größer	          | `>`      |
| größer oder gleich  | `>=`     |
| kleiner             | `<`      |
| kleiner oder gleich | `<=`     |

---

## Übung `b04_floatingPointNumbers`

- C++ Template und Übungs-Angaben

```c
/*
************************************************************************
   
b05_conditionals.cpp

Summary:
Program calculates billing charge for an online purchase based on unit
price and amount purchased.

Read unit price and amount purchased from stdin, and calculate total
price.

If total price is greater or equal to 35.00 Euros, the billing charge
is equal to the total price minus 2 percent discount. Else, a shipping
charge of 3.90 Euros (sybolic constant SHIPPING) is added to the total
price.

Independent of the above condition, the billing charge and the VAT
(dt. USt.), which is 16.67 percent of the billing charge are printed
to screen:, e.g.,

Gesamtpreis ...........     39.20 Euro
Enthaltene USt. .......      6.55 Euro

************************************************************************
*/

#define _CRT_SECURE_NO_WARNINGS // allow scanf() in Visual C++

#include <cstdlib>   // system()
#include <cstdio>    // printf(), scanf()
#include <iostream>  // cin, cout, endl
using namespace std; // std::cout ---> cout


/* main program */
int main()
{
    
    /* wait for keystroke */
    // system("PAUSE");
    
    /* exit success */
    return 0;
}
```


- Abgabe im Kursnotizbuch - Arbeitsaufträge ...

  - Quellcode von `b04_floatingPointNumber.cpp` als PDF und Ausdruck

  - Bildschirmausschnitt der Programmausgabe








