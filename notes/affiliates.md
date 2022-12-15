# Our Affiliate Initiatives

There are a lot of related initiatives in the R infrastructure & cross-pharma
space aiming to deliver open solutions to health authority engagement. 

This document aims to outline some of these intiatives and help to outline the
overlap and differences between initiatives:

## [the R Consortium](https://www.r-consortium.org/)

> The central mission of the R Consortium is to work with and provide support to
> the R Foundation and to the key organizations developing, maintaining,
> distributing and using R software through the identification, development and
> implementation of infrastructure projects.

The R Consortium sponsors many working groups, such as the R Validation Hub. The
R Consortium represents general R community interests, which includes supporting
adoption of R in industry.

Noteable initiatives sponsored by the R Consortium that will be helpful partners
to help us tackle regulatory-ready package assessment and/or distribution
include:

- the [Submissions Working Group](https://github.com/RConsortium/submissions-wg)
- the [R Repositories Working Group](https://github.com/RConsortium/r-repositories-wg)

## [the R Validation Hub](https://www.pharmar.org/)


> The main challenge of using R in late-phase trials is ensuring validation
> documentation. In June 2018, the R-Consortium awarded funding to create an
> online repository for R package validation in accordance with regulatory
> standards.
>
> > R Validation Hub is a collaboration to support the adoption of R within a
> > biopharmaceutical regulatory setting

The R Validation Hub is our parent organization. We are one of multiple
initiatives that each support the grand vision of streamlining the use of R in
a regulated setting.

In the past this has involved endorsing a white paper that details how R might
be used in a regulated setting, building tools to support individual R package
evaluation, and offering an open forum for companies to share their approaches.

To further support this, the next phase of the R Validation Hub initiatives have
been focused on lifting these activities out of individual organizations and
into an open, shared context. This is where we come in!

## [`pharmaverse`](https://github.com/pharmaverse)

> A curated, opinionated, pharma stack of open source R packages to enable
> clinical reporting (from CRF to eSubmission) backed by a community of
> passionate individuals and organisations committed to co-creating efficiency
> in our mission to improve health.

In other words, a set of R packages to achieve common submission workflows.
Although these packages intend to meet a level of quality that would make them
suitable for developing submission analysis. 

## [Submissions Working Group](https://github.com/RConsortium/submissions-wg)

> The R submission working group is a cross industry pharma working group
> focusing on improving practices of R-based clinical trial regulatory
> submission.

The submissions working group has fostered close ties to health authority
representatives and runs periodic pilots to solicit feedback from health
authorities regarding focused R submission concerns in an open setting. 

In the past this has included such topics as:

- How to submit R packages, which rely on directory structures and file
  extensions not currently supported through the FDA's electronic submissions
  platform.
- Feedback on Shiny-based analysis dashboards as a resource for submission
  review

In the future, the Submissions Working Group might be a valuable resource to
deliver questions to health authorities regarding the usefulness of planned
deliverables.

| `us`               | `them`             |                                                                  |
| :-:                | :-:                | :--                                                              |
| :x:                | :heavy_check_mark: | Broad consideration for the entirety of the R delivery pipeline  |
| :heavy_check_mark: | :x:                | Focus on the distribution of packages                            |

## [R Repositories Working Group](https://github.com/RConsortium/r-repositories-wg)

> The goal of this working group is to collaboratively explore how to support,
> maintain, and improve the tooling for package distribution, particularly with
> an eye to meeting new needs (e.g. the demands of regulated submission as
> experienced by the pharma community) and making sure R is well poised to
> thrive for the next 20 years. 

The R Repositories Working Group has been focused on [understanding the CRAN
checks with the goal of improving
transparency](https://github.com/RConsortium/r-repositories-wg/blob/main/Documents/Proposal%20to%20CRAN.md).
Their remit includes shaping the R ecosystem to support spaces such as the
pharma community, which makes them a key partner.

More discussion is needed to understand whether this group intends to develop
infrastructure outside of CRAN. Wether on CRAN or not, If so, it will be our
responsibility to articulate the regulatory requirements that need to be met to
make such a repository actionalbe for regulatory use.
