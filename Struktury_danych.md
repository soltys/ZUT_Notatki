# Pojęcie typu danych
Każda stała, zmienna, wyrażenie, operator lub funkcja ma określony typ, związany z danymi wykorzystywanymi do ich zdefiniowania lub przez nie przetwarzanymi.

**Abstrakcyjny typ danych** to zbiór wartości i operacji na tych wartościach, który jest dostępny **jedynie** za pośrednictwem zdefiniowanego *interfejsu*. Interfejs określa sposób dostępu do danych oraz wszystkie dostępne operacje. Metody organizacji  danych, czyli struktury danych oraz funkcje realizujące operacje są oddzielone od interfejsu.

**Typ wartości** oznaczonej przez stałą, zmienną lub wyrażenie można jednoznacznie określić na podstawie ich postaci lub  eklaracji (bez konieczności wykonywania procesu obliczeniowego).

Każdy operator lub funkcja ma argumenty **ustalonego typu**.

Rezultat działania operatora lub funkcji jest także **ustalonego typu** (jeśli operator lub funkcja mają argumenty różnych typów,  o typ rezultatu zależy od specyficznych cech języka, w którym zdefiniowano problem, czyli konkretnej implementacji).

# Moc typu danych 
Liczbę wszystkich dopuszczalnych i różnych wartości należących do pewnego typu danych T określa się mianem mocy typu danych T  wielkość ta umożliwia między innymi określenie wielkości pamięci niezbędnej do przechowywania/reprezentacji dowolnej zmiennej lub stałej typu T).

----

# WYLICZENIOWY TYP DANYCH
Dane należą do skończonego zbioru elementów, których reprezentacja binarna będzie zazwyczaj odpowiadała liczbom całkowitym. 

Brak relacji porządkującej ten zbiór (bez względu na interpretację przyporządkowanych im liczb całkowitych).

Wyliczeniowy typ danych definiuje się przez wyliczenie wszystkich możliwych "wartości" elementów zbioru danych:

```
type T = (c1, c2, c3, ..., cn);

moc(T) = n
```

Przykłady:

```
type shape = (rectangle, triangle, circle);
type Boolean = (false, true);
type sex = (female, male);
type day_of_week = (monday, tuesday, wednesday, thursday, friday, saturday,
sunday);
type colour = (red, green, blue, magenta, cyan, yellow);
type lecture = (algorithmics, cryptology, foundations of computer sciences);
```

