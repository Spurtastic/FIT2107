# FIT2107

This will cover all items from Week 3 - 11

## Week 3
* Random Testing 
  * capable of finding mostly low level bugs
### Partition testing 
Basically the below two testing methods breaks the program into two or more disjoint classes that have different behaviours

* Equivalence Testing
  * Here we can say that it takes two conditions or points where the input will go by so in essence they will be two conditions that the input has to pass through.
  * But the additive quality here is that if an input works to a condition then we know that it will work for all the inputs in that partition.

```
def mentalage(subject_age):
  if subject_temp < 3:
      print("Baby")

  elif subject_age>= 13 and subject_age<=19:
      print("irresponsible tweens")
  else:
      print("brutal adult living life ")
    
```
NOTE: the above code
{< 3} {13, 19} { > 19}
the above are the equivalence partitions

* Category Partitioning Testing
  * Divides the input space i.e. the parameters and args in a function 
  * Understand the characteristics
  * Add constraints 


## Week 4
* Boundary Value Testing
* Combinatorial Testing
* Pairwise Testing
    * The use of pairwise, is more efficient in the long run, the rule is to select two properties that relate to one another. 

## Week 5

* 


