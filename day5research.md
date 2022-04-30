https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Map
Research: Map Object in JavaScript

Map
<ul>
	<li>Holds key-value pairs and remembers the original insertion order of the keys</li>
	<li>Any value(both object and primitive value) may be used as key or value</li>	
	<li>Iterates its elements in insertion order by use of a "for…of" loop. It returns an array of the key-value pair for each iteration</li>
	<li>Equality of a key is based on the sameValueZero algorithm</li> 
	<li>Similar to object</li>
	<li>Map does not contain any keys by default, only what's explicitly put into it whereas Object has a prototype</li>
	<li>Map keys can be any value whereas Object must be a String or Symbol</li>
	<li>Number of items in a Map easily retrieved from its size property whereas Object must be determined manually</li>
	<li>Iterable (Object has no implemented iteration protocol)</li>
	<li>Performs better in scenarios involving frequent additions and removals of key-value pairs</li>
	<li>No native support for serialization or parsing whereas Object does
https://stackoverflow.com/q/29085197/</li>
	<li>Storing data in the Map correctly is done through the set(key, value) method</li>
	<li>Map() creates a new Map object</li>
</ul>
