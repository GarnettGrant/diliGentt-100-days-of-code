https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map
Research: Map Object in JavaScript

Map
	- Holds key-value pairs and remembers the original insertion order of the keys
	- Any value(both object and primitive value) may be used as key or value	
	- Iterates its elements in insertion order by use of a "for…of" loop. It returns an array of the key-value pair for each iteration
	- Equality of a key is based on the sameValueZero algorithm 
	- Similar to object
	- Map does not contain any keys by default, only what's explicitly put into it whereas Object has a prototype
	- Map keys can be any value whereas Object must be a String or Symbol
	- Number of items in a Map easily retrieved from its size property whereas Object must be determined manually
	- Iterable (Object has no implemented iteration protocol)
	- Performs better in scenarios involving frequent additions and removals of key-value pairs
	- No native support for serialization or parsing whereas Object does
https://stackoverflow.com/q/29085197/
	- Storing data in the Map correctly is done through the set(key, value) method
	- Map() creates a new Map object
