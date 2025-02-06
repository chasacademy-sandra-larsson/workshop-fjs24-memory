# Workshop - Memory

👋 
## Diskutera

* Hur hanterar man events i React
* Vad är state i React? Hur använder man useState()
* Vad är side-effects? Hur fungerar useEffect? Vad är är skillnaden [], [variabel] som dependency-array?

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
* Du måste lösa uppgiften med att använda useState()
* Du kan lösa uppgiften även med useEffect där dependencyarrayen håller reda på 
  om någon state eller variabel ändras.

```

const [value, setValue] = useState("initilal value")

useEffect(
  () => {
    console.log("change1 eller change2 ändrades")
  }
, [change1, change2])

```

## Extra

* Generera X antal kort i spelet
* Animation när man vänder kort
* Maxtid
  

Lycka till!
// Sandra 🤩
	
