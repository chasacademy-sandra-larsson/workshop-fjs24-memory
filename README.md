# Workshop - Memory

👋 
##Innehåll denna workshop:


* Hantera events i React
* Hantera local state med useState()
* Hantera sideeffects med useEffects()
* Frivilligt: Använda Tailwind CSS [https://tailwindcss.com/](https://tailwindcss.com/)

## Din uppgift

Du ska skapa ett interaktivt memoryspel.

* När användaren vänder två kort lika så ska dessa vara vända uppåt
* Memoryspelet är slut när alla kort/par är vända uppåt


![https://github.com/chasacademy-sandra-larsson/workshop-fjs24-memory/blob/main/memory-game%20(1).gif
](https://github.com/chasacademy-sandra-larsson/workshop-fjs24-memory/blob/main/memory-game%20(1).gif)

## Att tänka på


* Hur hanterar du state när användaren klickar ett kort?
* Hur kan du hålla reda på om användaren har klickat två kort?
   - Vad gör du om det två korten är lika?
 - Eller olika?

**Obs!** Kom ihåg att du kan använda useEffects dependencyarrayen för att hålla reda på 
  om någon state eller variabel ändras.

```

useEffect(
  () => {
    console.log("change1 eller change2 ändrades")
  }
, [change1, change2])


```

## Extra

Installera senaste Tailwind 4 (Vite installation) 
[https://tailwindcss.com/docs/installation/using-vite](https://tailwindcss.com/docs/installation/using-vite)

Installera extensions som Tailwind Intellisense och Tailwind Unfold.

Avnänd AI för att omvandla vanliga CSS-regler till Tailwinds klasser. Exempelvis Github co-pilot eller annat valfritt verktyg.


Lycka till!
// Sandra 🤩
	
