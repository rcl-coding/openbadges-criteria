# Introduction

## The objective of the Coding Skills Foundation is to facilitate the recognition of a person's achievement of coding skills outside the formal education and training system.

### View Available Criteria

You can view the [available criteria here](/openbadges-criteria/criteria/current-criteria.html).

### Open Badges Specifications

We hope to foster a truly open system where badge issuers, learners and employers create an environment of mutual trust for recognition of coding skills.

To this end, we have adopted the [Open Badges V2.0 Specification](https://www.imsglobal.org/sites/default/files/Badges/OBv2p0Final/index.html) published by the [ IMS Global Learning Consortium](https://www.imsglobal.org/).

### Criteria for OpenBadges

The criteria for obtaining an open badge lists the knowledge , skills and requirements that a learner must demonstrate to be awarded the badge.

### Structure for a Criteria 

The criteria is an html file hosted at a publicly accessible endpoint.

The criteria must contain :
- Title (required) - title of the criteria
- Level (required) - the level of the criteria (foundation, intermediate, advanced)
- Version (required) - the version number of the criteria (eg: V 1.0)
- Code (required) - a unique identification code for the criteria 
- Skills (required) - the skills that a learner must demonstrate to achieve the badge
- Knowledge (required) - the knowledge that a learner must apply to achieve the badge
- Requirements (required) - A description of the task or activities that the learner must demonstrate
- Range (optional) - The range of situations that the learner must demonstrate  skill and/or knowledge

### Contributing to Criteria

Anyone with a coding skill can contribute to a creating a new criteria or recommending revisions to an existing criteria. This project accepts contributions via GitHub Pull Requests (PRs). The following outlines the process to help get your contribution accepted.

**Contributing**

- You need a basic understanding of Git and GitHub.com.
- Open an [issue](https://github.com/rcl-coding/openbadges-criteria/issues) describing what you want to do, such as changing an existing criteria or creating a new one. Wait for approval before you invest much time.
- Fork the [rcl-coding/openbadges-criteria](https://github.com/rcl-coding/openbadges-criteria) master repo and create a branch for your changes. Name the branch 'recommendations'.
- Make changes to an existing criteria or create a new criteria following the instructions below
- Submit a Pull Request (PR) to master with your changes.
- Respond to PR feedback.

**Recommend changes to an existing criteria**

- In your forked branch, open the criteria from the 'criteria' folder. Make your changes in Markdown.

**Create a new criteria**
- In your forked branch, open the criteria folder.
- Create a new Markdown file for the new criteria (eg: csharp-foundation.md)
- Create your criteria and ensure you comply with the structure for a criteria as explained above
- Add metadata (title, parent, nav_order) to your markdown file to establish proper navigation to your new criteria

**Sample Criteria File**
```markdown

---
title: CS-001 Programming with C-Sharp
parent: Criteria
has_children: false
nav_order: 1
description: Programming with C-Sharp - Foundation
---

# Title: Programming with C-Sharp
## Level: Foundation
## Version: V 1.0
## Code: CS-001

## Skills :

#### To achieve this badge the learner must :

- Write C# code using **types**
- Write C# code using **statements**

## Knowledge :

#### To achieve this badge the learner must know and understand :
- Types : string, int, long, bool, DateTime 
- Statements : if-else, do-while, for loop, arrays, foreach loop

## Requirements

#### To achieve this badge the learner must create:
- At least three (3) C# .NET Standard console applications demonstrating all the skill and knowledge requirements identified above

```
