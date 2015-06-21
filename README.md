# Oreki
Oreki is a small AI that was programmed in Java that would use its memory to make decisions. Oreki is programmed with
theoretically the 5 senses humans have.

If an object is spawned, Oreki will already know what it looks, smells, and sounds
like. Using its information on <b>similar</b> objects from it's memory, it will decide whether or not to touch and/or taste
the object. If Oreki doesn't have any similar objects, it will try/taste it so it has more knowledge for future objects.

Below are example test(debugs) of Oreki:

<b>Similarity Logic</b>

<img src="http://i.imgur.com/xO56IiX.jpg"/>

The logic is, Oreki first was given a rock. He had no knowledge so he touched and tasted the rock. He decides touching
it was fine but not tasting it. <br>
He was then given a blueberry, <b>from comparisons he knew the blueberry was nothing like the
rock</b> so he needed to taste/touch it to expand his knowledge.<br>
Next he was given a raspberry, <b>he saw this object was similar to a blueberry</b>, since he knew it was good to eat
the blueberry, he decides it's okay to touch/taste the raspberry.<br>
Lastly he was given talc, <i>Talc is rock type</i>, <b>he knew from before talcs qualities are similar to a rock and not a 
raspberry or blueberry</b>, so he decided not to eat the talc but to only touch it.

<b>Memory Logic</b>

The other type of logic Oreki uses is just whether he has seen the object before, he will then remember the results from
last time and weigh the benefits/drawbacks to come to a decision as such.

<img src="http://i.imgur.com/b50l9MO.jpg"/>
