# Establishing a “minimum standard of care” for open source scientific software

*Last update: June 12, 2024*

This is a companion document to the OS Scientific Software Project Archetypes framework, which aims to provide tailored recommendations to help OSS research software developers and teams align their OSS practices with their project’s goals. Once the items below have been taken care of, hop over there for more specific guidance.

This document is meant to outline the “table stakes” practices needed to work in the open. 

**Note that we do not cover engineering best practices here as there are many references available; this document is focused on communicating with the external community and, when relevant, creating an architecture of participation.**

## Minimum standards of care

- The README and/or main landing page of the project clearly states the following:
    - The maintenance status of the project
    - How decisions are made, and by whom (i.e., governance). Is this only the founding / internal team? Is this a formal governing committee? Is this a wide open democratic project?
    - Who contributes code to the project? Is this only the founding / internal team, or are external contributions welcome? If external contributors are accepted and/or encouraged, see the additional requirements below. 
- The project can be redeployed by someone outside of the project’s home institution. This will be a bigger lift for some project archetypes (e.g., a scientific platform) than others (e.g., a scientific library). 

For projects where external contributions are an important part of their current development and/or long-term sustainability plan, the following are also required:
- Contributor guidelines, including an easy onramp
- A public-facing, high-level roadmap
- A plan for providing support to contributors

## Example language

Example statements for each of the main categories include:
- **Maintenance status**
    - This project is unmaintained. Source code is available for transparency, repurposing, and archival purposes.
    - This project is being actively developed, but not supported. Things may break without notice, and it is not likely the developers will respond to requests for user support.
    - This project is being actively maintained. For bugs or feature requests, please submit an issue. For help using the project, please see the [documentation, wiki, and/or help forum].
- **How decisions are made**
    - [someone] is the project founder and operates as a benevolent dictator for all PRs. 
    - This project is funded by [some grant] with [someone] as the PI. Our current focus is meeting the deliverables associated with the funded work. 
    - Core Developers have permissions to approve contributions. Overall project priorities and direction is defined by the Steering Council with input from Core Developers and the community of users and contributors.
- **Who can contribute**
    - We are not accepting code contributions at this time. If you would like to report a bug, please file an issue.
    - Contributions are welcome. If you are interested in contributing, please review the contribution guidelines.

The following examples show how the pieces above can be compiled into a more complete narrative, with some including the additional requirements when external contributions are allowed. The examples below are provided in the context of relevant [archetypes](/archetypes.md):
- *Rocketship to the moon*: This is a prototype built by [some team]. We do not currently intend to maintain it long term, we expect lots of bugs, and we are not accepting code contributions or feature requests at this time.
- *Multi-institutional collaboration* (incubation of project): This package is actively maintained as a collaboration between [organization] and [institution]. Core developers [someone] and [someone] have final decision-making authority for all contributions. We welcome contributions that support the priorities in our [roadmap], as well as bug reports and feature requests. Documentation for contributors and users can be found at [handbook], but we are unable to provide additional user support beyond the members of the collaborating organizations.
- *Scientific Library*: This project is actively maintained by the [project name] community, led by the [project] steering council and core developers [links defining these groups]. Contributions are welcome. If you are interested in contributing, please review the contribution guidelines, which outlines our roadmap, how we make decisions, and processes for local development. Get started with issues marked “Good First Issue”.
- *Rocketship to Alpha Centauri*: This project is actively maintained by [organization] as a critical component of [project]. The roadmap, features, and technical decisions on the project are determined by the project maintainers at [organization]. We are not accepting code contributions or feature requests at this time. Feel free to fork or reuse any code herein. If you would like an opportunity to give feedback on [project], please sign up for a session [here]. 

More mature projects will likely have much more extensive documentation than the above, with robust documentation and forums for both forums and developers. For example:
- **Project Jupyter**: The [main project page](https://jupyter.org/) links to a variety of other resources describing the minimum standards described above: [About Us](https://jupyter.org/about) describes the project status and history, [governance](https://jupyter.org/governance/intro.html) identifies how decisions are made, and [Community](https://jupyter.org/community) describes how to get help (as a user or contributor).
- **napari**: The [main project page](https://napari.org/stable/index.html) links to other resources, including [Community](https://napari.org/stable/community/index.html) (e.g., about the project, governance) and [Contributing](https://napari.org/stable/developers/index.html) (separate guides for contributors and core developers).