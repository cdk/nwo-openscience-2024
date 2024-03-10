# Software Management Plan

Modelled after the eScience Center [2023 template](https://www.esciencecenter.nl/wp-content/uploads/2023/01/SS-2023-3.-Template-Software-Management-Plan-2023.docx).

This software management plan covers two aspects of this project. First, it will cover the Chemistry Development Kit (CDK) itself, but with also cover the
management of software patches developed in this project. The tools this project will upgrade are not under our direct control, but each is open source, and
for several we are in direct contact with the developers.

## 1. Please provide a brief description of your software, stating its purpose and intended user community.

### The Chemistry Development Kit

The [Chemistry Development Kit](https://cdk.github.io/) is an open source, Java cheminformatics library that has been developed for already 25 years
and has been used in [numerous research papers](https://openalex.org/works?page=1&filter=default.search%3A%22chemistry%20development%20kit%22&sort=relevance_score%3Adesc&group_by=publication_year,open_access.is_oa,authorships.institutions.lineage,type).
The purpose is to enable the development of research software to answer chemical and biochemical questions.

### Research software for which patches will be developed

The grant will also aim to update various software that uses the CDK, as described in the proposal:

* [KNIME (CDK Nodes)](https://github.com/cdk/nodes4knime)
* [rcdk](https://github.com/CDK-R/cdkr)
* [AMBIT](https://sourceforge.net/projects/ambit/)
* [JChemPaint](https://github.com/JChemPaint/jchempaint)
* [ToxTree](https://sourceforge.net/p/toxtree/)
* [DECIMER](https://github.com/Kohulan/DECIMER-Java)
* [ChemViz (Cytoscape)](https://github.com/RBVI/chemViz2)
* [OpenChrom](https://github.com/Openchrom/openchrom)
* [PaDEL-descriptor](https://yapcwsoft.com/dd/padeldescriptor/)

## 2. Which version control system will you use to manage your source code? 

### The Chemistry Development Kit

Git and hosted on [GitHub](https://github.com/cdk/cdk) and [SourceForge](https://sourceforge.net/projects/cdk/).

### Research software for which patches will be developed

* [KNIME (CDK Nodes)](https://github.com/cdk/nodes4knime): Git
* [rcdk](https://github.com/CDK-R/cdkr): Git
* [AMBIT](https://sourceforge.net/projects/ambit/): Git
* [JChemPaint](https://github.com/JChemPaint/jchempaint): Git
* [ToxTree](https://sourceforge.net/p/toxtree/): Git
* [DECIMER](https://github.com/Kohulan/DECIMER-Java): Git
* [ChemViz (Cytoscape)](https://github.com/RBVI/chemViz2): Git
* [OpenChrom](https://github.com/Openchrom/openchrom): Git
* [PaDEL-descriptor](https://yapcwsoft.com/dd/padeldescriptor/)

## 3. How will you make your software publicly available? Please provide links to the software if this is already the case.

### The Chemistry Development Kit

The CDK is being released via [GitHub](https://github.com/cdk/cdk/releases), [Zenodo](https://zenodo.org/doi/10.5281/zenodo.592588),
[Maven Central](https://search.maven.org/search?q=g:org.openscience.cdk), and Linux distributions like [Debian GNU/Linux](http://packages.debian.org/libcdk-java) and [Ubuntu](https://packages.ubuntu.com/libcdk-java).

### Research software for which patches will be developed

For all the git repositories, forks will be created where patches will be developed in git branches.
Git branches will be archived at the end of the project, as patch files on Zenodo.

## 4. What licence will your software have?

### The Chemistry Development Kit

All patches for the CDK will use the same license as the CDK: [GNU Lesser General Public License v2.1](https://github.com/cdk/cdk/blob/main/LICENSE.txt) 

### Research software for which patches will be developed

All patches for the updated software will be released under the same license as those projects:

* KNIME (CDK Nodes): LGPL
* rcdk: LGPL
* AMBIT: LGPL
* JChemPaint: LGPL
* ToxTree: GPL v2
* DECIMER: MIT
* ChemViz (Cytoscape): LGPL
* OpenChrom: EPL 1.0
* PaDEL-descriptor: public domain

## 5. What measures will be taken during the project to ensure the long-term sustainability of the software developed in the project? (max. 300 words)

### The Chemistry Development Kit

Long-term sustainability is ensured by a wide adoption and open license, and based on a code base that has been used
for more than 25 years, sustainability is evident. The CDK is developed by an international community of well over 100 authors,
with support commonly coming from use in research projects, and involvement of multiple smaller and larger companies using
the cheminformatics platform.

### Research software for which patches will be developed

By updating the third-party software, we contribute to relevance of the software. The upgrade to a recent
CDK version will make the software more accurate and faster. These software have been chosen based on their
use, and many have been sustained for many years already. By updating them, we intend to keep them relevant
for many years more.

## 6. What measures will be taken to support the software after completion of the project? (max. 300 words)

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...


## 7. What resources are needed to ensure the long-term usability and availability of the software, and how will these resources be funded or obtained? (max. 300 words)

Some examples include:
    • Storage or compute infrastructure to host the software.
    • RSEs to maintain the software and support the community that uses it.
    • A user support desk.

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 8. Are there other measures that will be taken to promote the software’s longevity? (max. 300 words)
Some examples include:
    • Additional project proposals which will help to further develop the software.
    • The software is integrated into teaching in a course on the Bachelor or Master level.
    • Outreach though mainstream media such as newspaper articles, blogs. YouTube videos, tweets, etc.

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 9. How will your software be documented? Please provide a link to the documentation, if available.
Software will be documented for different users (user documentation, developer documentation). If you have any (additional) plans on how your software will be documented (e.g. creating tutorials, incorporating it in teaching, etc.) please specify.

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 10. How will your software document its installation requirements? Please provide a link to the installation documentation, if available.
Explain system requirements (e.g. dependencies) for deploying the software and instructions for installation and testing.

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 11. How will you enable citation of your software by users? Please provide a link to software citation data and/or DOI if available.
The eScience Center uses the Citation File Format (CFF) to provide citation metadata for software, and Zenodo to provide DOIs for software releases. Please specify if there are reasons to use a different approach. 

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 12. How will your software be tested? Please provide a link to automated testing results, if available.
Incorporate tests to ensure your software works and continues to work as intended. Different types of testing (unit, functional, integration, linting, typing, regression, etc.) could be used. Coverage tools should also be used to assess the extent of the tested code.

### The Chemistry Development Kit

...

### Research software for which patches will be developed

to be written ...

## 13. How will your software be packaged and distributed? Please provide a link to available packaging information (e.g. entry in a packaging registry, if available).
Use appropriate package managers to allow users to install/deploy your software with ease. Examples include PyPI, CRAN, NPM, Maven, Crates, conda, etc.

### The Chemistry Development Kit

The CDK library itself is distributed via various channels, including [GitHub](https://github.com/cdk/cdk/releases), [Zenodo](https://zenodo.org/doi/10.5281/zenodo.592588),
[Maven Central](https://search.maven.org/search?q=g:org.openscience.cdk), and Linux distributions like [Debian GNU/Linux](http://packages.debian.org/libcdk-java) and [Ubuntu](https://packages.ubuntu.com/libcdk-java).

But it is also reused in many other tools, like the research software which we will update to the latest CDK (see [Work Package 2](https://github.com/cdk/nwo-openscience-2024/issues?q=is%3Aissue+is%3Aopen+label%3AWP2)).

### Research software for which patches will be developed

Because the release management of the other tools we will develop patches for, we do not necessarily have control over this. Fortunately,
most of those release managers are active member of the CDK community.

The patches will be shared as git branches with matching pull requests. We will explore an appropriate way to archive those, with as default backup a dump with `git am` (if not merged in before
the end of the grant, we will release those on Zenodo).

# Signature

The authors of this document will ensure that this Software Management Plan is carried out as specified above.


Name: Egon Willighagen

Affiliation: Maastricht University

Date:			

Signature:		
