# Functional Programming Principles In Scala (Coursera)
[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/vicboma1/functionalprogrammingprinciplesinscala/trend.png)](https://bitdeli.com/free "Bitdeli Badge")[![Analytics](https://ga-beacon.appspot.com/UA-68658653-1/injector/readme)](https://github.com/igrigorik/ga-beacon)

##Course classes and assignments

####Forcomp
```scala
package forcomp

import common._

object Anagrams { ... }
  
```

####FunSet
```scala
package funSet

/**
 * 2. Purely Functional Sets.
 */
object FunSets { ... }
  
```

####Huffman
```scala
package forcomp

import common._

object Huffman { ... }
  
```

####ObjSets
```scala
package tweetsets

import common._
import TweetReader._

class Tweet(val user: String, val text: String, val retweets: Int) {

  override def toString: String =
    "User: " + user + "\n" +
    "Text: " + text + " [" + retweets + "]"

}

abstract class TweetSet { ... }
  
```

####Recursion
```scala
package recursion

import common._

object Main { ... }
  
```

####Streams
```scala
package streams

import common._

trait GameDef { ... }
  
```


