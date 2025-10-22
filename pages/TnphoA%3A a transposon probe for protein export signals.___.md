date:: 12/1985
issn:: "0027-8424, 1091-6490"
issue:: 23
doi:: 10.1073/pnas.82.23.8129
title:: TnphoA: a transposon probe for protein export signals.
pages:: 8129-8133
volume:: 82
item-type:: [[journalArticle]]
access-date:: 2025-09-04T20:52:56Z
original-title:: TnphoA: a transposon probe for protein export signals.
language:: en
url:: https://pnas.org/doi/full/10.1073/pnas.82.23.8129
short-title:: TnphoA
publication-title:: Proceedings of the National Academy of Sciences
journal-abbreviation:: Proc. Natl. Acad. Sci. U.S.A.
authors:: [[C Manoil]], [[J Beckwith]]
library-catalog:: DOI.org (Crossref)
links:: [Local library](zotero://select/library/items/NVGA5FAV), [Web library](https://www.zotero.org/users/6106196/items/NVGA5FAV)

- [[Abstract]]
	- We constructed a derivative of transposon TnS that permits the generation of hybrid proteins composed of alkaline phosphatase (EC 3.1.3.1) lacking its signal peptide fused to amino-terminal sequences of other proteins. Such a hybrid gives alkaline phosphatase activity if the protein fused to alkaline phosphatase contributes sequences that promote export and thus compensate for the missing alkaline phosphatase signal peptide. Fusions to both a secreted periplasmic protein and a complex cytoplasmic membrane protein led to alkaline phosphatase activity. TnphoA fusions should help localize export signals within the structure of a protein, such as a transmembrane protein, as well as identify new chromosomal genes for secreted and transmembrane proteins.
- Attachments
	- [PDF](zotero://select/library/items/Z54HNJHU) {{zotero-imported-file Z54HNJHU, "Manoil and Beckwith - 1985 - TnphoA a transposon probe for protein export signals..pdf"}}
- Tn5 transposase! ATACseq??
- Protein fusions are important for study of protein export
	- most of these use \beta\gal, but this can't pass through the cytoplasmic membrane
	- so use alkaline phosphatase instead so that you can get into periplasm
	- You can attach different signal sequences and get them through
- Use transposon to do this attachment in vivo
- ((68f8352c-8b1e-4c18-8ea9-815b6ed84615))
	- opal stop mutant
	- They use lac to screen for transposition into plasmids
		- also use a high concentration of kanamycin to select for multicopy
	- plasmid are described elsewhere bruh
- Construct a derivative of Tn5 that has alkaline phosphatase on one end
	- but without the signal sequence, importantly
	- so this should transfer phoA when it jumps
	- schematic of this shown in figure 1
	- I'm not sure I really understand how recombination works
		- why does it switch direction
- Test function by transferring \beta\lactamase, periplasmic location
- There's an opal nonsense mutation at the junction between phoA and IS50L sequence fragment
	- this isn't ideal
	- They expected this, so they used an opal suppressor strain
	- mutate with a selection for plasmid linked suppressor independent expression of phoA
- Figure 2 has a western blot that didn't work lmao
	- B3 has no band
	- eh there's a band nvm it's just faint
- So it seems that during recombination you get an inversion of the R fragment at the end of phoA and it becomes L
	- or maybe the whole thing inverts?
- B-[1234] are bla-phoA fusions
- G-[34] are lacZ-phoA fusions
-
- Tom questions
	- Make sure you understand the logic and rationale of the approach
	- What are the limitations of this technique?
		- You need to have transposon jumping, so probably need to have a lot of screening? How can you be sure that the transposon jumps to the right spot in the genome? off target effects? limit it to one jump?
	- How could you decide whether these limitations are serious?
		- It seems that you can do the screening fairly easily because it's all in E. coli
		- Maybe the off target effects just suppress? Is there a way to activate/deactivate the transposon when you want it? add and then remove a plasmid?
	- what would you do to test the possibilities of the approach further?
	- Suggest at least two possible reasons for the low-level alkaline phosphatase activity in the "cytoplasmic" fusions and propose experiments that could distinguish between them.
		- So we know that alkaline phosphatase is not active in the cytoplasm
		- pH? can't fold correctly because of a charge imbalance
		- Some kind of phosphorylation? or other post translational modification that inactivates it
		- Oh it seems that it's a disulfide bond thing according to Tom above
	- How do you think the Sec machinery assembles membrane proteins with multiple transmembrane domains? polytopic membrane proteins?
		- This is a great question I have not ever thought about
		- It could wrap it around other hydrophobic things that can insert more easily into the membrane?
		- Make some kind of core
		- could you slip the whole transmembrane domain out of the translocon in one moment