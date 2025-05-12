# Statisk kode analyse

## ESLint og refaktorering
Til at lave statisk kode analyse er der anvendt ESLint og linting regler.

![Linting regler](../img/ESLintregler.png)

Der er lavet reglerne:

- Ingen comma-dangle (ingen komma uden efterfølgende punkter).

- Der skal altid bruges === eller !== (både navn, type og værdi skal være den samme i sammenligninger).

- Der skal bruges 2 mellemrum til indrykning.

- Ingen brug af eval.

- Ingen mellemrum efte semikolon.

- Ingen ubrugte variabler.

- Ingen brug af variabeltypen 'var'.

- Brug altid const, hvis variblen ikke ændrer sig.

- Altid bruge singlequotes.

- Altid bruge semikolon.