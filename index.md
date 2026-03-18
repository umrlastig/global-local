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

<p style="text-align:center;">{% include button.html text="arXiv paper :page_facing_up:" link="https://arxiv.org" color="#FA0740" %} {% include button.html text="ISPRS Paper :globe_with_meridians:" link="https://www.isprs.org" color="#9CEDFF" %}</p>

## Which limitations today ?

**1. Insufficient and asymmetric exploitation of the various categories of data sources.**
Such exploitation depends on the application and the domain the contributors fall into. This is a community-based bias, where every community defines what is _auxiliary source_ or _metadata_. Each geographical extent and data source has its specific contribution but many approaches limit themselves to two of them and ignore the other ones. This narrows down their potential. It often comes from the fact that one spatial extent is often a _master_ extent, from which the core information is extracted. The _slave_  one(s) is(are) only inserted for a specific step (supervision or alternative input source), without (i) being appropriately handled and (ii) retroaction loop, for the benefit of this slave extent.

**2. Limited two-way interactions.**
Few initiatives adopt a back-and-forth or retroaction strategy. _Slave_ level(s)  can help improving the _master_ one in terms of spatial, temporal, semantic information. This can be cast into the _lifecycle data assessment_ or _critical analysis of the sources_ paradigms.

## Which lines of research ?

### :arrow_up: Extending AI models

First, among the well-known AI generic model-centric issues, few are highly relevant in our context:
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

* Handling unseen sources.
* Federated and knowledge-based learning.
* Handling domain shifts, domain generalization issues.
* Mitigating bias transfer.
* Estimating uncertainty and moving to interpretability.

### :dart: Real-world benchmarking and validation
Heavily related to the previous point, key aspects are:
* Consistent and muti-faceted benchmarks.
* Spatially and temporally consistent reference data across data sources and extents for validation.
* Handling genuine applications (economics, history, social sciences) to help understanding complex cases.

### :raising_hand: Adopting a user-centric perspective
Pure predictive performance on mainstream data sources is over, which calls for:
* Disantangling data producer, model designer, and end-user perspectives.
* Adopting a critical analysis of the sources or a hermeneutics perspectives.
* Quo vadis human-centric machine learning ?
* Enforcing source diversity.

### :arrows_counterclockwise: Discoverability, and reuse of existing research
Open models and data does not suffice to comply with FAIR principles.
* Closing the gap in the discoverability and comparability of available benchmarks, models, and algorithms across research communities;
* Improving the tools for providing curating and comparable research resources, and user feedbacks on such resources.

## :book: Key references
* Arribas-Bel, D., 2014. Accidental, open and everywhere: Emerging data sources for the understanding of cities.
_Applied Geography_, 1, 45-53.
* Baek, E., Park, K., Ko, J., hwan Oh, M., Gong, T., Kim, H.-S., 2025. AI should sense better, not just scale bigger:
Adaptive sensing as a paradigm shift. _NeurIPS_.
* Editorial, 2016. So long to the silos. _Nature Biotechnology_, 34, 357.
* Koldasbayeva, D., Tregubova, P., Gasanov, M., Zaytsev, A., Petrovskaia, A., Burnaev, E., 2024. Challenges in
data-driven geospatial modeling for environmental research and practice. _Nature Communications_, 15(10700).
* Kommers, C. et al., 2026. Computational Hermeneutics: Evaluating Generative AI as a Cultural Technology. _Fron-
tiers in Artificial Intelligence_, 9(1753041).
* Larivière, V., Haustein, S., Börner, K., 2015. Long-Distance Interdisciplinarity Leads to Higher Scientific Impact.
_PLOS ONE_, 10(3), 1-15.
*  Shi, F., Evans, J., 2023. Surprising combinations of research contents and contexts are related to impact and emerge
with scientific outsiders from distant disciplines. _Nature Communications_, 14, 1641.
* Stammler-Gossmann, A., 2024. Knowledge exchange in the arctic environmental studies: Bridging science and the
local community in dialogue. _Polar Science_, 41, 101103.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.


