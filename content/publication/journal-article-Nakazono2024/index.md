---
title: "The Quasar Catalogue for S-PLUS DR4 (QuCatS) and the estimation of photometric redshifts"
authors:
- Nakazono et al.
date: "2024-04-09"
doi: "10.1093/mnras/stae971"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-30"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: MNRAS, 531, 327-339
# publication_short:

abstract: "The advent of massive broad-band photometric surveys enabled photometric redshift estimates for unprecedented numbers of galaxies and quasars. These estimates can be improved using better algorithms or by obtaining complementary data such as narrow-band photometry, and broad-band photometry over an extended wavelength range. We investigate the impact of both approaches on photometric redshifts for quasars using data from Southern Photometric Local Universe Survey (S-PLUS) DR4, Galaxy Evolution Explorer (GALEX) DR6/7, and the unWISE catalog for the Wide-field Infrared Survey Explorer (WISE) in three machine learning methods: Random Forest, Flexible Conditional Density Estimation (FlexCoDE), and Bayesian Mixture Density Network (BMDN). Including narrow-band photometry improves the root-mean-square error by 11 per cent in comparison to a model trained with only broad-band photometry. Narrow-band information only provided an improvement of 3.8 per cent when GALEX and WISE colours were included. Thus, narrow bands play a more important role for objects that do not have GALEX or WISE counterparts, which respectively makes 92 per cent and 25 per cent of S-PLUS data considered here. Nevertheless, the inclusion of narrow-band information provided better estimates of the probability density functions obtained with FlexCoDE and BMDN. We publicly release a value-added catalogue of photometrically selected quasars with the photo-z predictions from all methods studied here. The catalogue provided with this work covers the S-PLUS DR4 area (∼3000 square degrees), containing 645 980, 244 912, 144 991 sources with the probability of being a quasar higher than, 80 per cent, 90 per cent, 95 per cent up to r < 21.3 and good photometry quality in the detection image. More quasar candidates can be retrieved from the S-PLUS data base by considering less restrictive selection criteria."

# Summary. An optional shortened abstract.
summary: "This paper provides a catalogue of photometrically selected quasars with the photo-z predictions from three machine learning methods: Random Forest, Flexible Conditional Density Estimation (FlexCoDE), and Bayesian Mixture Density Network (BMDN). The catalogue provided with this work covers the S-PLUS DR4 area (∼3000 square degrees), containing 645 980, 244 912, 144 991 sources with the probability of being a quasar higher than, 80 per cent, 90 per cent, 95 per cent up to r < 21.3 and good photometry quality in the detection image. More quasar candidates can be retrieved from the S-PLUS data base by considering less restrictive selection criteria."
tags:
- S-PLUS
featured: true

links:
# name: Custom Link
# url: http://example.org
# url_pdf: http://eprints.soton.ac.uk/352095/1/Cushen-IMV2013.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: Nakazono et al. 2024 (MNRAS)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo academia's Markdown slides feature.
{{% /alert %}}

<!-- YOUR_COMMENT_HERE 
# Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
# the folder could be journal-article, conference-paper or preprint
-->