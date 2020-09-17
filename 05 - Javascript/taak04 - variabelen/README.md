# FRONTEND-ESSENTIALS

## Javascript

## taak04 - Variabelen

### Introductie

Bij Frontend Basic heb je te maken gehad met variabelen. Oh wacht eens even.. bij de vorige opdracht natuurlijk ook....

Een belangrijk principe is het declareren:

```js
let mijnVoornaam = "Bart";
```

en het gebruiken:

```js
console.log(mijnVoornaam);
```

Maar stel nou eens dat de waarde van een variabele veranderd:

```js
let mijnLeeftijd = 16;
mijnLeeftijd = 17;
console.log(mijnLeeftijd);
```

Het getal 16 in dit voorbeeld bestaat niet meer. De variabelen heeft een nieuwe waarde.

Andersom dat zou niet kunnen want de variabele is nog niet gedeclareerd:

```js
mijnLeeftijd = 17;
let mijnLeeftijd = 16;
```

![Fout melding](images/foutmelding.png)

### Opdracht

1. Maak een index.html met de gebruikelijke tags en daarbij ook een script tag. (je kunt de index.html van taak01 nemen ;)
2. Maak een variabele `codingIsCool` en geef deze een boolean waarde
3. Op de volgende regel geef je dezelfde variabele de andere boolean waarde

### Bronnen

- [Programmeren in Javascript/Variabelen](https://nl.wikibooks.org/wiki/Programmeren_in_JavaScript/Variabelen)
  