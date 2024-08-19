# Archetypes for Research OSS Projects

*"OS" doesn't stand for "One Size"*

*Last update: June 12, 2024*

This project presents a framework and guidelines for the many ways of doing OSS in science.

## Why and when to use this framework

We heard from a lot of teams developing OSS Scientific software that it can be difficult to understand what “true open source” means for different kinds of projects, and that it can be overwhelming trying to prioritize all of the OSS “best practices,” especially when these may not be aligned with their broader strategic goals.

We set out to create a set of resources to help project developers and teams:
- Understand different models of open source projects
- Identify which of these models is most appropriate for achieving their project’s goals
- Prioritize the most important open source best practices with tailored recommendations based on their archetype

This project/framework contains three main files:
- This README, which includes a [quickstart guide](#quickstart-how-to-use-this-framework)
- A table of [archetypes](/archetypes.md), describing models of OSS development
- A [Minimum standards of care](/min-standard-care.md) guide

We encourage you to use this framework early and often – projects may transition between archetypes as they move through different stages of maturity.

## Quickstart: How to use this framework

### 1. The basics: Minimum standards of care

First, take a look at the [Minimum standards of care](/min-standard-care.md) guide. This guide describes the most important foundational open practices that we think all projects should incorporate first, before attending to archetype-specific practices. If there’s still work to be done there, focus on those items first, and come back to this guide when you’re ready.

### 2. Identify your project’s archetype(s)

There are two suggested starting points for identifying your project’s archetypes. With either path, there are a few things to keep in mind:
- Some projects with separable components (e.g., frontend, backend, pipelines, database; core package with plugins; etc) may find that different components are best described by different open source archetypes. 
- A project’s archetype may change over time as it matures or resources change
- These are **archetypes** of projects, meaning there may be some cells in the table where your project differs from its closest archetype. That’s okay! Part of this exercise is to identify those gaps and consider thoughtfully why those gaps are either important to keep or important to address. 

#### Starting Point A: Start from your strategic goals and work backwards

**While any project can start from here, it may be most helpful for new-ish projects just getting started.**

Reflect on the big picture of what you want to achieve with your project. Look through the rows labeled *Starting Point A* to identify project archetypes that are most closely aligned with your goals. Then, consider the other attribute rows – especially those labeled *Starting Point B* – in the table to identify which of these is the closest fit. With this approach in particular, you may find that the archetype(s) that most closely match your goals are different from the archetype(s) that match your practices or other project characteristics. This is informative! Make a note of both of these, and we’ll make a plan in the next step.

#### Starting Point B: Start from your team structure and work forwards

**While any project can start from here, this starting point may be especially helpful for projects with some momentum which are ready to think about long-term sustainability.**

Two of the defining characteristics of an open source project are who is invited to make decisions, and who is invited to directly contribute to the codebase. Take a look at the rows labeled *Starting Point B* to identify project archetype(s) that reflect how you work **in practice** (e.g., while any open source project could technically have a PR sent in from an external contributor, it’s important to consider whether you’re actually likely to invite or incorporate outside work.). Then take a look at the other attribute rows – especially that labeled *Starting Point A* –in the table to identify which of these is the closest fit. You may find that the archetype(s) that most closely match your goals are different from the archetype(s) that match your practices or other project characteristics. This is informative! Make a note of both of these, and we’ll make a plan in the next step.

*Not all open source projects have to be open to contributions! However, it is important to communicate this appropriately and ensure your code is redeployable if someone wants to fork your project (for more, see the [Minimum Standards of Care](/min-standard-care.md) guide).*

### 3. Finally, make a plan for growth

1. Use the [OSS Needs Assessment](https://internews.org/areas-of-expertise/global-tech/resources/open-source-software-lightweight-needs-assessment/) to take inventory of your current open source practices
- There are truly no wrong answers; a “higher” score on this assessment doesn’t always mean better!
- What we care about is alignment between your strategic goals and your OSS practices.
- Pay special attention to the factors listed in the ‘most important OSS practices’ row for your project’s archetype

2. Make a plan for growth
- Based on your self assessment and the key practices for your archetypes, consider where there are gaps between your goals & your practices. 
- Make a plan with small, meaningful, achievable steps to bring your project’s practices into better alignment with your goals.

## Quick links

- [OSS Needs Assessment](https://internews.org/areas-of-expertise/global-tech/resources/open-source-software-lightweight-needs-assessment/) from Internews, which is aligned with the “most important practices” guidelines in the [archetype table](/archetypes.md).

- [Minimum standards of care](/min-standard-care.md): Guide to the most foundational open practices that we think all projects should incorporate first, before attending to archetype-specific practices

- [Mozilla Open Source Archetypes’](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf): an earlier set of archetypes, on which this project is built.

- **[WIP] Discussion guide for workshop facilitators**: For existing projects, it can be daunting to try and define or re-evaluate your open source strategy. We created a workshop discussion guide to walk you through key questions to consider in setting your open source goals and making a manageable, stepwise plan toward them.

## Project status, governance, and contributions

This framework was developed by members of the Open Source Software Working Group within [CZ Science](https://chanzuckerberg.com/science/) at [Chan Zuckerberg Initiative](https://chanzuckerberg.com/). We put this together in response to internal needs, and chose to share it publicly as a resource for others, too!

Authors:
- Sidney Bell ([@sidneymbell](https://github.com/sidneymbell))
- Kate Hertweck ([@k8hertweck](https://github.com/k8hertweck))
- Justin Kiggins ([@neuromusic](https://github.com/neuromusic))
- Kirsty Ewing ([@KirstyEwing](https://github.com/KirstyEwing))
- Justine Larsen ([@justinelarsen](https://github.com/justinelarsen))

We are happy to receive feedback and contributions to this framework. You are welcome to interact with us through [issues]([url](https://github.com/chanzuckerberg/oss-archetypes/issues)) or via email at [sci-opensource-wg@chanzuckerberg.com](mailto:sci-opensource-wg@chanzuckerberg.com).

If you would like to contribute via a pull request, please fork the repo to create the necessary changes.

## License

[![CC BY-SA](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/legalcode.en)

This project is licensed under CC BY-SA, per the requirements of the [Mozilla Open Source Archetypes’](https://blog.mozilla.org/wp-content/uploads/2018/05/MZOTS_OS_Archetypes_report_ext_scr.pdf) license.

## Code of Conduct

[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-baaaa.svg)](CODE_OF_CONDUCT.md)

This project adheres to the Contributor Covenant [code of conduct](https://github.com/chanzuckerberg/.github/blob/master/CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [opensource@chanzuckerberg.com](mailto:opensource@chanzuckerberg.com).
For more information on the Contributor Covenant,
please [visit their website](https://www.contributor-covenant.org/).

## Reporting Security Issues

If you believe you have found a security issue, please responsibly disclose by contacting us at [security@chanzuckerberg.com](mailto:security@chanzuckerberg.com).
