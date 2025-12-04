---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        ALMIN
      image:
        filename: almin.jpg
      cta:
        url: '/about/'
        label: "À propos de l'ALMIN"
        icon_pack: fas
        icon: lightbulb
      cta_alt:
        url: '/people/'
        label: "Rencontrez le comité"
      text: |
        <br>
        
        L'ALMIN développe et anime le réseau des anciens de la Faculté d'Informatique de l'Université de Namur. Retrouvez nous également sur [Facebook](https://www.facebook.com/groups/638582541369865) et [LinkedIn](https://www.linkedin.com/groups/145747/).<br>  

  - block: collection
    id: events
    content:
      title: Prochains évènements
      subtitle:
      text: 'Venez assister à nos prochains évènements!'
      count: 5
      filters:
        folders:
          - event
        author: ''
        category: ''
        featured_only: false
        exclude_featured: false
        exclude_future: false
        exclude_past: true
        publication_type: ''
        tag: ''
      offset: 0
      order: asc
      page_type: event
    design:
      view: 2
      columns: '2'
  
  - block: collection
    content:
      title: "Dernières nouvelles de l'ALMIN et de ses membres"
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - post
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: showcase
      columns: '2'
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Rencontrez le commité →" %}}
    design:
      columns: '1'
---
