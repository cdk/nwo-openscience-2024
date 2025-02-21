# SMARTCyp
Link to github issue trackter:  https://github.com/cdk/nwo-openscience-2024/issues/22
 
## SMARTCyp
    • source code: http://smartcyp2.sund.ku.dk/download.php
    • SMARTCyp version 2.4.2 is using CDK 2 is upgraded to CDK 2.9.
    • what website to link to / how to acknowledge the previous source:  or if applicable:

    SMARTCyp 2.4.2
    P. Rydberg, D. E. Gloriam, J. Zaretzki, C. Breneman and L. Olsen, ACS Med. Chem. Lett., 2010, 1, 96-100 , P. Rydberg, D. E. Gloriam and L. Olsen, Bioinformatics, 2010, 26, 2988-2989, P. Rydberg and L. Olsen, ACS Med. Chem. Lett., 2012, 3, 69-73, P. Rydberg and L. Olsen, ChemMedChem, 2012, 7, 1202-1209, P. Rydberg et al., Angew. Chem, Int. Ed. 2013, 52, 993-997 and P. Rydberg et al., Mol. Pharmaceutics 2013, 10, 1216-1223.

    SMARTCyp 3.0
    Lars Olsen, Marco Montefiori, Khanhvi Phuc Tran, Flemming Steen Jørgensen, SMARTCyp 3.0: enhanced cytochrome P450 site-of-metabolism prediction server, Bioinformatics, Volume 35, Issue 17, September 2019, Pages 3174–3175,  https://doi.org/10.1093/bioinformatics/btz037
     
## Code analysis 
    • SmartCyp 2.4.2 uses
    • to help find the maven modules that are dependencies:
        ○ org.openscience.cdk (2.9):
        ○ org.openscience.cdk (2.2):
            § Compile: 
                □ cdk-data: cdk-interfaces, cdk-core.
                □ cdk-renderbasic (cdk-standard, cdk-render), cdk-renderawt, cdk-renderextra
                □ cdk-extra: cdk-io, cdk-atomtype, cdk-ctab:jar, cdk-ioformats, cdk-valencycheck, cdk-formula, cdk-dict, cdk-smiles.
                □ cdk-sdg.
                □ cdk-smarts: cdk-isomorphism.
                □ cdk-legacy: cdk-signature, cdk-qsar, cdk-charges, cdk-reaction.
    
    • what functionality is being used: see list above.
        ○ OpenChrom is a program that can read and analyse chromatography and mass spectrometry data files. 
    • record larger dependency eco-system (e.g. which tools depend on this tool)
        ○ OpenChrom
    • how the code is being compile and executed
        ○ See the link to developers information on https://github.com/OpenChrom/openchrom/wiki/Quickstart
    • how the code is tested
 
## Upgrading tools
    • what CDK API change affected the upgrade to 2.10. 
        ○ None.
    • what testing results before and after the upgrade. 
        ○ None.
    • who was involved? 
        ○ Matthias Mailänder & RvdPloeg
 
## Reporting results
    • where were the results announced? 
    • how was the upgrade received/ used? 
        ○ cdk-2.10 is incorperated in the software.