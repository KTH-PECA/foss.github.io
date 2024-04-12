---
layout: default
title: Open Source Contributions
nav_order: 2
has_children: true
permalink: /Contributions-3-2-Ind
---

## Suitability assessment

With the intended purpose established, the next step is to assess the suitability of the contribution.

* Will the potential benefits warrant the effort needed?
* How likely is the company to achieve the purpose by making the contribution(s)?
* Are there any risks connected to the activity?

The suitability assessment  should consist of business- and technical considerations, as covered in this section, as well as legal and intellectual property rights aspects, as covered in the next section. Together with the purpose, these two suitability dimensions will constitute a basis for the decision to contribute or not.

* **Resource allocation.** The question of resource allocation is closely connected to the type of contribution. In cases of minor one-time bug fixes and corrections, the contribution may not demand much more than the push of a button. Such momentary cases will not require noticeable resources. On the other hand, if the intention is to strategically engage in a open source software project over time, the company will likely need to allocate internal resources such as developers or project managers to the project. Thus, for larger contribution activities, the company needs to balance the open source software project activity against other prioritized activities. In general, consider assigning an internal “owner” for continuous contributions and/or to funnel contributions through some kind of control instance, such as an Open Source Program Office (OSPO) or other cross-competence team.
  
* **Technical and financial boundaries.** Heavy engagement in an open source project may e.g. involve paid membership in a governing body, frequent meetings and/or substantial engagement of internal developers, which suggests keeping a budget or taking other measures for cost control purposes. Further, it may also be worth considering if any technical boundaries should be settled for the contribution. If the open source software project pivots in an irrelevant or misaligned direction, the company may have decreased strategic interest to stay involved. A technical boundary could also be necessary in terms of the contributions as such, i.e. the company may be comfortable contributing code for one part of the open source software project, but unwilling to share in adjacent technical areas. Whether expressed as formal boundaries/mandates or not, consider whether any such framing is needed for the engagement and/or if any exit criteria can be defined.

* **Brand exposure:** Once the company starts openly interacting with the open source software project, it will associate its brand with the project and any company developers will represent the company brand in the context. As such, at least when the intention is to get heavily involved, the company should assess if there are any bad will risks entailed with being associated with the open source software project. Bad will risks may also arise if the company provides poor quality contributions or if its employees misbehave in the project, e.g. acting in breach of the project’s Code of Conduct. On the other hand, being associated with an open source software project in a positive way will of course carry a potential of goodwill, thereby strengthening the company brand and enhance the perception of the company as an open source software friendly company.

## Suitability assessment – Legal & Intellectual Property Rights (IPR)

Depending on the type of contribution and the scope thereof, various legal and IPR aspects may need to be considered. In short, the company needs to:

* Ensure that it is not violating third party rights.
* Avoid non-intended exposure of its own proprietary assets.
* Ensure compliance with relevant laws and regulations.
* Observe any legal instruments required by the FOSS project in question (such as Contributor License Agreements or Developer Certificates of Origin).

### Third party rights

A fundamental starting point when considering a contribution is that the contributing company has appropriately secured the right to do so in the first place. Any source code and corresponding documentation should be assumed to be protected by copyright unless it can safely be assumed to lack originality[^copyright].  In unclear cases, it is advisable to involve legal counsel before ruling out copyright as a relevant factor.

[^copyright]: Copyright is automatically granted to the author of a literary or artistic work (in this case, source code and documentation) upon the creation of such work. In a business context, the copyright will typically pass from the author (i.e. the developer) to the employer pursuant to law and/or the employment contract. In general, the copyright holder has an exclusive right to prevent others from making copies of the work (source code or documentation) and to make it available to the public. Reversely, this means that the source code or documentation may only be copied and distributed to others with the permission of the copyright holder. Such permission is generally referred to as a license.

Before making a contribution of copyright-protected material:

* Ensure that you know who the author(s) of the material are.

* If any part of the material was created by a third party, such as a consultant or a supplier, ensure that the ownership of the copyright was passed on to your company or that you received license rights that allow you to make the contribution. Do not proceed with the contribution without such agreement with the copyright holder(s).

* If the material is developed inhouse, but includes code snippets or text passages from other sources, assess whether this use of third party sources is prevented from a copyright perspective.

* If the material has been developed with the support of generative AI, it may require additional considerations depending on the AI tool in question. For instance, if the terms and conditions of the AI tool allows for such use of its output and to which extent the output is truly generative rather than derivative from the dataset that the AI tool has been trained on. 

Apart from copyright, a contribution may also be subject to other third party rights:

* A contribution to an open source project will be a public disclosure of information and it is therefore important to ensure that the contribution does not lead to confidentiality or trade secrets violations.

* The use, functionality or specific implementations of the contribution may be subject to third party patent rights. When contributing new features to an open source software project, align with the internal IP department or an IP expert about whether to perform freedom-to-operate patent investigations before making such contributions.

### The legal consequence of contributing an information asset to an open source software project

Contributing to an open source software project is an act of transforming company-internal information – code, know-how, experience, or documentation – into an external asset shared with others. From the legal perspective, the company will normally not transfer its ownership of the contributed IP. However, by making the contribution, the company will essentially pledge the asset and the corresponding intellectual property rights to become open in a manner which will significantly reduce the possibilities for the company to restrict future use of the contributed asset. This loss of legal control should be viewed as part of the price of becoming a contributor.

Open source software projects will from time to time use various legal instruments to ensure the company’s and/or developer’s commitment to the contribution:

* To begin with, the open source software project will have a license regime for outbound licensing where one or more licenses are predominantly used or required for the downstream distribution. Such license regime may be defined in the project charter (if such charter exists) or elsewhere. At the very least, there is typically one or more LICENSE files in the repository. Although most open source software licenses focus on the outbound, downstream licensing rather than how to receive contributions, some open source software licenses also include specific terms and conditions for making contributions, such as the Apache License, Version 2.0[^asl2.0].

[^asl2.0]: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0){:target="_blank"}

* A frequently used open source software project philosophy is inbound = outbound, meaning that the project has declared (e.g. in the project charter or a CONTRIBUTIONS file) that it only accepts contributions under the same license as the outbound license. As such, making a contribution to the project will be assumed to be licensed in to the project on the same terms as it is licensed out from the project.

* In order to legally solidify and secure the commitment of contributors, some open source software projects also use so-called Developer Certificates of Origin (DCO), Contributor License Agreements (CLA), or similar.

* A DCO is a unilateral sign-off by the contributor certifying that it has the adequate rights to make the contribution and that it understands the public nature of the contribution (including the sign-off)[^dco].  Different open source software projects may use different mechanisms for recording the DCO, but the typical approach is that the sign-off is embedded in the git commits.

[^dco]: [Developer Certificate of Origin](https://developercertificate.org/){:target="_blank"}

* A CLA is an agreement between the contributor – an individual or a legal entity – and the open source software project owner[^ccla].  In general, the purpose of a CLA is to improve the project’s ability to rely on contributions from a contributor. Please note that a CLA may in various ways extend beyond the contribution at hand, e.g. to cover any future contributions by employees of a company or group of companies. As such, it is strongly recommended to review and understand the terms and conditions of any CLA before signing it and proceeding with contributions.

[^ccla]: [Corporate Contributor License Agreement](https://www.apache.org/licenses/cla-corporate.pdf){:target="_blank"}

* As mentioned above, most open source software projects will retrieve contributions on a license basis, not by transfer of ownership. However, a project owner can in theory acquire the IPR instead of licensing it. To do so, an IPR assignment agreement would have to be executed between the contributor and project owner. Please note that an assignment of the IPR in a contribution would entail a complete transfer of rights and should be carefully deliberated before it is accepted.

* Before making a contribution, a company should make sure to review and understand the implications of the specific CLA, DCO or other terms and conditions applicable for the contribution. Whether or not the contributing company is legally bound by the terms and conditions of an open source software project will depend on the circumstances in the specific case, but a contributing company should try to avoid any ambiguity and potential conflicts in this regard.

* If – for some reason – the contributing company wishes to make any reservations or contribute under different terms and conditions than what is established in the open source software project, it is important to be clear and explicit about such reservations. A suggestion is to reach out to the project owner or a maintainer to initiate a dialogue about a potential conditional contribution before making the contribution.

### Compliance with laws and regulations

Apart from what is stated above, participation in an open source software project  may trigger various regulatory considerations. This is not unique to open source software projects, but nevertheless important to keep in mind.

* For instance, competitor representatives may interact in steering committees or other forums of an open source software project, which entails competition/antitrust law considerations.

* In any context where representatives from actual or potential competitors are participating, avoid sharing commercially sensitive information and use customary mechanisms to remind about and record diligence with applicable competition/antitrust law regimes.

* Larger open source software projects and/or Open Source Foundations may have their own antitrust guidelines[^lf-antitrust].  Many companies will also have their own policies in respect of competition law compliance. Contributors should ensure awareness of such guidelines and policies and assess whether they require any particular actions or precautions for the intended engagement.

[^lf-antitrust]: [Anti Trust Policy](https://www.linuxfoundation.org/legal/antitrust-policy){:target="_blank"}, Linux Foundation

* Moreover, the technology in itself – or its distribution – may be regulated, for instance under export control regulation (although published open source software is often exempted) or specific product or technology legislation. Involve relevant experts as necessary in cases of uncertainty whether specific code or documentation can be shared in an open source software context and/or if it requires specific measures, such as BIS and NSA notifications for non-standard cryptography software[^lf-export-controls]. Certain technology fields may also be subject to special regulation[^eu-ai-act].

[^lf-export-controls]: [Understanding US export controls with open source projects](https://www.linuxfoundation.org/resources/publications/understanding-us-export-controls-with-open-source-projects){:target="_blank"}

[^eu-ai-act]: Such as specific AI or cybersecurity legislation in certain jurisdictions.
