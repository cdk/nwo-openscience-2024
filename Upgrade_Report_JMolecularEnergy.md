# JMolecularEnergy
Link to github issue trackter:  https://github.com/cdk/nwo-openscience-2024/issues/32
 
## JMolecularEnergy
	•	source code:  https://github.com/RamiManaf/JMolecularEnergy
	•	JMolecularEnergy version 1.0.1-SNAPSHOT was using CDK 2.8 and is now applying CDK 2.10.
	•	what website to link to / how to acknowledge the previous source: https://ramimanaf.github.io/JMolecularEnergy/
 
## Code analysis
	•	JMolecularEnergy uses Java code synthax 1.8.
	•	to help find the maven modules that are dependencies:
		◦	org.openscience.cdk:
			•	compile: cdk-core, cdk-interfaces, cdk-standard, cdk-charges, cdk-ctab, cdk-reaction, cdk-dict, cdk-valencycheck, cdk-atomtype, cdk-isomorphism, cdk-smarts, cdk-ioformats.
			•	test:  cdk-io, cdk-data
		◦	org.hamcrest:
			•	test: hamcrest-core
		◦	javax.vecmath:
			•	compile: vecmath
	•	what functionality is being used: see list above.
		◦	JMolecularEnergy is a Java library for calculating force fields, molecular dynamics, and QSAR.
	•	record larger dependency eco-system (e.g. which tools depend on this tool)
		◦	none
	•	how the code is being compile and executed
		◦	JMolecularEnergy is a library with a public API: to compile use "mvn clean install"
	•	how the code is tested
		◦	"mvn test"
 
## Upgrading tools
	•	what CDK API change affected the upgrade to 2.9. No API changes for JMolecularEnergy.
	•	what testing results before and after the upgrade.
		◦	No failures or errors were reported before or after the upgrade.
	•	who was involved?
		◦	RvdPloeg

## Reporting results
    • where were the results announced? 
    • how was the upgrade received/ used? 
        ◦	See github.