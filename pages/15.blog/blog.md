---
title: Blog
subtitle: 'News, tips and reflections for all the courses'
hide_git_sync_repo_link: false
sitemap:
    changefreq: monthly
blog_url: /blog
show_sidebar: true
show_breadcrumbs: true
show_pagination: true
modular_content:
    items: '@self.modular'
    order:
        by: folder
        dir: dsc
content:
    items:
        - '@self.children'
    limit: 6
    order:
        by: date
        dir: desc
    pagination: true
    url_taxonomy_filters: true
bricklayer_layout: true
display_post_summary:
    enabled: false
feed:
    limit: 10
    description: 'News, tips and reflections for all the courses'
pagination: true
child_type: item
---

