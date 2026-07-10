alias:: [[Third Rotation/Deepika Project]]

- Reading
  collapsed:: true
	- [[Lef1 expression in fibroblasts maintains developmental potential in adult skin to regenerate wounds]]
	- [[Single‐cell transcriptomic analysis of small and large wounds reveals the distinct spatial organization of regenerative fibroblasts]]
	- [[Distinct Regulatory Programs Control the Latent Regenerative Potential of Dermal Fibroblasts during Wound Healing]]
	- [[Epithelial-Mesenchymal Micro-niches Govern Stem Cell Lineage Choices]]
	- [[Assaying proliferation and differentiation capacity of stem cells using disaggregated adult mouse epidermis]]
		- protocol for Phan paper (Lef1)
-
- Imaging
	- [[Jul 7th, 2026]] mKate2 first try
	  id:: 6a51404c-8f21-4ef0-ac8e-a03ab8c36b2d
	  collapsed:: true
		- Mouse:
			- Genotype: mKate2 homo
			- DOB: 4/24/2026
			- Cage number: 200949
			- Notes
				- intradermal injection 1mg optoEGFR LNP into each ear
		- Goals:
			- Try fluorescent light stimulation
			- Use mKate2 for the first time
		- Time course:
			- Nair and intradermal injection was done yesterday
			- Imaging day
				- Anesthesia Parameters
					- 150 uL ketamine 2:30
					- isofluorane
				- Imaging Parameters
					- copied from Kai mKate2 lif file
					- 1200 laser, 20 - 30% laser power to begin
						- Bumped laser power up to 25 - 35% after bleaching
					- 2x2 region, 4um \Delta\z
					- min time interval 3min45 seconds, \Delta\t=4min
				- Blue light stimulation
					- 30 minutes movie no stim
					- 30 minutes continuous stim with fluorescent bulb
						- 10% power
					- image, 5 minutes stim repeat 8 times
		- Notes
			- Bleaching evident after 30 minutes fluorescent exposure
			- Unclear if cells moved, need to do more analysis for that
			- Tried to keep curtain closed during stimulation but this wasn't 100% successful
				- Chunyan had to use the iso induction chamber so it was open for some time
				- Shouldn't be a big deal
	- [[Apr 29th, 2026]] Imaging Back skin on the 2 photon
	  collapsed:: true
		- mTmG / Macgreen 12wk old
		- shoulder was tough
			- Lots of movement from both breathing and heartbeat
			- but this is a better place to image from flatness and tissue thickness perspectives
				- Way thinner so it's easier to get good data
			- Mouse also started to wake up so that was not ideal
		- flank was better in some ways but worse in others
			- Less movement (although definitely still some)
			- Squish as much as you want
		- Mouse died
			- probably because it got wet and then body temp got too low
		- Made some movies for Deepika to show in lab meeting
-
- Sorts
	- Next sort try with the mKate2 mouse from ((6a51404c-8f21-4ef0-ac8e-a03ab8c36b2d))
		- I'm curious what the cell recovery will look like in the ear
		- Flow booked for 11am [[Jul 14th, 2026]]
-
- Current main task
	- Full thickness ear wounds testing on [[Jul 13th, 2026]]
	- Meeting with Jared and Danelle soon to actually do the single cell experiment
	- Done
	  collapsed:: true
		- See ((69f3bc88-138d-4616-b1e3-9cb813736006))
		- Read protocols of these single cell papers and other papers from Elaine Fuchs' lab and find some common threads to try this soon (next week?)
			- Starting with adult skins that don't mean much / not useful
- To dos
	- TODO Get the flow data from the Toettcher sorter
	- DONE Get a list / suggestions for cell strainers
	- DONE Re-read epidermis dissociation protocols because that didn't work very well
	  collapsed:: true
		- Do I need to get a different reagent? Trypsin w/o EDTA?
		- Better mincing?
	- DONE Write notes from talking to Deepika here so I have them for easier reference
- Questions
- Meeting Notes
	- [[Apr 30th, 2026]] Chat with Deepika
	  id:: 69f3bc88-138d-4616-b1e3-9cb813736006
	  collapsed:: true
		- 2 photon was a big hit in the Devenport lab (not surprising, it's super cool)
			- Danelle thinks that the movement is not tooooo bad
				- We can compensate for it because it's periodic
				- And the theoretical optoEGFR driven migration would still be visible even with that
		- Decided to not try for opto in the single cell
			- We're not going to be able to capture cells in a time frame that could be influenced by optoEGFR
				- too sensitive, and too fast
			- Low chance of getting really good data
			- Alternative is a certainly better control
				- This is the way
				- Not worth the risk
		- Next steps
			- Try ear intradermal injections and image back skin for a bit longer [[May 7th, 2026]]
				- 12wk mTmG mice needed for this (how many?)
					- Claimed two in 195633
					- Do I want different mice if we're doing Cre LNP intradermal injections?
			- Use [[Jared Toettcher]] sorter
			  :LOGBOOK:
			  CLOCK: [2026-04-30 Thu 16:50:04]--[2026-04-30 Thu 16:50:04] =>  00:00:00
			  :END:
				- Tentatively [[May 8th, 2026]]
				- This one is gentler and we don't have to pay for it which is nice
				- 4 days post LNP transduction - hopefully we have more green cells
				- Use scraping protocol
					- ((69f3bec5-9697-4897-80a7-0a71023223d5))
		- TODO Regate flow data to see if dead cells have enrichment of GFP+
			- Use lab flowjo for this, or computers in the flow core
			- Are the LNP transduced cells more fragile? Are they just dying during the process of sorting?
		- TODO Talk to Kai about some stuff [[Kai Meetings]]
			- Thoughts about how much movement there was in the back skin movies
				- Show the movie
			- How to use the fluorescent beads in an intradermal injection
				- Use Evan's blue instead
				  background-color:: yellow
					- easy to use
				- maybe dextran? 70kd rhodamine dextran
			- Learn how to do the scraping dissociation protocol
			  id:: 69f3bec5-9697-4897-80a7-0a71023223d5
		- TODO Talk to Emily about going off protocol
			- Thoughts abouts using the LNPs
				- This is tricky because if we want to wait 4 days to image they have to go back to the colony
			- I did not do this and then she went on vacation but it's probably fiiinneeeeee
				-
	- [[Feb 4th, 2026]] Quick chat with Deepika re what does the rotation look like
	  collapsed:: true
		- End goal of project is delivering optoEGFR to a wounded mouse skin and using blue light stimulation to try to heal wounds faster
		- There is a lot of steps before this though
			- Delivery
				- Lipid nanoparticles were chosen as the delivery vehicle because they do localized and transient expression
					- Does not extend very far from injection site so slightly further away cells don't get uptake of vector
					- no genome integration like in a virus, you don't want this to stay around
				- Intradermal injection
				- Payload is variable
					- Cre is very helpful on an mTmG background so that you can clearly see which cells have been transduced (membrane green)
					- optoEGFR
					- other synRTKs
			- Characterization
				- Dosage
				- Extent of delivery
				- What's the effect of the delivery on nearby cells that don't get it? Inflammatory? Immunogenic?
			- Wounding
				- Doing the wound experiment is apparently a lot of work which I don't quite understand coming from Kai's lab
				- I think a good chunk of that is IACUC stuff
				- dermis is hydrophobic so it doesn't really like taking LNPs from the wound
					- broadly much worse uptake in the wounded condition
		- What am I going to be doing in my rotation?
			- Adult skin single cell dissociation
			- This has not been done in the lab before, so I gotta find protocols for this and optimize / figure out one that works well
			- Targeting experiment that looks at potential gene expression differences in an unwounded skin with control and vector delivery (Cre)
				- no flow because we want to look at all cells, but we'll be able to computationally pull out the Cre ones + mT vs mG
	- [[Flow Training]]
	-