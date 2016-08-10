# Playlist!

* Create a constructor function called `Artist`. The `Artist` constructor function should have 2 properties:
  * a `name` property, which can be accepted as an argument of the constructor function and set on the object
  * and a `songs` property that defaults to an empty array

* Create a constructor function called `Song`.  The `Song` constructor function should have 3 properties:
  * a `title` property, which can be accepted as an argument of the constructor function and set on the object
    * the `title` should be a string containing the title of a song
  * an `artist` property, which can be accepted as an argument of the constructor function and set on the object
    * the `artist` should be an instance of an `Artist` object
  * a `playCount` property that defaults to 0

* Inside the `Song` constructor function, find the current `song`'s `artist` property, and push the current `song` object into the `artist`'s `songs` array property. This way, the `song` has a reference to the `artist`, and the `artist` has an array that contains all of their `songs`. 
  * Think about how to refer to the current `Song`. What keyword does an instance use to refer to itself?

BONUS:

* Write a `play()` function for a `Song` that increments `playCount`.

## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.
