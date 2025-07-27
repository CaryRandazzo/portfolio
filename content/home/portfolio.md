---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Heat Transfer Simulation
      tag: HTS
    - name: Atmopheric Dynamics
      tag: ATMOS
    - name: Electromagnetic Simulation
      tag: ESIM
    - name: Fluid Dynamics
      tag: FD
    - name: Sports Science
      tag: SSCI
    - name: Unreal Engine
      tag: UE
    - name: Virtual Reality
      tag: VR
    - name: NLP
      tag: NLP
    - name: Anomaly Detection
      tag: AD
    - name: Other SW Engineering
      tag: SWE



design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
