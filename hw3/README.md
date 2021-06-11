# Objectives

  * Write tests to accomplish MC/DC coverage
  * Generate by hand static type proof certificates for simple programs

# Reading

See the following in the [lecture notes](https://bitbucket.org/byucs329/byu-cs-329-lecture-notes/src/master/):

  * [whitebox.md](https://bitbucket.org/byucs329/byu-cs-329-lecture-notes/src/master/whitebox/white-box.md)
  * [Property based testing](https://bitbucket.org/byucs329/byu-cs-329-lecture-notes/src/master/property-based-testing/)
  * [type-checking](https://bitbucket.org/byucs329/byu-cs-329-lecture-notes/src/master/type-checking.md)

# Problems

## MC/DC Coverage

1) Write a minimal number of tests to achieve MC/DC coverage for `edu.byu.cs329.mcdc.McDcTest.f`. Justify the final set of tests in the comments. Look in the `src/test` directory for the code. Make clear in the comments how the test input gives MC/DC coverage including a table for any decisions with more than one condition.

2) Write a minimal number of tests to achieve MC/DC coverage for `edu.byu.cs329.mcdc.MergeSortMcDcTest.sort`. Justify the final set of tests in the comments. Make clear in the comments how the test input gives MC/DC coverage including a table for any decisions with more than one condition (e.g., the if-statement in the loop). What makes this problem hard is finding the inputs to exercise the needed condition values for the if-statement in the loop. Find the needed condition values, then find the input to give those values.


## Type Checking

3) Type or write by hand a type proof for `edu.byu.cs329.hashtable.LlHashTable.get`. The proof should be in the form of a tree in a file in the same directory as this *README*. Name each file by the problem number. Uploading a picture of your paper-pencil solution is fine (and preferred). Assume the existence of the environment that does the right thing. 

## Optional

Practice writing type proofs for  `edu.byu.cs329.hashtable.LlHashTable.equals` and `edu.byu.cs329.hastable.LlHashTable.remove`. 

## Rubic

See Canvas for details

