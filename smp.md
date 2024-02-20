# Software Management Plan

Modelled after the eScience Center [2023 template](https://www.esciencecenter.nl/wp-content/uploads/2023/01/SS-2023-3.-Template-Software-Management-Plan-2023.docx).

## 1. Please provide a brief description of your software, stating its purpose and intended user community.

The [Chemistry Development Kit](https://cdk.github.io/) is an open source, Java cheminformatics library that has been developed for already 25 years
and has been used in [numerous research papers](https://openalex.org/works?page=1&filter=default.search%3A%22chemistry%20development%20kit%22&sort=relevance_score%3Adesc&group_by=publication_year,open_access.is_oa,authorships.institutions.lineage,type).
The purpose is to enable the development of research software to answer chemical and biochemical questions.

## 2. Which version control system will you use to manage your source code? 
Git and hosted on [GitHub](https://github.com/cdk/cdk) and [SourceForge](https://sourceforge.net/projects/cdk/).

## 3. How will you make your software publicly available? Please provide links to the software if this is already the case.

The CDK is being released via [GitHub](https://github.com/cdk/cdk/releases), [Zenodo](https://zenodo.org/doi/10.5281/zenodo.592588),
[Maven Central](https://search.maven.org/search?q=g:org.openscience.cdk), and Linux distributions like [Debian GNU/Linux](http://packages.debian.org/libcdk-java).

## 4. What licence will your software have?
[GNU Lesser General Public License v2.1](https://github.com/cdk/cdk/blob/main/LICENSE.txt) 

## 5. What measures will be taken during the project to ensure the long-term sustainability of the software developed in the project? (max. 300 words)
Some examples include:
    • A researcher or RSE from a research institute is allocated to the project to co-develop the software during the project and help maintain it afterwards.
    • A community will co-develop the software and help maintain it afterwards.
    • Organizing workshops and hands-on user training to create or extend a community around the software.
    • The software will be developed as part of an overarching software suite used in other (research) projects.
    • A commercial partner interested in exploiting the software is included as co-applicant on the basis of a concrete in-cash or in-kind investment. 	

## 6. What measures will be taken to support the software after completion of the project? (max. 300 words)
Some examples include:
    • The software is hosted by an institute and a user support desk is made available for a certain period.
    • The software is integrated into a research infrastructure based on a large community.
    • A commercial partner or spin-off will continue the support and development of the software.

## 7. What resources are needed to ensure the long-term usability and availability of the software, and how will these resources be funded or obtained? (max. 300 words)
Some examples include:
    • Storage or compute infrastructure to host the software.
    • RSEs to maintain the software and support the community that uses it.
    • A user support desk.

## 8. Are there other measures that will be taken to promote the software’s longevity? (max. 300 words)
Some examples include:
    • Additional project proposals which will help to further develop the software.
    • The software is integrated into teaching in a course on the Bachelor or Master level.
    • Outreach though mainstream media such as newspaper articles, blogs. YouTube videos, tweets, etc.

## 9. How will your software be documented? Please provide a link to the documentation, if available.
Software will be documented for different users (user documentation, developer documentation). If you have any (additional) plans on how your software will be documented (e.g. creating tutorials, incorporating it in teaching, etc.) please specify.

## 10. How will your software document its installation requirements? Please provide a link to the installation documentation, if available.
Explain system requirements (e.g. dependencies) for deploying the software and instructions for installation and testing.

## 11. How will you enable citation of your software by users? Please provide a link to software citation data and/or DOI if available.
The eScience Center uses the Citation File Format (CFF) to provide citation metadata for software, and Zenodo to provide DOIs for software releases. Please specify if there are reasons to use a different approach. 

## 12. How will your software be tested? Please provide a link to automated testing results, if available.
Incorporate tests to ensure your software works and continues to work as intended. Different types of testing (unit, functional, integration, linting, typing, regression, etc.) could be used. Coverage tools should also be used to assess the extent of the tested code.

## 13. How will your software be packaged and distributed? Please provide a link to available packaging information (e.g. entry in a packaging registry, if available).
Use appropriate package managers to allow users to install/deploy your software with ease. Examples include PyPI, CRAN, NPM, Maven, Crates, conda, etc.


Signature

The authors of this document will ensure that this Software Management Plan is carried out as specified above.


Name:			……

Affiliation:		……

Date:			……

Signature:		……

(please copy this section if needed)
