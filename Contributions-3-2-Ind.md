---
layout: default
title: Open Source Contributions
nav_order: 2
has_children: true
permalink: /Contributions-3-2-Ind
---

## The business process of making an open source software contribution part 2

### Suitability assessment

With the intended purpose established, the next step is to assess the suitability of the contribution.

* Will the potential benefits warrant the effort needed?
* How likely is the company to achieve the purpose by making the contribution(s)?
* Are there any risks connected to the activity?

One part of this assessment is of a business- and technical character, as covered in this section. The next section will cover the legal and intellectual property rights aspects of the suitability assessment. Together with the purpose, these two suitability dimensions will constitute a basis for the decision to contribute or not.

* **Resource allocation.** A fundamental question is resource allocation, which is in turn closely connected to the type of contribution. In cases of one-time bugfixes and corrections, the contribution may not demand much more than the push of a button (if the fix has already been developed internally). Such momentary cases will of course not require any significant additional resources. On the other hand, if the intention is to strategically engage in the open source software project over time, the company will need to allocate internal resources to the project, such as developers, project managers, or other necessary personnel. Consequently, for larger contribution activities, the company needs to balance the open source software project activity against other prioritized activities. In general, it is recommended to assure that a continuous contribution activity has an internal “owner” and/or that contributions are funneled through some kind of control instance, such as an Open Source Program Office (OSPO) and/or a cross-competence team set up for governance purposes.
  
* **Technical and financial boundaries.** For continuous engagement in open source software projects, it may be necessary to define certain boundaries of both technical and financial character. Heavy engagement may e.g. involve paid membership in a governing body, frequent meetings and/or substantial engagement of internal developers, which suggests keeping a budget or taking other measures for cost control purposes. Further, it may also be worth considering which technical boundaries – if any – that should be settled for the contribution. Such boundaries could apply to the general project evolution, i.e. if the open source software project pivots in an irrelevant or misaligned direction, the company may have decreased strategic interest to stay involved, or face the decision whether to fork out a subproject. A technical boundary could also be necessary in terms of the contributions as such, i.e. the company may be comfortable contributing code for a particular part of the open source software project, but unwilling – for strategic reasons – to share in other adjacent technical areas. Whether expressed as formal boundaries/mandates or not, it is recommended to consider whether any such framing is needed for any given engagement. The boundaries can also be used to define exit criteria for the engagement.

* **Brand exposure:** Once the company starts interacting with and contributing to the open source software project, it will associate its brand with the project and any company developers will represent the company brand in the context. Generally speaking, the larger the contribution/engagement, the larger the brand exposure. As such, the company should assess if there are any bad will risks entailed with being associated with the open source software project. Bad will risks may also arise if the company provides poor quality contributions or if its employees misbehave in the open source software project, e.g. acting in breach of the project’s Code of Conduct. On the other hand, being associated with an open source software project in a positive way will of course carry a potential of goodwill, thereby strengthening the company brand. The decision to support an open source software project might be an opportunity for the marketing unit to provide a press release on the topic and thus strengthening the perception of the company as an open source software friendly company.

## Suitability assessment – Legal & Intellectual Property Rights (IPR)

Depending on the type of contribution and the scope thereof (see Section 1.2 above), various legal and IPR aspects may need to be considered. In short, the company needs to:

* Ensure that it is not violating third party rights.
* Avoid non-intended exposure of its own proprietary assets.
* Ensure compliance with relevant laws and regulations.
* Observe any legal instruments required by the FOSS project in question (such as Contributor License Agreements or Developer Certificates of Origin).

### Third party rights

A fundamental starting point when considering a contribution is that the contributing company has appropriately secured the right to do so in the first place. Any source code and corresponding documentation should be assumed to be protected by copyright unless the contribution is rudimentary to the point where it can safely be assumed to lack originality.  In unclear cases, it is generally advisable to involve legal counsel before ruling out copyright as a relevant factor.

Before making a contribution of copyright-protected material, consider the following:

* Ensure that you know who the author(s) of the material are.

* If any part of the material was created by a third party, such as a consultant or a supplier, review the contract to ensure that the title and ownership of the copyright was passed on to your company or that you otherwise received license rights that would allow you to make the contemplated contribution. If such contract is not in place, or if the existing contract does not explicitly grant sufficient rights to make a contribution, do not proceed with the contribution until an adequate contract or contract amendment has been negotiated with the copyright holder.

* If the material has been developed independently or if it may include portions of material made by others, for instance by copying and pasting code snippets or text passages from other sources. In the latter case, it will be necessary to assess from a copyright perspective whether this use of third party sources prevents the contribution in question.

* If the material has been developed with the support of generative AI, it may require additional considerations depending on the AI tool in question. This includes, for instance, whether the terms and conditions of the AI tool allows for such use of its output, and to which extent the output is truly generative rather than derivative from the dataset that the AI tool has been trained on. Please note that it is unlikely that material created exclusively by an AI is possible to protect by means of intellectual property rights, such as copyright.

Apart from copyright, a contribution may also be subject to other third party rights. For instance:

* It may contain trade secrets or confidential information of third parties. Be aware that a contribution to an open source project will be a public disclosure of the information in question. It is therefore important to ensure that the contribution does not breach any confidentiality obligations or otherwise misappropriate any trade secrets of others.

* The use, functionality or specific implementations of the contribution may be subject to third party patent rights. In contrast to the literal scope of copyright protection, patents protect technical inventions – products or processes, i.e. a certain functionality. As such, even if the copyright to the code contribution belongs with the contributing company, using the code can at the same time be infringing on third party patent rights if it facilitates the execution of a patent-protected invention in a specific technical context. For minor contributions (bugfixes, etc.), this is unlikely an issue, but when contributing new features to an open source software project, align with the internal IP department or an IP expert about whether to perform freedom-to-operate patent investigations before making such contributions.

### The legal consequence of contributing an information asset to an open source software project

Contributing to an open source software project is an act of transforming company-internal information – be it code, know-how, experience, or documentation – into an external asset shared with others. It is generally an irreversible transaction without any direct monetary reimbursement. As such, as mentioned in the beginning of this module 3, it is important from a business perspective to make a conscious decision about what to share and how.

From the legal perspective, the company will normally not assign or transfer its ownership of the intellectual property rights of the contributed asset. However, by making the contribution, the company will essentially pledge the asset and the corresponding intellectual property rights to become open in a manner which will significantly reduce the possibilities for the company to restrict future use of the contributed asset – except for enforcement vis-á-vis future users who do not comply with the open source software license in question. This loss of legal control should be viewed as part of the price of becoming a contributor.

Open source software projects will from time to time use various legal instruments to ensure the company’s and/or developer’s commitment to the contribution.

* To begin with, the open source software project will have a license regime for outbound licensing where one or more licenses are predominantly used or required for the downstream distribution. Such license regime may be defined in the project charter (if such charter exists) or elsewhere. At the very least, there is typically one or more LICENSE files in the repository. Although most open source software licenses focus on the outbound, downstream licensing rather than how to receive contributions, some open source software licenses also include specific terms and conditions for making contributions, such as the Apache License, Version 2.0.

* A frequently used open source software project philosophy is inbound = outbound, meaning that the project has declared (e.g. in the project charter or a CONTRIBUTIONS file) that it only accepts contributions under the same license as the outbound license. As such, making a contribution to the project will be assumed to be licensed in to the project on the same terms as it is licensed out from the project.

* In order to legally solidify and secure the commitment of contributors, some open source software projects also use so-called Developer Certificates of Origin (DCO), Contributor License Agreements (CLA), or similar.

* A DCO is a unilateral sign-off by the contributor certifying that it has the adequate rights to make the contribution and that it understands the public nature of the contribution (including the sign-off).  Different open source software projects may use different mechanisms for recording the DCO, but the typical approach is that the sign-off is embedded in the git commits.

* A CLA is an agreement between the contributor – an individual or a legal entity – and the open source software project owner.  In general, the purpose of a CLA is to improve the project’s ability to rely on contributions from a contributor. Please note that a CLA may in various ways extend beyond the contribution at hand, e.g. to cover any future contributions by employees of a company or group of companies. As such, it is strongly recommended to review and understand the terms and conditions of any CLA before signing it and proceeding with contributions.

* As mentioned above, most open source software projects will retrieve contributions on a license basis, and not by transfer of ownership. However, a project can of course in theory acquire the intellectual property rights (IPR) instead of licensing it. To do so, an IPR assignment agreement would have to be executed between the contributor and project owner. Please note that an assignment of the IPR in a contribution would entail a complete transfer of rights and should as such be carefully deliberated before it is accepted.

* Before making a contribution, a company should make sure to review and understand the implications of the specific CLA, DCO or other terms and conditions applicable for the contribution.

* To which extent the contributor is legally bound to the terms and conditions set out by an open source software project depends on the circumstances in the specific case. A signed CLA will of course more solidly establish the contribution than a general inbound=outbound principle.

In summary, a contributing company should consider the following:

* Different open source software projects will have different methods of validating your contribution, ranging from implicit presumptions to requiring formal agreements. In any case, there will be a general expectation that your contribution becomes open source software.

* Whether or not the contributing company is legally bound by the terms and conditions of an open source software project will depend on the circumstances in the specific case, but a general approach for a contributing company should be to avoid any ambiguity and potential conflicts in this regard.

* If – for some reason – the contributing company wishes to make any reservations or contribute under different terms and conditions than what is established/assumed in the open source software project, it is important to be clear and explicit about such reservations. A suggestion is to reach out to the project owner or a maintainer to initiate a dialogue about a potential conditional contribution before making the contribution.

### Compliance with laws and regulations

Apart from what is stated above, participation in an open source software project – depending on its nature – may trigger various regulatory considerations. This is not unique to open source software projects as such, but nevertheless important to keep in mind.

* For instance, competitor representatives may interact in steering committees or other forums of an open source software project, which entails competition/antitrust law considerations.

* In any context where representatives from actual or potential competitors are participating, it is advisable to avoid any sharing of commercially sensitive information and to have customary mechanisms to remind and record diligence with applicable competition/antitrust law regimes.

* Larger open source software projects and/or Open Source Foundations may have their own antitrust guidelines.  Many companies will also have their own policies in respect of competition law compliance. Contributors should ensure awareness of such guidelines and policies and assess whether they require any particular actions or precautions for the intended engagement.

* Moreover, the technology in itself – or its distribution – may be regulated, for instance under export control regulation (although published open source software is often exempted) or specific product or technology legislation. Involve relevant experts as necessary in cases of uncertainty whether specific code or documentation can be shared in an open source software context and/or if it requires specific measures, such as BIS and NSA notifications for non-standard cryptography software.  Certain technology fields may also in various jurisdictions be subject to special regulation.
