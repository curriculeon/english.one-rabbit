# One Rabbit Caused Confusion
* **Objective**
	* To identify the number of animals headed in the direction of the river.
* **Description**
	* 1 rabbit saw 6 elephants while going to the river.
	* Every elephant saw 2 monkeys going towards the river.
	* Every monkey holds 1 parrot in their hands.

## Problem Interpretation
* Because there are no commas, we associate each noun with each verb starting with the last clause, and ending with the first clause.
* [Parsimony principle](https://en.wikipedia.org/wiki/Occam%27s_razor) states that one should not make more assumptions than necessary. Thus, it is best to use as few commas as possible, then allow the sentence structures to manifest and resolve naturally.


## Analyzing Each Sentence 

### Statement A
* `StatementA`
	1. `1 rabbit saw 6 elephants while going to the river`
	2. `(1 rabbit saw) (6 elephants while going to the river)` 
	3. `(clauseA1) (clauseA2)`
		* One may expect this to appear in the form `(clauseA1) && (clauseA2)`.
		* This expression appears to be multiplicative because it is the behavior of an object.
		* Object behaviors translate to multiplicative operations because they are said be _causes_ of an _effect_, or more simply, they [produce](https://simple.wikipedia.org/wiki/Product_(mathematics)) an effect.
			* `rabbit.see(elephant1, elephant2, elephant3, ... elephant6)`
	4. `(clauseA1) (6 elephants while going to the river)`
		* `clauseA2` takes the form of a [positive-imperative-clause](https://completeenglishgrammar.com/imperative-clauses-positive-and-negative/). Thus we can inject the presumed noun and helping verb to the predicate without loss of precision.
	5. `(clauseA1) (6 elephants while [the elephants are] going to the river)`
	6. `1 rabbit saw (6 elephants while [the elephants are] going to the river)`
	6. `1 rabbit saw 6 elephants while [the elephants are] going to the river`
	7. `1 rabbit saw 6 elephants while the elephants are going to the river`

#### Conjecture
* From `StatementA`, we conjecture 6 elephants are going to the river
* From `StatementA`, we conjecture 6 animals are going to the river


<hr>
### Statement B
* `StatementB`
	1. `Every elephant saw 2 monkeys going towards the river.`
	2. `Each elephant saw 2 monkeys going toward the river.`
	3. `Each [of the six] elephant[s] saw 2 monkeys going toward the river.`

```
  elephant1 + (monkey1 + monkey2)
  elephant3 + (monkey3 + monkey4)
  elephant4 + (monkey5 + monkey6)
  elephant2 + (monkey7 + monkey8)
  elephant5 + (monkey9 + monkey10)
  elephant6 + (monkey11 + monkey12)
= 6 elephants + 12 monkeys
= 18 animals
```

#### Conjecture
* From `StatementB`, we conjecture 6 elephants + 12 monkeys are going to the river.
* From `StatementB`, we conjecture 18 animals are going to the river.


### Statement C
* `StatementC`
	1. Every monkey holds 1 parrot in their hands.
	2. Each monkey holds 1 parrot in their hands.
	3. Each monkey holds 1 parrot in [the monkey's] hands.   
	4. Each [of the twelve] monkeys holds 1 parrot in [the monkey's] hands.
	
```
  elephant1 + ( [monkey1 parrot1] + [monkey2 + parrot2] )
  elephant3 + ( [monkey3 + parrot3] + [monkey4 + parrot4] )
  elephant4 + ( [monkey5 + parrot5] + [monkey6 + parrot6] )
  elephant2 + ( [monkey7 + parrot7] + [monkey8 + parrot8] )
  elephant5 + ( [monkey9 + parrot9] + [monkey10 + parrot10] )
  elephant6 + ( [monkey11 + parrot11] + [monkey12 + parrot12] )
= 6 elephants + 12 monkeys + 12 parrots
= 18 animals + 12 parrots
= 30 animals
```

### Conjecture
* From `StatementC`, we conjecture 6 elephants + 12 monkeys + 12 parrots are going to the river.
* From `StatementC`, we conjecture 18 animals + 12 parrots are going to the river.
* From `StatementC`, we conjecture 30 animals are going to the river.