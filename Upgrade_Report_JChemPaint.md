# JChemPaint
Link to github issue trackter: https://github.com/cdk/nwo-openscience-2024/issues/11
 
## JChemPaint
    • source code: https://github.com/JChemPaint 
    • JChemPaint version is using CDK 2.0 but is upgraded to CDK 2.10+.
    • what website to link to / how to acknowledge the previous source: https://jchempaint.github.io or https://github.com/JChemPaint/jchempaint/wiki#literature--citations
    
## Code analysis 
    • JChemPaint uses Maven model version 4.0.0 (prerequisites 3.0.0).
    • JChemPaint snapshot 3.4, java 8 syntax.
    • to help find the maven modules that are dependencies:
        ○ org.openscience.cdk (2.10): 
            § compile: cdk-interfaces, cdk-data, ,cdk-core , cdk-atomtype, cdk-io, cdk-ioformats, cdk-ctab, cdk-isomorphism, cdk-formula, cdk-render, cdk-renderbasic, cdk-renderextra, cdk-standard, cdk-smarts, cdk-smiles, cdk-sdg, cdk-extra, cdk-legacy, cdk-reaction, cdk-charges, cdk-qsar, cdk-libiocml, cdk-valencycheck, cdk-signature, cdk-dict, cdk-inchi.
            § test: cdk-test

    • what functionality is being used: see list above.
        ○ JChemPaint is a Chemical 2D structure editor application/applet based on the Chemistry Development Kit. 
    • record larger dependency eco-system (e.g. which tools depend on this tool)
        ○ None
    • how the code is being compile and executed
        ○ mvn clean install
        ○ Runnen JChemPaint: java -jar ./app-jar/target/JChemPaint.jar 
    • how the code is tested
 
## Upgrading tools
    • what CDK API change affected the upgrade to 2.10. 
        ○ None.
    • what testing results before and after the upgrade. 
        ○ None.
    • who was involved? 
        ○ John Mayfield & Egon Willighagen & RvdPloeg
 
## Reporting results
    • where were the results announced? 
    • how was the upgrade received/ used? 
        ○ cdk-2.10 is incorporated into the software.
