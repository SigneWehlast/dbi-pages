End-to-end testing anvendes til at tjekke et helt flow i ens applikation fra start til slut ud fra, hvordan brugeren kunne interagere på applikationen. Her testes om alt funktionalitet og navigationen på siden virker, som det skal.

Til at teste flowet anvendes Cypress. Til at lave en end-to-end test skal der laves en mappe, som hedder 'e2e' hvor ens test-filer ligger (udover de mapper, som Cypres selv opretter). Inde i denne e2e-mappe oprettes filer, hvori koden der testet på laves.

Til den ene udførte end-to-end test er flowet, at en bruger logger ind, laver et nyt skema og til sidst gemmer skemaet. Her er der oprettet filen createSkema.cy.js og her skrives koden til ens test.

