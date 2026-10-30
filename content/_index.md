---
title: ''
summary: ''
type: landing

sections:
  # ── Block 0: Splash (custom block, layouts/_partials/hbx/blocks/splash) ──
  - block: splash
    id: splash
    content:
      username: me
      title: 'Michael M. Schulreich'
      subtitle: 'Astrophysicist'
    design:
      spacing:
        padding: ['0', '0', '0', '0']
      background:
        image:
          filename: splashscreen.jpg
          size: cover
          # focal point on the person: keeps him in frame on narrow (phone) screens
          position: '22% 40%'
          parallax: false

  # ── Block 1: About (custom block, layouts/_partials/hbx/blocks/about) ──
  # bio, interests, positions & education are read from data/authors/me.yaml
  - block: about
    id: about
    content:
      username: me
      title: About
      image: about.jpg
      image_alt: Michael M. Schulreich at a blackboard with the equations of hydrodynamics
      interests_title: Research interests
      show_tools: true           # "Software & tools" (data/authors/me.yaml → tools); false to hide
      tools_title: Software & tools
    design:
      date_format: 'Jan 2006'

  # ── Block 2: Selected publications (custom block; featured: true in content/publications/*) ──
  - block: pubcards
    id: publications
    content:
      title: Selected publications
      count: 9
      archive:
        text: All publications
        link: publications/

  # ── Block 3: Projects ────────────────────────────────────────────────
  - block: projects
    id: projects
    content:
      title: Projects
      items:
        - name: ORION
          subtitle: Origins of Radionuclides In Our Neighborhood
          meta: FWF Principal Investigator Project · University of Vienna · 2027–2031
          logo: projects/orion-logo.jpg
          text: Which supernovae shaped the Sun's cosmic neighborhood — the Local Bubble and the superbubbles around it — and when did their debris reach the Earth? ORION combines 3D magnetohydrodynamic simulations of interacting superbubbles with *Gaia*-based reconstructions of nearby star clusters to explain the live radionuclides found on Earth and the Moon.
          # shown from the RELIC submission on (needs a rebuild after that date)
          text_extra: The open-source framework RELIC reconstructs the underlying supernova histories.
          text_extra_date: 2027-02-01
          link: orion/
          link_text: Project page
          funder_logo: projects/fwf-logo.svg

  # ── Block 4: Recent & upcoming talks (data/talks.yaml) ──────────────
  - block: talks
    id: talks
    content:
      title: Recent & upcoming talks
      mode: recent
      count: 5
      archive:
        text: All talks
        link: talks/

  # ── Block 5: Teaching (data/teaching.yaml) ───────────────────────────
  - block: teaching
    id: teaching
    content:
      title: Teaching
      intro: Graduate-level lectures, lab courses, and seminars at TU/FU Berlin, and supervision of Bachelor's, Master's, and PhD theses.

  # ── Academic service (data/service.yaml) ─────────────────────────────
  - block: service
    id: service
    content:
      title: Academic service

  # ── Block 6: Outreach ────────────────────────────────────────────────
  - block: outreach
    id: outreach
    content:
      title: Outreach
      image: outreach.jpg
      image_alt: Michael M. Schulreich explaining planetary scales with a model during a public lecture
      text: Sharing how the cosmos around us works — and how we can read its history in atoms on Earth — is part of my work.
      items:
        - when: Current
          title: 'Planetarium show *Encounters in the Milky Way*'
          url: https://www.amnh.org/exhibitions/space-show
          text: Scientific consulting and quantitative modeling for the fulldome space show at the Hayden Planetarium of the American Museum of Natural History, New York, whose Local Bubble segment is based on my simulations.
        - when: 2024
          title: Public talks
          text: Long Night of Science, Berlin (Jun 22) · [37th University Days of Physics — New Findings in Astronomy](https://www.uni-marburg.de/de/fb13/news/hochschultage-physik/hochschultage-2024), Marburg (Feb 15–16)
        - when: 2009–2025
          title: Outreach at TU Berlin
          text: Long Nights of Science, Girls' Days, information days for school students, and career fairs; responsible for public inquiries at the Zentrum für Astronomie und Astrophysik (2016–2025).
      media_title: Watch
      media:
        - kind: video
          src: media/amnh-local-bubble.mp4
          poster: amnh-poster.jpg
          title: 'Local Bubble formation sequence from *Encounters in the Milky Way*'
          source: Hayden Planetarium space show · © American Museum of Natural History
        - kind: youtube
          id: tTkFsxQmdzU
          title: 'Wir leben in einer Blase – Geheimnisse des kosmischen Staubs'
          source: Public lecture (German) · Urknall, Weltall und das Leben · 2024
          url: https://www.youtube.com/watch?v=tTkFsxQmdzU
        - kind: youtube
          id: FKT84xH7Hhk
          title: The supernova link between the Local Bubble and deep-sea radioisotopes
          source: Invited seminar · IAU Commission H1 "The Local Universe" · 2023
          url: https://www.youtube.com/watch?v=FKT84xH7Hhk

  # ── Block 7: Contact ─────────────────────────────────────────────────
  - block: contact
    id: contact
    content:
      title: Contact
      text: Questions about my research, collaborations, or the ORION project are welcome.
      email: michael.schulreich@univie.ac.at
      address:
        - Department of Astrophysics
        - University of Vienna
        - Türkenschanzstraße 17
        - 1180 Vienna, Austria
---
