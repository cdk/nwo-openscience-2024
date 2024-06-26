# SMARTCyp

* https://github.com/cdk/nwo-openscience-2024/issues/22

## Source code
* source code: http://smartcyp2.sund.ku.dk/download.php
* SMARTCyp 2.4.2 is using CDK 1.4.8
* what website to link to / how to acknowledge the previous source --> to be clarified

## Code analysis
* which Java packages are being used
* to help find the maven modules that are dependencies
* what functionality is being used
* record larger dependency eco-system (e.g. which tools depend on this tool)
  * being reused in Squonk, Bioclipse, VHP4Safety
* how the code is being compile and executed
  * only `.java`files were in the source drop
  * a Maven build set up was written from scratch
* how to the code is tested
  * `java -jar target/smartcyp.jar -png -smiles "CC(=O)Nc1ccc(O)cc1"` (added to a new `README`)

## Upgrading tools
* CDK API change affected the upgrade
  * `IMolecule` to `IAtomContainer`: https://github.com/cdk/smartcyp/commit/50e48dbe13e33f73300e9bf8876a80ae7c52ee42
  *  `IChemObjectBuilder`: https://github.com/cdk/smartcyp/commit/4573c0dbf00ef2866f9a01fc9bee5fe0a285572c
* what testing results before and after the upgrade
  * who was involved?

## Reporting results
* where were the results announced?
  * https://github.com/christinadebruynkops/GLORYx/issues/5
  * https://chem-bla-ics.linkedchemistry.info/2024/04/07/cdk2024.html
* how was the upgrade received/ used?

  
