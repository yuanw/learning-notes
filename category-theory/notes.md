<http://www.math.mcgill.ca/triples/Barr-Wells-ctcs.pdf>

# Chapter 1. Preliminaries

## 1.1 Set  <http://mathworld.wolfram.com/topics/SetTheory.html>

A set is entity that is distinct from, but completely determined by, its elements (if any). (e.g it is fine to be an empty set). For every entity x and set S, the statement x ∈ S, read `x` is an element of S



Cartesian product of set S and T, is the set S x T of ordered pairs (s,t)



## 1.2 Function (function’s definition is closely tie to set)


A function f has the following properties:



1. f has domain and a codomain, each of which must be a set
2. for every element x of the domain, f has a value at x, which is an element of the codomain and is denoted f(x)

​           `λx.x*x`



​        The graph of a function f : S -> T is the set of ordered paris: `{(x, f(x)) | x ∈ S}`



​    Thus the graph of a function from S to T is a relation from S to T. However, not any relation will do; it must have the **functional property** that for all s belongs S, there is one and only one t belongs T, such that (s, t) is in the graph.



   1.2.4 The image of a function (also called its range) is its set of values; that is, the image of f : S -> T is {t belongs T, any s belongs S for which f(s) = t}.



  The metaphor behind the names “maps” and “image” reveals a way of thinking that is basic in modern mathematics: A function f : S -> T is thought of a map in the space T (in the sense of cartography) of its domain S. Thus a map of New York City (= S) is a collection of symbols on a piece T of paper together with the (partially implicit) information about which points on the paper T correspond to actual locations in the city S; this is the function that takes a point in the city to a point on the sheet of paper. The image is the set of symbols and their arrangement on the page, forgetting what in the city they correspond to.



The fact that the locations on the paper corresponds to the location in the city comes from the fact that the map is (approximately) shape-preserving. Most functions actually used in mathematics preserve some kind of structure.



 1.2.5 A function f : S -> T is injective if whenever s is not equal s’ in S, then f(s) is not equal f (s’) in T.



Another name for injective is one to one. The identity and inclusion functions described previously are injective. The function x |-> x*x : R -> R is not injective since it takes 2 and - 2 to the same value, namely 4. On the other hand, x |-> x*x*x is injective.



The is a unique function e: ∅→T for any set T. It has no values. It is vacuously injective.



Do not confuse the definition of injective with the property that all functions have that if s = s’ then f(s) = f (s’). Another way of saying that a function is injective is via the contrastive of the definition of injective : if f (s) = f (s’), then s = s’.



1.2.6 A function f: S -> T is surjective if its image is T.



  The identity function on a set is surjective, but no other inclusion function is surjective.



A function is bijective if it is injective and surjective. A bijective function is also called a one to one correspondence.





1.2.7 Functions and cartesian products



If S and T are sets, the cartesian product S x T is equipped with two coordinate or projection functions proj1 : S x T -> S and proj2 S x T -> T. The coordinate functions are surjective if S and T are both nonempty. Coordinate functions for products of more than two sets defined analogously.



1.2.8 If X, S and T are sets and f : X -> S and g : X -> T are functions, then the function (f, g) : X -> S x T is defined by  (f, g) (x) = (f(x), g(x)) for all x belongs X.



1.2.9 If X, Y, S and T are sets and f : X -> S, g: Y -> T are functions, then f x g : X x Y -> S x T is the function defined by (f x g) (x, y) = (f(x), g(y)). It is called the cartesian product of the functions f and g.



1.2.10 If f : S -> T and g : T -> U, then the composite function g . f : S -> Y.

1.2.11 If f : S -> T, and A ⊆ S, then the restriction of f to A is the composite f . i, where i : A -> S is the inclusion function. if T ⊆ B, f is called the corestriction of the function i . f : S -> B to T, where j is the inclusion of T in B. Thus, in 1.2.2, the function (i) is the lcorestriction to R+ of the function in (ii).



1.2.12 Functions in theory and practice



The concept of function can be explicitly defined in term of its domain, codomain, and graph.

Precisely, a function f : S -> T could be defined as an ordered tripe (S,Γ, T) with the property that Γ is a subset of the cartesian product S x T with the functional property (Γ is the graph of f). Then for x belongs S



TO FILL IN THE FUTURE



1.2.13 Let S and T be sets, and let Hom(S, T) denote the set of all functions with domain S and codomain T.



   Hom(S, x) is overloaded notation

   when x is a set, Home(S, x) is a set of functions

   When x is a function, Hom(S, x) is a function



   Hom(S, f) (g) = f . g



What is <https://en.wikipedia.org/wiki/Homomorphism>

​

Exercises on Function:



1. let h : W -> S be a function and define a function Hom (h, T) : Hom(S, T) -> Hom(W, T)







1.3 Graph



A category is, roughly speaking, a graph in which paths can be composed.



Definition: To specify a graph, you must specify its nodes (or objects) and its arrows.



set of set is also known as class, or proper class



<https://en.wikipedia.org/wiki/Class_(set_theory>)





<https://en.wikipedia.org/wiki/Category_(mathematics)#Small_and_large_categories>



The key of category is to compose



The basic property

**## unital**



**## associativity**



**## commutativity**







**Category Theory:**



   **Abstraction**



   **Composition**



   **Identity**







**a category is “bunch” of objects**





**Category**



**Objects (usually represent as dots)**



**Morphisms (usually represent as arrow)**



**An object is a primitive in this subject, there is no properties associated with an object**



**Morphism has a beginning and end**



**It is possible to have** **multiple** **arrows between two objects**





morphism can be composed.



​       f          g

a  ——> b ——> c





g o f is composition of f and g



For every object a, there is an identity arrow





Category has identity law



left identity and right identity



for arrow f  from object a to object b



(id a) . f = f



f (id a) = f



Another law is composition is associativity





<http://www.math.jhu.edu/~eriehl/compose.pdf>





<https://www.youtube.com/watch?v=aZjhqkD6k6w>





Introduce the simplest category, is possible to have a category with zero object ?



zero object means zero arrow, the identity and compose law by default are satisfied



initial object ?



category has one object,







1 Examples of categories, orders, monoids



Graph represent category,



each node needs an identity arrow to be category, for every pair of compose arrow



Free construction, not adding more constrains





Preorder category, thin category



<https://en.wikipedia.org/wiki/Preorder>





1. Reflexivity: a ![img](data:image/gif;base64,R0lGODlhCQAOANUnAAAAAC4AAAAALlwAAGZBAHBBAAAuTwBPcC5PeZFwQZ+JcABcn6uRic23n829vdLCpZGrwqvC15/X8qXX97fc9+DSwuDg4O7gzeXg4P/3zerq4Pfq1//30uDl5cjl+9fu++Dy/+rq6v/37uXy+//78v//9/L7/////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAACcALAAAAAAJAA4AAAY6wJNwSCwaj8UNgzIkPQoAhOd0UQQMkJGQMwAsQMVSJQE4RExFUYMAkJQwFksnpHF8Ml2AHiCYIP+AQQA7) a for all ![img](data:image/gif;base64,R0lGODlhHQAOAOZoAAAAAC4AAAAALkEAAE8AAHkuAEEuLgAAQQAATwAAXC4ATwAAZgAAcC4AZgAucE9BQU9PT0FBXE9cXE9mXHlwXIIuAJEuAJFBAJhBAJhPALFwAKVwLsJ5LolwQb2CAMKRQciYXM2lcNyrZuCxeQBcmABcpQBmsU9wgphwmHCYny6RzU+YyE+YzVyf12ax4JGYt5+9vdKfidexierCifLNkfLSmPLSpf/lt//qt//qvYKx3JHC4JHI7pHN7p/X8rfg+7fq/73q/83Nzc3N0tLS0tLS1+Xc0uXc1//uyP/ywv/y0v//0s3u/9zq98jy/9Ly+9L3/+Dy+9L7/9z7/+Xl5ffu6vfu7v//6v//7uru8u7u8u7u9+73++r3//Ly8vfy8vvy8vv38v//8v/79/f/////+/v7//v//////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAGgALAAAAAAdAA4AAAfHgGiCg4SFhoeIiYlhWWdjipCCZSEAEwYHkWhVVJxUXIQ5AD1oNw2QVxsAqqothDQAPGhYKIIyERQBLINlGiRRiUgECD9oZmgfDFNLA6OCSQpSkDYAB8QzAkBoNQhQg6+rqz6GNgHJGCVkYhkmhDgJT19e8lpngzFBgiMHThYqZR4AUrwgIwiLhRX1DnFwIUjEgikgqMGo4IAJISUFBEiAAOGBjoIXAJzoAGCHICsEwRAsVMbIECJEhDSRtKXMkSJdMuncyVNQIAA7).
2. Transitivity, a <= b, and b <= c, implies a <= c.



<https://en.wikipedia.org/wiki/Partially_ordered_set>



<http://mathworld.wolfram.com/PartialOrder.html>





A relation “![img](data:image/gif;base64,R0lGODlhCQAOANUnAAAAAC4AAAAALlwAAGZBAHBBAAAuTwBPcC5PeZFwQZ+JcABcn6uRic23n829vdLCpZGrwqvC15/X8qXX97fc9+DSwuDg4O7gzeXg4P/3zerq4Pfq1//30uDl5cjl+9fu++Dy/+rq6v/37uXy+//78v//9/L7/////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAACcALAAAAAAJAA4AAAY6wJNwSCwaj8UNgzIkPQoAhOd0UQQMkJGQMwAsQMVSJQE4RExFUYMAkJQwFksnpHF8Ml2AHiCYIP+AQQA7)” is a partial order on a set S if it has



1. Reflexivity: a ![img](data:image/gif;base64,R0lGODlhCQAOANUnAAAAAC4AAAAALlwAAGZBAHBBAAAuTwBPcC5PeZFwQZ+JcABcn6uRic23n829vdLCpZGrwqvC15/X8qXX97fc9+DSwuDg4O7gzeXg4P/3zerq4Pfq1//30uDl5cjl+9fu++Dy/+rq6v/37uXy+//78v//9/L7/////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAACcALAAAAAAJAA4AAAY6wJNwSCwaj8UNgzIkPQoAhOd0UQQMkJGQMwAsQMVSJQE4RExFUYMAkJQwFksnpHF8Ml2AHiCYIP+AQQA7) a for all ![img](data:image/gif;base64,R0lGODlhHQAOAOZoAAAAAC4AAAAALkEAAE8AAHkuAEEuLgAAQQAATwAAXC4ATwAAZgAAcC4AZgAucE9BQU9PT0FBXE9cXE9mXHlwXIIuAJEuAJFBAJhBAJhPALFwAKVwLsJ5LolwQb2CAMKRQciYXM2lcNyrZuCxeQBcmABcpQBmsU9wgphwmHCYny6RzU+YyE+YzVyf12ax4JGYt5+9vdKfidexierCifLNkfLSmPLSpf/lt//qt//qvYKx3JHC4JHI7pHN7p/X8rfg+7fq/73q/83Nzc3N0tLS0tLS1+Xc0uXc1//uyP/ywv/y0v//0s3u/9zq98jy/9Ly+9L3/+Dy+9L7/9z7/+Xl5ffu6vfu7v//6v//7uru8u7u8u7u9+73++r3//Ly8vfy8vvy8vv38v//8v/79/f/////+/v7//v//////wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAGgALAAAAAAdAA4AAAfHgGiCg4SFhoeIiYlhWWdjipCCZSEAEwYHkWhVVJxUXIQ5AD1oNw2QVxsAqqothDQAPGhYKIIyERQBLINlGiRRiUgECD9oZmgfDFNLA6OCSQpSkDYAB8QzAkBoNQhQg6+rqz6GNgHJGCVkYhkmhDgJT19e8lpngzFBgiMHThYqZR4AUrwgIwiLhRX1DnFwIUjEgikgqMGo4IAJISUFBEiAAOGBjoIXAJzoAGCHICsEwRAsVMbIECJEhDSRtKXMkSJdMuncyVNQIAA7).
2. AntiSymmetry: a <= b and b <= a implies a = b
3. Transitivity, a <= b, and b <= c, implies a <= c.





<https://en.wikipedia.org/wiki/Total_order>, <http://mathworld.wolfram.com/TotallyOrderedSet.html>



beside all the properties of partial order, plus



1. Comparability: For any ![img](data:image/gif;base64,R0lGODlhLQAPAOZ6AAAAAAICAgMDAwQEBAUFBQYGBgoKCgsLCw4ODhISEhYWFhsbGxwcHB8fHyEhISUlJScnJygoKCwsLC4uLi8vLzExMTMzMzY2Njs7Ozw8PD4+Pj8/P0BAQEFBQUJCQkRERE1NTU9PT1JSUlNTU1RUVFVVVVdXV1tbW15eXl9fX2BgYGFhYWNjY2dnZ2pqamtra21tbW5ubnBwcHJycnNzc3V1dXZ2dnd3d3t7e319fYKCgoODg4mJiYuLi42NjZGRkZKSkpOTk5SUlJWVlZeXl5qamp6enqKioqSkpKampqenp6ioqKysrLKysrOzs7W1tb29vb6+vr+/v8LCwsTExMjIyMnJycvLy87Ozs/Pz9DQ0NHR0dLS0tXV1dbW1tnZ2dra2tvb29zc3N3d3d/f3+Pj4+Tk5OXl5ebm5ufn5+jo6Onp6erq6uvr6+zs7O3t7e/v7/Pz8/X19fb29vf39/j4+Pr6+vz8/P39/f7+/v///wAAAAAAAAAAAAAAAAAAACH5BAEAAHoALAAAAAAtAA8AAAf/gHqCg4SFhoeIiYqLjI2OenFTQ3SPhXlYbHpllWMlDZWETBUrFhg3oCcuiXBWVa5rhHYMSYIbTZV3CU+HcywFGh/BToRrADqCQ2+CSy0oHDmJUgIvEhdfhDEkZoohAEaEShl2WgBUiTIFXnkUNINzB2iLch4BS4JhBttICniJDkCCLPQYxCXAg4MIwQyCM0fPHAwEyOjhsUFPnQgsEhXMBGeAQkFuEJRxQ5JkP0FFsgjaAoCJHhAq7NAAQASKnB5iCu3AIMiEj0IfeCRKYUMQEwFn9AgJcMEKgBFyogD4UOhIiR8zghgqcwFCDRxgrQyiMKHDigUuBaURFG+liENJHBHdubIkid0wg7aV6XISURsYVUAJPqRGzmBQgQAAOw==), either ![img](data:image/gif;base64,R0lGODlhHQAPAOZmAAAAAAICAgMDAwQEBAYGBgoKChISEhYWFhcXFxkZGRsbGxwcHB8fHyEhISgoKCsrKywsLC0tLS8vLzMzMzY2Njc3Nzs7Ozw8PD8/P0BAQEFBQU1NTVNTU1VVVVZWVldXV1tbW15eXmBgYGFhYWNjY2RkZGdnZ2pqamtra29vb3BwcHJycnNzc3h4eH19fYKCgoODg4WFhYmJiYuLi42NjZGRkZKSkpOTk5SUlJWVlZeXl5ubm6KioqSkpKWlpaenp6ioqLW1tbq6ur29vb+/v8LCwsTExMbGxsjIyMnJydDQ0NHR0dLS0tPT09bW1tnZ2dra2tvb293d3eHh4eTk5OXl5ebm5ufn5+np6erq6u/v7/Dw8PLy8vPz8/T09PX19ff39/j4+Pr6+vz8/P39/f7+/v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAGYALAAAAAAdAA8AAAewgGaCg4SFhoeIiYqLjINdRTlgjYxSHQyThVEtU4UgJ5hmYT4aDS9ehGMGQYVAJiEZLoRNKQkeQmSGRAIoEBRPZj8XYkoARoNYEQAxXIgqBE5lEixRBVRmPQe4hEglCCNHhg02ghMzMhihDiSIXTsVD9aCTAFZZloDUBsiYiwAOkOKlmwZBMOCoA80zOAIQCEJAA5fBm1ZoKCixV+CeHSoseLGoCuCrIAaVGWkyZOIAgEAOw==) or ![img](data:image/gif;base64,R0lGODlhHQAPAOZmAAAAAAICAgMDAwQEBAYGBgoKChISEhYWFhcXFxkZGRsbGxwcHB8fHyEhISgoKCsrKywsLC0tLS8vLzMzMzY2Njc3Nzs7Ozw8PD8/P0BAQEFBQU1NTVNTU1VVVVZWVldXV1tbW15eXmBgYGFhYWNjY2RkZGdnZ2pqamtra29vb3BwcHJycnNzc3h4eH19fYKCgoODg4WFhYmJiYuLi42NjZGRkZKSkpOTk5SUlJWVlZeXl5ubm6KioqSkpKWlpaenp6ioqLW1tbq6ur29vb+/v8LCwsTExMbGxsjIyMnJydDQ0NHR0dLS0tPT09bW1tnZ2dra2tvb293d3eHh4eTk5OXl5ebm5ufn5+np6erq6u/v7/Dw8PLy8vPz8/T09PX19ff39/j4+Pr6+vz8/P39/f7+/v///wAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAACH5BAEAAGYALAAAAAAdAA8AAAewgGaCg4SFhoeIiYqEXUU5YIuRglIdDJKXICeRUS1Ti2MGQYlhPhoNL16LRAIoEBRPhE0pCR5CZIdAJiEZLmYqBE5lEiyDWBEAMVyIPxdiSgBGZg02ghMzhUglCCNHhVEFVGY9B2RMAVlmWgNQh107FQ/hgjIYZmEOJGYwFoIfNItLtgzaIEIMCwA6hvDoUGPFjUJbFiiYSBGWIBwBKCQBwOGLoCqXDF0RZCWkyZORAgEAOw==)



Every finite totally ordered set is well ordered. Any two totally ordered sets with k elements (for k a nonnegative integer) are order isomorphic, and therefore have the same order type.



Thin category (aka <https://en.wikipedia.org/wiki/Posetal_category>)



Every category with only one object is call Monoid



Associativy:

  (a * b) * c = a * (b * c)



Exist e, for any a = a * e = a



3.2 Kleisli Category



category of subset (a partial order set )
