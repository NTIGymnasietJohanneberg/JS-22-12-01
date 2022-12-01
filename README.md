# JS-22-12-01

[InspirerandePortfolioSajter](https://dev.to/ruppysuppy/7-developer-portfolio-for-inspiration-4no7)

[LoopÖvningar](https://www.freecodecamp.org/news/how-to-loop-through-an-array-in-javascript-js-iterate-tutorial/)


## Dagens övningar!

1. Vad skrivs ut av följande kod?
```
 for( let i=2; i<7; i++ ) {
    if( i!= 5 )
        console.log('nummer ' + i);
}
```
2. Gör en loop som skriver ut texten "hej" på konsolen fem gånger.

3. Vad skrivs ut av följande kod?
```
const array = ['äpple', 'päron', 'banan']
for( let index=0; index<array.length; index++ ) {
    console.log( array[index] )
}
```
4.  Skapa en array med fyra decimaltal, som du hittar på. Gör en loop som skriver ut alla talen på varsin rad.

5. Gör en loop som skriver ut talen 10 till och med 15.

6. Gör en loop som skriver ut de jämna talen från 10 till och med 18.

7. Ändra loopen från uppgift 2.3, så att den skriver ut elementen (strängarna med fruktnamn) i omvänd ordning. (Banan ska alltså skrivas ut först.)

8. Skriv en loop som räknar ut summan av talen 1 till och med 10. Tips: du behöver en variabel.

## Object

1. Vad skrivs ut av följande kod?
```
let object = { x: true }
object.y = false
console.log(x)
console.log(y)
console.log(z)
```
2. Skriv om följande kod så att den samlar egenskaper som hör ihop i objekt, i stället för variabler. Tips: det bör bli mer än ett objekt.
```
let userName = 'kalle'
let userAge = 20
let userScore = 10
let totalUserCount = 100
let animalType = 'ekorre'
let animalFood = 'nötter'
```
3. Gör en loop som skriver ut hur stort värde som finns i kundvagnen sammanlagt.
```
const user = {
    name: 'Sam',
    cartValues: [19, 120, 200]
}
```
4. Gör en loop som skriver ut hur mycket alla varor i kundens kundvagn kostar sammanlagt.
```
const user = {
    name: 'Sam',
    cart: [
        {
            name: 'Tangentbord', price: 199, amount: 1
}, {
            name: 'USB-mus', price: 249, amount: 2
        },
        {
            name: 'Webbkamera', price: 399, amount: 1
} ]
}
```
