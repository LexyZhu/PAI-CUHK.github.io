---
title: Publications
type: landing

sections:
  - block: collection
    id: pai-publications
    content:
      title: Publications
      text: |
        <style>
          :is(#pai-publications, #pai-preprints) .li-cite-author,
          :is(#pai-publications, #pai-preprints) .li-cite-author * {
            font-weight: 400 !important;
          }
        </style>
      count: 0
      filters:
        folders:
          - papers
        publication_type: '2'
    design:
      view: citation
      columns: '1'

  - block: collection
    id: pai-preprints
    content:
      title: Preprints
      count: 0
      filters:
        folders:
          - papers
        publication_type: '3'
    design:
      view: citation
      columns: '1'
---
