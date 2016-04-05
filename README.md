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
|Search Term      | Occurrences |
|-----------------|-------------|
| following       | 1           |
| flow            | 2           |
| classification  | 1           |
| class           | 1           |
| flower          | 3           |
| friend          | 4           |
| friendly        | 4           |
| classes         | 1           |


### Constraints
* Your application must demonstrate it meets the acceptance criteria.
* You can NOT use any stemming frameworks or libraries. 
* Your solution must be able to be run on Windows 7.
* Solutions can be submitted by committing your code to GitHub and providing the link - OR - email a zip file to david.coleman@uk.bnpparibas.com
* We wouldn't expect this to take more than 2 hours. 

### Optional
* Write any assumptions you've made.


