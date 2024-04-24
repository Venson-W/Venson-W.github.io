---
title: "A coupled finite difference-spectral boundary integral method with applications to fluid diffusion in fault structures"
authors:
- admin
- Elías Rafn Heimisson

author_notes:
- "Corresponding author"
date: "2024"
doi: "https://doi.org/10.1002/nag.3740"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal For Numerical And Analytical Methods In Geomechanics*"
publication_short: ""

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

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

**Abstract:** Fluid migration in geological materials, a subject of great interest in various geophysical applications, has been interpreted through multiple numerical methods. Taking advantage of both a volume-based method and a boundary integral method, we innovate a hybrid spectral-boundary-integral and finite-difference method (SBI-FDM) to describe the fluid injection and propagation in the fault structure. The coupling of the two methods is established from the consistent exchange of the pressure gradient from the volume-based method and the boundary flux applied in the SBI boundary. The hybrid method benefits from its capability to truncate the domain and capture the fluid-induced pore pressure in geological systems without modeling the whole bulk. After establishing the numerical framework, we verify the SBI-FDM under both homogeneous and heterogeneous mediums using an analytical solution and the FDM results, respectively. After model verification, a sensitivity test showcases the stability of the numerical scheme. A speedup comparison of the SBI-FDM against the FDM is presented. We observe that the proposed method can achieve better computational efficiency with up to one thousand times speedup in our test. Utilizing the proposed hybrid method, we also perform parametric studies to reveal the significance of mobility contrast between the damage zone and host rock, as well as the role of fault width during fault injection.