---
# Leave the homepage title empty to use the site title
title:
date: 2024-08-14
type: landing

sections:
  - block: markdown
    content:
      title: |
        TRAILS - Trustworthy and Inclusive Machines
        <br><br>{{< figure src="trails_logo_small.png" alt="TRAILS - Sponsored by the Federal Ministry of Education and Research" >}}
      image:
        filename: trails_logo.png
      text: |

        Natural language processing (NLP) has demonstrated impressive performance in some human tasks. To achieve such performance, current neural models need to be pre-trained on huge amounts of raw text data. This dependence on uncurated data has at least four indirect and unintended consequences:
        
        1. Uncurated data tends to be linguistically and culturally non-diverse due to the statistical dominance of major languages and dialects in online texts (English vs. North Frisian, US English vs. UK English, etc.).
        
        2. Pre-trained neural models such as the ubiquitous pre-trained language models (PLM) reproduce the features present in the data, including human biases.
        
        3. Rare phenomena (or languages) in the "long tail" are often not sufficiently taken into account in model evaluation, leading to an underestimation of model performance, especially in real-world application scenarios.
        
        4. The focus on achieving state-of-the-art results through the use of transfer learning with giant PLMs such as GPT4 or mT5 often underestimates alternative methods that are more accessible, efficient and sustainable.
        
        As inclusion and trust are undermined by these problems, in TRAILS we focus on three main research directions to address such problems: (i) inclusion of underrepresented languages and cultures through multilingual and culturally sensitive NLP, (ii) robustness and fairness with respect to long-tail phenomena and classes and "trustworthy content", and (iii) robust and efficient NLP models that enable training and deployment of models for (i) and (ii). We also partially address economic inequality by aiming for more efficient models (objective (iii)), which directly translates into a lower resource/cost footprint.

        TRAILS is funded by the German Federal Ministry of Education and Research (BMBF) under the funding code 01IW24005.
    design:
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      
  - block: people
    content:
      title: 
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
      user_groups:
        - Principal Investigators
        - Researchers
        - PhD Students
        - Administration
        - Visitors
        - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true

# https://docs.hugoblox.com/getting-started/page-builder/#personalizing-blocks
  - block: collection
    content:
      title: News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
    #  view: card
    #  columns: '1'
      #view: 3
      view: compact
      columns: '1'

# https://docs.hugoblox.com/getting-started/page-builder/#personalizing-blocks
  - block: collection
    content:
      title: Recent Publications
      text: ""
      count: 15
      filters:
        folders:
          - publication
        #publication_type: 'article'
    design:
      view: compact
      columns: '1'

# https://docs.hugoblox.com/getting-started/page-builder/#personalizing-blocks
  - block: markdown
    content:
      title: ""
      text: |
        {{< figure src="bmbf_and_trails_logo_small.png" alt="TRAILS - Sponsored by the Federal Ministry of Education and Research" >}}
    design:
      view: compact
      columns: '1'
      background:
        color: 'white'
---
