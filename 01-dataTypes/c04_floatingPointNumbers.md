---

title: Floating Point Numbers
author: soew
version: 1.0
date: 2025-05-21
topic: C-Programming, AIIT, AINF, FI
theme: beige
handout: true

---

# Floating Point Numbers (Kommazahlen)

C-Programmierung - Kapitel 4

---

## Kommazahlen

- Siehe Kapitel [Kommazahlen](https://www.c-howto.de/tutorial/variablen/datentypen/kommazahlen/) im C-[Tutorial](https://www.c-howto.de/tutorial) von C-HowTo.

![image](./_img/04-dataTypes-floats.png)

---

### Die Gleitpunkttypen `float` und `double`

- Siehe auch entsprechendes [Unterkapitel](http://openbook.rheinwerk-verlag.de/c_von_a_bis_z/005_c_basisdatentypen_008.htm#mj357b36b759cbb526c1701f1341d99a96) im [C-Kompendium](https://openbook.rheinwerk-verlag.de/c_von_a_bis_z/index.htm) von Jürgen Wolf.

![image](./_img/04-dataTypes-floatAndDouble.png)

---

### Datentyp `float`

- Von engl. **floating point number** (dt. *Gleitpunkt-Zahl*).
- Anmerkung: Das Dezimalzeichen ist im Englischen ein **Punkt** und kein Komma, daher die ungewöhnliche Bezeichnung!
- Speichergröße 4 Byte = 32 bit.
- Früher der Standard-Datentyp für Kommazahlen auf PCs.
- **Geringe Genauigkeit** von nur 6-7 Stellen!
- Formatkennzeichner `%f`

![image](./_img/04-dataTypes-float.png)

---

### Datentyp `double`

- Von engl. **double precision**, (dt. *doppelte Genauigkeit*).
- Speichergröße: 8 Byte = 64 bit.
- **Standarddatentyp** für Kommazahlen auf PCs!
- **Genauigkeit** mind. 15 Stellen!
- Formatkennzeichner `%lf` (von engl. *long float*).

![image](./_img/04-dataTypes-double.png)

---

## Mathematische Funktionen

- [Referenz](http://cplusplus.com/reference/cmath) der C/C++ Mathematik-Bibliothek unter [cplusplus.com](https://cplusplus.com/)

  - Kurze Funktionsbeschreibungen (engl. *Summary* oder *Synopsis*).
  - Funktionsparameter (auch: *Argumente*).
  - Rückgabewert (engl. *return value*).
  - Code-Beispiele.
  
![image](./_img/04-dataTypes-cReference.png)

---

## Übung `b04_floatingPointNumbers`

- C++ Template und Übungs-Angaben

```c
/*
************************************************************************
   
b04_floatingPointNumbers.cpp

Summary:
The program reads the lengths of legs a and b of a rectangular triangle
as floating point numbers from stdin.

It calculates the hypotenuse c, the angles alpha and beta (in degrees)
and the area.

Results are printed to screen, all numbers right-aligned with two
decimal places.

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
    
    /* done */
    return 0;
}
```
