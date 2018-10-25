# JavascriptConcepts
JavascriptConcepts
forEach :Iterates over an array ,runs callback on each value and returns undefined.

Map:creates a new array ,runs a callback
on each vale and pushes the result of each callback in the new array

Filter: creates  a new array ,runs a callback on each value and
if the result of the callback returns true ,the value is added to the new array

Some:iterates through an array and
runs a callback on each value if the callback for at least one value returns true,
some returns true otherwise false;

Every:iterates through an array and runs a callback on each value
f the callback at any time returns false every returns false


Reduce: returns a accumulated value which is
determined by the result of what is returned to each callback


let creates TDZ:-Temporal Dead Zone,let does not hoist

const declaring same variable twice results in syntax error not type error



block scope if ,while catch try finally


Template Strings-String interpolation-backticks

can use multi line strings

Arrow functions-no return if placed in single line
Arrow functions wont get own this..=-->enclosing

Arrow functions wont get arguments.Never use in method functions

Maps
If you need keys that are not strings but objects will always be string in keys
key value added and removed
Weakmaps->no primitive data types only object also garbage
collector clears the map easily and cant be iterted

maps implement symbol.iterator so can be iterated easily
and no overwriting like in object.prototypes

Sets-->unique values s.has, s.delete s,size
weak set->performance->all should be objects
async /await--->promise is invoked

await waits to resolve the functions
awist faild javascript auto handles but user can add try catch block

arguments object->no  longer acessed in arrow functions
this keyword->is also ot accessed in arrow functions
Promises
if resolved  "then" function will be invoked otherwise "catch" function will be executed when its rejected
"promise.all" will be executed one after other
A promise is settled if it’s not pending (it has been resolved or rejected).
Sometimes people use resolved and settled to mean the same thing: not pending.
Once settled, a promise can not be resettled. Calling resolve() or reject() again will have no effect.
The immutability of a settled promise is an important feature.
Iterables and iterator
iterator doesnt work on objects but work in sets map etc
Sets are array objects which accepts unique objects
Generator,symbol.iterator
Genrators hold state of objects

When generator is invoked it will return to us with keys of value and done
value is returned using pause function using yeild functins
done returns when function completes
