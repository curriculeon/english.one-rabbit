# One Rabbit Caused Confusion
* **Objective**
	* To identify the number of animals headed in the direction of the river.
* **Description**
	* 1 rabbit saw 6 elephants while going to the river.
	* Every elephant saw 2 monkeys going towards the river.
	* Every monkey holds 1 parrot in their hands.

## Problem Interpretation
* Because there are no commas, we associate each noun with each verb starting with the last clause, and ending with the first clause.
* [Parsimony principle](https://en.wikipedia.org/wiki/Occam%27s_razor) states that one should not make more assumptions than necessary. Thus, it is best to use as few commas as possible, then allow the grammar structures to manifest and resolve naturally.


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

### Statement B
* `StatementB`
	1. Every elephant saw 2 monkeys going towards the river
	2. Each elephant saw 2 monkeys going toward the river

```
  elephant1 + monkey1
  elephant3 + monkey3
  elephant4 + monkey4
  elephant2 + monkey2
  elephant5 + monkey5
  elephant6 + monkey6
= 12 animals
```


* `StatementC`
	* Every monkey holds 1 parrot in their hands.

* `StatementA` = 1 rabbit saw 6 elephants while going to the river
		   = (1 rabbit saw) (6 elephants while going to the river)
		   = (clauseA1) (clauseA2)
		   
// clauseA2 takes the form of a [positive-imperative-clause](https://completeenglishgrammar.com/imperative-clauses-positive-and-negative/)
// thus we can inject presumed predicates without loss of precision

		   = 1 rabbit saw (6 elephants while [the elephants are] going to the river)
				=> 6 elephants are going to the river
				= 6 animals going to the river
= 6 animals going to the river


StatementB = Every elephant saw 2 monkeys going towards the river