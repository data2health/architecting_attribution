# Budget
Don't edit this - the RPPR generator populates this section

# Research Design
There has been a fundamental shift that recognizes both the interdisciplinary, team-based approach to science as well as the more fine-grained characterization and contextualization of the hundreds and thousands of contributions of varying types and intensities that are necessary to move science forward. Unfortunately, little infrastructure exists to identify, aggregate, present, and (ultimately) assess the impact of these contributions. These significant problems are technical as well as social and require an approach that assimilates cultural and social aspects of these problems in an open and community-driven manner. Here we approach these issues from a variety of perspectives - technical and cultural. Ongoing efforts include the development of a contribution role ontology (built on CRedIT through the CRedIT ontology) to support modeling of the multiple additional ways in which the translational workforce contributes to research; better understanding of the types of research objects generated; and mining of acknowledgements section of publications to harvest existing contributor roles to understand the current state and serve as “ground truth”. The acknowledgements work can also help demonstrate that the population of the ontology with actual data is successful to drive additional development. All work is carried out in a collaborative, open, and friendly manner - with an eye toward making credit and attribution easier for everyone.

# Methodology
The Architecting Attribution team runs a version of the Agile methodology. Agile is most often associated with software development, but this method of planning work incrementally, paired with continuous feedback, integration, and testing is conducive to the forward progress of this project.  We run bi-weekly sprints, with daily stand-ups where team members can call out blockers and dependencies. Similar to software development this team breaks work into user stories. 

This team has two integral members who are allocated at a small percentage to this project. The Agile framework allows the team to maximize productivity and collaboration to meet its goal. Piecing out what is a very large task into management chunks has seen our progress accelerate. Previously the team had operated on a more traditional waterfall methodology. This was not as effective as blockers were mainly discussed at Core meetings with little time for resolution. Team members lost valuable time with these waits. As work was not portioned out, it was not always clear what needed to be tackled first or upon what other people, decisions, or processes progress was dependent. 

# Expected Outcomes
- Technical components to compute attribution in research information systems, publishing platforms, and repositories, among other stakeholders
- Framework to empower individuals to better identify and represent their contributions, and simultaneously allowing outside persons or groups to understand these contributions in the context of work on a project, research group, or discipline

# Deliverables
- [CRedIT Ontology](https://github.com/data2health/credit-ontology)
- [Contributor Role Ontology (CRO)](https://github.com/data2health/contributor-role-ontology) released & enhanced
  - CRO is available in various ontological resources (Bioportal, Ontobee)
  - CRO is available in multiple formats (OWL, OBO)
- [CRO](https://github.com/data2health/contributor-role-ontology) ready to pilot in research information systems
- Attribution workshop and community building
  - Workshop brings together community members from across different aspects of the CTSA program and beyond
  - Community implementation requirements are documented
  - First implementation partners are identified and processes planned 
- Best practices for attribution and use of attribution are documented in the Reusable Data Guidebook (RDG)
- An increased knowledge base of contribution / attribution data available
  - Summary statement describing the components of the architecting attribution project and how they function together. 
  - Annotation file format defined. An example will be provided.

# Timeline (monthly)
- 4/1/19 CRedIT ontology [complete]
- 4/1/19 enhanced contribution role ontology [complete]
- 5/1/19 finalize strategy for digital object types [complete]
- 6/1/19 finalize annotation file format [in progress]
- 9/1/19 demonstrator for the individual [ongoing]
- 10/1/19 Credit, Attribution, and Incentives workshop
- 12/15/19 Best practices for attribution and use of attribution guide in RDG
- 3/1/20 implementation of data models into external workflows to pilot and gather data

# Potential Pitfalls and Alternative Strategies
**Demonstration project.** We don’t have a clear picture of the demonstration project development process or responsible party. We’re developing a person-based process for identifying contributor roles, based on the Northwestern Promotion and Tenure documentation, specifically the critical references form, in partnership with the Office of Faculty Affairs, as a guide to faculty members to better identify and claim contributor roles for research objects. This work will allow us to demonstrate the value and power of the data models.


# Y3 (July 1, 2019-June 30, 2020) Accomplishments 
The following content is from the June 30 - Dec 30, 2019 mid year progress report [here](https://docs.google.com/document/d/1LLe3uCfEUakWxIJyi5SA4ZocYDmINvhySTperaui1Bw/edit).  Please add progress for Jan 1 - June 30th, 2020. 

* [CRedIT Ontology](https://github.com/data2health/credit-ontology) 
    * CRedIT is a simple taxonomy of 14 contributor role concepts and was “ontologized” to make it computable and better able to serve as a framework for the subsequent work needed in the Architecting Attribution project. This work was carried out 04/01/2019 and is in [a GitHub repo](https://github.com/data2health/credit-ontology).  Since this time, the CRedIT ontology has been communicated to key stakeholders in conversations, conference presentations, and email correspondence. 

* Contributor Role Ontology (CRO) released & enhanced.  CRO is available in various ontological resources, such as EBI OLS, bioportal, Ontobee, etc.  CRO is available in multiple formats (OWL, RDF, RDF/XML, csv, etc.):
    * The Contributor Role Ontology (CRO) is a structured representation of contribution roles, built on the CRedIT taxonomy, for use in research information systems and designed for crediting persons or organizations.  The CRO was first [released](https://data2health.github.io/contributor-role-ontology) on GitHub and [announced](https://www.force11.org/blog/introducing-contribution-role-ontology-developing-sustainable-community-driven-approach) on 8/7/2019. Ongoing enhancements have been made, including the most recent release on 12/11/2019.
      * CRO on [OBO](https://raw.githubusercontent.com/data2health/contributor-role-ontology/master/cro.owl) (OWL format)
      * [Ontobee](http://www.ontobee.org/ontology/CRO) - (OWL and OBO)
      * [Github](https://github.com/data2health/contributor-role-ontology) - (OWL and OBO)
      * [OLS](https://www.ebi.ac.uk/ols/ontologies/cro) - (OWL format)
      * [Bioportal](https://bioportal.bioontology.org/ontologies/CRO) (OWL format)

* CRO ready to pilot in research information systems:
    * With its initial release in spring 2019, the CRO is ready to pilot in Research Information Systems (RIS). This news was communicated to the community through blog posts by Nicole Vasilevsky, including one that was shared by Force11. Since that time, there were subsequent releases in 08/2019 and 12/11/2019.

* Local guide to support attribution in CTS at the hub level - Best practices for attribution and use of attribution are documented in the Reusable Data Guidebook:
    * The guidebook chapter has been completed and is available [here](https://reusable-data-best-practices.readthedocs.io/en/latest/chapters/chapter_8.html). This guidebook chapter outlines a number of aspects of attribution in biomedical research that are relevant to the person and to the organization.

* An increased knowledge base of contribution / attribution data available
Summary statement describing the components of the architecting attribution project and how they function together.
Annotation file format defined. An example will be provided.
    * A summary statement describing the components of the architecting attribution project and how they function together is provided by the [Contributor Attribution Model](https://contributor-attribution-model.readthedocs.io/). Of particular note is the [description of the information model](https://contributor-attribution-model.readthedocs.io/en/latest/info_model/index.html). 
The [draft critical references guidance](https://docs.google.com/document/d/10s3nScM4nrL1G00JvuhGTkREEc9mX4_KL0yVP_ZyWP4/edit) is available.
The [annotation file format](https://docs.google.com/spreadsheets/d/1sqDi2RtErDUqP1ovyV45Cz07vYvxnpyOjwBVJt2k3a8/edit#gid=0) is complete and available. An example has been included.


