- Adult skin
  collapsed:: true
	- Seems like there's different protocols for collecting dermis or epidermis
	  collapsed:: true
		- Need to look a bit closer at each paper to see what they're actually looking for in the single cell
		- Not entirely sure which compartment Deepika would be interested in looking at tbh
			- both
			- Sample list could be epidermis; dermis (mT - no Cre); dermis (mG - Cre transduction)
	- Paper methods
	  collapsed:: true
		- [[The pioneer factor SOX9 competes for epigenetic factors to switch stem cell fates]] Fuchs
			- the whole back skins were first dissected from the mouse. After **scraping off the fat tissues from the dermal side**, the tissues were incubated in **0.25% trypsin/ethylenediaminetetraacetic acid (EDTA) (Gibco) for 45–60 min at 37 °C**. After quenching the trypsin with cold FACS buffer (5% foetal bovine serum, 10 mM EDTA and 1 mM HEPES in PBS), the epidermal layer and HFs were scraped off the epidermal side of the skin. The tissues were mechanically separated and filtered through a 70 μm cell strainer (BD) into a single-cell suspension
			- Doesn't say if they do dermal side up or down
			- epidermis
		- [[Assaying proliferation and differentiation capacity of stem cells using disaggregated adult mouse epidermis]] Phan method
			- This one is quite detailed plus pics
			- Epidermis
			  collapsed:: true
				- Remove fat and muscle from dermis side
				- Float the tissue epidermal side up in 10 ml 0.25% trypsin w/o EDTA in a petri dish either overnight at 4 °C or for 2 h at 37 °C
				- Transfer the floating tissue to the inside of the lid of the petri dish epidermal side up
				- Scrape the epidermis off the dermis, discard dermis
				- mince and pipette to dissociate, 50um cell strainer
			- Embryonic dermis
			  collapsed:: true
				- They say that adult dermis is way worse at disaggregation
				  collapsed:: true
					- But this protocol was used for an adult skin paper so probably fine
				- Dispase-trypin solution (0.25% trypsin w/o EDTA + dispase 1:1 ratio) for 1h at 37C
				- Mince dermis in 0.25% collagenase/FAD+Ca, incubate for 1h at 37C
				- Pipette to dissociate
			- Yields
			  collapsed:: true
				- ((698a1bae-c6c3-47a6-98f0-65dc4a595591))
		- [[Hedgehog stimulates hair follicle neogenesis by creating inductive dermis during murine skin wound healing]] Lim
			- Skin wounds were collected ... and **incubated in 20 mM EDTA solution at 37 °C for 30 min** to separate dermis from epidermis. The separated dermis was incubated in **DMEM containing 10% FBS and 0.35% type I collagenase at 37 °C for 1 h**
			- dermis
		- [[Distinct Regulatory Programs Control the Latent Regenerative Potential of Dermal Fibroblasts during Wound Healing]] Abbasi
			- ((698a2145-6810-48bf-8a3c-61f5e0959dca))
			- 3-4 minutes is kinda crazy, and no mention of mechanical dissociation either
			  collapsed:: true
				- I guess they scrape with a scalpel but that's not very intense
			- I think this might be an aggregate protocol, not a single cell suspension. They don't have a clear protocol for the single cell
	- Protocol
		- Dissect trunk skin
		- Dispase to separate dermis and epidermis
			- 5mg/mL; 30 minutes; 37C in HBSS / PBS -/-
			- Notes / alternatives
				- Concentrations range from 1 - 5 mg/mL
				- Time is 30-120 minutes
				- 0.25% trypsin/EDTA can also be used; 1h; 37C
		- Epidermis
			- 0.25% Trypsin w/o EDTA; 1h; 37C
				- we only have trypsin w/ EDTA, hopefully that's fine too
			- mince in beginning, pipette at end for mechanical dissociation
			- 40 um cell strainer
			- Notes / alternatives
			  collapsed:: true
				-
		- Dermis
			- 0.35% collagenase; 1h; 37C in DMEM / F12
				- 3.5 mg/mL equivalent
			- mince in beginning, pipette at end for mechanical dissociation
			- 40 um cell strainer
			- Spin 400g x 10 min
			-
			- Notes / alternatives
			  collapsed:: true
				- Concentrations used are .2 - .35% collagenase
		- Spin (400g ), wash, count
		- spin, resuspend in FACS buffer
	- Trial 1 [[Feb 11th, 2026]]
		- |Sample|Blotter Paper|Dispase|Collagenase||
		  |--|--|--|--|--|
		  |Right Anterior (RA) | No paper |2.5 mg/mL ; 2 mL ; 1h|2.5 mg/mL ; 2mL; 1h||
		  |Right Posterior (RP) |No paper|5 mg/mL ; 2 mL ; 1h|2.5 mg/mL ; 2mL; 1h||
		  |Left Anterior (LA) |Paper|2.5 mg/mL ; 2 mL ; 1h|2.5 mg/mL ; 2mL; 1h||
		  |Left Posterior (LP) |No paper|5 mg/mL ; 2 mL ; 1h|2.5 mg/mL ; 2mL; 1h||
		- Dispase to separate dermis from epidermis
		- Collagenase digestion for dermis
		- Trypsin/EDTA digestion for epidermis
		- Outcomes
			- Dispase
				- Filter paper seems to work quite well, that one was the easiest to remove the dermis
				- 5 mg/mL is the right concentration
				- 2h at 37C seems to be good
					- no loss of cell viability after 2h, but better dissociation
				- Collect supernatant and spin
			- Collagenase
				- Better viability in media, still high even after o/n +4
			- Epidermis
				- 👎 no good
				- Did not properly mince it
				- Even after o/n +4 digestion in trypsin there were barely any cells dissociated
		- Other notes
			- Did not scrape hypodermis off of the dermis because I thought Deepika's dissection was good, but there was definitely fat in the wells
				- Should scrape next time
	- Trial 2 [[Feb 17th, 2026]]
		- I dissect skin
		- Things to try
			- Miltenyi epidermis protocol uses o/n +4 dispase, so lets try that
			- Really mince up the epidermis before starting trypsin digest
			- Scrape the fat off of the dermis gently before starting anything
				- This did not seem to work at all, not sure what we're doing differently
		- Doing in 12 well plates
		- Dispase
			- 5mg/mL in PBS -/- ; used same as last time (so ~1 week old solution, seemed to work totally fine)
			- 2h 37C on gyrating shaker, 7.5% CO2, filter paper
				- This worked very well!
			- o/n +4 on planar shaker, filter paper
			- Most of it was able to be simply peeled off in a big blob, very easy
			- Scrape rest with forceps + scalpel on lid of 60mm petri dish
		- Collagenase
			- 2.5 mg/mL; used same as last time (so ~1 week old solution)
			- 1h 37C on gyrating shaker, 7.5% CO2
			- Dermis
				- Collagenase in F media
				- Pelleted dispase solution and added that to the collagenase digest as well
			- Epidermis
				- Minced with double scalpel on lid of 60mm dish
					- This worked quite well, chopped into small pieces
				- Collagenase in HBSS (this isn't ideal for viability, but should still work to digest, and it's expensive so use up the solution)
				-
- Embryonic skin
	- Will be getting protocol from Mallarino lab
	- Rendl Lab has a series of papers that do embryonic dissociation
		- Helpfully, they all have slightly different protocols :eyeroll:
		- [[Dermal Condensate Niche Fate Specification Occurs Prior to Formation and Is Placode Progenitor Dependent]]
-
- Reagents and Equipment
	- [Mitenyi MACS Cell Strainers](https://www.miltenyibiotec.com/US-en/products/macs-smartstrainers.html#130-110-915)
		- these are recommended in the 10X sample prep guide and fit both 15 and 50 mL conicals which is nice
		- Get both 30 and 70 um sizes for dermis / epidermis
	- [Collagenase](https://www.sigmaaldrich.com/US/en/product/sigma/c0130)
- General resources that may be helpful
	- [Worthington tissue guide](https://www.worthington-biochem.com/tools-resources/tissue-dissociation-guide)
		- [specific skin one](https://www.worthington-biochem.com/tools-resources/tissue-tables/skin)
	- [10X sample prep guidelines](https://assets.10xgenomics.com/m/7122b03c55bc48ca/original/CG00053_Handbook_CellPreparation_SingleCellProtocols.pdf)
	- [MACS Epidermis dissociation guide](https://static.miltenyibiotec.com/asset/150655405641/document_bo8124fnnl24j2fpqgltr7881a?content-disposition=inline)
		- [Here's the product link](https://www.miltenyibiotec.com/US-en/products/epidermis-dissociation-kit-acf-mouse.html)
		- This is an established but proprietary protocol for dissociating adult mouse epidermis (6-10 week old female Bl/6)
		- They almost certainly do a dispase o/n +4 incubation (enzyme G)
		- And then a 2 enzyme very quick digestion of the epidermis
			- 100ul Enzyme P, 20 ul Enzyme A, for 20 minutes at 37C in Buffer S
			- A comes as a powder, P as a liquid
			- I think A might be collagenase? P is likely trypsin
	-