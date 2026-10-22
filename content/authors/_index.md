---
title: ''
summary: ''
date: 2026-10-22
type: landing

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      # TODO: upload your CV as static/uploads/resume.pdf, or delete this button
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        Darry Lab studies a gap that most AI security work leaves open: what happens when intelligent systems are deployed where connectivity is intermittent, compute is scarce, and the people relying on them cannot afford a failure. The lab works across three connected threads.

        **Securing AI systems.** Guardrails, provenance and attestation for large language models and autonomous agents, designed to keep working offline and on modest hardware.

        **Securing the software they depend on.** Supply chain protection for emerging software stacks, starting with quantum computing.

        **Putting trustworthy AI to work.** Crop diagnostics, loss attribution and digital teaching tools built with and for communities in Zambia and the wider SADC region.

        The lab welcomes collaboration with researchers, funders and practitioners who share these concerns.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      show_date: false
      show_read_time: false

  - block: collection
    id: papers
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
