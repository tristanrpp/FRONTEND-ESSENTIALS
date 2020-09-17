# FRONTEND-ESSENTIALS

## Javascript

## taak05 - Conditionals

Als je uit een vliegtuig springt met een parachute dan heb je een keuze te maken: "Doe ik de parachute open of niet? Als ik dat niet doe dan val ik te pletter, doe ik het wel dan land ik veilig op de grond."

![Parachute](images/parachute.gif)

Je maakt een keuze en die heeft specifieke (soms definitieve) gevolgen.

In het programmeren kun je dit ook tegenkomen. Die keuze worden conditionals genoemd. Anders gezegd: Voorwaardes. Er moet aan een specifieke voorwaarde voldaan worden om die specifieke uitkomst te krijgen.

Een keuze zoals in het verhaal hierboven wordt als volgt in een zin omschreven, daarna wordt dezelfde zin in code.

> Als ik de parachute open dan land ik veilig op de grond

En zo kun je dat in code schrijven

```js
    let parachuteIsOpen = true;

    if(parachuteIsOpen){
        alert("Ik land veilig op de grond! Yeah!");
    }
```

Je ziet een if-statement staan. En tussen de haakjes bij de if -statement staat een boolean. Als de boolean variabele waar (true) is dan land je veilig. Als de boolean variabele NIET waar (false) is dan stort je te pletter.

> - Als het WAAR is dan wordt de alert() uitgevoerd.
> - Als het NIET WAAR is dan wordt de alert() niet uitgevoerd.

Je kunt ook het volgende coderen:

```js
    let x = 5;
    let y = 5;

    if(x == y){
        console.log("De twee getallen zijn gelijk.");
    }
```

in de if-statement staat een bepaalde voorwaarde (condition). Als die voorwaarde true is dan krijgen we in de console de zin te zien. In bovenstaand voorbeeld zijn de getallen __gelijk aan elkaar__ en dus is de if-statement `TRUE` en dus wordt de zin getoond!

> - Opmerking: Je ziet twee = tekens staan: `==`
> - Dit is geen type-fout.
> - Dit noemen we een __vergelijkingsoperator__: je vergelijkt twee waardes
> - 1 = teken gebruikje bij het 'vullen' van een variabele (waarde toekennen)

### Opdracht

1. Maak een index.html met de gebruikelijke tags en daarbij ook een script tag. (je kunt de index.html van taak01 nemen ;)
2. Maak de volgende variabelen
   - mijnLeeftijd
   - stemGerechtigeleeftijd = 18;
3. Maak een if-statement die de waardes vergelijkt
4. Codeer een alert()-box met het resultaat

### Bronnen

- [Programmeren in Javascript/Conditionele statements](https://nl.wikibooks.org/wiki/Programmeren_in_JavaScript/Conditionele_statements)
  