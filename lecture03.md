# BIS101 F2013 Lecture 3: Gene Interaction

## Quiz review

## Questions from last time?

## How to study

read chapter ahead of time.
stuff i never cover in lecture will not be focused on

## Predictions: probability

Useful for studying pedigress, for knowing proportions of offspring, gamete production, etc.

**Product rule:** 
For independent events, multiply

## Quiz1

save on board

**Addition rule:**
For mutually exclusive events (can't both happen)

* you can add

**Complement rule:**

P(A)=1-P(not A)

**Conditional probability**

Pr(A|B) read as A given B = P(A ∩ B) / P(B)  or A intersect B (both A and B happen) divided by prob of B

Example: 

Prob. offspring of monohybrid cross with a>A is Aa given a- phenotype: P(Aa | a-) = P(Aa ∩ a- ) / P(a-) =  (1/2 are both Aa and a-)/(3/4 are a-) = 2/3

* So *given* that individual has the dominant phenotype prob it is het = 2/3

## Quiz 2

**Hard problem**

How many progeny will i have to grow to get at least one tb1-T/tb1-T;wxy/wxy;adh1/adh1 genotype from selfing tb1-M/tb1-T;Wxy/wxy;adh1/adh1 with 90% certainty?

* Subtract from what's easy to calculate (complement rule). Easy here to say what's prob of never seeing progeny?
* <strong style="font-size: 150%; color: red;">?</strong> What's probability of getting progeny i want in first seed (1/16)
* <strong style="font-size: 150%; color: red;">?</strong> What's probability of not getting progeny i want (15/16) in first seed
* <strong style="font-size: 150%; color: red;">?</strong> What's the probability of not getting my progeny if I grow 3 plants?
	- (15/16)^3
	- Prob of getting my progeny? 1-(15/16)^3=17.6% 
* <strong style="font-size: 150%; color: red;">?</strong> what is prob of getting ≥1 if I grow n plants?
	- 1-(15/16)^n
* So to get 90% certainty, I solve:
	- 1-(15/16)^n=0.9
	- (15/16)^n=0.1 
	- n(ln(15/16))=ln(0.1) 
	- n=ln(0.1)/ln(0.9375)=35.7 == 36 plants

## Allele effects

How many alleles can we have at a locus <strong style="font-size: 150%; color: red;">?</strong> (tons)

#### dominant/recessive

* lethal allele <strong style="font-size: 150%; color: red;">?</strong>
* can be dominant or recessive — <strong style="font-size: 150%; color: red;">?</strong> why is recessive more common?

* deleterious mutations often but not always recessive — dominant negative examples in book
* <strong style="font-size: 150%; color: red;">?</strong> **null mutation** which producess a non-functioning copy (not all mutations are null!)
* null will lead to nonfunctional protein. recessive<strong style="font-size: 150%; color: red;">?</strong> seems likely but, could be inco. dominant, dominant, or even codominant too. not all null alleles deleterious either!

* Figure 6-1 and 6-2 nice drawing explaining haplosufficiency: maybe 1 copy of protein product not enough (haplounsufficient, mutant dominant) or mutant makes a messed-up-protein that causes problems (dominant, but not haploinsufficient)

#### pleiotropy

an allele that has an effect on more than one phenotype

**tb1** on both branching and sex of terminal inflorescence

<img src="/Users/jri/Documents/courses/bis101/fall2014/images/tb1_pleiotropic.jpg" style="width: 400px;"/>

## How many loci?

Two mutants, we want to know if mutant alleles are same or different locus. If they are at same locus we calle them **allelic**

First we check they are single gene mutants? How?? Pure-breeding line, cross to WT, look at segregation in F2. 

Then we cross inbred lines for each mutant. This is called a **complementation** test.  

##### Example

Two recessive mutants with effects on tillering/branching.  We will call them mut1 and mut2.  

**Scenario 1:** Both mutants are in same locus

Draw parents phenotype, genotype and F1 genotype. Reulting phenotype<strong style="font-size: 150%; color: red;">?</strong> mutant!

**Scenario 2:** Each mutants is in different locus

Draw parents, F1. Resulting phenotype<strong style="font-size: 150%; color: red;">?</strong> wild type!

**NOTE** fig. 6-12 in the book rad

So you can use complementation crosses to figure out how many loci involved.  Cross two homozygote recessives and see what phenotype comes out the other end.

<strong style="font-size: 150%; color: red;">?</strong> why use recessive and not dominant mutants? (because no complementation even if in different genes)

## Quiz 3


## Pathways

genes not in vacuum and not just make one product that does it's thing

we've considered effects of alleles at each genes independent of others

* e.g. effects of alleles at the round/wrinkled locus not change effects of alleles at the yellow/green locus
* often not the case for phenotypes of interest
    
section 6.3 on inferring gene interaction is good.

9:3:3:1 and 3:1 PHENOTYPIC ratios are for independent genes. (don't memorize)

#### Simple pathway example

Example: oversimplification of shade pathway in maize (KEEP ON BOARD)

<img src="/Users/jri/Documents/courses/bis101/fall2014/images/shade_path.jpg" style="width: 150px;"/>

tb1-T/tb1-T phenotype? lots of branches. WT? few branches

gt1'/gt1' also makes lots of branches and tillers.

I take tb1-T/tb1-T;gt1'/gt1' and cross to WT tb1-M/tb1-M;gt1+/gt1+.  Then self F1.  I see: 9:7 in progeny.  What's going on?

Draw genotypes, ask phenotypes and why <strong style="font-size: 150%; color: red;">?</strong>

9 tb1-M/- ; gt1+/-  WT
3 tb1-M/- ; gt1/gt1 lots of branches (nonfunctioning gt1)
3 tb1-T/tb1-T ; gt1+/- lots of branches (nonfunctioning tb1)
1 tb1-T/tb1-T ; gt1/gt1 lots of branches ( no function in either)

9:7 ratio gene interaction: genes are in the same pathway, both needed for function (don't memorize)

## Epistasis

**epistasis** "stand upon": double mutant shows phenotype of one single mutant, but not the other. you infer epistasis when mutant allele at one locus masks the phenotype of mutant allele at another locus

* precursor-> (enzyme A makes pigment)-> yellow pigment->(enzyme B turns yellow red)->red fruit (wt ) 
	- DRAW (leave on board) with enzymes as looped arrows not in pathway

for each locus A1>A2 B1>B2 and A1 and B2 wild type with A2 and B2 mutant alleles

ask each of these <strong style="font-size: 150%; color: red;">?</strong>

9: A1/- B1/- (red: both function normally)
3: A1/- B2/B2 (yellow: B enzyme fails to turn yellow pigment red)
3: A2/A2 B1/- (white: no yellow pigment is made, enzyme B can't do anything)
1: A2/A2 B2/B2 (white: no yellow pigment made, so B locus doesn't matter)

so phenotypic ratio is: 9:4:3, and mutation at locus A is epistatic to locus B

<strong style="font-size: 150%; color: red;">?</strong> Is the same true of B? B depends on genotype at A (either yellow or white)

the epistatic locus is upstream in the pathway, changing precursor or action of other genes downstream.  

this example was **recessive epistasis**. dominant is possible too!  so a>A, then Aa would also be white and ratio would be 12: 3 : 1 (work this out yourself)

Epistasis vocab (know definition, work through simple crosses in text)

* **suppressor**  (mutant that suppresses effects of other mutant making it wt)
* A some locus that does stuff.  A2 recessive mutant allele. B2 is a mutation at locus B that suprresses mutation in 1. (e.g. B2 produces a protein that can bind with either WT or mutant protein of A)

	- A1/- - WT  
	- A2A2 B1B1 mutant
	- A2A2 B2- WT

* Why might we see a 9:3:3 ratio <strong style="font-size: 150%; color: red;">?</strong>
* **synthetic lethals** (two mutants @ different genes each nonlethal together lethal)
	- double mutant is lethal, but each single mutant not. 

## Phenotypic descriptions

* **penetrance** (% individuals with the phenotype)
* **expressivity** how much expressed (little effect on drought tolerance or lots) varies among individuals
	- why would it vary<strong style="font-size: 150%; color: red;">?</strong> other genes, environment
	- e.g. mutant that makes you inefficient at getting water from soil will show low penetrance in an irrigated system

(for mitochondrial traits **homoplasmy** and **heteroplasmy** which helps explain incomplete penetrance or expressivity)

<img src="/Users/jri/Documents/courses/bis101/griffiths/ch06/figure_06_22.jpg" style="width: 250px;"/>


## Example # 37 Ch6

Snapdragon breeds true for white petals. x snapdragon breeds true for purple.  All F1 were white.  F2 are 240 white, 61 solid purple, 19 spotted purple. for a total of 320.  

If you're not supposed to memorize these ratios, how to solve these? 

First, rarely do you have to do science fast. So take some time, relax, and think.

It's really just hypothesis testing. 

H1: It's one locus dominant white dominant to purple. Prediction (after drawing punnet square): 3:1. Rejected!

H2: simple interaction in pathway. Prediction (draw out punnet square: 9:7 -- rejected!)
 (reject, not 9:3:4)

H3: Dominant epistasis.  We'll invent some genotypes:

mutant white A > a purple WT . mutant b spots < B WT no spots.

AAbb white parent
aaBB purple parent  <strong style="font-size: 150%; color: red;">?</strong> Why do parents have to be homozygous?  Because are true breeding.

Because white is most common phenotype in F2, let's say white epistatic to purple, so then:

1 AABB white
2 AABb white
1 AAbb white
2 AaBB white
4 AaBb white
2 Aabb white
1 aaBB purple
2 aaBb purple
1 aabb ??

That gives us 12 white : 3 purple : 1 ??  Is this consistent with what we see <strong style="font-size: 150%; color: red;">?</strong>

Could then do a chi-sq. to test goodness of fit.

<!-- cover if time

## Chi squared

Reality never perfect, e.g. we see 267 vs 93 which we interpret as 3:1 (though not perfect 270:90). But would we interpret 280:80 or 290:70? 

So how to know if close enough? Chi-squared test 

I expect 270:90; i observe 267:93

Chi^2 = Sum((E-O)^2/E); sum over classes. compare to table with df (degrees freedom?)

df = here is number of phenotypic classes -1 (here 2 classes so 1 df)
don't worry about how to calculate df.

sum = 0.13, 1 df, from table 3-1 in book, to be significant at p=0.05 (i.e. <5% chance of observing data under our null model of 3:1) need 3.841.

<strong style="font-size: 150%; color: red;">?</strong> so what do you conclude? (can't reject null hypothesis of expectation, != to saying it is right!), that is 3:1 is a not wrong way of describing this

redo yourself with 244:104. <strong style="font-size: 150%; color: red;">?</strong> If 3:1 is correct, what is predicted numbers? should show the predicted ratio for 3:1 is: 261:87 

value is 4.43 -> reject 3:1 ratio!

Can use for equal segregation (numbers of big A and a in offspring from one locus, association among loci, population genetics, etc.)

will return to Chi-squared for other things in the future.
-->

## Quiz 4 
## Quiz 5