# BIS101 F2013 Lecture 13: Bacterial Gene Expression

## Gene regulation possibilities

constitutive? (always on) vs regulated: 

transcriptional regulation can affect 1) initiation 2) amount

* **Activator**
 	- binds to activator binding site on DNA (on or near promoter region, or in enhancer sites in eukaryotes)
	- facilitate binding of RNA polymerase and initiate transcription
	- can require binding of an **effector**
	- **allosteric domain** and conformation change
   - **inhibitor** can prevent from binding
* **Repressor**
	- binds to control sequence called an **operator** and prevents transcription
	- **corepressor** molecule can be required for binding
	- **inducer** molecule can prevent from binding

<img src="/Users/jri/src/bis101/images/activators.jpg" style="width: 400px;"/>
<img src="/Users/jri/src/bis101/images/repressors.jpg" style="width: 400px;"/>

Gene: What is a gene<strong style="font-size: 150%; color: red;">?</strong> 

Fundamental physical and functional unit of heredity which carries information from one generation to the next

A segment of DNA, composed of a transcribed region and usually a regulatory sequence that makes possible transcription.
    
What is an operon <strong style="font-size: 150%; color: red;">?</strong> a group of genes that are coregulated.  Each codes for a separate product, but all share common transcription and regulation.

makes for efficient regulation of a system or pathway

polycistronic transcription (vs. monocistronic): makes multiple proteins from same transcript; common in bacteria, rare in eukaryotes

## lac operon

<img src="/Users/jri/src/bis101/images/lacoperon.jpg" style="width: 700px;"/>

normally E. coli uses glucose for metabolism

lac operon is inducible -- normally not highly expressed, doesn't take up or use lactose
    in absence of glucose, lac+ (wild type) can induce expression of operon to use lactose

confusing naming

#### genes:

lacZ lacY lacA are protein-coding DNA

* permease lacY allows lactose in
* lactose -> galactose + glucose by enzyme beta-galactosidase (**lacZ**)
	- occasionally produces allolactose 
* **lacA** transacetylase -> not well known but perhaps transfer acetyl group from nonmetabolizeable sugars so as to prevent reentry into cell?

#### regulatory regions

lacP promotor

CAP binding site binds CAP-CAMP complex: catabolite activator protein (CAP) and cyclic adenosine monophosphate (cAMP) (signal transduction). bends DNA to open for RNA pol and ++ expression

glycolisis? (metabolic pathway get energy from glucose) reduces availability of cAMP, keeping expression low

####  Glucose, no lactose

<img src="/Users/jri/src/bis101/images/glucose.jpg" style="width: 400px;"/>

lacI repressor protein binds to lacO operator

lacO actually overlaps promoter and transcript; RNA pol can't bind

lacI operate cis or trans<strong style="font-size: 150%; color: red;">?</strong>	 (trans)

mutations in lacO cis or trans <strong style="font-size: 150%; color: red;">?</strong>  (cis)

#### Lactose, no glucose

<img src="/Users/jri/src/bis101/images/lactose.jpg" style="width: 400px;"/>

RNA pol binds to lacP promoter (not operator as in figure)

cAMP abundant, CAP-cAMP open DNA -> lots of transcription

Problem <strong style="font-size: 150%; color: red;">?</strong> need lactose to get started, but how's it get in with no permease<strong style="font-size: 150%; color: red;">?</strong> 

repressor falls off occasionally!

####  Glucose and lactose?

cAMP very limited, so low expression of operon

allolactose inducer may be present, no binding of repressor
    
#### Mutants of lac operon
   
* Oc repressor can't bind: effect <strong style="font-size: 150%; color: red;">?</strong> constitutive expression of lac operon (cis/trans<strong style="font-size: 150%; color: red;">?</strong>)
* I- bad repressor, can't bind.
* Z- or Y- can't make functional genes
* complementation (?) because can make a merodiploid by using F plasmid

Go over F’ I+P+OcZ-Y+A+/ I+P+O+Z+Y-A+
        F' can't make galactosidase, bacteria can't make perm ease. neither functions
        F' also constitutively expressed b/c can't bind promoter.
        het functions normally -> constitutive expression of permease, inducible expression of galactosidase
       
## Hawaiian bobtail squid

<img src="/Users/jri/src/bis101/images/quid.jpg" style="width: 600px;"/>


bioluminescescent underbelly to be camouflaged at night against starry/moonlight sky
contains special organs to capture and cultivate Alivibrio fischeri bacteria

A. fischeri lux operon is expressed under glucose starvation (CAMP binding site)
    bidirectional transcription between I & R

also binding site for transcription activator luxR, which only binds when bound to its effector luxI

luxI protein secreted from cell. a single cell doesn't produce enough luxI to bioluminesce (free-living A. fischeri don't bioluminesce!)

when cells are concentrated, enough luxI produced -> feedback loop        
        
## Attenuation of tryp operon

<img src="/Users/jri/src/bis101/images/trypoperon.jpg" style="width: 600px;"/>

(draw "some genes to make tryptophan" downstream)

makes amino acid tryptophan

has repressor-cosupressor model (tryptophan is corepressor, needed to bind & repress)

but instead of just on/off like lac, has dimmer switch in form of repeats in RNA

initial short polypeptide w/ repeated tryp codons

lots of tryp: ribosome stops at small stop codon and is on top of 1&2, loop 3-4 forms and terminates transcription of polymerase

little tryp: ribosome stalls in initial polypeptide b/c can't make it through tryp AAs.  stalled ribosome let 2-3 mRNA loop form



