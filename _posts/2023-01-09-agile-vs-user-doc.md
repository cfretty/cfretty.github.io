---
title: Agile vs user doc
date: 2023-01-09 08:00:00 -0600
categories: [Technical Writing]
tags: [agile,agile manifesto,software development,user documentation,work]  # TAG names should always be lowercase
#image:  https://chirpy.cotes.page/posts/write-a-new-post/#preview-image
#  path: 
#  alt:  
---
<!-- excerpt -->
*When software development teams adopt agile methodologies, new conflicts can arise between the dev and doc teams. This is a post I wrote at my former job when a development team told their technical writers that they no longer had time for documentation.*

![blank open book](/assets/img/doc.jpg){: w="400" h=" "}
_Photo by [Brando Makes Branding](https://unsplash.com/pt-br/@brandomakesbranding?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/images/things/book?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)_
  
Agile development methodology is not anti-documentation. When discussing Agile and documentation, it is common to get hung up on the Agile Manifesto's software over doc value:

>**Individuals and interactions** over processes and tools <br>
:point_right: **Working software** over comprehensive documentation :point_left: <br>
>**Customer collaboration** over contract negotiation <br>
>**Responding to change** over following a plan

A couple of points:
- "Documentation" is documentation in the broadest sense, including traditional internal development deliverables such as Systems Requirements, Systems Design, Vision and Scope, use cases, schemas, work-flow diagrams, Rational Unified Process artifacts, and so on. Do not confuse with user documentation.
- The very next line of the manifesto is: "...While there is value in the items on the right, we value the items on the left more." In other words, there is value in comprehensive doc. Do not eliminate all documentation. Instead, it's more like: what’s the least amount of deliverable that we need right now.

Teams will interpret this value and execute any number of ways, but here are some ideas: 
- Deliver working software first, comprehensive user documentation later. Deliver in later cycles, just in time, and iteratively. Assume the correct time for the user doc is later than "in active development." Add docs as a feature request and prioritize the backlog.
- Ensure at a minimum there are user stories in place. This is can be the base for internal and customer-facing doc.

Questions and comments for teams having the "working software over comprehensive documentation" discussion: 
- Doc team, are we embracing agile values and principles? No one adopting agile will listen if you reject these values and principles outright. Are we figuring out ways to work faster, smaller, and iteratively? Can we learn how to work with slimmed down, "just barely good enough" and "just in time" internal doc/info/artifacts? That may mean evaluating and letting go of processes, deliverables, schedules, and so on that no longer serve us. 
- Dev team, how does providing the resources necessary to create quality user documentation, for example, internal artifacts or developer/BA/QA time, impede the "working software" side?
- Docs team, what is the minimal viable deliverable we need from dev to do our work? What do we need? When do we need it? Who creates it (BA, Product Management, or ?)? 
- Dev and Docs team, can we agree on what makes up "just barely good enough" and "just in time" artifacts for stakeholders?
- Dev team, remember principle 1: "Our highest priority is to satisfy the customer through early and continuous delivery of valuable software." If the customer expects user documentation or does not KNOW about the value (functionality) the software delivers, are we truly satisfying the customer and thus meeting our highest priority? 
- All team members, consider principle 12: "At regular intervals, the team reflects on how to become more effective, then tunes and adjusts its behavior accordingly."

## References
[Agile Manifesto](https://agilemanifesto.org/){:target="_blank" rel="noopener"}

[Nuclino "Agile Development Methodology and Documentation:
To document or not to document?"](https://www.nuclino.com/articles/agile-documentation){:target="_blank" rel="noopener"}

[DITA Strategies "IA Design and Agile Development: Mission (Im)possible!" by Amber Swope](https://www.ditastrategies.com/media/ia-design-and-agile-development-mission-impossible){:target="_blank" rel="noopener"}