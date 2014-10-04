#BIS101 F2013 Lecture 2: Mendel

## Notes from last time

Papers are on smartsite or linked.

Github link in announcements.

Reading units.

## Other forms of inheritance:

#### sex linked

Notice reciprocity in crosses above.  This doesn't always happen!

Above we have considered non-sex chromosomes, also called **autosomes**

humans have two sex chromosomes X and Y. 1 from each parent, but XX is female, XY male. 

* some plants have sex chromosomes! (and sexually transmitted diseases!)
* instead of heterozygote or homozygote we say heterogametic or homogametic
* works same, but genes on X ≠ Y

Drosophila also have XY system

* Draw Punnet square for w+/w+ Drosophila female (red WT) x w male
* Compare to square for red w+ male x w/w/ female (if time permits)
* For both show color, sex of F1 and F2 products

<img src="/Users/jri/Documents/courses/bis101/griffiths/ch02/figure_02_19.jpg" style="width: 500px;"/>

Reciprocal crosses not same for sex-linked traits

Not all F1 will be the same

Ratios not the same because gene is not present on both chromosomes.          

#### organellar

Eukaryotes defined by presence of nucleus and organelles
Some phenotypes defined by organellar (Mitochondria and chloroplast) genes.

***Endosymbiosis***

There are some mitochondrial diseases (some deafness, muscle myopathy)

Mito in mammals -- always maternal

<img src="/Users/jri/Documents/courses/bis101/fall2013/images/mito_pedigree.jpg" style="width: 500px;"/>

**homoplasmy** and **heteroplasmy** which helps explain incomplete penetrance

Not always maternal

- redwoods both mito and cp are male
- some pine trees, cpDNA male, mtDNA female
- mussels have double uniparental: F mito is maternal, M mito is paternal


## Mendel's Second Law:

Independent assortment <strong style="font-size: 150%; color: red;">?</strong> 
Unlinked genes assort independently: what happens at one locus, stays at one locus.

Work through example.

<img src="/Users/jri/Documents/courses/bis101/griffiths/ch03/figure_03_04.jpg" style="width: 500px;"/>

* Describe parents phenotype. 
* Ask gametes. 
* Ask F1. 
* Draw Punnett square. 
* Get phenotypes. 
* work out all 16 progeny, figure out phenotype based on dominant/recessive 
* Show monohybrid 3:1 <strong style="font-size: 150%; color: red;">?</strong> is this phenotype? for dominance or codom too? 
* dihybrid 9:3:3:1 for phenotype
* for genotype more complex. how many diff genotypes? <strong style="font-size: 150%; color: red;">?</strong> (3^2), most common is RrYy at 4 ways to get it.

Don't worry about Dihbyrid ratios with sex vs. autosomal loci

## Chi squared

Reality never perfect, e.g. we see 267 vs 93 which we interpret as 3:1 (though not perfect 270:90). But would we interpret 280:80 or 290:70? 

So how to know if close enough? Chi-squared test 

I expect 270:90; i observe 267:93

Chi^2 = Sum((E-O)^2/E); compare to table with df (degrees freedom?)

df = here is number of phenotypic classes -1 (here 2 classes so 1 df)
don't worry about how to calculate df.

sum = 0.13, 1 df, from table 3-1 in book, to be significant at p=0.05 (i.e. <5% chance of observing data) need 3.841.

<strong style="font-size: 150%; color: red;">?</strong> so what do you conclude? (can't reject null hypothesis of expectation, != to saying it is right!), that is 3:1 is an OK way of describing this

redo yourself with 244:104. <strong style="font-size: 150%; color: red;">?</strong> If 3:1 is correct, what is predicted numbers? 261:87 should show the predicted ratio for 3:1 is: 261:87 

value is 4.43 -> reject 3:1 ratio!

Can use for equal segregation (numbers of big A and a in offspring from one locus, association among loci, population genetics, etc.)

will return to Chi-squared for other things in the future.
￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼
## Predictions: probability

Useful for studying pedigress, for knowing proportions of offspring, gamete production, etc.

**Product rule:** 

For independent events -> multiply

<strong style="font-size: 150%; color: red;">?</strong> Chance of rolling a 2 on a die? 1/6

<strong style="font-size: 150%; color: red;">?</strong> Of rolling a 2 then a 5? 1/6*1/6 = 1/36

* AaBb chance of getting an ab gamete? 1/4! 
* <strong style="font-size: 150%; color: red;">?</strong> Chance to get aBcd from AaBbCcDd -> 1⁄2^4 = 1/16

*Example:*  (save on board)

tb1-wt/tb1-ref;Wxy/wxy;adh1/adh1; <strong style="font-size: 150%; color: red;">?</strong> Which is dominant? (i didn't say)

<strong style="font-size: 150%; color: red;">?</strong> If I self, what's the chance of getting a tb1-ref/tb1-ref;wxy/wxy;adh1/ adh1 ?

(1⁄2\*1⁄2)\*(1⁄2\*1⁄2)=1/16=6.25%

<strong style="font-size: 150%; color: red;">?</strong> What's chance of getting tb1-ref/tb1-ref;wxy/wxy;adh1/Adh1 (0 unless mutation)

**Addition rule:**
For mutually exclusive events (can't both happen)

* you can add
* chance of getting A or a from AaBb (1) chance of getting AB, Ab, aB, or ab ? (1)

**Complement rule:**

P(A)=1-P(not A)

So prob. of getting two heads = 1/2 \* 1/2 = 1/4.

Prob. of not getting two heads = 3/4

**Conditional probability**

Pr(A|B) read as A given B = P(A ∩ B) / P(B)

Example: 

Prob. offspring of monohybrid cross with A>a is Aa given A- phenotype: P(Aa | A-) = P(Aa ∩ A- ) / P(A-) =  (1/2 are Aa and A-)/(3/4 are A-) = 2/3

* So *given* that individual has the dominant phenotype prob it is het = 2/3

**Hard problem**

How many progeny will i have to grow to get the tb1-ref/tb1-ref;wxy/wxy;adh1/ adh1 from example above @ 90% certainty?

* Subtract from what's easy to calculate (complement rule). Easy here to say what's prob of never seeing progeny?
* <strong style="font-size: 150%; color: red;">?</strong> What's probability of not getting progeny i want (15/16) in first seed
* <strong style="font-size: 150%; color: red;">?</strong> What's the probability of getting my progeny if I grow 3 plants?
	- 1-(15/16)^3=17.6% 
* <strong style="font-size: 150%; color: red;">?</strong> what if I grow n plants?
	- 1-(15/16)^n
* So to get 90% certainty, I solve:
	- 1-(15/16)^n=0.9
	- (15/16)^n=0.1 
	- n(ln(15/16))=ln(0.1) 
	- n=ln(0.1)/ln(0.9375)=35.7 == 36 plants


