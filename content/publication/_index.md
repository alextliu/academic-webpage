---
title: Publications
# cms_exclude: true
# Page type - we want a landing page (such as a homepage)
type: landing

# View.
# view: citation

# Optional header image (relative to `static/media/` folder).
# banner:
#   caption: ''
#   image: ''

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    content:
      text: |
        A complete publication list can be found on Tianyi Liu's profiles in [Google Scholar](https://scholar.google.com/citations?user=SAJ8bL8AAAAJ&hl=en) and [Research Gate](https://www.researchgate.net/profile/Tianyi-Liu-3).
  - block: collection
    content:
      title: Theses
      text: ""
      count: 0
      filters:
        folders:
          - publication
        publication_type: "thesis"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Book Chapters
      text: ""
      count: 0
      filters:
        folders:
          - publication
        publication_type: "chapter"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Preprints
      text: ""
      count: 0
      filters:
        folders:
          - publication
        publication_type: "manuscript"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Journal Articles
      text: ""
      count: 0
      filters:
        folders:
          - publication
        publication_type: "article-journal"
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Conference Proceedings
      text: ""
      count: 0
      filters:
        folders:
          - publication
        publication_type: "paper-conference"
        exclude_featured: false
    design:
      view: citation
---
