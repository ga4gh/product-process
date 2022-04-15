# Product development and approval process - 2022 revision, main process draft v1 for comment


## Principles



1. GA4GH is an open standards development organisation
    1. Work should take place in ways that are publicly accessible, inclusive of new contributors, and decision making should be transparent - see Best Practices and Code of Conduct
2. GA4GH products should be developed through **broad consultation and consensus**
3. GA4GH aims to develop a small number of products that are of broad utility
4. GA4GH works alongside other standards development organisations in a cooperative manner in whatever way best supports the application of genomics in health and the broader genomics community (including other groups developing standards)
5. Products should seek to interoperate with existing products (from GA4GH or elsewhere). Members of the Technical Alignment Subcommittee (TASC) are the custodians of technical alignment information and decision making. This information should be consulted throughout development work.
6. GA4GH should seek to reuse or adopt existing products, from outside GA4GH, where that makes sense
7. All behaviour should meet our Code of Conduct
8. Groups should follow our Best Practises (or be willing to demonstrate to Steering Committee that their alternative practices are more appropriate)
9. GA4GH policies on copyright, intellectual property (IP), and other topics must be observed and should be shared at the start of calls and when onboarding (along with our Best Practises, Code of Conduct, and all relevant documentation)
10. Documentation generated for products during product development and approval should give clarity on the points on which decision making is based. It should not be longer than is essential. Reuse, where appropriate, is encouraged.
11. New versions of existing standards can fast track documentation by using existing documentation and highlighting changes. However, they must still follow the process and principles defined in this document: consultation, clear problem definition, and stakeholder engagement. These are not optional.


![Flowchart](Flowchart.png?raw=true)

## Specific notes

The following provide detail on the **correspondingly numbered steps in the product development and approval process draft v1 flow chart** above.



1. For products that originated outside of GA4GH (e.g. BED), check if there is any potential conflict with GA4GH policies, for example, relating to IP. Existing IP, or other factors, may prevent GA4GH from being able to adopt a product. 
    1. Decision makers: the decision should be made jointly by a) those interested in the product, b) Secretariat, and c) experts called on by Secretariat. In the case of disagreement, the final decision is with Secretariat.
    2. Criteria: is there anything in the history of the product that would make it incompatible with GA4GH policies? (Checklist to be developed by IP group)
2. Does a group already exist within GA4GH whose interests are closely aligned with this topic? This might be a group that developed a previous version of the product, a broader work stream, or a group formed for some other purpose but whose interests are similar.
    1. Decision makers: a) those interested in the new topic, b) the leaders of the existing group, and c) Secretariat. In the case of disagreement, the final decision is with Secretariat.
    2. Criteria: The decision should consider current group membership (broad and with interests aligned to the product under consideration) and level of activity (that the group be active and engaged). Is there an existing group that is a natural fit with the product or topic being considered, and that has the appropriate knowledge and level of engagement to consider the topic?
3. Having engaged with an existing group, is there interest in the topic and support for taking the new topic forward for exploration in a study group?
    1. Decision makers: this should be based on a consensus opinion from the existing group, expressed by the group leads.
    2. Criteria: based on immediately and easily available information (without in depth study), does the topic, in the group’s opinion, merit further study? 
4. In the absence of an existing group that fits the topic well, work with Secretariat to develop an outreach strategy. This should aim to contact individuals or groups likely to have a shared interest. This should extend beyond those already involved in GA4GH and actively seek people in a range of geographic locations and working in different contexts (i.e. research/clinic), to the fullest extent possible.
5. Has it been possible to form a group to consider forming a study group and, if so, does that group wish to proceed to form a study group on this topic? 
    1. Decision makers: Secretariat to decide if a suitable group has been formed to consider study group formation. If not, outreach work can continue or the topic can be retired. If a suitable group has been formed (as judged by Secretariat), the group should decide through consensus if a study group should be formed, with the decision voiced by the group’s leaders.
    2. Criteria: Secretariat should consider the breadth of geographic and domain areas represented in the group. There should be groups from at least two continents represented. More than one organisation, project or platform of a given type should be represented (similar to requiring at least two Driver Projects). If, in the context of the product there are collaborative efforts (i.e. Terra on a Google platform, funded by NIH and built by Broad) those links could be considered as a single entity and efforts made to seek input from additional entities across ecosystems. In deciding to form a study group, the group should consider if, based on immediately and easily available information (without in depth study), does the topic, in the group’s opinion, merit further study?
6. Form a study group and establish a Product Review Committee
    1. Study group:
        1. The aim is to investigate if a product (of broad utility) is needed, could be developed, and would fulfil a need not met by any existing efforts
        2. Successful exploration of a topic leading to a decision not to proceed is a valid and worthwhile outcome for a Study group
        3. The date of study group formation should be recorded by Secretariat
        4. Study group activities include:
            1. Broad outreach effort (work with communications team)
            2. Stakeholder engagement
            3. Consultation with Regulatory-Ethics and Security
            4. Consideration of the existing landscape: what products already exist and, if a new product were developed, how would it interoperate?
        5. <a name="basicstudyoutputs">Study group outputs include:</a>
            1. Landscape analysis
            2. Use cases (and whose use cases they are)
            3. List of potential adopters who have expressed interest
            4. Problem Statement defining the topic and stating what will be in and out of scope
    2. Product Review Committee (PRC)
        1. The PRC exists to provide expert review of the product and to give feedback at some stages of the development process.
        2.  The PRC should consist of three people with domain knowledge who are not part of development work:
            1. A leader from one other Work Stream
            2. A member of a third, different, Work Stream
            3. A representative of the wider community of adopters, possibly from one of the Driver Projects requiring the product or another adopter
        3. An attempt should be made to have broad representation in the PRC
        4. Conflicts of interest must be declared
        5. The Secretariat should work with the group to identify potential PRC members. In case of disagreement, the Executive Committee will be consulted. Final decision on PRC membership will be with Secretariat.
7. If the work is considering an update to an existing product:
    1. The Study group must consult existing adopters of the product, obtaining responses from a cross-section of existing adopters
    2. The views of existing adopters should form an additional output, [alongside those listed under point 6](#basicstudyoutputs)
    3. Documentation from previous versions of the product can be reused
        1. Differences should be highlighted (git diff or similar is acceptable)
        2. A paragraph of text should be supplied explaining why the changes are needed
        3. The previous PRC should be reconvened if at all possible.
8. For products that originated outside of GA4GH:
    1. The study group should include consultation with existing adopters in their outputs
    2. The landscape analysis may be brief and focus on existing use of the product
    3. The group should state if the intention is to consolidate or further develop the product. This should be made clear in the Problem Statement.
    4. Existing documentation can be used in the initial submission to the PRC ([point 10](#prcstudyreview)) assuming it is aligned with the requirements of GA4GH processes and provides the necessary information required by the PRC.
    5. Documentation can be kept to a minimum but should be clear on the utility of the standard (which may be obvious) and why it should be adopted by GA4GH.
9. Periodically, the study group should review progress
    1. Decision maker: group consensus expressed by the group leaders.
    2. Criteria: is the study group satisfied that the outputs are ready to proceed to the next steps of the process? Does the study group feel that more work is required? Does the study group feel that work should cease? The group should consider if the outputs are sufficient to clearly demonstrate to those not closely involved in the work that the decision making criteria have been met. If work has stalled, can the group determine actions likely to remove the block?
    3. For groups that have run for over a year as a Study group, Secretariat will initiate a meeting between the group leadership and the PRC. This is repeated annually for the duration of the study group.
        1. Decision maker: PRC, Study group, and Secretariat jointly. Final decision with Secretariat in event of disagreement.
        2. Criteria: Should the work proceed to next steps, continue as a study group or cease? Are the outputs ready for next steps? Is there a clear plan of actionable steps to progress work? Has the work stalled irretrievably? Has it been concluded that the topic should not be pursued?
10. <a name="prcstudyreview">The PRC reviews the outputs from the study group.</a>
    1. Outputs to be reviewed include:
        1. Landscape analysis
        2. Use cases (and whose use cases they are)
        3. List of potential adopters who have expressed interest
        4. Problem Statement defining the topic and stating clearly what will be in and out of scope
        5. If the product is from outside GA4GH or an update to an existing product, a summary of the views of those who adopted the previous version of the product
    2. Decision maker: the PRC (with support from Secretariat to provide additional required information) can choose to support the outputs going forward to Steering Committee or provide comments to the Study group, asking them to review
    3. <a name="prcstudycriteria">Criteria:</a>
        1. Is there engagement from a varied cross section of the community? 
        2. Is the problem, as stated, of broad interest and utility?
        3. Is there a need for new work? Could existing products be used effectively?
        4. Have any pre-development interoperation concerns been identified and clearly scoped?
        5. Does the problem fit within GA4GH’s remit?
        6. Is the Problem Statement in line with GA4GH’s decentralised and federated philosophy, where we avoid centralised infrastructure?
        7. Is the Problem Statement clearly defined?
        8. Does the content of the Problem Statement make sense?
11. Presentation to Steering Committee
    1. The Study group should present their work at the next Steering Committee meeting
    2. The materials generated for the PRC should be shared with the Steering Committee at least two weeks before the meeting
12. <a name="subsetstudyballotprocess">Steering Committee subset/delegates offline ballot following this process:</a>
    1. Following the Study group’s presentation to Steering Committee, the Steering Committee will be balloted to determine if the group should proceed to development work
    2. Steering Committee members can:
        1. Choose to cast a vote themselves
        2. Ask a nominee to vote on their behalf
            1. For example, a Driver Project Champion might ask a colleague on the same Driver Project with knowledge of the domain
        3. Excuse themselves from the vote if they feel the topic is outwith their expertise
    3. A simple majority of cast votes determines the outcome. If the outcome is tied, development work goes ahead.
    4. The ballot closes two weeks after the Steering Committee presentation
    5. Votes must be cast by (or on behalf of) >50% of Steering Committee members for the outcome to be valid and development work to proceed.
        1. If this is not achieved, Secretariat should work with Steering Committee members to understand the reasons members were unwilling to vote. Secretariat should then present a possible plan of action, two weeks ahead of the next Steering Committee call, which will be put to a vote of Steering Committee members on that call, where Steering Committee members can vote for the plan or for the work to be discontinued.
    6. If approved, a list should be made of all Steering Committee members (or their delegates) who wish to be kept informed of development work.
13. Steering committee subset/delegates decide if the Problem Statement should be taken through to development using the ballot process described under [point 12](#subsetstudyballotprocess)
    1. Decision makers: Steering Committee members or their nominees
    2. Criteria:  are [the same as for the PRC](#prcstudycriteria) under point 10
14. Product development process:
    1. Work commences on developing a product, as defined by the Problem Statement presented to Steering Committee
    2. There is further broad communication (beyond existing GA4GH contributors) that the group is being set up (work with comms). This should include contacting specific key stakeholders.
    3. Those intending to adopt the product, those who have already adopted the product, and Steering Committee members who have registered an interest in the product should be kept informed about work. This should follow Best Practice and should include sharing decisions, in summary format (not full meeting minutes), in a timely manner.
    4. Development work should be based on real use cases across multiple environments
    5. For products originating outside of GA4GH, this work may be limited to formalising documents ahead of public comment. That work should, however, align with GA4GH’s working methods.
    6. <a name="developmentoutputs">Outputs</a>
        1. Decision record documenting the major decisions taken during development and why they were taken
        2. The product specification
        3. Implementations
            1. There should be at least two implementations created by independent groups (i.e. not two implementations created by the same entity for two different projects)
            2. At least one of these implementations should be open
            3. Interoperability of these implementations should have been demonstrated
            4. In client server models, there should be both two client and two server implementations, operating in different systems
            5. Work streams do not need to build the implementations. The intention is that these would be built by Driver Projects.
            6. Implementation work should inform the development process
        4. Documented feedback from adopters
15. Periodically, the development group should review progress
    1. Decision maker: group consensus expressed by the group leaders
    2. Criteria: is the development group satisfied that the outputs are ready to proceed to the next steps of the process? Does the development group feel that more work is required? Does the development group feel that work should cease? The group should consider if the outputs are sufficient to clearly demonstrate to those not closely involved in the work that the decision making criteria have been met. If work has stalled, can the group determine actions likely to remove the block?
    3. For groups that have run for over a year in development, Secretariat will initiate a meeting between the group leadership and the PRC. This is repeated annually for the duration of development.
        1. Decision maker: PRC, development group and Secretariat jointly. Final decision with Secretariat in event of disagreement.
        1. Criteria: Should the work proceed to next steps, continue development or cease? Are the outputs ready for next steps? Is there a clear plan of actionable steps to progress work? Has the work stalled irretrievably? Has it been concluded that the topic should not be pursued?
16. Open for comment:
    1. Following a decision to proceed, taken by the development group, the development outputs should be made available for public comment. This is the opportunity for everyone to express an opinion on the content of the product.
    2. The public comment announcement should be circulated widely, including to everyone associated with GA4GH
    3. This is also the period when Steering Committee members (or their delegates) are invited to express their views on the product. Those who previously registered interest should be notified directly of the comment period.
    4. The public comment period should be of a minimum of one month.
    5. The PRC should be consulted on when the public comment period should close.
17. Regulatory-Ethics, Security and the PRC review the development outputs, with revisions following public comment
    1. Regulatory-Ethics and Security
        1. The combined Regulatory-Ethics and Security questionnaire should be completed. This can be done in a single meeting with representatives from those work streams who can assist in completing the questionnaire.
    2. PRC review
        1. The [outputs listed under point 14](#developmentoutputs). For the implementations, the PRC should be satisfied that interoperation has been demonstrated and that at least two implementations exist, at least one of which is open
    3. Decision makers
        1. Regulatory-Ethics and Security
        2. PRC, with support from Secretariat to provide additional information. The PRC can approve, request minor revisions, major revisions or indicate that they believe there are fundamental flaws with the work.
    4. Criteria
        1. Regulatory-Ethics and Security
            1. Does the product meet the standards of ethics and security established by those Work Streams?
        2. <a name="prccriteria">PRC</a> 
            1. Does the delivered product answer the Problem Statement?
            2. Is there evidence that the implementations are interoperable?
            3. Have adopters been consulted and their views documented?
            4. Is it clear what use cases the product serves?
            5. Have issues of interoperability with other GA4GH products or products outside of GA4GH been addressed?
            6. Is this a product of broad utility?
            7. Is the decision making reasonable?
            8. Is there anything, in the reviewers expert opinion, that is a concern?
            9. Is the work aligned with wider GA4GH and does it follow the recommendations of TASC?
                1. This could include using the Data Model Library, data model reuse, complying with namespace conventions, etc
                2. It is acceptable for the PRC to delegate this aspect of the review
    5. Meetings between the development leads and the PRC, Regulatory-Ethics or Security should be arranged as is helpful to enable discussion and provide clarification - this is particularly useful where changes are requested by the PRC
18. Following revisions, the PRC, Regulatory-Ethics and Security make a decision on the product.
    1. Decision makers: primarily the PRC, with input from Regulatory-Ethics and Security on their reviews. The PRC can approve, withhold approval or, if there has been substantial change since the public comment, ask for the work to undergo another round of public comment
    2. Criteria: [as for the PRC under point 17](#prccriteria). In addition, have there been substantial changes since the last public comment period?
19. Development group and Secretariat review in event of PRC withholding approval. They should decide if the work returns to development or if it ceases.
    1. Decision makers: development group and Secretariat. Final decision with Secretariat.
    2. Criteria: Can the reasons that the PRC gave for withholding approval be addressed through further development work? Can a plan of action be clearly established to do this?
20. <a name="subsetcontentballot">Steering Committee subset/delegates offline ballot on content, following this process:</a>
    1. The Steering Committee will be balloted to determine if the content of the product is acceptable
    2. Documents generated for the PRC should be shared with Steering Committee
    3. Steering Committee members can:
        1. Choose to cast a vote themselves
        2. Ask a nominee (for example a colleague on the same Driver Project with knowledge of the domain) to vote on their behalf
        3. Excuse themselves from the vote if they feel the topic is outwith their expertise
    4. A simple majority of cast votes determines the outcome. If the outcome is tied, development work goes ahead.
    5. The ballot closes two weeks after documents have been shared
    6. Votes must be cast by (or on behalf of) >50% of Steering Committee members for the outcome to be valid and the product to proceed.
        1. If this is not achieved, Secretariat should work with Steering Committee members to understand the reasons members were unwilling to vote. Secretariat should then present a possible plan of action, two weeks ahead of the next Steering Committee call, which will be put to a vote of Steering Committee members on that call, where Steering Committee members can vote for the plan or for the work to be discontinued.
    7. If approved, the product should move to final process approval by Steering Committee.
21. Steering committee subset/delegates decide if the product is acceptable using the process decribed under [point 20](#subsetcontentballot)
    1. Decision makers: Steering Committee members or their nominees
    2. Criteria:  [are the same as for the PRC under point 17](#prccriteria)
22. Final presentation to Steering Committee for approval that the product development has followed our process
    1. The following should be shared with Steering Committee at least two weeks before the call where a vote is scheduled
        1. Outputs listed [under point 10](#prcstudyreview) and [under point 14](#developmentoutputs)
        2. Evidence of outreach
        3. Evidence that those who registered interest in the product were kept informed
    2. Decisions makers: Steering committee members
        1. Members on the call can abstain or vote to approve or reject
        2. A simple majority is sufficient for approval
        3. In the event of a tie, the product is approved
    3. Criteria: based on the available documentation are members satisfied that the process outlined in this document has been followed and that the process has been open, fair and completed to a good standard?
