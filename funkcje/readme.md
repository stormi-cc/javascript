Definicja funkcji (zwana też deklaracją funkcji, lub instrukcją funkcji) składa się ze słowa kluczowego [function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/function) oraz:

* Nazwy funkcji.
* Listy argumentów zamkniętych w nawiasach i oddzielonych przecinkami.
* Instrukcji JavaScript, które definiują funkcję, zamkniętych w nawiasach klamrowych, `{ }`.

Poniższy przykład przedstawia definicję funkcji obliczającej kwadrat liczby:

```
function square(number) {
  return number * number;
}

```

Funkcja `square` przyjmuje jeden argument, nazwany `number`. Funkcja składa się z jednej instrukcji, która zwraca argument (`number`) pomnożony przez siebie. Instrukcja [return](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return) oznacza wartość zwracaną przez funkcję.