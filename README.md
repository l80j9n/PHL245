java c
Shortened truth tables 
PHL245 
We have been using the method of truth tables to determine various semantic properties of SL constructions. You might have noticed that some of these properties require us to check every row of a truth table, whereas other properties can be determined by just one row.
To determine that an argument is valid, for example, we have to check every row in the table to ensure that there is no row in which the premises are all true and the conclusion is false. But if the argu-ment is invalid, to determine this it suffices to find just one coun-terexample row: a row in which the premises are all true and the conclusion is false.
So, it would be nice if we could find a way to write just one row that shows that something has one of these properties, without hav-ing to write out a full truth table. We can do this by completing a shortened truth table.
Shortened truth table for an invalid argument 
Given an invalid argument in SL, we know that the full truth table (if we wrote it out) has at least one row in which the premises are all true and the conclusion is false. So we begin by filling in a ‘T’ under the main connective of each premise, and an ‘F’ under the main connective of the conclusion. From there, we “work backwards” to figure out a TVA that gives these truth values for the premises and conclusion.
Let’s work through an example using this invalid argument:

Since this argument contains five distinct sentence letters, its full truth table is 25 = 32 rows long. This would be tedious to complete, so it’s a good thing that we have the shortened truth table method available! We begin by filling in the desired truth values under the main connective of each sentence:

Now, our goal is to fill in the values under the sentence letters in a way that fits with the values we have already filled in under the connectives. Importantly, every occurrence of the same sentence letter must have the same truth value under it.
In this example, we should begin by working on the conclusion. Here’s why: There are three different ways for a conditional to be true (first premise), and three different ways for a disjunction to be true (second premise), but there is only one way for a conditional to be false (conclusion). Since the conclusion is a false conditional, we have to fill in a ‘T’ for its antecedent and an ‘F’ for its consequent:

And, there is also only one way for the conclusion’s antecedent (a conjunction) to be true: when both conjuncts are true. So we know that the TVA we’re looking for is one on which P, Q are true and R is false. We then copy these truth values for the sentence letters under each of their occurrences in the argument.

Now, looking at the first premise, we see that its antecedent is true on this TVA, so its consequent must also be true for th代 写PHL245 Shortened truth tablesC/C++
代做程序编程语言is conditional to be true. The consequent is a disjunction and one of its disjuncts R is false, so the other disjunct S has to be true:

Looking now at the second premise, it is a disjunction where one of the disjuncts is a conjunction where both conjuncts Q, P are true. So, the conjunction Q ∧ P is true. This is enough to ensure that the disjunction T ∨ (Q ∧ P) is true (as desired), so T can be either truth value. We need to assign every sentence letter a truth value, so let’s arbitrarily assign truth to T (but assigning F to T would work here too).

We are now done. The above shortened truth table shows that the argument is invalid, by showing that there is a TVA on which the premises are all true and the conclusion is false.
Other semantic properties 
We have seen that a shortened truth table can show that an argument is invalid. Shortened truth tables can also be used to show that a set of sentences is consistent, that a sentence is not a tautology, that a sentence is not a contradiction, and that two sentences are not logically equivalent.
The definitions of these properties are our guide to setting our desired values for the sentences in the set or pair. Once we set our desired values under the main connective(s), the process for finding a TVA that gives the desired values is as described above.    Using the guidelines below, try and complete the shortened truth table problems on Assignment 3.
Shortened truth table for a consistent set of sentences 
Recall: A set of sentences of SL is consistent if there is at least one TVA on which all sentences in the set are true.
To show that a set of sentences is consistent, we set all the sen-tences in the set to be true by filling in a ‘T’ under the main connec-tive of each sentence.
Shortened truth table for a non-tautology 
Recall: A sentence of SL is not a tautology if there is at least one TVA on which the sentence is false.
To show that a sentence is not a tautology, we set the sentence to be false by filling in an ‘F’ under its main connective.
Shortened truth table for a non-contradiction 
Recall: A sentence of SL is not a contradiction if there is at least one TVA on which the sentence is true.
To show that a sentence is not a contradiction, we set the sentence to be true by filling in a ‘T’ under its main connective.
Shortened truth table for two sentences that are not logically equivalent 
Recall: Two sentences of SL are not logically equivalent if there is at least one TVA on which they have different truth values.
To show that two sentences of SL are not logically equivalent, we set one of the sentences to be true (by filling in a ‘T’ under its main connective) and the other sentence to be false (by filling in an ‘F’ under its main connective).







         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
