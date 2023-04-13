---
date: "2023-04-01"
type: landing
sections:
- block: about.avatar
  content:
    text: null
    username: admin
  id: about
- block: people
  content:
    title: Group members
    user_groups: 
        - Students
    sort_by: last_name
    sort_ascending: true
  design:
    show_social: false
    show_interests: true
    show_role: true
    show_organizations: true
  id: people
- block: portfolio
  content:
    text: null
    filters:
      folders:
          - post
    username: admin
  id: posts
- block: collection
  content:
    title: Publication highlights
    text: |-
        >See all publications at [GoogleScholar](https://scholar.google.com/citations?user=3y8AwdsAAAAJ&hl=en&oi=ao) and [ORCID](https://orcid.org/0000-0002-6399-0035).<br>
    filters:
      folders:
        - publication
      exclude_featured: true
  id: publications
---
