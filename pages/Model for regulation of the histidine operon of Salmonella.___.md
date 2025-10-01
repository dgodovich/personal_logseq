date:: 01/1980
issn:: "0027-8424, 1091-6490"
issue:: 1
doi:: 10.1073/pnas.77.1.508
title:: Model for regulation of the histidine operon of Salmonella.
pages:: 508-512
volume:: 77
item-type:: [[journalArticle]]
access-date:: 2025-09-04T20:52:19Z
original-title:: Model for regulation of the histidine operon of Salmonella.
language:: en
url:: https://pnas.org/doi/full/10.1073/pnas.77.1.508
publication-title:: Proceedings of the National Academy of Sciences
journal-abbreviation:: Proc. Natl. Acad. Sci. U.S.A.
authors:: [[H M Johnston]], [[W M Barnes]], [[F G Chumley]], [[L Bossi]], [[J R Roth]]
library-catalog:: DOI.org (Crossref)
links:: [Local library](zotero://select/library/items/B2WTX6VY), [Web library](https://www.zotero.org/users/6106196/items/B2WTX6VY)

- [[Abstract]]
	- A model is proposed that accounts for regulation of the histidine operon by a mechanism involving alternative configurations of mRNA secondary structure (the alternative stem model). New evidence for the model includes sequence data on three regulatory mutations. The first (his01242) is a mutation that deletes sequences needed to form the attenuator mRNA stem and causes constitutive operon expression. The second mutation (his09654) is a His- ochre (UAA) mutation in the leader peptide gene; the existence of this mutation constitutes evidence that the leader peptide gene is translated. The third mutation (his09663) is remarkable. It neither generates a nonsense codon nor affects a translated sequence; yet, it is suppressible by amber suppressors. We believe this mutation causes a His- phenotype by interfering with mRNA secondary structure. The suppressibility of the mutation is probably due to disruption of the attenuator stem by ribosomes that read through the terminator codon of the leader peptide gene. This explanation is supported by the observation of derepression of a wild-type control region in the presence of an amber suppressor. Evidence is presented that hisT mutants (which lack pseudouridine in the anticodon arm of histidine tRNA) may cause derepression of the his operon by slowing protein synthesis in the leader peptide gene.
- Attachments
	- [PDF](zotero://select/library/items/YQ7MSSG5) {{zotero-imported-file YQ7MSSG5, "Johnston et al. - 1980 - Model for regulation of the histidine operon of Salmonella..pdf"}}
- His has no regulatory protein (repressor or activator) -> how does that work?
- Background
	- There's a large number of constitutive mutants, which is nice
	- 6 classes of these
		- hisO is in the operon
			- cis dominant
		- HisR, S, T, U, W are not near the operon
			- seems like all of these are not in a repressor, but change the tRNA
			- recessive
	- operon expression must sense the level of histidyl-tRNA
	- control region has a barrier to transcription called the attenuator
	- the operon sequence has dyad symmetry which makes a 14 bp stem loop (hairpin)
	- also has a 16 AA peptide that has 7 histidines in it
		- could be sensing here?
- ((68dca599-c8bd-42f9-bed9-f21af77726b6))
	- ((68dca1a3-1d35-490f-89e8-6709a792e034))
		- steric block?
	- If the promoter proximal (5') end is in a different secondary structure when the 3' end is made, no attenuation happens
	- there's other possible loop pairing that wouldn't cause attenuation
		- I'm not sure why this is the case? why would a loop in a different spot not block the polymerase complex?
	- assumption that ribosomes can disrupt RNA secondary structure as they translate RNA
	- there's A-F sequences that can form stem loops and which ones do depend on where the ribosome is
		- which depends on how much tRNA there is? not sure how they get here
		- oh I see
			- there's a repetitive sequence
			- CAU CAU CAC CAU CAU CCU GAC UAG(stop)
			- CAU and CAC are histidine codons
	- excess of histidyl tRNA means the ribosome can keep up and get to the stop, and translation stops
	- if there's not enough tRNA the ribosome falls behind the polymerase and a different set of stem loops forms
		- no attenuator stem because half of it is in a different loop
	- some kind of kinetic model is more likely in actuality
- ((68dca58a-3e8f-42e5-8a9e-21fdb5eb711f))l
	- Attenuator constitutive mutant is unable to form an EF sequence stem (figure 2)
	- figure 3 has a map of the operon
		- nonsense mutations exist in there
		- His- mutants revert to His+ with high frequency
	- Leader peptide gene is translated; there's a nonsense mutation in this gene that is suppressed by ochre suppressors
		- UAA mutation (ochre) causes His- phenotype because of formation of attenuation loop
- What's up with the amber suppressors
	- they have a mutant that does not cause an amber mutation but can still be suppressed by amber suppressors (His- to His+)
	- It's in the B sequence and the "amber" mutation destabilizes the BC stem
	- so because BC is unfavorable you get CD and EF, and attenuation at all conditions
	- amber suppressors allow the ribosome to read through the normal stop of the leader peptide
		- there's another stop (UGA) at the attenuation stem
		- but when you get this close you would disrupt the stem and get activation
	- they check if amber suppressors generally activate the his system with a lac fusion
		- yep, they do
- hisT is a mutation in \Psi generation on tRNAs, which impacts their function and makes this system not work
	- they test this by looking in an amber suppressor that has a similar mutation
	- find that the hisT mutant weakens suppression
-