RanDepict
Link to github issue trackter: https://github.com/cdk/nwo-openscience-2024/issues/33

RanDepict
	• source code: https://github.com/Steinbeck-Lab/RanDepict
	• RanDepict version 1.4.0 used 2.8 and is now using CDK 2.10
	• what website to link to / how to acknowledge the previous source: https://github.com/Steinbeck-Lab/RanDepict or use
	Brinkhaus, H.O., Rajan, K., Zielesny, A. et al. RanDepict: Random chemical structure depiction generator. J Cheminform 14, 31 (2022). https://doi.org/10.1186/s13321-022-00609-4
	
Code analysis 
	• RanDepict; run RanDepict python code in a conda enviroment.
	• RanDepict uses the cdk classes:
		○ org.openscience.cdk (2.10)
			§ .tools.manipulator.AtomContainerManipulator
			§ .smiles.SmilesGenerator"
			§ .smiles.SmilesParser
			§ .smiles.SmiFlavor
			§ .silent.SilentChemObjectBuilder
			§ .interfaces.IAtomContainer
			§ .depict.DepictionGenerator
			§ .renderer.SymbolVisibility
			§ .geometry.cip.CIPTool
			§ .CDKConstants
			§ .depict.Abbreviations
			§ .geometry.GeometryTools
			§ .layout.StructureDiagramGenerator
	
	• what functionality is being used: see list above.
		○ This repository contains RanDepict, an easy-to-use utility to generate a big variety of chemical structure depictions (random depiction styles and image augmentations) based on RDKit, CDK, Indigo and PIKAChU.
	• record larger dependency eco-system (e.g. which tools depend on this tool)
		○ None
	• how the code is being compile and executed
		○ See https://github.com/Steinbeck-Lab/RanDepict:
			i. Installation: 
			$ git clone https://github.com/OBrink/RanDepict.git
			$ cd RanDepict 
			$ python -m pip install -U pip #Upgrade pip
			$ pip install .
			ii. Install from PyPI: $ pip install RanDepict
	• how the code is tested
		○ Run first: pip install -e ".[dev]" and second: tox -e py38

Upgrading tools
	• what CDK API change affected the upgrade to 2.10?
		○ n.a. 
	• what testing results before and after the upgrade. 
		○  1 error
	• who was involved? 
		○ Kohulan Rajan

Reporting results
	• where were the results announced? 
	• how was the upgrade received/ used? 
		○ See github
