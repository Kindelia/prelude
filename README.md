# prelude

The
[HVM](https://github.com/Kindelia/HVM)
is been built, and we are going to need to decide wich purely functional data structures  will be used on Kindelia.
To handle access of information on memory.

The image below represents partially what we are interested in:
![](https://www.lavivienpost.com/wp-content/uploads/2021/02/data-structures-and-java-apis2.jpg)

A great source of functional algorithms with examples is the
[Okasaki Book](https://br1lib.org/book/502927/5b4598)
( [other links](https://br1lib.org/s/PRUTELY%20FUNCTIONAL%20DATA%20STRUCTURES%20OSAKI) )
, and 
[this list of links](https://cstheory.stackexchange.com/questions/1539/whats-new-in-purely-functional-data-structures-since-okasaki).

There is a 
[video tutorial](https://www.youtube.com/watch?v=ECstIu4I3NM) in portuguese
made by kindelia team explaining how to implement the patricia tree,
based on this 
[paper](https://ittc.ku.edu/~andygill/papers/IntMap98.pdf).

There isn't a language since it's been built from zero, and it's not necessary on functional programing.
Anyway, there are some functions which are been used repeatedly, 
maybe you can find more about then on 
[kind repository](https://github.com/Kindelia/Kind/tree/master/base)

## List of implementations

### Okasaki
* Lists (done)
* Binary Search Trees (Miguel)
* Leftist Heaps
* Red-Black Trees (done)
* Streams
* Queues (Daniel e Lucas)
* Binomial Heaps (done)
* Splay Heaps
* Pairing Heaps

#### Advanced
* The Banker's Method
* The Physicist's Method
* Lazy Pairing Heaps
* Scheduling
* Real-Time Queues
* Binomial Heaps
* Bottom-Up Mergesort with Sharing
* Batched Rebuilding
* Global Rebuilding
* Lazy rebuilding
* Double-Ended Queues
* Positional Number systems
* Binary Numbers
* Skew Binary Numbers
* Trinary and Quaternary Numbers
* Structural Decomposition
* Structural Abstraction 
* Bootstrapping to aggregate Types
* Queues and Deques 
* Catenable Double-ended Queues


### StackExchange
* IntMap (done)
* Finger Trees (Santi)
* Ideal Hash Trees
* Priority Search Queues
* Bootstrapping one-sided flexible arrays
* New catenable and non-catenable deques
* Maxiphobic heaps
* Purely Functional Worst Case Constant Time Catenable Sorted Lists
* Confluently Persistent Tries for Efficient Version Control
* A new purely functional delete algorithm for red-black trees
* RRB-Trees: Efficient Immutable Vectors

### Others
* [Data-List](https://hackage.haskell.org/package/base-4.16.1.0/docs/Data-List.html) (Igor)
* Biased Search Trees (Guilherme)



