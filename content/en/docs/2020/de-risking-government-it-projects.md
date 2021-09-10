---
title: "De-risking government IT projects"
subtitle: "Sample challenge function questions"
description: "The GC Digital Standards provide a useful framing for challenge questions, applicable to online services, back-office systems, and IT projects in general. This guide is adapted from questions developed originally by 18F."
date: 2020-02-28
datePublished: 2021-08-10
author: "Lucas Cherkewski"
draft: false
---

_Guide developed by the [Canadian Digital Service](https://digital.canada.ca/)_

The [GC Digital Standards](https://www.canada.ca/en/government/system/digital-government/government-canada-digital-standards.html) provide a useful framing for challenge questions, applicable to online services, back-office systems, and IT projects in general. Other useful reference documents include [18F’s “De-risking government technology” guide](https://derisking-guide.18f.gov/) and the [US DOD DIB Guide: Detecting Agile BS](https://media.defense.gov/2018/Oct/09/2002049591/-1/-1/0/DIB_DETECTING_AGILE_BS_2018.10.05.PDF).

This guide is adapted from questions developed originally by 18F. We also suggest the list of aligned and non-aligned behaviors developed by the Digital Change Sector of the Office of the Chief Information Officer “[Digital Standards In-Flight Check-in](https://docs.google.com/document/d/14pOf4rkhmlY0-DDQQGSgc3oLd4A6nZsbraFpRozC1k4/edit)” (currently being finalized).

Many of these questions may be similar to ones already asked through the challenge function process. The goal of this document is to clarify which answers might be causes for concern (increasing risk) or good signs (mitigating risk).


## Design with users

1. **What is the user need?**
    * Causes for concern: Anything that doesn’t name clear needs of end users identified via design research. Initiatives responding largely to “business needs”, without a clear picture of how end users will benefit.
    * Good signs: The department has determined specific needs based on direct interviews, surveys or other feedback with end users (members of the public who would use the service – not public servants acting like members of the public), and can name several of those needs specifically.
    * Note: for public-facing services (or IT projects that will affect the public), “user needs” should include needs of members of the public; because most systems affect public servants, “user needs” should include their needs, too; [needs differ from “business requirements”](https://cds-snc.github.io/design-research-handbook/design-research-biz-reqs/), focusing on what people _need to do_, not _how they might do it_.
2. **What clear, measurable, short- and medium-term outcomes are proposed for the people who will use the service (or project supporting a service)?**
    * Causes for concern: Anything technical in nature, instead of about improving the user experience. Goals related to technical implementation rather than outcomes that benefit end users.
    * Good signs: One or more specific outcomes directly related to user needs are named.
3. **Who are your ultimate users, and how will you gather and incorporate feedback from them before the first small-scale, pilot release? How frequently will you conduct design research and usability testing with them?**
    * Causes for concern: “We’ve consulted with stakeholders to develop the requirements.” “The project requirements are already established.” “We’ll test with internal staff.”
    * Good signs: The team can identify different groups of people who will use their initiative, including the public and public servants, with approximate numbers for each. The team has clear plans for design research and usability testing with end users, with a timeline and processes to continuously integrate feedback into the development of the system or service.
4. **How will success be measured, and how frequently? Is measurement focused on outcomes for users instead of compliance? How will you gather data to assess this? Will performance data be made available publicly?**
    * Causes for concern: “Success is completing this project because it was in our annual investment plan.” “Our success metrics are being within a close percentage of our originally-planned budget and timelines.”  “We can’t collect performance data for privacy reasons.”
    * Good signs: One or more specific metrics based on users’ experience of the service, connected to user needs, with clear steps for gathering these (for example: web analytics, completion rates and online channel adoption, feedback form responses, an intake process for call centre or in-person staff to pass along user feedback). Plans for how performance data will be publicly published in a real-time or frequently-updated way.


## Iterate and improve frequently

5. **Is this project’s size and scale likely to be achievable? How much will this cost, how was that costing determined?**
    * Causes for concern: “It matches our budget allocation.” “The budget was determined several years ago.”
    * Good signs: “It’s smaller than $20M.” “It will be operational in months, not years.” “We’ve broken a large project into several smaller ones.”
    * Notes: These questions are likely very similar to ones already posed through the challenge function. The emphasis here is on the idea of scoping projects smaller than is often the case for IT initiatives, encouraging departments to focus on delivering concrete value sooner than later, better managing spending in the process.
6. **How long will it take from the start of the project until improvements are initially visible and usable by the public? How frequently will changes be delivered to people using the systems?**
    * Causes for concern: “When the project is fully finished.” “All at the end.” “More than 6 months from now.”
    * Good signs: “Within the next 6 months.” “Continually starting on X date as individual pieces of the project are completed.” 
7. **Does the department have a plan to have the right, multidisciplinary mix of talent needed to develop and implement the initiative? Will those teams remain in place on an ongoing basis to sustainably support the service?**
    * Causes for concern: “We have staff assigned to the project for the development period only.” “We have a dedicated project team, but the software developers are on short-term rotations from the central IT group.” “Once the project is completed, no further changes will be needed or made.” “We’ll engage an external vendor to make future changes as needed.”
    * Good signs: “We have a multidisciplinary team in place that is fully assigned to the project, including design and software development staff.” “Our proposal includes ongoing funding for a dedicated team, rather than time-bound project funding.”
    * Notes: This can be a shift from conventional thinking, which views IT projects as capital assets with significant upfront investment followed by gradual depreciation. This depreciation, coupled with drawn-out timelines for subsequent improvements, causes major issues (e.g., slow to respond to critical errors, inability to implement new policy direction, accretion of legacy systems, and so on). The perspective offered here is one of sustainability, emphasizing the need for ongoing attention (in the form of a dedicated team, whose size and shape might change over time). This can avoid significant replacement costs down the line.
8. **Are there pre-set requirements for how the system will operate? If so, how many requirements are included?**
    * Causes for concern: “We’ve spent the past year reviewing our business requirements, and we’ve written hundreds of requirements into the project proposal (or TB submission, project brief, etc), to ensure that we get exactly what we need.”
    * Good signs: “We’re more focused on the outcomes we want from the new system. We’ve developed a backlog of user stories (connecting a user need to something a user would do with the system) to help guide the team’s work, rather than producing a detailed list of technical requirements.”


## Empower staff to deliver better services

9. **Has a single, empowered business owner who is accountable for the project been clearly identified?**
    * Causes for concern: “Responsibility for the project is shared between several senior executives (or departments).” “The project is accountable to several executives (a committee).” “This executive is the business owner, and this (other) executive is the technical owner.”
    * Good signs: A specific senior executive (with spending and hiring authorities) is identified to be accountable for achieving the intended outcomes of the project. That executive can hire technical staff (e.g., CS, IS, etc) to form multidisciplinary teams.
10. **How will the project team learn from front-line and operational staff in the design of the project?**
    * Causes for concern: “Management from operational branches are involved in the project design.” “We sent a survey to front-line staff to gather their feedback.” “Making changes to operational processes is outside the scope of this project.”
    * Good signs: “We’re conducting design research alongside front-line staff to understand their operational realities.” “We’re authorized to change business processes to empower front-line staff and improve their experience interacting with the service.”
11. **How many technologists (designers, design researchers, software developers, or product managers) are directly involved in the planning and execution of the project? **(Note: this total should exclude traditional project managers, business analysts, and oversight roles.)
    * Causes for concern: “None.” “The project has been fully planned by our business, policy, or program units.” 
    * Good signs: “We have a multidisciplinary team including technologists that is empowered to define the project’s direction and to course-correct as needed.”
12. **Will the majority of resources assigned to this project be dedicated to delivery work? What proportion of the funding will be used for “watching” (managing, generating documentation like project reports, presenting updates, assessing compliance, etc) vs “doing” (designing interfaces, writing code, researching with users, etc)?**
    * Causes for concern: “More than 25% of our resources are assigned to project planning, compliance, and oversight work.”
    * Good signs: “Our team is empowered to make decisions directly, based on feedback from users.” “We’ve exempted the project from our traditional oversight committees and procedures.”
    * Note: A significant contingent of planning, compliance, and oversight staff is a natural response to the significant reporting burden put on departmental teams. One approach to encourage “doing” would be to reduce this burden by asking for “demos, not memos” – teams responsible for software initiatives should demo that software directly, instead of writing lengthy reports about their progress. If written status updates are required (e.g., due to legal or policy requirements, or to create a “paper trail”), they should be brief, with links or instructions for how to access the software itself.


## Work in the open by default & use open standards and solutions

13. **Who will own any custom software developed through this project? Who will be able to modify the software?**
    * Causes for concern: “The vendor.”
    * Good signs: “The Government of Canada” or “it will be published under an approved open source license.”
14. **Will this project use any proprietary software? How will you avoid vendor lock-in?**
    * Causes for concern: “We use proprietary software from our department’s preferred vendors.” “We’re using an existing Enterprise Agreement to procure software for this project.”
    * Good signs: “No.” “Yes, but only where needed to connect to existing legacy systems.” “Yes, but with the ability to fully export all data contained by the proprietary software.”
15. **Will there be ongoing licensing costs for custom or proprietary software from vendors? If so, how long will the contract for such licenses run?**
    * Causes for concern: “The licensing contract runs longer than three years.”
    * Good signs: “Yes, but the licenses are in one-year increments, with no lock-in. We’re working to replace the proprietary software and will stop renewing it once we have an open source solution in place.”


## Address security and privacy risks

16. **How frequently does your department typically update its existing services? How quickly could it publish fixes to software bugs or security vulnerabilities?**
    * Causes for concern: “1-2 times per quarter.” “Only when needed.”
    * Good signs: “5-10 times per month (or more).” “We use a continuous integration pipeline.” “We have automated monitoring systems.”
    * Note: Update frequency is a good indicator of a department’s ability to respond to fast moving security threats, to incorporate findings from research with end users, and more.


## Build in accessibility from the start

17. **How will you ensure that the software you build or procure meets government accessibility requirements?**
    * Causes for concern: “We’ll make accessibility improvements once purchased.” “The software already meets accessibility requirements, so we don’t need to do any more testing.” “Our use-case doesn’t need to meet accessibility requirements.”
    * Good signs: “We have a plan to test the software with users of accessibility tools (for example, through SSC’s AAACT program).” “We have a team dedicated to making continued improvements to the software, once launched.” “We’ve included fully meeting WCAG 2.1 AA as a mandatory requirement in our RFP documents.” “We have a publicly-available Accessibility Statement detailing how we respond to and address accessibility concerns.”

---

## Indicators of effective delivery

There are certain behaviours that indicate a program is delivering software in a reliable, effective way. Generally speaking, you should be able to, regularly:

* use a demo
* sit in on a research/usability testing session conducted with people who actually use the software
* see changes being committed to code, in the open (e.g., on GitHub, GitLab, etc.)
* join a planning or review session

If a program can accommodate your doing those four activities on a regular basis, it’s likely delivering software reliably.

---

Questions? Contact: [lucas.cherkewski@tbs-sct.gc.ca](mailto:lucas.cherkewski@tbs-sct.gc.ca) or [cds-snc@tbs-sct.gc.ca](mailto:cds-snc@tbs-sct.gc.ca)
