---
# An instance of the Pages widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 39

active: True

title: Publications
subtitle: ''

content:
  # Filter on criteria
  filter_button:
    - name: All
      tag: '*'
    - name: Poster Presentation
      tag: Poster
    # - name: arch-test
    #   tag: Architectural Compatibility Testing
  filters:
    folders:
      - publication
    tag: ''
    category: ''
    publication_type: ''
    author: ''
    exclude_featured: false
    exclude_future: false
    exclude_past: false
  # Choose how many pages you would like to display (0 = all pages)
  count: 0
  # Choose how many pages you would like to offset by
  offset: 0
  # Page order: descending (desc) or ascending (asc) date.
  order: desc

design:
  # Choose a view for the listings:
  view: citation
  columns: '2'


---

<!-- {{% callout note %}} -->
<!-- Quickly discover relevant content by [filtering publications](./publication/). -->
<!-- {{% /callout %}} -->
