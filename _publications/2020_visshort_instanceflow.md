---
layout: publication
# The quotes make the : possible, otherwise you can do it without quotes
title: "InstanceFlow: Visualizing the Evolution of Classifier Confusion on the Instance Level"
key: 2020_preprint_instanceflow
# paper | preprint | poster
type: paper
# optional url for a different site; defaults to data.caleydo.org
paper_content_url: 


# The shortname is used for auto-generated titels
shortname: InstanceFlow
# add a 2:1 aspect ratio (e.g., width: 400px, height: 200px) to the folder /assets/images/papers/
image: 2020_visshort_instanceflow.png
# add a 2:1 aspect ratio teaser figure (e.g., width: 1200px, height: 600px) to the folder /assets/images/papers/
image_large: 

# Authors in the "database" can be used with just the key (lastname). Others can be written properly.
authors:
- Michael Pühringer
- hinterreiter
- streit 

journal-short: VIS'20 Short Paper
year: 2020

bibentry: inproceedings
bib:
  booktitle: Proceedings of the IEEE Visualization Short Papers
  publisher: IEEE Computer Society Press
  url: https://arxiv.org/abs/2007.11353 

preprint: https://arxiv.org/abs/2007.11353 # here you can put all preprint links (arxiv.org, osf.io,...)

# Add things like "Best Paper Award at InfoVis 2099, selected out of 4000 submissions"
award:

non_group_project: False

# Use if this paper is linked to an internal project. This will link to the project site
project: 

# Use this if you have an external project website
external-project: 

# The reference to the video entry
video: 
# The reference to the preview video entry
#preview-video:

# the prerint
pdf: 2020_preprint_instanceflow.pdf
# A supplement PDF
#supplement: 2017_preprint_taggle_supplement.pdf

# Extra supplements, such as talk slides, data sets, etc.
supplements:
#- name: General UpSet
#  # use link instead of abslink if you want to link to the master directory
#  abslink: http://vials.io/talk/
#  # defaults to a download icon, use this if you want a link-out icon
#  linksym: true

# Link to the repository where the code is hostet
code: 

abstract: "Classification is one of the most important supervised machine learning tasks. During the training of a classification model, the training instances are fed to the model multiple times (during multiple
epochs) in order to iteratively increase the classification performance.
The increasing complexity of models has led to a growing demand
for model interpretabilty through visualizations. Existing approaches
mostly focus on the visual analysis of the final model performance
after training and are often limited to aggregate performance measures. In this paper we introduce InstanceFlow, a novel dual-view
visualization tool that allows users to analyze the learning behavior
of classifiers over time on the instance-level. A Sankey diagram
visualizes the flow of instances throughout epochs, with on-demand
detailed glyphs and traces for individual instances. A tabular view
allows users to locate interesting instances by ranking and filtering. In this way, InstanceFlow bridges the gap between class-level
and instance-level performance evaluation while enabling users to
perform a full temporal analysis of the training process.
"

# After the --- you can put information that you want to appear on the website using markdown formatting or HTML. A good example are acknowledgements, extra references, an erratum, etc.
---


# Acknowledgements


