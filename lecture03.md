# BIS101 F2013 Lecture 3: Gene Interaction

## Questions

## Reading

Skip 4.3,4.4

## Allele effects

#### dominant/recessive

* bad mutations often but not always recessive — dominant negative examples in book
* <strong style="font-size: 150%; color: red;">?</strong> **null mutation** which producess a non-functioning copy (not all mutations are null!)
* Figure 6-1 and 6-2 nice drawing explaining haplosufficiency

#### incomplete dominance (white/pink/red, draw genotypes) 

* intermediate phenotype — mixing on a quantitative scale
* remember this is from phenotype perspective -- here looks like mixing
* also not the same as a **quantitative trait** e.g. human height is not incomplete dominance! because >1 locus is involved

#### codominance  — both alleles are expressed

* blood types (ignoring the Rh factor +/- here)
	- 3 alleles, I^A, I^B, i
	- I^A / (A or i) A blood type
	- I^B / (B or i) B
	- I^A / I^B AB type
	- i/i O type
	
* at phenotypic level looks different from incomplete dominance
* at genetic level both are pretty much the same
* reality we treat dominance as a variable, where 0 is recessive and 1 is dominant
* phenotype can be e.g. 0, a*d, a (don't need to know, and notation not really correct)
        
#### lethal

* can be dominant or recessive — <strong style="font-size: 150%; color: red;">?</strong> why is recessive more common?

#### pleiotropy — has more than one effect

* can be silly <strong style="font-size: 150%; color: red;">?</strong> what other effects might an allele that increases height have?
* "real" pleiotropy is traits that are less obviously correlated.  perhaps an enzyme is ne5eded for pathway to flower and to make leaf hairs.  a mutant in the gene for that enzyme would have two phenotypes

<<<<<<< HEAD
## How many loci?

In Arabidopsis example (hairy vs. glabrous leaves) from last time, two mutants, how know if same or different loci?

 **complementation** test: fig. 6-12 in the book rad

<!-- REDO BELOW W/ ARABIDOPSIS TRICHOME EXAMPLE-->

WT red plant, mutant white

* make recessive homozygote lines of two recessive mutants (so now a<A and b<B), cross to make double mutants
=======
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
>>>>>>> exam
* draw out two possibilities (separate loci, same locus)
* <strong style="font-size: 150%; color: red;">?</strong> If I cross two whites -> red 1 or 2 loci (what are genos)? 	
 	- aaBB x AAbb (both white) = ? AaBb (red)
* <strong style="font-size: 150%; color: red;">?</strong> why use recessive and not dominant mutants? (because no complementation even if in different genes)
* <strong style="font-size: 150%; color: red;">?</strong> how do you know if your mutant is recessive? (make F1 and self!)
* what if I take two white plants w/ recessive mutants cross and = white?
	- perhaps aaBB x a'a'BB = aa'BB (fail to complement b/c just two mutations of same gene)

<<<<<<< HEAD

## Pathways

genes not in vacuum and not just make one product that does it's thing

we've considered effects of alleles at each gene independent of others

* e.g. effects of alleles at the round/wrinkled locus not change effects of alleles at the yellow/green locus
* usually or often not the case
    ￼
Example: oversimplification of flowering time pathway in rice

<img src="./images/rice_pathway.jpg" style="width: 300px;"/>

=======
fig. 6-12 in the book rad
>>>>>>> exam

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