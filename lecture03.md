# BIS101 F2013 Lecture 3: Gene Interaction

## Quiz review

## Questions from last time?

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

**Hard problem**

How many progeny will i have to grow to get the tb1-T/tb1-T;wxy/wxy;adh1/ adh1 from example above @ 90% certainty?

* Subtract from what's easy to calculate (complement rule). Easy here to say what's prob of never seeing progeny?
* <strong style="font-size: 150%; color: red;">?</strong> What's probability of getting progeny i want in first seed (1/16)
* <strong style="font-size: 150%; color: red;">?</strong> What's probability of not getting progeny i want (15/16) in first seed
* <strong style="font-size: 150%; color: red;">?</strong> What's the probability of not getting my progeny if I grow 3 plants?
	- (15/16)^3
	- Prob of getting my prgeny? 1-(15/16)^3=17.6% 
* <strong style="font-size: 150%; color: red;">?</strong> what if I grow n plants?
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

**tb1** on both branhing and sex of terminal inflorescence

<img src="/Users/jri/Documents/courses/bis101/fall2014/images/tb1_pleiotropic.jpg" style="width: 400px;"/>


## How many loci?

In Arabidopsis example (hairy vs. glabrous leaves) from last time, two mutants, how know if same or different loci?

 **complementation** test: fig. 6-12 in the book rad

## Pathways

genes not in vacuum and not just make one product that does it's thing

we've considered effects of alleles at each gene independent of others

* e.g. effects of alleles at the round/wrinkled locus not change effects of alleles at the yellow/green locus
* usually or often not the case
    ￼
Example: oversimplification of flowering time pathway in rice

<img src="./images/rice_pathway.jpg" style="width: 300px;"/>

#### Simple pathway example

* precursor1-> (enzyme A from gene A)-> precursor2->(enzyme B gene B)->red fruit (wt ) 	- DRAW (leave on board) with enzymes as looped arrows not in pathway
* make recessive homozygote lines of two recessive mutants (so now a<A and b<B), cross to make double mutants
* **complementation** test

* draw out two possibilities (separate loci, same locus)
* <strong style="font-size: 150%; color: red;">?</strong> If I cross two whites -> red 1 or 2 loci (what are genos)? 	
 	- aaBB x AAbb (both white) = ? AaBb (red)
* <strong style="font-size: 150%; color: red;">?</strong> why use recessive and not dominant mutants? (because no complementation even if in different genes)
* <strong style="font-size: 150%; color: red;">?</strong> how do you know if your mutant is recessive? (make F1 and self!)
* what if I take two white plants w/ recessive mutants cross and = white?
	- perhaps aaBB x a'a'BB = aa'BB (fail to complement b/c just two mutations of same gene)

## Epistasis

section 6.3 on inferring gene interaction is good.

9:3:3:1 and 3:1 ratios are for independent genes. (don't memorize)

What about interaction among genes? like in these pathways?

**epistasis** "stand upon" 

<<<<<<< HEAD
<!--* statistical epistasis is observation of an interaction, but unknown gene(s)
=======
* statistical epistasis is observation of an interaction, but unknown gene(s)
>>>>>>> exam
	- late flowering allele may make you flower 3 days later in one plant, but only 1 day later in another or 2 days earlier in a third
	- an allele that always made all plants flower 3 days later, regardless of genotype —> no epistatic interactions
* biochemical epistasis -> known pathway & functions

<<<<<<< HEAD
Above distinction not clear and not important.  Skip.
-->

#### simple pathway example: 

precursor-> (enzyme A makes pigment)-> yellow pigment->(enzyme B turns yellow red)->red fruit (wt ) 
	- DRAW (leave on board) with enzymes as looped arrows not in pathway
=======
#### back to drawing (precursors): 

precursor-> (enzyme A makes pigment)-> yellow pigment->(enzyme B turns yellow red)->red fruit (wt ) 
>>>>>>> exam

aaBB ( white ); aabb (white); AAbb (yellow); AABB (red); AABB (red); 

mutant a is epistatic to b —> nonfunctioning mutation at locus A gives white regardless of locus B (always white)

<strong style="font-size: 150%; color: red;">?</strong> Is the same true of B? B depends on genotype at A (either yellow or white)

the epistatic locus is upstream in the pathway, changing precursor or action of other genes downstream.  

that's an example of recessive epistasis

dominant is possible too!  so now Aa - -  would also be white! (a > A)

Epistasis vocab (know definition, but not worry about crosses on test)
<<<<<<< HEAD

=======
>>>>>>> exam
* **suppressor**  (mutant that suppresses effects of other mutant making it wt)
* **synthetic lethals** (two mutants @ different genes each nonlethal together lethal)
* **penetrance** (% individuals with the phenotype)
	- e.g. mutant that makes you inefficient at getting water from soil will show low penetrance in an irrigated system
* **expressivity** how much expressed (little effect on drought tolerance or lots) varies among individuals

(for mitochondrial traits **homoplasmy** and **heteroplasmy** which helps explain incomplete penetrance or expressivity)

<img src="./griffiths/ch06/figure_06_22.jpg" style="width: 250px;"/>

## Example # 37 Ch6

Snapdragon breeds true for white petals. x snapdragon breeds true for purple.  All F1 were white.  F2 are 240 white, 61 solid purple, 19 spotted purple. for a total of 320.  

If you're not supposed to memorize these ratios, how to solve these? 

First, rarely do you have to do science fast. So take some time, relax, and think.

It's really just hypothesis testing. 

H1: It's one locus dominant. Prediction (after drawing punnet square): 3:1. Rejected!

H2: Two loci, recessive epistasis. Save you the time and think wait then why do we see white and purple dominate? Leave this for now and test dominant epistasis.

H3: Dominant epistasis, two loci. We'll invent some genotypes:

AAbb white parent
aaBB purple parent  <strong style="font-size: 150%; color: red;">?</strong> Why do parents have to be homozygous?  Because are true breeding.

Because white is dominant, let's say white epistatic to purple, so then:

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