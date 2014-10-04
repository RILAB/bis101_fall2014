# BIS101 F2013 Lecture 16: Gene Isolation and Manipulation

## Notes

Sanders

Exam: same as last time. More short answer, less problem solving.  Took TA's <2 hours before clarification, both said easier than last exam. Will ask to keep answers brief for faster grading.

Regrades should be done -- check online in case you haven't been emailed.

Online evaluations. Please do! Especially constructive changes -- order of chapters, how best to incorporate papers, do you have a better suggestion than the papers?

Uploaded some slides on tb1 for this week's paper.

## Gene manipulation

In vitro vs. in vivo (vs. in silico)

## PCR

Need primer homologous to sequence of interest.
Nucleotides
Polymerase that can tolerate high temps (from where <strong style="font-size: 150%; color: red;">?</strong> T. aquaticus)

Work through two rounds of PCR

<img src="/Users/jri/Documents/courses/bis101/griffiths/ch10/figure_10_03.jpg" style="width: 300px"/>

## cDNA

Can use reverse transcriptase to amplify RNA and make cDNA. What would you use as a primer<strong style="font-size: 150%; color: red;">?</strong> T's to match poly-A tail.

RT then makes single-strand DNA complement. Then can sequence, transform, etc. Often useful for putting genes in bacteria or other organisms so no need to worry about correct splicing.

## Sequencing

#### Dideoxy 

(RIP Fred Sanger). Do PCR with a special nucleotide that blocks sythesis (lacks hydroxyl groups so later nucleotides cannot be added). Do four times once with special A, T, etc.

Result is set of fragments of different lengths corresponding to where special nucleotide was inserted (draw example seq. with A fragments, C fragments, etc.

Run the PCR done with A out on gel, get sizes. That tells you where A's were.  Etc.

#### Fancier

Dideoxy w/ flourescent nukes, can run all at once and look at color of fragment to get base

#### Even fancier

Sequencing by synthesis. Illumina. Chop up DNA. Add adapter seq. 

Use PCR of adapter to make tons of copies in physical spot on a chip. 

Each round, incorporate special bases that block more polymerase and are flourescent. Wash to remove unincorporated. Photo.

Remove 3' block (keep nucleotdie) and dye, repeat.

Draw how image on chip of red-blue-blue-green-red gives sequence.

$2.50 for 500bp of Dideoxy

$2.50 for 50,000,000bp of Illumina

## Cloning

Restriction enzymes <strong style="font-size: 150%; color: red;">?</strong> . Proteins that cut DNA. Can leave blunt or sticky ends.

e.g. EcoRI GAATTC cuts at first G on both strands (show). Where else have we seen sticky ends from restriction enzymes<strong style="font-size: 150%; color: red;">?</strong> TE insertion sites.

Sequences will have multiple restriction sites. Presence absence of sites can be found by running on gel. Can separate DNA based on size. DNA negatively charged, so can run current and DNA moves through gel.

These size fragments can be used as a marker! I do a digest of two individuals and their offsrping, places where they have different restriction sites will show up as different sized bands.  Presence/absence of these bands will segregate in offspring, and I can build genetic map.

#### Cloning

Not how to make Jusassic park, but instead process of copying a DNA not by PCR but by making bacteria do it for you.

Insert sequence of interest in plasmid -- circular self-replicating chromosome in a bacteria. Also called a vector.

Useful cloning plasmid needs:

* origin of replication (why<strong style="font-size: 150%; color: red;">?</strong> ) to replicate in host cell
* restriction sites (why <strong style="font-size: 150%; color: red;">?</strong> ) 
* reporter (antibiotic resistance) for <strong style="font-size: 150%; color: red;">?</strong> knowing plasmid made it into bacteria
* often will include reporter to break (lacZ) <strong style="font-size: 150%; color: red;">?</strong> so you know it has gene in there.  lacZ + beta-X-gal makes blue dye product.  So white colonies that survive = gene!

<img src="http://www.sigmaaldrich.com/content/dam/sigma-aldrich/life-science/molecular-biology/t7ampr.Par.0001.Image.gif" style="width: 300px"/>

MCS is set of restriction sites, where you insert sequence of interest.

**Show** how sticky-end allows cutting one sequence and inserting into plasmid.

Can work with blunt ends, just less efficient.  Both need ligase to connect the sugar-phosphate backbone.

New DNA inserted into bacteria by:

* Transformation: expose to DNA (sometimes heat shock cells so take up DNA more readily)
* Conjugation: exchange of DNA between bacteria
* Transduction: DNA from a bacteriophage <strong style="font-size: 150%; color: red;">?</strong> can be inserted into and taken up by bacteria.

A number of human proteins are engineerd in e. coli: insulin, HGH, erythropoetin (for bicyclists), proteases in laundry

## Probing

We can use cloning to make libraries of seuqence (cDNA or DNA). But how do we check for presence of sequence of interest.

Can use a petri dish of colonies or gel.

Transfer DNA from gel or plate onto a membrane, and wash the membrane with radioactively labelled sequence of interest. Then expose to X-Ray film (results is **autoradiogram**)and find witch band or which colony has sequence. Can also use flourescently tagged DNA and expose to light and photograph. 

Probe for DNA is called a Souther blot (after Dr. Edwin Southern).
Probe for RNA is called a Northern (because someone thought it was funny)
Probe for DNA uses an antibody, called a Western blot. Could use a non-antibody protein to detect protein-protein interactions. Then a far-western blot. Probe for post-translational modification of protein (phosphoylation etc) called an Eastern blot.

## Transformation in eukaryotes

Define: transgene: any gene introduced artificially into a genome. Can be from same species!

Anything with a transgene is a transgenci organism or a GMO. 

I have pretty strong opinions on GMOs and happy to talk about them if anyone's interested. But general fact is that there is no good science arguing that GMOs are dangerous. There is good science showing they are useful. Some might be bad, and some might have ecological consequences.  So testing/regulation a must. 

Transgene can either replace target gene or insert at dseired locus, or insert **ectopically**

<img src="/Users/jri/Documents/courses/bis101/griffiths/ch10/figure_10_24.jpg" style="width: 300px"/>


#### Yeast

Shuttle vector (yeast and e. coli Ori)

* do gene manipulation (cloning, etc.) in bacteria
* move into yeast, get homologous recombination -- replace sequence.

#### Plants

Agrobacterium

* T-region, flanked w/ repeats. This region encodes genes that make tumors. multiplies Agro. in plant.
* virulent region & conjugative  -> proteins to infect cell, transfer DNA, move to nucleus (prob.)
* make two plasmids
	- one with virulent/conjugative
	- one with new genes of interest & antibiotic or antiherbicide. add selectable marker (what is <strong style="font-size: 150%; color: red;">?</strong> ) to be sure you have the transformation vector and/or not the other vector

<img src="/Users/jri/Documents/courses/bis101/images/agro.jpg" style="width: 600px"/>

Gene gun: shoot DNA-coated tungsten (or gold) and hope for illegitimate recombination. Rare, so need to do a lot of cells.

Grow up cells in culture -> treat with hormones to get adult plant. Usually hemizygous (<strong style="font-size: 150%; color: red;">?</strong>) so need to self.

* round-up ready
* bt toxin
* golden rice (vitamin A)


#### Animals 
    
Inject into nucleus of fertilized egg cell (or gonads, etc.). In som animals will get incorporated into germline, and progeny will have mutation.

Can also use yeat-like homologous recombination in stem cells. Then insert stem cells into embryo to get transgenic animal.

* knock-out -- destroy locus
* knock-in -- insert something directly into a specific locus

Make libraries of knockouts, knockins for community use.

#### ZFN

Fancy genome editing: make use of enzymes that recognize specific sequences (Zinc Finger Domain remembered from where <strong style="font-size: 150%; color: red;">?</strong> ).  E.g. Zinc finger nucleases will cause cut at specific site determined by their binding domain. You can engineer the domain.  Cut can lead to:

* deleteion because cut is repiared how<strong style="font-size: 150%; color: red;">?</strong> NHEJ
* if also transform DNA w/ homologous sequence, can get insertion of new sequence. Allows you to e.g. cut out an A and add in a T.  Not easy to do. 

And now other technologies used. Advantages are can engineer specific proteins to modify specific site in genome. Disadvantages: harder and often mroe expensive to do.
















