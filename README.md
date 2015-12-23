# canon_fodder
The idea here is to brainstorm, detail, and implement a data storage mechanism for fictional works in a way that offers testing of substories cast against them.

# concepts
The idea here is to allow someone writing fiction to keep tabs on the contents of their worlds.  Examples where canon are extremely tightly controlled, for example, would include Star Trek, Harry Potter, or Lord of the Rings.  Keeping tabs on the canon allows multiple authors to participate with relative security, or may help just the one author keep things straight in their mind.

Trouble being, if you have this universe of places, times, characters and objects, how do you search them for anything that might conflict when you wish to add a new of any of the above.  Individuals will have their ways... some may just not, and produce dodgy content as a result.  But what if there was a way to submit the new content and have a semi-intelligent database just tell you... THAT causes a conflict with X, Y, Z.  Alternatively, it may just be a simple matter of asking the database... 'hey, round about the year 3199AD, how old are X, Y, Z?  Based on the answers, the author may design their intended new content to snap into the results preemptively.

Naturally, this database will have to be able to store and comprehend localities, objects (including characters), and track both over periods of time.  

# development
## stage 1...
* determine a markup language that canon scripts would run against
  * Needs to be human readable as well as script dissectable
  * Needs to be relatively easy to update

## stage 2...
* determine an algorithm that can parse a 'suggestions' against the canon database

