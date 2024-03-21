---
layout: default
title: Open Source Contributions
nav_order: 2
has_children: true
permalink: /Contributions-3-3-Ind
---

## The business process of making an open source software contribution part 3

## Creating a new open source software project

Deciding to create a new open source software project shares many of the same considerations with the choice of making major or continuous contributions to existing open source software projects. For instance, the three cornerstones are equally applicable:

* Purpose. A defined purpose for creating the open source software project.

* Suitability. A suitability assessment from relevant perspectives, based on the purpose.

* Conscious decision. A conscious decision based on the above, including the allocation of adequate and suitable resources.

A significant difference, however, is that the creator of a new open source software project needs to take several additional decisions to establish the project in the first place, and that the project essentially needs to be viewed as any other software development project. In other words, it needs to be planned, staffed, funded, launched, governed, and maintained over the project lifecycle[^todo-starting-a-project]. Further, the success of the project will depend on successful external community building.

[^todo-starting-a-project]: [Starting Open Source Projects](https://todogroup.org/resources/guides/a-guide-to-outbound-open-source-software/#starting-open-source-projects){:target="_blank"}

### Defining the purpose of the open source software project

Similar to what is described in module 3 for contributions to existing open source software projects, it is important to have a clear purpose for creating an open source software project. Why should we create this project?

Given that it will require some effort, and that internal assets will be published under a (more or less) permissive open source software license, there should be an obvious business reason to start the project.

For instance, the reason could be to push an open standard in a software layer that drives a lot of internal development costs, but which does not as such add distinctive features to the company’s end-product. An open source software standardization effort could also be a response to a competing proprietary standard or to attempt disrupting a monopolistic market. Another scenario could be that the company has identified a business model where the open source software project is used to drive broad adoption, but there is a good potential for revenue streams connected to services relating to the open source software project. In this context, so-called ‘dual licensing’ models are getting increasingly common, where the software is simultaneously released both as open source software – typically under a strong copyleft license[^gpl3]  – and as a traditional commercial license. Further, one reason could simply be that the company lacks sufficient competence and knowledge to maintain a software asset and/or wishes to share the development and maintenance costs for it. The reason may even be altruistic, in the sense that the open source software asset holds no business value for the company but has a potential value for society (where an indirect business reason could be goodwill). Many other potential business reasons exist; the key point is that a company needs to identify at least one to proceed with the activity.

[^gpl3]: [General Public License](https://www.gnu.org/licenses/gpl-3.0.html){:target="_blank"}

When the question “why” is answered, it will as a next step be necessary to assess the suitability in terms of needed resources, engagement, timeframe, legal and IPR, etc. Starting an open source software project also comes with a set of choices, as further outlined below.

### Suitability and Choices

Starting an open source software project is a strategic choice. Even if it has a limited impact in relation to the overall business of the company, it is still recommended to approach it as a strategic choice compared to other available alternatives. Thus, before creating such a project, a company should ask itself:

* Is it aligned with our company strategy to release this asset as open source software?
* What will our future engagement be (in the short and long term)?
* Will the potential benefits warrant the level of engagement (in the short and long term)?
* What is the expected outcome, and how can that be secured?
* Are there any risks connected to the activity?
* Are there any other open source software projects attempting to solve the same problem? If so, why create a new project instead of contributing to an existing project?

The suitability assessment set out in module 3.1 is generally applicable to the creation of an open source software project as well. Below follows a few examples of additional considerations relating to the creation of open source software projects.

* **Governance model:** As mentioned in see module 3, open source software projects can be governed in different ways. It is essential to set up a governance model that will support the purpose of the project. As mentioned, projects controlled by a single company typically lack community-based governance fora such as Technical Steering Committees and the company appoints Committer roles to its employees to gatekeep all code going into the codebase. The benefit of this is of course a strong control position, but such a control position may also deter others from engaging in the project. An opposite extreme would be to “donate” the software asset to a neutral party, typically an existing Open Source Foundation (or a new foundation created for the purpose). A hybrid model can also be to have a phased approach, where the company retains initial control but gradually moves over to a meritocracy-based governance model. Depending on the size of the initiative, it could on the one hand be of such monumental scope that it requires some kind of umbrella organization with its own governance (and e.g. specific committees to handle technical sub-streams), and it could on the other hand be sufficient to have a very lean setup for a simple niche open source software library. Many variants exist, each with pros and cons. The bottom line is that the company should thoroughly consider which governance model fits best for the specific project.

* **Communication:** Communication is an important part of launching – as well as maintaining – a successful open source software project. Roughly speaking, it needs to serve the high-level marketing purpose of attracting a strong community, as well as the detailed purpose of ensuring that all contributors understand the rules of engagement in the project. As such, consider which communication channels to use, how to clearly reach out with the project’s vision and problem statement (and the benefits of its purported solution), as well as more detailed day-to-day information. Consider engaging internal or external marketing expertise for larger open source software projects.

* **Timing:** The timing of launching the open source software project is important from several perspectives. As a first example, the maturity of the asset itself is of course a factor – it will be significantly harder to gain traction for an unmaterialized idea compared to a working software application. Waiting too long, on the other hand, will waste internal resources on efforts which could potentially have been shared with others in open collaboration. If the purpose is standardization, there will always be a risk that other de facto standards grow strong while the company prepares to publish its own initiative. Once again, it will be important to find a good balance between speed and readiness to achieve the purpose, but as a general notion, the company should at least make sure to go through and make necessary preparations for the items proposed in this see module 3, as well as perform relevant technical reviews of the open source software asset (see module 3), before launching the project.

* **Choice of repository:** The choice to create an open source software project will also come with a choice of how to publish and host the software in question. The company should make an educated choice of repository to keep the code safe and version-controlled, and which facilitates collaboration and enables statistics and analysis as necessary. If in doubt, it is likely a good idea to use one of the reputable and well-known repository services on the market.

### Suitability and Choices – Legal & Intellectual Property Rights (IPR)

When starting an open source software project, various legal and IPR aspects will need to be considered. In short, the company needs to:

* Ensure that it is not violating third party rights.
* Ensure that contributions and contributors are not violating third party rights.
* Ensure compliance with relevant laws and regulations.
* Choose relevant legal instruments (e.g. the open source software license) and policies for the project.

#### Third party rights

The legal and IPR suitability assessment set out in module 3.1 is generally applicable to assets that the company itself puts into the open source software project, from the start as well as thereafter. In the following, additional considerations relating to the creation of open source software projects have been added.

* **Choice of license:** The choice of license for the downstream distribution is highly connected to the goal of the open source software project. If it is crucial to drive continuous openness, it is an argument for choosing a copyleft license. If broad adoption by commercial downstream implementers and re-distributors is key, however, it is an argument for a non-copyleft license. If the software is created in a heavily patented landscape, it may be worth choosing a license with explicit patent language (patent license/non-assertion, etc.) rather than relying on licenses where patents are not mentioned (i.e. where the patent license is at best implied). If the software is intended to be combined with other open source software, make sure that the selected license is compatible (or if suitable identical) with the other open source software project license. In theory, a company can draft its own tailored license for the published software. However, this has the drawback of using a license that is not yet recognized by reputable institutions such as the Open Source Initiative, which in turn increases the threshold to establish general trust in the license and may make it harder to build a community. As such, the alternative of drafting a unique license is seldomly worth the effort (and lawyer hours), and should primarily be considered for strategic and large open source software projects with an equally strong branding agenda where the license can be branded as part of the initiative. Consult legal expertise if necessary to make a good choice in this respect.

* **Choice of contribution model:** The company needs to decide whether or not to use a CLA, DCO or other legal instrument to record inbound contributions of if it should simply make an inbound = outbound statement or similar. Like other decisions in this area, choices that increase the company’s control may at the same time deter collaborators and contributors from engaging in the open source software project. In any case, it is not advisable to leave it completely open for contributors to set terms and conditions for their contributions – that will eventually create chaos in the project and hamper both downstream and contributor interest. In conclusion, it is recommended to clearly communicate a contribution model to contributors, irrespective of whether it leans towards maximizing control (e.g. a CLA) or if the main driver is simplicity (e.g. an inbound=outbound statement).

* **Antitrust Guidelines:** As the facilitator of an open collaboration forum, the company may potentially also be inviting actual or potential competitors to participate in the co-creation of the open source software asset. This section will not attempt to exhaustively describe such legislation, but it is important to note that certain interactions and agreements between competitors are prohibited, in particular the creation of cartels. In certain jurisdictions, liability may extend also to a coordinator of a cartel between other parties. In light of this, it is generally advisable to establish an antitrust guideline for any open source software project where competitors may interact, and – needless to say – to comply with the said guideline and applicable antitrust and competition laws.

* **Data Privacy:** Please note that by governing an open source software project, the company may be deemed a data controller responsible for the processing of personal data under the GDPR and other data privacy laws. As such, make sure to establish customary privacy notices, cookie consent forms and other measures to ensure compliance with such laws.
