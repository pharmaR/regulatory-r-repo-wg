# Regulatory R Package Repository

This document details the scope and initial short-term goals supporting the
creation of a cross-pharma regulatory package repository.

## How to get involved

- Reply to our ["sign up" thread](https://github.com/pharmaR/regulatory-r-repo-wg/issues/1)
  to be contacted about planning meetings.
- Sign up for the [R Validation Hub mailing list](https://www.pharmar.org/contact/)

## Scope

### In-Scope

In roughly the order in which tasks will be addressed, this work will include

- Feature scoping
- Exploration of feasibility
- Evaluation of compute hosting and execution options
- Evaluation of package repository hosting solutions
- Initial prototype implementation
- Enterprise stress testing and evaluation of technical capabilities
- Soliciting feedback from experts in R infrastructure and automation (`R-Hub`,
  `ROpenSci`, `CRAN`)
- Characterizing tradeoffs and making a recommendation based on evaluations

### Out-of-Scope

- Deciding on exact criteria required for qualification (this
  discussion is better had by the broader R Validation Hub)

## Milestones

```mermaid
gantt
    title Regulatory R Package Repository
    dateFormat  YYYY-QQ

    section  
    Team Assembling & Scoping  :m1, 2022-Q4,  90d
    Knowledge Gathering & POCs :m2, after m1, 90d
    Public Prototype Build     :m3, after m2, 180d
```

### Milestone 1 (Est. 3 Months)

The first milestone (projected three months) will be primarily focused around
building an initial core team and more thoroughly scoping the project

- [ ] Assemble a team with backgrounds spanning
  - R package development (specifically testing & builds)
  - Infrastructure & administration (containers, CI/CD, repository hosting)
  - Front end & API serving
- [ ] Itemize blocking uncertainties
- [ ] Scope & prioritize key deliverables
  - Specify technical objectives
  - Produce budget estimate for R Consortium Board if the initiative would 
    benefit from monetary funding (Deadline EOY 2022)

### Milestone 2 (Est. 3 Months)

The next milestone will focus on immediately actionable proofs of concepts and
knowledge gathering, leveraging existing experts in this space for guidance and
suggestions.

- [ ] For technical feasibility that can be assessed quickly, implement
  proofs-of-concept to demonstrate features.
- [ ] For open questions that require deeper expertise, solicit feedback from
  experts in this area, soliciting feedback from R Consortium and ROpenSci
  expertise for the evaluation of packages, hosting of build services and
  serving of package repositories.
- [ ] Decide on scope for a prototype

### Milestone 3 (Est. 6 Months)

The third milestone will focus on prototyping a system, with the goal of using
such a prototype as a public showcase of what such a solution could offer.
Cosmetics, UI/UX and performance are out of scope. An ideal outcome would be
that such a prototype could be used to foster more interest and endorsement of a
cross-industry solution. 

- [ ] Build a service for the evaluation of packages
- [ ] And the hosting or publishing of packages to a publically accessible R
  repository

## Ideation & Proposals

Initial ideation was proposed to the [R Consortium Repositories
WG](https://github.com/RConsortium/r-repositories-wg/blob/main/Documents/RValHub-Wishlist.md)
