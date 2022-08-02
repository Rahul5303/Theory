# Theory Assignment:
## Props and State?
Props are used to pass data from one component to another. The state is a local data storage that is local to the component only and cannot be passed to other components.

##Explain the useState API?
The useState() is a Hook that allows you to have state variables in functional components . so basically useState is the ability to encapsulate local state in a functional component.

##Explain the how map, filter, reduce work?
Map, Filter, and Reduce are the most used array functions. Each of them iterates over the array, performs some operations, and returns the new array with the updated results, 
we will discuss how we can use these map, filter and reduce in React to iterate over the array.


##Create your own map, filter, reducer methods and attach it to an array using prototype chain?
var new_array = arr.map(function callback(element, index, array) {
    // Return value for new_array
}[, thisArg])

var new_array = arr.filter(function callback(element, index, array) {
    // Return true or false
}[, thisArg])

arr.reduce(callback[, initialValue])





