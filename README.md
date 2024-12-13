# gruppexamination-datalogiskt

https://www.figma.com/board/BGjo1LPulpOTt5fsI2iU3N/Untitled?node-id=0-1&t=mUGfENniSP8MjDSF-1

https://docs.google.com/document/d/1n8sol0dG-NwIhnMhBkzR6zNrESsrHR2nUklSpxTAKqU/edit?tab=t.0

# **Sammanfattning**

## **Introduktion**

Vi har analyserat och designat Airbean-appen, som syftar till att möjlig göra beställning av kaffe med leverans via drönare.
Vårt arbete har utgått från datalogiskt tänkande genom att använda:
**decomposition**, **pattern recognition**, **abstraction** och **algorithm design**.
Syftet var att skapa en användarvänlig och effektiv lösning.

---

## **Decomposition**

Vi delade upp projektet i mindre delar för att göra det hanterbart:

- **Registrering/inloggning**.
- **Menystruktur** (kaffesorter, storlekar och tillval).
- **Beställningsflöde** (från val till betalning och leverans).
- **Orderhistorik och feedback**.

### Avvägningar

Vi valde att fokusera på ett enkelt flöde, där användaren kan beställa som gäst eller genom att logga in. Detta gjorde processen flexibel och tillgänglig.

---

## **Pattern Recognition**

Vi identifierade mönster i menyer och användarflöden, såsom:

- Kategorisering av kaffe baserat på tidigare beställningar.
- Visa populära val och specialanpassade alternativ (veganskt, laktosfritt, koffeinfritt).

### Avvägningar

Menyn organiserades för att lyfta fram de mest populära valen högst upp. Detta förenklar användarupplevelsen.

---

## **Abstraction**

För att förenkla beställningsflödet fokuserade vi på att minimera antal steg:

1. **Välja kaffe och tillval.**
2. **Bekräfta beställning.**
3. **Välja betalningssätt.**

Vi skapade också en generell vy som fungerar för både gäster och inloggade användare.

### Avvägningar

Vi valde bort vissa komplexa funktioner, såsom avancerad orderuppföljning, för att hålla fokus på enkelhet.

---

## **Algorithm Design**

Vi designade ett flöde som tar användaren från landningssida till en bekräftad beställning:

1. **Starta från menyval.**
2. **Bekräfta order och betalning.**
3. **Få statusuppdateringar.**
4. **Slutföra med feedback.**

### Avvägningar

Flödet är anpassat för att minimera tid och klick för användaren, med tydliga steg från start till slut.

---

## **Slutsats**

Genom att använda datalogiskt tänkande kunde vi skapa en struktur som är både logisk och användarvänlig.
Airbean-appen är utformad för att leverera kaffe snabbt och smidigt med fokus på användarens behov.
