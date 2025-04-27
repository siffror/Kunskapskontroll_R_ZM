Kunskapskontroll_R_ZM
Detta projekt handlar om att bygga och utvärdera regressionsmodeller för att förutsäga försäljningspriset på begagnade Volvobilar.

Sammanfattning
Syftet var att undersöka hur väl linjär regression kan användas för prissättning av bilar, och hur valet av prediktorer påverkar modellens träffsäkerhet. Två modeller jämfördes:

Modell 1: Använde endast numeriska variabler (Miltal, Modellår, Hästkrafter, Motorstorlek).

Modell 2: Lade till kategoriska variabler (Bränsletyp och Växellåda) för att förbättra prediktionen.

Resultat
Modell 2 presterade bättre än Modell 1 (lägre RMSE och MAE).

Log-transformering av priset hjälpte till att hantera snedfördelning och förbättra modellens prestanda.

Residualdiagnostik visade mindre avvikelser men inget som undergrävde modellens tillförlitlighet.

Använda tekniker
Linjär regression

Log-transformering

Residualanalys (Shapiro-Wilk, Breusch-Pagan, Durbin-Watson)

Multikollinaritetstest (VIF)

Visualiseringar med ggplot2


Projektet visar att även relativt enkla modeller kan ge användbara insikter när de byggs och valideras noggrant.
