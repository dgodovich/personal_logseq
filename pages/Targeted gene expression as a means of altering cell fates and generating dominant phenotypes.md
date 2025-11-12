date:: [[Jun 1st, 1993]]
issn:: "0950-1991, 1477-9129"
issue:: 2
doi:: 10.1242/dev.118.2.401
title:: Targeted gene expression as a means of altering cell fates and generating dominant phenotypes
pages:: 401-415
volume:: 118
item-type:: [[journalArticle]]
access-date:: 2025-09-04T20:52:14Z
rights:: http://www.biologists.com/user-licence-1-1/
original-title:: Targeted gene expression as a means of altering cell fates and generating dominant phenotypes
language:: en
url:: https://journals.biologists.com/dev/article/118/2/401/37970/Targeted-gene-expression-as-a-means-of-altering
publication-title:: Development
authors:: [[Andrea H. Brand]], [[Norbert Perrimon]]
library-catalog:: DOI.org (Crossref)
links:: [Local library](zotero://select/library/items/FFINYX5J), [Web library](https://www.zotero.org/users/6106196/items/FFINYX5J)

- [[Abstract]]
	- We have designed a system for targeted gene expression that allows the selective activation of any cloned gene in a wide variety of tissue- and cell-speciﬁc patterns. The gene encoding the yeast transcriptional activator GAL4 is inserted randomly into the Drosophila genome to drive GAL4 expression from one of a diverse array of genomic enhancers. It is then possible to introduce a gene containing GAL4 binding sites within its promoter, to activate it in those cells where GAL4 is expressed, and to observe the effect of this directed misexpression on development. We have used GAL4-directed transcription to expand the domain of embryonic expression of the homeobox protein even-skipped. We show that even-skipped represses wingless and transforms cells that would normally secrete naked cuticle into denticle secreting cells. The GAL4 system can thus be used to study regulatory interactions during embryonic development. In adults, targeted expression can be used to generate dominant phenotypes for use in genetic screens. We have directed expression of an activated form of the Dras2 protein, resulting in dominant eye and wing defects that can be used in screens to identify other members of the Dras2 signal transduction pathway.
- Attachments
	- [PDF](zotero://select/library/items/LTA9394Z) {{zotero-imported-file LTA9394Z, "Brand and Perrimon - 1993 - Targeted gene expression as a means of altering cell fates and generating dominant phenotypes.pdf"}}
- ((69140fbd-7988-4dfb-bd5f-1c3a11472737))
	- Site specific expression of anything is useful
		- this sounds like optogenetics light
	- Heat shock is an option that already exists
		- This is inducible which is nice
		- But you get expression everywhere, it's leaky, and heat shock itself causes phenotypes
	- Can also drive expression from a tissue specific promoter
		- tissue specific
		- but requires a lot of work and can be toxic
	- Their method uses two lines
		- One has silent target gene because there's no activator
		- Second has activator but no target gene
		- So it's only the progeny that get both
	- Use yeast GAL4 as an ectopic activator
		- This needs a specific site to bind to, UAS (Upstream Activation Sequence)
	- Pattern the activator to get expression patterns
		- Can use characterized promoters to drive GAL4 expression
		- Can also attach it to a transposase promoter that can drive itself or be attached to other genes
	- Can generate dominant phenotypes in adult with the same system
		- Hopefully they explain more of this later I didn't get it
- ((69141223-0344-4c69-8a41-bdc476e5d87a))
  id:: 6914120e-0b86-4d5d-9e45-75ae5fe35c5d
	- Liz says we need to read the methods
	- enhancer detection
	- I don't really get it but that's ok
- ((691417c0-5d77-4fff-9dae-69b8d8add157))
	- fuse to an ocelli specific promoter and that works, Fig 2
- ((6914193a-72d2-4b05-9f0e-3505cbf112b8))
	- They have a vector that's sensitive to enhancers? How does that work?
	- directed by weak promoter of the P-transposase gene
	- random integration and then the promoter goes under the control of genomic enhancers
	- NLS on the P-transposase sequence so it's transcriptionally active GAL4
	- They somehow get a lot in the salivary glands but this seems like an accident
	- Generally they get a good amount that have tissue specific expression
		- Look at some examples of this in figure 3
- ((69141ad5-4461-4d5c-bd33-b996c2ffb2c5))
	- Combo tissue specific GAL4 with target gene UAS to get misexpression of target gene
	- UAS-eve with *hairy* enhancer line, so eve shows up where *hairy* is supposed to be
	- Extra denticle phenotype because you don't get wingless
- ((69141ba6-a240-45b0-b4a5-775a3841f5ee))
	- Limit transcription of a mutant to a non-essential tissue so that it's not lethal
	- Dras2^Val14 mutant is lethal most of the time and always has a severe phenotype
		- But you can make this not a problem if you limit it's expression to just the eye with a tissue specific Gal4
		- Has to be the right tissue, because depending on when it's expressed it could still be lethal
		- But you get more control in any case
	-
-
- Questions:
- 1) What can you learn from misexpression/overexpression of a gene?
- 2) What are the advantages of a 2-part system like GAL4/UAS?
- 3) What are the two strategies for deploying the GAL4 activator and how do they differ?
- 4) What are enhancer traps and why are they useful?
- 5) Why might it be useful to generate dominant phenotypes?