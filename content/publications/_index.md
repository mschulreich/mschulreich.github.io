---
title: Publications
type: landing
description: "Publications by Michael Schulreich: refereed journal articles, conference proceedings, and theses on superbubbles, the Local Bubble, and live radionuclides."
# Generated from SciX/ADS (author:"Schulreich, M"); one folder per publication.

sections:
  - block: markdown
    id: publications
    content:
      title: Publications
      text: |-
        Complete list of my publications. Up-to-date records and citation metrics are available on
        [SciX/ADS](https://scixplorer.org/search?p=1&q=author%3A%22schulreich%2C+m%22&sort=date+desc&d=general)
        and [ORCID](https://orcid.org/0000-0001-7761-9766).
    design:
      spacing:
        padding: ['7rem', '0', '1rem', '0']

  # custom block: shows nothing while there is no submitted manuscript
  - block: pubgroup
    id: submitted
    content:
      title: Submitted
      publication_type: manuscript

  - block: collection
    id: journal
    content:
      title: Refereed journal articles
      count: 0
      filters:
        folders: [publications]
        publication_type: article-journal
    design:
      view: citation

  - block: collection
    id: conference
    content:
      title: Conference contributions
      count: 0
      filters:
        folders: [publications]
        publication_type: paper-conference
    design:
      view: citation

  - block: collection
    id: white-papers
    content:
      title: White papers
      count: 0
      filters:
        folders: [publications]
        publication_type: report
    design:
      view: citation

  - block: collection
    id: thesis
    content:
      title: Thesis
      count: 0
      filters:
        folders: [publications]
        publication_type: thesis
    design:
      view: citation
---
