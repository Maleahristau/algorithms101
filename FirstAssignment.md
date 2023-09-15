# Assignment One:
### Show your understanding of big O notation.
Create methods that show:
- Constant O(1)
- Linear O(n)
- Quadratic O(n2)  
In each method include comments that explain how your method demonstrates the concept.

## Example of Constant O(1)
```
var pizza = [1,2,3,4,5,6,7,8];
pizza[3]; // Gives 4 everytime regardless of array size

```
This type of notation means that regardless of the load or size of data the time it takes to process will always be the same,
for this example it takes the same acount of time to find the second item in the array regardless of how many items are added to the array.

## Example of Linear O(n)
```
for (var i = 0; i <Pat.length; i++){ console.log(Pat[i]);} // Would give 4
for (var i = 0; i <Jake.length; i++){ console.log(Jake[i]);} // Would give 6
var Pat =[cheese, chicken, milk, eggs];
var Jake =[beef, potatoes, coffee, chips, apples, cornmeal];
```
This type of notation means that the more data you add is porpotional to the time it takes to process it. So in this example say jake and Pat
are both looking for items in a store, Jake would take longer because he is looking for more items.

## Example of Quadratic O(n2)
```
    for (var wrap= 0; wrap < elements.Count; wrap++)
    {
        for (var toppings = 0; toppings < elements.Count; toppings++)
        {
            // Don't compare with self
            if (wrap == toppings) continue;
            if (elements[wrap] == elements[toppings]) console.log(Bad Burrito);
        }
```
This type of notation means that there's nested data, and the time it takes to sort that date is linear but squared due to there being two
layers to get into. Our example is for a burrito where the outer layer is the wrap, and inner is toppings. The idea being if there's the same amount
of toppings as there is wrap then thats a bad burrito.
