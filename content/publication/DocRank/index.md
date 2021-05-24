---
title: "Generation of Hindi Word Embeddings and Their Utilization in Ranking Documents Using Negative Sampling Architecture, t-SNE Visualization and TF-IDF Based Weighted Average of Vectors"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
author_notes:
- "Equal contribution"

date: "2018-12-17T00:00:00Z"
doi: "2019-05-21"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Innovations in Bio-Inspired Computing and Applications*
publication_short: In *IBICA 2018*

abstract: Hindi is the official language of India and has over 500 million speakers worldwide. Being a dominant language with a widespread impact, implies the need for development of technologies that cater to its native speakers. In this paper, a text mining based information retrieval model has been developed to generate Hindi word embeddings and their application ranking documents in order of relevance to an input query. Word embeddings are multi-dimensional vectors that can be created by utilizing the linguistic context of words in a large corpus. To generate the embeddings, a corpus was created from the Hindi Wikipedia dump, on which the skip-gram approach was applied using a neural network based negative sampling-architecture. The weighted average of each word embedding along with its tf-idf score generated the embeddings for each individual document. The cosine-similarity was then calculated between each document vector and the query vector. Using these similarity scores, the documents were ranked in descending order of relevance to the query. Highly relevant rankings were obtained in response to a query input. The results of the model were visualized using the t-SNE visualization method. The accuracy of this method proves that in the process of conversion of words to numeric vectors, the semantic context of the words was preserved.

# Summary. An optional shortened abstract.
summary: ""

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://link.springer.com/chapter/10.1007/978-3-030-16681-6_28'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://aryaprabhudesai.netlify.app/project/documentrank.jpg/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- DocumentRank

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
