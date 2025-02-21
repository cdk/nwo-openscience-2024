# Chemviz2
Link to github issue trackter:  https://github.com/cdk/nwo-openscience-2024/issues/18

## Chemviz2
    • source code:  https://github.com/RBVI/chemViz2
    • Chemviz2 version bundle 2.0.3 is using CDK 2.9
    • what website to link to / how to acknowledge the previous source: https://www.cgl.ucsf.edu/cytoscape/chemViz2/index.shtml
    
## Code analysis 
    • Chemviz2 is used by Cytoscape API version3.10.0.
    • to help find the maven modules that are dependencies:
        ○ org.cytoscape (3.10.0)
            § provided: model-api, event-api, group-api, application-api, swing-application, work-swing, property, session-api, vizmap, core-task, io, filter, viewmodel, presentation, work, service, swing-util, util, command-executor
        ○ org.openscience.cdk (2.9)
            § compile: cdk-core, cdk-interfaces, cdk-smiles, cdk-ioformats, cdk-standard, cdk-valencycheck, cdk-smarts, cdk-ctab, cdk-charges, cdk-isomorphism, cdk-inchi, cdk-qsar, cdk-qsarmolecular, cdk-atomtype, cdk-reaction, cdk-formula, cdk-dict, cdk-fragment, cdk-hash, cdk-render, cdk-renderbasic, cdk-renderextra, cdk-renderawt, cdk-builder3d, cdk-data, cdk-forcefield, cdk-sdg, cdk-fingerprint, cdk-silent, cdk-legacy, cdk-signature, cdk-io, cdk-extra.
        ○ org.hamcrest (1.1)
            § test: hamcrest-core
        ○ xom (1.2.5)
        ○ xerces (2.8.0)
            § xercesImpl
        ○ org.freehep (2.4)
            § freehep-graphicsio-svg, freehep-graphics2d, freehep-io, freehep-graphicsio-tests, freehep-graphicsbase, freehep-graphicsio-pdf
        ○ javax  
            § compile: vecmath (1.5.2.)
            § provided: javahelp (2.0.05), jaxb-api (2.3.0)
        ○ dan2097 (1.2.1)
            § compile: jna-inchi-core (1.2), jna-inchi-api, jna-inchi-smiles, jna-inchi-linux-x86-64, jna-inchi-darwin-aarch64, jna-inchi-darwin-x86-64, jna-inchi-win32-x86-64.
    • what functionality is being used: see list above.
        ○ Chemviz2 is a Cytoscape app that extends the capabilities of Cytoscape into the domain of cheminformatics. The extention makes it possible to calculate chemical characterstics for a compound and make networks.
    • record larger dependency eco-system (e.g. which tools depend on this tool)
        ○ Cytoscape
    • how the code is being compile and executed
        ○ ChemViz2 capabilities can be added to Cytoscape by adding ChemViz2 as an extension. To do so, the following steps need to be performed:
            i. Start Cytoscape.
            ii. In the menu at the top, click on ‘Apps’ and select ‘Install App from File’ in the App Store.
            iii. Go to the repository folder of ChemViz2. If no ChemViz2 repository folder is on your computer, go to the GitHub page and create a repository (https://github.com/RBVI/chemViz2/tree/master). To create a repository, first download the ZIP file by clicking on ‘Download ZIP’, which becomes visible after clicking on the ‘Green Button’ with ‘Code’ in it. After downloading, unzip the file.
            iv. Select the chemViz2-2.0.3.jar file, which can be found in the 'target' folder within the ChemViz2 folder, and click on ‘Open’.
            v. If no target folder is present perform the following steps: open a terminal forexample in an IDE and go to the chemViz2 folder and type 'mvn clean install' no the folder should be present.
    • how the code is tested
        "mvn test"

## Upgrading tools
    • what CDK API change affected the upgrade to 2.9. ChemViz2 (Cytoscape 3.9.0) used to work with CDK 2.7.1 with JNA InChI but is not replaced with the JNI library.
    • what testing results before and after the upgrade. 
        ○ Errors, 
    • who was involved? 
        ○ Scooter Morris

## Reporting results
    • where were the results announced? 
    • how was the upgrade received/ used? 
        ○ cdk-2.9 is used by chemviz which is een plugin for Cytoscape API version 3.10.0.
