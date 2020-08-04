---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Sentiment analysis of YouTube comments"
summary: "Machine learning for sentiment analysis"
authors: []
tags: []
categories: []
date: 2018-12-02T23:16:39+05:30

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/oishi-poddar/Sentiment-Analysis-of-comments-on-Youtube-videos"
url_pdf: "https://docs.google.com/document/d/1LQQGMTAK1WW9xpYWwSZw-DdLoQikLoPpnHQ2twz4Ch8/edit?usp=sharing"
url_slides: "https://drive.google.com/file/d/1ZCRdv5K4-GC0i3CfUkjtGExvHw8uN3lb/view?usp=sharing"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Applied the Naive Bayes algorithm to analyze sentiment of YouTube comments on a particular video which were fetched using the YouTube Data API. The model was trained on a pre-categorised dataset of words and could then classify the overall sentiment of the comments as positive or negative. The accuracy achieved is 80% and the various libraries used were Scipy, Matplotlib, Scikit-learn, NLTK in Python.