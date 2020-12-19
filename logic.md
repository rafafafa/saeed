### (Mathematical) Logic

**Natural language tend to be ambiguous**, i.e. one word can have different meanings depending on the leasener/interpreter (the words used does not relate in a functional way with their meanings). It is important to say that this (very usually) does not happen or should never happen in the formal (computational) languages. Then to "validate" the "reasoning process" that turns to happen using language **we need to use a model that build some constrains to this ambiguity** or at least that makes it evident.

Logic is then the discipline (science*) of building crietria to **validate reasoning chains or arguments** and then **determine its trueness/falseness**. These arguments are composed by sentences or propositions for which validation has to be determined under a logical framework constituted by this mentioned criteria. 

**Mathematical logic** is a refinement of this idea an it can be thought as an analytic theory about the process of reasoning/argumenting for which its principal objective is to systematize (codify) the principles that determine the validity/invalidity of an argument.

An **informal idea of validity** of an argument would be that if we **obtain true conclusions** from **true propositions/sentences (hypothesis)** then the argument will be classified as valid. An informal idea of an **invalid argument** would be that this turn to be if we can conclude a **false conclusions** departing from **true hypothesis**.

### Falseness and Trueness (primitive concepts)

This **concepts are primitve because we do not explain them in terms of other primitve concepts**. This statement is necessary because if not, the process of defining a concept would never end since every non primitve concept use other concepts to define itself. Then we will *not* define this two concepts, and we will **assume that everyone has a primitive idea about both of them**. Particularly, it is important to **state that a sentence/affirmation can not be false and true simultaneously**.

### Propositional logic

**Definition 1.** We will say that a **proposition** is any affirmation that one can classify as *true* or *false*.

*Example:*

1. A dog is a mammal.
2. Mexico is a counry.
3. The man is mortal.

*An example of a not proposition:*

1. This phrase is false.

The propositions would be represented using letters: $~p,q,r,s~$ or $~P,Q,R,S~$ or $~p_1,p_2,q_3...$

To form new (composite) propositions departing fromo others we will use the next **logical connectors**:

$$\neg,~\wedge,~\vee,~\Rightarrow,~\Leftrightarrow$$

Then if $p,~q$ are propositions, so they are:

$$\neg p,~p\wedge q,~p\vee q,~p\Rightarrow q,~p\Leftrightarrow q$$

And lets note that it is not forbidden to take $p=q$.

The trueness/falseness of this new composite propositions is determined departing from the truness/falseness of its composing propositions.

We define the logical connectors using their "truth tables".

**Definition 2. "$\neg$"** or **negation** is defined by the table:

| <div style="width:100px">$p$</div>| <div style="width:100px">$\neg p$</div>|
|---|---|
| 0 | 1 |
| 1 | 0 |

$\neg p$ should be read as *not $p$*

This truth table means that whenever $p$ is a true proposition then $\neg p$ will be false.

**Definition 3. "$\wedge$"** or **conjunction** is defined by the table:

|<div style="width:100px">$p$</div>|<div style="width:100px">$\neg q$</div>|<div style="width:100px">$p\wedge q$</div>|
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 0 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

$p\wedge q$ should be read as *$p$ and $q$*

This truth table means that the conjunction of two propositions is true whenever both propositions are true individually, then it will be false whenever any or both of the propositions are false.

**Definition 4. "$\vee$"** or **disjunction** is defined by the table:

|<div style="width:100px">$p$</div>|<div style="width:100px">$\neg q$</div>|<div style="width:100px">$p\vee q$</div>|
|---|---|---|
| 0 | 0 | 0 |
| 0 | 1 | 1 |
| 1 | 0 | 1 |
| 1 | 1 | 1 |

$p\vee q$ should be read as *$p$ or $q$* 

This truth table means that the disjunction of two propositions is true whenever any or both propositions are true, then it will be false whenever both of the propositions are false.

**Definition 5. "$\Rightarrow$"** or **implication** is defined by the table:

|<div style="width:100px">$p$</div>|<div style="width:100px">$\neg q$</div>|<div style="width:100px">$p\Rightarrow q$</div>|
|---|---|---|
| 0 | 0 | 1 |
| 0 | 1 | 1 |
| 1 | 0 | 0 |
| 1 | 1 | 1 |

$p\Rightarrow q$ should be read as *$p$ implies $q$, $p$ then $q$*, if $p$ then $q$*, $p$ only if $q$, $q$ if $p$, $p$ is sufficient condition for $q$, $q$ is necessary condition for $p$*  

This truth table means that the implication of $p\Rightarrow q$ is false whenever $p$ is true and $q$ is false. Note that if $p$ is false then the implication is always true, for what we can conclude that *false implies whatever* or that one can conclude anything from a false proposition (related with the implication connector).


### First order logic (predicate logic)


### Modal logics
