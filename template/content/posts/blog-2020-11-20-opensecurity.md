---
date: 2020-12-02
description: "The Value of Open Security"
published_url: "/posts/blog-2020-11-20-opensecurity/"
title: "The Value of Open Security"
featured_image: "/images/community.jpg"
author: "Jason Keirstead"
publisher: "Open Cybersecurity Alliance"
summary: " We are at the pinnacle of innovation for security. Yet, Security leaders today are stressed with too much to do, too many security tools, too much complexity, too many alerts, and not enough skills. For the most part, we all have access to roughly the same types of technology.  The challenge is that the tools providing this technology, don’t talk to each other. The reasons why vary for every person and company – there is, however, one direction that the cybersecurity industry is starting to move in together to solve these challenges, and that direction is \"open\""
tag: "blog"
---
<h4 style="margin-left: 0.5em; margin-top:-1.5em">
- by <a href="https://www.linkedin.com/in/jasonkeirstead/">Jason Keirstead</a>
</h4>

<img style="text-align:center;display:block;width:100%;margin-bottom:2em;" src="/images/change.jpg"/>

Let me lay out a scenario for you. Forward leaning organizations are embracing change. They’re refactoring apps to become more modular, containerized, and are increasingly shifting to SaaS, in order to move fast and scale. They’re treating data as a shared resource between departments, partners, and communities; and using AI and analytics to find untapped value. They’re embracing hybrid cloud, to match the right workload to the right cloud environment for their business. 

However, this new world is bringing along with it a unique set of challenges. Public cloud, private cloud, traditional infrastructure - security and security tools are sprinkled everywhere. As a result, it is increasingly difficult to detect threats, investigate and remediate. The problem is exacerbated by there being too many vendors, and too much complexity - there are too many alerts and incidents to deal with - meanwhile, simultaneously, those incidents often lack context and intelligence, due to lack of seamless information flows across the overly complex ecosystem of vendors and tools.

This current state of the industry, is simply unsustainable long term. But how do we as a cybersecurity community address it?

## Learning from History

<img style="text-align:center;display:block;width:100%;margin-bottom:2em;" src="/images/designthink.jpg"/>

I believe that one place that we as an industry can look for inspiration, is to see how we can learn from other domains of information technology. Over the past two decades, most major innovations have evolved from an open approach that has fueled success in every major technology category - including operating systems ([Linux](https://www.kernel.org/), [Android](https://source.android.com/)), data ([Hadoop](https://hadoop.apache.org/), [MongoDB](https://github.com/mongodb/mongo), [Elasticsearch](https://github.com/elastic/elasticsearch)), technology management ([Docker](https://www.docker.com), [Kubernetes](https://kubernetes.io/)), and more. 

The evidence is indisputable - open technology is winning the day. But what of cybersecurity? 

Security is the next frontier when it comes to open. Of course, there are a handful of very popular [open-source security tools](https://www.oasis-open.org/projects-committees/?filter-technology=cybersec) and open source and [standards](https://www.oasis-open.org/standards/?filter-technology=cybersec) are currently the foundation for many key areas of cybersecurity around things like cryptography, identity management, etc. However, the adoption of “open” as the de-facto and mainstream development model in cybersecurity, is still very much in its infancy compared to other areas of the IT sector. 

## Why Open Security, and What Is Holding Us Back

<img style="text-align:center;display:block;width:100%;margin-bottom:2em;" src="/images/lock_fence.jpg"/>

The benefits that come from Open Security align around two key areas: 

**Trust & Transparency** – the fact that you can trust that the code, the solution, the practice, is doing what you expect it to do, when you expect it to, and that there are not hidden pitfalls to relying on that in your environment. This is enabled by increased collaboration and “the power of the crowd” being applied to cybersecurity.

**Speed & Awareness** – having near real-time access to the latest innovations and research as it is developed, allows you to speed time to value, which in this space means time to protection from the latest novel threats against your environment.

If Open Security can bring all of these benefits, then why does it continue to be such a laggard? Let's start with a basic premise - what security is at its core, is mitigation against fear and uncertainty. I am sure many here are aware of the [CIA triad](https://www.f5.com/labs/articles/education/what-is-the-cia-triad) - confidentiality, integrity, and availability. These three key attributes are supposed to define the object of cybersecurity practice - however, we have to highlight that the CIA triad is supposed to apply to data, **not** to the cybersecurity practice itself. There exists a fundamental tension in the cybersecurity space between core principles such as privacy of the individual, vs situational awareness of attacks, and collaboration around defensive posture, vs sharing our knowledge with adversaries. This tension is a good thing, and important. Unfortunately, the history of cybersecurity has led to the industry over-pivoting toward one extreme, where we worry more about protecting what we think is our "secret sauce", than collaborating across the industry.

## The Four Pillars of Open Security

<img style="text-align:center;display:block;width:100%;margin-bottom:2em;" src="/images/puzzle_pieces.jpg"/>

### Open Standards

[Standards are what make the world go around](https://www.nytimes.com/2019/02/16/opinion/sunday/standardization.html) and allow you to simply operate in daily modern life. Standards are what allow you perform a task as simple as plugging your newly purchased toaster oven into the wall and be assured that not only will the plug fit into the outlet, but that it won’t explode or catch on fire the first time you try to use it. In information technology, standards are what allow our systems to interoperate and communicate. This is not really new, and cybersecurity standards have existed for a long time. However, we are finding that as an industry we still have a way to go to make sure that the standards we create are both effortlessly consumable and workable for the end organization if they are to achieve the purpose they are meant to. A remarkable statistic to emphasize this point, is that according to an ESG study, organizations are spending as much money trying to get their security tools to work with each other, as they are on actual cybersecurity practices. This needs a lot of improvement.

### Open Source

[Open-source](https://opensource.org/faq#osd) code allows for more rapid research and innovation, as well as allows organizations to sometimes fill gaps in their toolset that the market has not yet filled. It would be false to presume that cost is the only driver in adopting open-source cybersecurity products. Open-source solutions for controlling security and privacy are increasingly gaining traction in the marketplace, occasionally to address existing commercial software gaps, but just as often to provide more open integrations. Organizations such as the [Open Cybersecurity Alliance](https://opencybersecurityalliance.org), are trying to use open source as a basis for improving the outcomes of standardization, by providing a common place that vendors and consumers can collaborate on open-source toolchains that, among other things, make standards work.

### Open Intelligence & Analytics collaboration. 

Vendors (as well as the community) have been building tools to better create, share, [collaborate on](https://www.nationalisacs.org/), and use cyber threat intelligence, as well as detections and analytics, for some time. These tools and data sets provide cross platform ways to express data as proprietary formats are too costly for enterprises to adopt and maintain. These trends will only accelerate, as any single defender or vendor will never be able to cover the entire threat landscape. 

While there is a marked improvement in sharing of some types of information – most notably threat intelligence – we still see that 66% of organizations are not even doing that, and that almost 50% of organizations outsource almost all of their threat intelligence. In the detection and analytics space, while there are pockets of encouraging community collaboration (such as the great work going on at the [Open Threat Research Forge](https://github.com/OTRF) and the [Sigma project](https://github.com/Neo23x0/sigma/tree/master/rules)), there is still a very, very long way to go in this area. It is still far too common today for organizations to develop the majority of their detections and analytics in individual silos with little to no collaboration, which results in the same work being duplicated over and over again across the industry, needlessly slowing our collective response to threats.

### Best Practices

The fourth pillar is best practices, which enable the best-of-breed solutions to be brought to bear in your environment, no matter what it’s size. Organizations that are able to leverage existing best practices tend to see a dramatic reduction in overall effort spent on their cybersecurity program. Best practice frameworks consist of guidelines and best practices to manage cybersecurity-related risk. The cost-effective approach helps to promote the protection and resilience of critical infrastructure and allows smaller organizations with finite resources to consume and deploy best practices curated by best of breed subject matter experts and practitioners. One of the most well-known promoters of best practices is the [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework), which consists of standards, guidelines, and best practices to manage cybersecurity-related risk. Another very important best practice framework would be the [CIS Controls](https://www.cisecurity.org/controls/). And finally, new standards such as [CACAO](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=cacao) are being created in order to allow you to collaborate on and consume industry best practice operations playbooks.

## The Common Thread - Community

<img style="text-align:center;display:block;width:100%;margin-bottom:2em;" src="/images/community.jpg"/>

What is the common thread among all of these pillars of Open Security? **Community**. Communities, combined with the previously discussed efforts, are what create the competitive advantage for Open Security. Otherwise known as the [“power of the crowd”](https://en.wikipedia.org/wiki/The_Wisdom_of_Crowds), the community is the unifying fabric of it all. As an industry, we have to learn how to lean into and embrace these community-driven models of standards, code, intelligence, analytics, and best practice. Only then will we be able to keep pace with, and hopefully get ahead of, emerging threats.

## Call to Action

The Open Cybersecurity Alliance is working tirelessly to advance the cause of Open Security, and we need your help. There are many ways you can [get involved at the OCA](https://opencybersecurityalliance.org/get-involved/). Maybe you are a developer who can help contribute to one of our several projects. Maybe you are a project manager who can help steward one of our several working groups. Maybe you are a subject matter expert who can contribute to our ongoing work around a unified cross-industry cybersecurity reference architecture. Maybe you want to [help guide the OCA mission itself as a sponsor](https://opencybersecurityalliance.org/sponsors/). Regardless of your current role, there is a place for you in the Open Cybersecurity Alliance. Come join us, and help us change the industry.


