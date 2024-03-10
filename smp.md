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

The CDK is currently maintained by an international team of developers consisting of Egon Willighagen
(applicant) and John Mayfield (UK).

### Research software for which patches will be developed

No special measure will be taken. The software has been selected because it is actively used.

## 7. What resources are needed to ensure the long-term usability and availability of the software, and how will these resources be funded or obtained? (max. 300 words)

### The Chemistry Development Kit

Because of a open science nature, the adoption of continuous integration, peer review, and coding
standards, the CDK project has been operating on minimal maintenance cost. Development has
been funding by research projects.

### Research software for which patches will be developed

Software has been selected because of active use. Continued, yearly funding to support upgrading software using
the CDK is most welcome, but is also driven by users of these softwares. Various tools are used by SMEs and
even developed by SMEs or research institutes, like AMBIT, ToxTree, PaDEL, and OpenChrom. Other software is not.

## 8. Are there other measures that will be taken to promote the software’s longevity? (max. 300 words)

During the project will we disseminate our efforts via GitHub: https://github.com/cdk/nwo-openscience-2024/issues
Releases of updated software will be announced via the social media account of the CDK.
General nodes on how to update software in case of API changes will be added to (at least) the
[Groovy cheminformatics with the CDK](https://egonw.github.io/cdkbook/migration.html) book.

The final hackathon will invite users of the CDK, the CDK-upgraded software listed above, as
well as users of other CDK-using software.

## 9. How will your software be documented? Please provide a link to the documentation, if available.

### The Chemistry Development Kit

The CDK has strict requirements on documentation and APIs are described with JavaDoc.

### Research software for which patches will be developed

No functional changes will be made to this software and we expect no additional documentation will be needed.

## 10. How will your software document its installation requirements? Please provide a link to the installation documentation, if available.

### The Chemistry Development Kit

The existing installation requirements are not expected to change.
Current instructions are found at https://github.com/cdk/cdk/blob/main/README.md

### Research software for which patches will be developed

When needed, installation instructions will be updated. But whenever possible, the updates to the software to the
latest CDK will be invisible to the user and not require changes in the installation instructions. Of course,
CDK 2.9 will be needed, instead of the currently older CDK version.

During the project we will collect instructions when missing in our project issue
at https://github.com/cdk/nwo-openscience-2024/issues and when appropriate, additional patches
for the updated software will be written.

## 11. How will you enable citation of your software by users? Please provide a link to software citation data and/or DOI if available.

### The Chemistry Development Kit

A pull request for the missing `CITATION.cff` for the CDK has been submitted: https://github.com/cdk/cdk/pull/1055

The information was already given in the `README.md` and the three main CDK papers have been cited 192 times since
2023, according to Google Scholar.

### Research software for which patches will be developed

We will create `CITATION.cff` for all Git repositories for which we will develop patches. This will not
provide information on how to cite the patches. We will discuss with the maintainers how the patches will
be acknowledged.

## 12. How will your software be tested? Please provide a link to automated testing results, if available.

### The Chemistry Development Kit

The CDK has a growing test suite that is run for every pull request, along with a human peer review process
performed by a senior CDK developer. Additional testing for coverage and code quality is done with sonarcloud
and results are available from https://sonarcloud.io/project/overview?id=cdk

### Research software for which patches will be developed

* KNIME (CDK Nodes): [testing protocol](https://docs.knime.com/latest/analytics_platform_new_node_quickstart_guide/index.html#_introduction)
* rcdk: 
* AMBIT
* JChemPaint
* ToxTree
* DECIMER
* ChemViz (Cytoscape)
* OpenChrom
* PaDEL-descriptor


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
