Za pomocą pętli możemy w łatwy sposób powtarzać pewne czynności. Ten rodział [JavaScript Guide](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide) zapoznaje z różnymi rodzajami pętli, dostępnymi w JavaScript.

Możesz myśleć o pętli jak o skomputeryzowanej wersji gry w której mówisz komuś, żeby zrobił X kroków w jedym kierunku a następnie Y kroków w innym; przykład "Zrób 5 kroków na zachód" może być wyrażone za pomocą pętli w ten sposób:

```
var step;
for (step = 0; step < 5; step++) {
  // Uruchamia się 5 razy, z wartościami od 0 do 4.
  console.log('Idę na zachód jeden krok');
}

```

Jest wiele różnych rodzajów pętli, lecz zwykle wszystkie robią to samo: powtarzają zadaną akcję pewną ilość razy (liczba powtórzeń może także wynosić 0). Różne mechanizmy pętli oferują różne sposoby określania początku i końca pętli. W różnych sytuacjach łatwiej jest użyć danego typu pętli niż innego.