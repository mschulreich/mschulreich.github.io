---
title: ORION — Origins of Radionuclides In Our Neighborhood
summary: FWF Principal Investigator Project at the University of Vienna (2027–2031) on the supernovae that shaped the solar neighborhood and left radioactive traces on Earth and the Moon.
type: landing

sections:
  - block: project
    id: orion
    content:
      key: orion                     # publications with `projects: [orion]` and talks with `project: orion` appear automatically
      logo: projects/orion-logo.jpg
      eyebrow: FWF Principal Investigator Project
      name: ORION
      longname: Origins of Radionuclides In Our Neighborhood
      facts:
        - label: Principal investigator
          value: Michael M. Schulreich
        - label: Host
          value: Department of Astrophysics, University of Vienna
        - label: Duration
          value: Feb 2027 – Jan 2031
        - label: Funding
          value: Austrian Science Fund (FWF), [10.55776/PAT1519826](https://doi.org/10.55776/PAT1519826)
      links:
        - text: Project outputs
          url: '#outputs'
        - text: FWF grant
          url: https://doi.org/10.55776/PAT1519826

      about_media:
        video: media/amnh-local-bubble.mp4
        poster: amnh-poster.jpg
        caption: 'Formation of the Local Bubble, based on my earlier simulations, as shown in the space show *Encounters in the Milky Way* at the Hayden Planetarium.<br>© American Museum of Natural History'
      about: |-
        Roughly 4.6 billion years ago, our Sun and Solar System were born and began a long journey around the center of the Milky Way. On this journey they pass through wildly different cosmic neighborhoods, from cold, dense star-forming clouds to vast, almost empty bubbles of hot gas. Today we live inside such a bubble: the **Local Bubble**, a cavity nearly a thousand light-years across, carved out by a series of supernova explosions over the past 10 to 15 million years.

        These explosions left a forensic record on Earth itself. Massive stars forge rare radioactive atoms such as <sup>60</sup>Fe and <sup>53</sup>Mn when they explode; even rarer ones such as <sup>244</sup>Pu come from collisions of neutron stars. Carried through space on tiny dust grains, these atoms settle onto the deep ocean floor, into lunar soil, and into Antarctic snow and ice — and reveal two distinct waves of supernova fallout, about 2–3 and 6–8 million years ago.

        ORION reconstructs the cosmic story behind those waves. It combines state-of-the-art magnetohydrodynamic simulations of the Local Bubble and its neighboring superbubbles with the most precise three-dimensional map of nearby stars, from the ESA *Gaia* mission. By following the debris of every ancient supernova through space and time, we calculate when each cosmic shower should have reached the Earth and compare these predictions with what is actually measured in the archives.

      questions:
        - title: How did the bubbles around the Sun form and interact?
          text: High-resolution 3D MHD models of the Local Bubble and its neighboring superbubbles, including dust and radionuclide transport and anisotropic thermal conduction — released as templates for models of Galactic chemical evolution.
        - title: Where do both waves of supernova fallout come from?
          text: Reproducing both <sup>60</sup>Fe peaks, together with other radionuclides such as <sup>26</sup>Al, <sup>53</sup>Mn, and <sup>244</sup>Pu, in a single self-consistent framework — and testing whether the Sun crossed a cavity already swept clean by earlier supernovae, which would explain why Earth received fewer <sup>244</sup>Pu atoms than expected.
        - title: What forms at the bubble walls?
          text: Whether instabilities at bubble interfaces create small clouds like the Local Interstellar Cloud that surrounds the Sun today, open chimneys toward the Galactic halo, or squeeze nearby molecular clouds hard enough to trigger new star formation.
        - title: Where are the remnants today?
          text: Predicting where the neutron stars left behind by these supernovae are now, as an independent test of the reconstructed explosion history.

      approach:
        - title: Simulations
          text: 3D magnetohydrodynamic simulations with adaptive mesh refinement (RAMSES), following gas, dust, and radionuclides through the evolving bubbles.
        - title: Stellar populations
          text: '*Gaia*-based reconstructions of nearby star clusters and their past supernovae, in close collaboration with the Alves group at the University of Vienna.'
        - title: Measurements
          text: Direct comparison with radionuclides in deep-sea sediments and crusts, lunar samples, and Antarctic snow and ice, as well as with gamma-ray lines, soft X-rays, and dust emission.

      # software produced by the project: shown first under "Project outputs"
      components:
        - name: RELIC
          publish_date: 2027-02-01     # hidden until a build on/after this date (RELIC submission)
          longname: Reconstructing Explosive Lineages In Clusters
          logo: projects/relic-logo.png
          text: |-
            RELIC is a probabilistic framework for supernova archaeology. Starting from *Gaia* data of nearby star clusters, it reconstructs which massive stars have already exploded, when, and where — with full uncertainty propagation — and thereby provides the supernova histories that drive the ORION simulations. Its first application is the Scorpius–Centaurus association, the birthplace of the Local Bubble.

            The code will be released on GitHub together with the first RELIC paper.
          links:
            - text: GitHub
              url: https://github.com/mschulreich

      # data products and visualizations (listed under "Project outputs" after Software)
      data_products:
        - name: Sco–Cen superbubble in 3D
          publish_date: 2027-02-01     # hidden until a build on/after this date (RELIC submission)
          description: 'Interactive 3D version of a figure from the RELIC paper: the Sco–Cen superbubble, a Local Bubble analog, as predicted by the generalized Kompaneets model, overlaid on the 3D interstellar dust maps of [Edenhofer et al. (2024)](https://doi.org/10.1051/0004-6361/202347628). The bubble is shown at three epochs — when the Sun entered the Local Bubble, at the time of the most recent <sup>60</sup>Fe signal on Earth, and today — in purple shades that grow lighter toward the present. The orange curve traces the Sun’s trajectory over the past 12 Myr up to its present position, with the Sun marked in white at its entry into the Local Bubble and in yellow at the time of the <sup>60</sup>Fe signal. Cyan dots mark the present-day Sco–Cen members, and a cross the effective supernova source.'
          url: relic/scocen/
          link_text: View in 3D
          image: projects/scocen-3d.jpg   # preview (screenshot of the scene), links to the scene

      # publications are listed automatically from content/publications/* with `projects: [orion]`;
      # use upcoming_publications only for papers without a publication page:
      # upcoming_publications:
      #   - { authors: [me], title: '...', status: in prep., venue: '*Journal*' }

      partners:
        - name: João Alves
          inst: University of Vienna, Austria
          role: '*Gaia*-based reconstructions of nearby stellar groups'
        - name: Maria Lugaro
          inst: Konkoly Observatory, Budapest, Hungary
          role: Stellar nucleosynthesis and isotope yields
        - name: Benjamin Wehmeyer
          inst: University of Wrocław, Poland
          role: Galactic chemical evolution
        - name: Thomas Siegert
          inst: University of Würzburg, Germany
          role: Gamma-ray line observations
        - name: Jenny Feige
          inst: Museum für Naturkunde Berlin, Germany
          role: Radionuclide measurements (AMS)
        - name: Josefa Großschedl
          inst: Astronomical Institute of the Czech Academy of Sciences, Prague, Czechia
          role: Orion–Eridanus stellar groups

      funding_logo: projects/fwf-logo.svg
      funding: |-
        This research was funded in whole or in part by the Austrian Science Fund (FWF) [10.55776/PAT1519826](https://doi.org/10.55776/PAT1519826).
    design:
      spacing:
        padding: ['0', '0', '0', '0']
---
