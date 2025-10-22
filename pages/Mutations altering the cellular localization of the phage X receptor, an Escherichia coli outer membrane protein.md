date:: 1978
title:: Mutations altering the cellular localization of the phage X receptor, an Escherichia coli outer membrane protein
item-type:: [[journalArticle]]
original-title:: "Mutations altering the cellular localization of the phage X receptor, an Escherichia coli outer membrane protein"
language:: en
publication-title:: Proc. Natl. Acad. Sci. USA
authors:: [[Scott D Emr]], [[MAXIME SCHWARTZt]], [[Thomas J Silhavy]]
library-catalog:: Zotero
links:: [Local library](zotero://select/library/items/CC475ZFR), [Web library](https://www.zotero.org/users/6106196/items/CC475ZFR)

- [[Abstract]]
	- Two mutant strains of Escherichia coli have been isolated in which the cellular location of an outer membrane protein, the phage X receptor (the lamB gene product), is altered. These mutations were initially selected in a strain containing a lamB-lacZ fusion. In the parent strain the protein coded for by the hybrid gene is located, at least in part, in the outer membrane. In the mutants it is located in the cytoplasm. The mutations responsible for the alteration of cellular location lie very early in the lamB gene, in a region corresponding to the NH2-terminus of the X receptor protein. One of these mutations is a small deletion internal to the lamB gene., When this mutation is present in an otherwise wild-type lamB gene, the protein produced is of lower molecular weight than normal receptor.. The other mutation behaves as a point mutation; when it is present in an otherwise normal lamB gene, reversion can be demonstrated. The molecular weight of this mutant protein, which is located in the cytoplasm, is larger than that of the wild-type gene product by approximately 2000. It is suggested that these two mutations *re in the portion of the lamB gene coding for a signal sequence and thereby block export of the protein.
- Attachments
	- [PDF](zotero://select/library/items/IPUZEQT6) {{zotero-imported-file IPUZEQT6, "Emr et al. - 1978 - Mutations altering the cellular localization of the phage X receptor, an Escherichia coli outer memb.pdf"}}
- Genetics for protein localization is pretty crazy to me but they're doing it
- signal sequence at the N terminus of proteins
	- this binds the new peptide to the ER and then is cut off
	- protein is translated into the ER, i.e. opposite side of membrane
- They use lacZ fusions to study this (in classic Tom fashion)
	- N terminus is from lamB gene, so it should be able to be localized
- ((68f81d3f-3810-4948-8992-b6a0febb2f18))
	- radiolabeling of amino acids with C14
	- these are translational fusions
	- wow there's like no methods
- ((68f81dbb-2b35-416c-89f8-03a5a6f9c662))
	- pop3186 has maltose induced expression of lamB-lacZ fusion
		- this is the normal way \lambda receptor synthesis is induced
	- Maltose sensitive?
		- I'm not sure how this works, it gets induced by maltose, but it's also sensitive to it?
		- MalR mutants are Lac-, so bgal isn't working correctly
			- some of these are amber mutants and can be suppressed
	- Look for mutants that are MalR but Lac+
		- these probably have a localization defect
		- they describe how they found these, pretty standard stuff
			- no mutagenesis, screen
	- Ok, so now where is \beta\gal?
	- ((68f81f28-2eb3-4db5-bec3-958f4ef65112))
		- parental strain has a mixture of cytoplasmic and membrane protein, but the mutants are basically all cytoplasmic
		- SE1068 also has a lower molecular weight
			- this has a deletion in the signal sequence so it can't localize
		- SE1069 has a point mutation in the signal sequence so it can't localize
	- ((68f81f81-5e30-4a96-8613-5d20e9c956dc))
		- this seems important
		- Parental line cells don't need lactose permease, but the mutants do
		- This works because active bgal in the membrane does extracellular cleavage of lactose and then the glucose/galactose are imported
- They do mapping in a very easy way
	- because the gene is on a phage gene, if you make a phage it should transfer the phenotype (transducing phage)
	- lysogenize a \Delta\lac stain to test if the phage transduced lac+ and did not make the cells MalS
		- it did
	- they also test this with a Dex phenotype
		- Dex- is lack of lamB
		- mutants crossed with deletions in lamB all stay Dex-
			- except if the deletion doesn't get to lamB, only in malK
				- then it can complement
- ((68f82117-6e62-4512-9632-163f781c21a3))
	- Since you don't have functional lamB (Dex- phenotype), you're probably also \lambda\R -> no functional lambda receptor
	- lamB is both the maltodextrin transporter and the lambda receptor
	- They're looking for MalR \lambda\R?
	- 2068 and 2069 don't have lacZ fusion anymore, but they do have the lamB mutations
		- 68 does not revert -> deletion
		- 69 does revert -> point mutation; revertant becomes \lambda\S
	- recombination happens on malK
	- loss of the prophage gets you Mal+ \lambda\R (figure 1 G)
- mutants are in the cytoplasm
- ((68f824fb-179e-4105-b3b5-42251a5877e7))
	- why is the gene fusion needed for isolation of these mutants?
		- I guess there's not really anything to screen for?
		- \lambda
-