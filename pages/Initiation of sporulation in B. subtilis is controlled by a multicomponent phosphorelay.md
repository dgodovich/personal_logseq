date:: 2/1991
issn:: 00928674
issue:: 3
doi:: 10.1016/0092-8674(91)90238-T
title:: Initiation of sporulation in B. subtilis is controlled by a multicomponent phosphorelay
pages:: 545-552
volume:: 64
item-type:: [[journalArticle]]
access-date:: 2025-09-04T20:52:10Z
rights:: https://www.elsevier.com/tdm/userlicense/1.0/
original-title:: Initiation of sporulation in B. subtilis is controlled by a multicomponent phosphorelay
language:: en
url:: https://linkinghub.elsevier.com/retrieve/pii/009286749190238T
publication-title:: Cell
journal-abbreviation:: Cell
authors:: [[David Burbulys]], [[Kathleen A. Trach]], [[James A. Hoch]]
library-catalog:: DOI.org (Crossref)
links:: [Local library](zotero://select/library/items/EPZERC7M), [Web library](https://www.zotero.org/users/6106196/items/EPZERC7M)

- [[Abstract]]
	- Stage 0 sporulation (spo0) mutants of Bacillus subtilis are defective in the signal transduction system initiating sporulation. Two of the products of these genes, Spo0A and SpoOF, are related to response regulator components of two-component regulatorysystemsused to control environmental responses in bacteria. The SpoOF response regulator was found to be the primary substrate for phosphorylation by the sporulation-specifi¢ protein kinase, KinA. Phosphorylated SpoOF was the phoaphodonor for a phosphotransferase, Spo0B, which transferred the phosphate group to the second response regulator, the transcription regulatory protein Spo0A. This phosphorelay provides a mechanism for signal gathering from several protein kinases using SpoOF as a secondary messenger. These divergent signals are integrated through Spo0B phosphotransferase to activate the Spo0A transcription factor. This system provides for many levels of control to prevent capricious induction of sporulation.
- Attachments
	- [PDF](zotero://select/library/items/D4T9HLKF) {{zotero-imported-file D4T9HLKF, "Burbulys et al. - 1991 - Initiation of sporulation in B. subtilis is controlled by a multicomponent phosphorelay.pdf"}}
- Integration of various phosphorylating signals
- Thoughts from the tommentary
	- phosphorelay is an extension of the two component regulatory system that we saw with the Omps
	- This gives you more fine tuned control over the kinetics and amplification of the signaling I guess?
	- Suppressor mutation that eliminates the need for all the other spo0 proteins is likely one that moves the equilibrium towards being phosphorylated
- ((68f45264-5f99-4718-9d24-af4eed334254))
	- Sporulating bacteria can initiate that in a small window of the cell cycle
	- Has to happen before the start of new DNA synthesis (i.e. G1)
	- Group of mutants that can't sporulate, only ever divide
		- spo0 mutants (A, B, E, F, H)
		- spo0A is the key regulatory protein
			- negative regulator of AbrB repressor
	- AbrB binds to promoter targets with cooperative binding
		- they say that this isn't a typical repressor but it sure sounds like one?
		- doesn't seem to have a DNA binding sequence, more about promoter secondary structure
	- falling AbrB levels gives release of repression, caused by higher Spo0A
	- Sof-1 is the suppressor mutant that doesn't need the other spo's
		- other genes modify Spo0A into the active form
	- N terminus is similar to OmpR N terminus
		- phosphorylation homology
	- There isn't a transmitter kinase yet
- ((68f45814-61fd-425c-b01a-955e44ea0119))
	- KinA can phosphorylate both Spo0F and Spo0A
		- but it's way better for Spo0F (3450 fold) table 1
	- Spo0B is needed to transfer phosphate from Spo0F to Spo0A
		- KinA can only phosphorylate Spo0F
		- Adding Spo0F along with B you get transfer of Pi to B
			- And adding A to this mix you get further transfer to A
		- This could be cause by a phosphotransfer, or something is changing KinA so that it's effective on Spo0A
	- KinA used to phosphorylate Spo0F and then that's transferred and that is sufficient to transfer to B and A
		- ((68f45a25-cd72-41dc-93e7-a9415d066597))
	- They also test that B can transfer independently to F and A
		- figure 4
		- When you have B_P, it preferentially transfers to A over F
	- They also check in Figure 5 which residue the P is transferred to
		- Asp 10 and Asp56 -> Asn mutations make it non functional
		- Analogous to CheY system, which makes sense
		- They also check this with pH sensitivity and it checks out
			- B is extremely sensitive to acid but not to base, this seems to be His
- ((68f45d00-8c21-49f0-bdeb-eff51104f9af))
	- response regulator is often a transcriptional activator
	- relay gives you another opportunity for control of a very expensive system
		- sporulation is hard and you wouldn't want to reverse it
	- KinA is also a phosphatase at high ATP levels
	- Spo0A turns off AbrB and also makes a \sigma for sporulation
	-