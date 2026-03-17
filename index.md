---
title: The Global-Local Loop
feature_text: |
  ## The Global-Local Loop
  What is missing in bridging the gap between geospatial data from numerous communities?
feature_image: "https://picsum.photos/1300/400?image=989"
excerpt: "In a native multi-source world, a key issue is to adequately and optimally exploit all available geospatial, even rare, sources. Community and discipline bias exist and siloed reasoning has dominated for numerous years. The geospatial-related communities should now devote more research efforts in higher cross-fertilization, barely documented fusion configurations and how to take advantage of main outputs of other communities or disciplines for key applications."
---

In a native multi-source world, a key issue is to adequately and optimally exploit all available geospatial, even rare, sources. Community and discipline bias exist and siloed reasoning has dominated for numerous years.
The geospatial-related communities should now devote more research efforts in higher cross-fertilization, barely documented fusion configurations and how to take advantage of main outputs of other communities or disciplines for key applications.

{% include button.html text="arXiv paper ☕️" link="https://arxiv.org" color="#f68140" %} {% include button.html text="ISPRS Paper ⚗️" link="https://www.isprs.org" %}

## Which limitations today ?

**1. Insufficient and asymmetric exploitation of the various categories of data sources.**
Such exploitation depends on the application and the domain the contributors fall into. This is a community-based bias, where every community defines what is _auxiliary source_ or _metadata_. Each geographical extent and data source has its specific contribution but many approaches limit themselves to two of them and ignore the other ones. This narrows down their potential. It often comes from the fact that one spatial extent is often a _master_ extent, from which the core information is extracted. The _slave_  one(s) is(are) only inserted for a specific step (supervision or alternative input source), without (i) being appropriately handled and (ii) retroaction loop, for the benefit of this slave extent.
**2. Limited two-way interactions.**
Few initiatives adopt a back-and-forth or retroaction strategy. _Slave_ level(s)  can help improving the _master_ one in terms of spatial, temporal, semantic information. This can be cast into the _lifecycle data assessment_ or _critical analysis of the sources_ paradigms.

## Installation

### Quick setup

To give you a running start I've put together some starter kits that you can download, fork or even deploy immediately:

- ⚗️🍨 Vanilla Jekyll starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-kit){:style="background: none"}
- ⚗️🌲 Forestry starter kit  
  [![Deploy to Forestry](https://assets.forestry.io/import-to-forestry.svg)](https://app.forestry.io/quick-start?repo=daviddarnes/alembic-forestry-kit&engine=jekyll){:style="background: none"}  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-forestry-kit){:style="background: none"}
- ⚗️💠 Netlify CMS starter kit  
  [![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/daviddarnes/alembic-netlifycms-kit&stack=cms){:style="background: none"}

- ⚗️:octocat: GitHub Pages with remote theme kit  
  {% include button.html text="Download kit" link="https://github.com/daviddarnes/alembic-kit/archive/remote-theme.zip" color="#24292e" %}
- ⚗️🚀 Stackbit starter kit  
  [![Create with Stackbit](https://assets.stackbit.com/badge/create-with-stackbit.svg)](https://app.stackbit.com/create?theme=https://github.com/daviddarnes/alembic-stackbit-kit){:style="background: none"}


## Key references
* Arribas-Bel, D., 2014. Accidental, open and everywhere: Emerging data sources for the understanding of cities.
Applied Geography, 1, 45-53.
* Baek, E., Park, K., Ko, J., hwan Oh, M., Gong, T., Kim, H.-S., 2025. AI should sense better, not just scale bigger:
Adaptive sensing as a paradigm shift. NeurIPS.
* Editorial, 2016. So long to the silos. Nature Biotechnology, 34, 357.
* Koldasbayeva, D., Tregubova, P., Gasanov, M., Zaytsev, A., Petrovskaia, A., Burnaev, E., 2024. Challenges in
data-driven geospatial modeling for environmental research and practice. Nature Communications, 15(10700).
* Kommers, C. et al., 2026. Computational Hermeneutics: Evaluating Generative AI as a Cultural Technology. Fron-
tiers in Artificial Intelligence, 9(1753041).
* Larivière, V., Haustein, S., Börner, K., 2015. Long-Distance Interdisciplinarity Leads to Higher Scientific Impact.
PLOS ONE, 10(3), 1-15.
*  Shi, F., Evans, J., 2023. Surprising combinations of research contents and contexts are related to impact and emerge
with scientific outsiders from distant disciplines. Nature Communications, 14, 1641.
* Stammler-Gossmann, A., 2024. Knowledge exchange in the arctic environmental studies: Bridging science and the
local community in dialogue. Polar Science, 41, 101103.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.


