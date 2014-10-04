# BIS101 F2013 Lecture 10: Mutation

## Point Mutations (single nucleotide/base)

We have mentioned these briefly, but now in more detail. Other forms of mutation include TEs, chromosomal aberrations

**bp substitution**. note substitution has a different connotation in popgen.

* **transition vs. transversion**
	- C-T/A-G vs. not
	- but keep track of both strands: GC->AT transition but GC->TA transverion
 * transitions caused by wrong form of base. 
	- Each of the bases exists in >1 form. 
	- Normal "keto" form is found in DNA. 
	- But shift of the bonds (ionized form) will lead to slightly different form that then pairs incorrectly. I.E. imino cytosine pairs with adenine instead of guanine during replication
* transversions caused by accidental pairing of pyrimidine w/ self or purine w/ self during replication

**indel** insertion/deletion

* determining ancestry hard (show)
* **Replication slippage.** Draw CTGAGAGA and complement.
* pops out a single strand loop.  loop either deleted or added next round.
* expansion of trinucleotide repeat arrays due to rep. slippage can cause diseases in humans like fragile X, huntington's disease (spinal and muscular atrophy)

when do mutations occur?  common misconception is that selection agent arises (say antibiotics) and that CAUSES adaptive mutations to arise. 

sometimes adaptation/evolution occurs from **spontaneous** mutations that arise after selection, but often occurs as a reulst of **standing genetic variation** or mutations segregating in the population.

Luria/Delbruck teset in book is classic experiment testing this.


### Effects on protein coding sequence

recall that DNA is transcribed to RNA, and RNA translated to protein in codons of 3bp.

**synonymous**. likely effect <strong style="font-size: 150%; color: red;">?</strong> usually mild

* codon usage bias: if most of the tRNAs use one codon, then another codon even of same AA will have to wait longer, so gene is transcribed slower. 
* weak or strong selection <strong style="font-size: 150%; color: red;">?</strong> weak. generally only found in genes that are really highly expressed and needed all the time.

**nonsynonmyous** (missense). likely effet <strong style="font-size: 150%; color: red;">?</strong> depends

* AA come in all sorts of categories: size, charge, hydrophobic/hydrophilic, etc.
* replacement of an AA with a similar one might be neutral. sometimes only need an AA of particular quality.
* example of protein storage gene globulin-1 

**premature stop** (nonsense, truncation). likely effect <strong style="font-size: 150%; color: red;">?</strong> bad

**frameshift** 

* can be cause by substitution <strong style="font-size: 150%; color: red;">?</strong> no. only indel
* shifts all codons -- shifts the "frame" of translation
* what happens if multiples of 3 <strong style="font-size: 150%; color: red;">?</strong>

**splice-site**. what is a splice site<strong style="font-size: 150%; color: red;">?</strong>

* usually bad, because turns intron -> exon and messes everything up

### Effects on noncoding

Harder to predict. Some proportion of noncoding DNA likely junk, so who cares.  

In Drosophila though a majority of noncoding mutations seem to be influenced by selection.

Why would noncoding mutation matter <strong style="font-size: 150%; color: red;">?</strong>

All sorts of important DNA regions that don't code for protein: promoters, enhancers, etc. -- regions where proteins or RNA that regulate a gene bind either to DNA or RNA

Consequences include change in expression level, in where expression occurs. Can be mild, but can be just as deleterious as changes in protein coding regions.

Mutations in a noncoding region could, for example, affect where PRDM9 binds and thus change where recombination hotspots occur.

## Mechanisms of spontaneous mutations

DNA replication as mentioned above

* In total, replication error is on order of 10^-5!! In human genome that means replication causes 30,000 new mutations!


#### Spontaneous lesions

Naturally occuring damage to DNA.

depurination - purine base losty when bond to deoxyribose as broken. happense spontaneously can be exacerbated by environment
 * resulting apurinic site has no base, so nothing to pair!

deamination - loss of amino group cytosine -> uracil

* next round of replication, uracil pairs with <strong style="font-size: 150%; color: red;">?</strong> adenine. so GC -> AT what kind <strong style="font-size: 150%; color: red;">?</strong> (transition)
* especially common in methlyated cytosine. as we will see, 5-methyl cytosine is important enough to be called sometimes 5th base

#### Induced mutation

Things that can cause mutants called **mutagens**

**base damage** 

* UV can cause pyramidines on same strand to covalently bond, preventing DNA replication or transcription. these are the primary cause of skin cancer in humans.
	- organisms living at high altitude have to adapt to increased UV radiation. CORN!
* ionizing radiation can cause apurination, strand breaks, etc.

**base analogs**. molecules sufficiently similar that can be incorporated, but pair wrong. (2-amino-purine e.g.)

**alteration of bases** causing them to pair incorrectly

**intercalation** <strong style="font-size: 150%; color: red;">?</strong> molecules that can slip between bases and cause insertion deletions during replication.

* how many of you worked with gel? EtBr is intercalating agent. how it binds DNA on gel, and what happens when it gets on you!

## Repair mechanisms

DNA polymerase

* polmyerase adds bases 5'->3' but can remove bases 3'->5'
* recognizes errors, cuts out and repairs
* mostly due to a very tight fit in the active site.
* different polymerases have different abilities to recognize/tolerate different mutations
* This drops from 10^-5 to 10^-7, but still 300 mutations every replication!

direct reversal

* other enzymes can directly reverse some mutations (e.g.thymine dimers) but in general rare

Several **homology based** <strong style="font-size: 150%; color: red;">?</strong> pathways to fix missing/bulky mutations

* suite of enzymes first remove altered base
* cut out surrounding DNA
* polymerase fills in, ligase seals shut
* base excision repair for nonbulky changes, nucleotide excision repair for bigger ones, etc.
* can recognize e.g. uracil which doesn't belong

Finally **mismatch repair** 

* similarly cuts out error, fills in
* How recognize which is the wrong base <strong style="font-size: 150%; color: red;">?</strong>
	- mentioned cytosine methylation, but adenine also methylated
	- since DNA replication is semiconservative, old strand will have methylation and errors always in new strand!
* unknown in eukaryotes!
* mutations in genes that do this in humans lead to e.g. syndromes that are high risk for cancer. so common odds are good 1 person in this room has it.
	- the locus is haplosufficient. cells with one good copy fxn normal
	- so is mutation dominant or recessive <strong style="font-size: 150%; color: red;">?</strong>
	- normally yes, but here what happens is anytime you accidentally lose or knock out the other copy, a cell with just the mutant copy (hemizygous) goes nuts and causes cancer. so the gene is haplosufficient but the syndrom is dominant!

Together these reduce from 10^-7 to 10^-9, so 3 errors per rep. That's still a lot considering how often DNA is replicated.
 
* will those be inherited <strong style="font-size: 150%; color: red;">?</strong>
* no. so if you spill EtBr on your elbow, you may get elbow cancer, but it won't effect your kids. 

These repairs mechanisms are **error-free** in that don't cause new errors.

**Translesion synthesis** or SOS system is sort of emergency backup. A polymerase that can tolerate blockages that would stop normal polymerases. But these tolerant polymerases don't have error-correction, so cause new errors (but better than cell death)

#### DSB repair

DSBs can be spontaneous, or caused by radiation.

How repair? No complementary strand to go off of.

**synthesis-dependent strand annealing.** uses strand invasion similar to what happens in recombination to repair one chromosome using the homolog as a template (instead of other strand). when can this happen <strong style="font-size: 150%; color: red;">?</strong> dividing cells only.

**NHEJ nonhomologous end joining**. enzymes that grab on to broken ends to prevent further problems, trim, and then ligase joins back together. when can this happen <strong style="font-size: 150%; color: red;">?</strong> anytime. and most cells are not undergoing division most the time.

 















