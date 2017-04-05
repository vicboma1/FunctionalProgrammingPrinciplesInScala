# Functional Programming Principles In Scala (Coursera)
[![Analytics](https://ga-beacon.appspot.com/UA-68658653-1/functionalprogrammingprinciplesinscala/readme)](https://github.com/igrigorik/ga-beacon)

## Course classes and assignments

#### Forcomp
```scala
package forcomp

import common._

object Anagrams { ... }
  
```

#### FunSet
```scala
package funSet

/**
 * 2. Purely Functional Sets.
 */
object FunSets { ... }
  
```

#### Huffman
```scala
package forcomp

import common._

object Huffman { ... }
  
```

#### ObjSets
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

#### Recursion
```scala
package recursion

import common._

object Main { ... }
  
```

#### Streams
```scala
package streams

import common._

trait GameDef { ... }
  
```

@Author : Victor Bolinches Marin
