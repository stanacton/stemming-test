# Stemming Test

## Background
A stemming algorithm is a process of linguistic normalisation, in which the variant forms of a word are reduced to a common form, for example,
````
   connection
   connections
   connective          --->   connect
   connected
   connecting
````
[See more here, Soure: https://xapian.org/docs/stemming.html](https://xapian.org/docs/stemming.html)
 
## Your Task
Using the the input text, in your given language, write a program that meets the acceptance criteria.

### Input
````
Friends are friendlier friendlies that are friendly and classify the friendly classification class. Flowery flowers flow through following the flower flows
````

### Acceptance Criteria
* 'following' appears 1 time
* 'flow' appears 2 times
* 'classification' appears 1 time
* 'class' appears 1 time
* 'flower' appears 3 times
* 'friend' appears 4 times
* 'friendly' appears 4 times
* 'classes' appears 1 time
