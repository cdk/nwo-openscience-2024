# OpenChrom
Link to github issue trackter:  https://github.com/cdk/nwo-openscience-2024/issues/15
 
## OpenChrom
    • source code: https://github.com/OpenChrom
    • OpenChrom version is using CDK 2.9 but is upgraded to CDK 2.10.
    • what website to link to / how to acknowledge the previous source: https://openchrom.net or if applicable:
     OpenChrom: a cross-platform open source software for the mass spectrometric analysis of chromatographic data, Philip Wenig, Juergen Odermatt, BMC Bioinformatics; 2010, doi:10.1186/1471-2105-11-405
     
## Code analysis 
    • OpenChrom uses API version3.10.0.
    • to help find the maven modules that are dependencies:
        ○ org.openscience.cdk (2.10): 
            § compile: cdk-data, cdk-core, cdk-interfaces, cdk-render, cdk-renderbasic, cdk-standard, cdk-renderextra, cdk-extra, cdk-io, cdk-atomtype, cdk-ctab, cdk-ioformats, cdk-formula, cdk-dict, cdk-smiles, cdk-smarts, cdk-legacy, cdk-reaction, cdk-isomorphism, cdk-valencycheck, cdk-signature, cdk-charges, cdk-qsar:jar.
        ○ Javax (1.5.2:
            § compile: vecmath
        ○ gov.nist.math (1.0.3):
            § compile: jama
        ○ xom (1.3.9):
            § compile: xom
        ○ uk.ac.ebi.beam (1.3.8):
            § compile: beam-core, beam-func
        ○ com.github.gilleain.signatures (1.1):
            § compile: signatures
        ○ jgrapht (0.6.0):
            § jgrapht
    
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
        ○ cdk-2.10 is incorporated in the software.