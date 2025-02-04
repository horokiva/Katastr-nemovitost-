# Land Register System

Tento projekt je jednoduchý systém pro správu katastru nemovitostí napsaný v C++.
Umožňuje přidávat, mazat a spravovat nemovitosti na základě města, adresy nebo regionu,
a zároveň poskytuje funkce pro změnu vlastníka a výpis seznamů.

## Použité technologie

- C++ – hlavní programovací jazyk

- STL (Standard Template Library) – std::vector, std::sort, std::lower_bound

- Objektově orientované programování (OOP) – třídy (CLandRegister, CIterator)

- Dynamická alokace paměti – správa paměti pomocí new/delete

- Iterátory a třídění – vlastní CIterator, std::sort pro různé způsoby řazení

## Jak spustit projekt

1. Zkompiluj program pomocí g++ nebo jiného C++ kompilátoru:

 ```
 g++ -std=c++17 -o landRegister main.cpp
```

2. Spusť program:
```
./landRegister
```
