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

1. Insufficient and asymmetric exploitation of the various categories of data sources.
Such exploitation depends on the application and the domain the contributors fall into. This is a community-based bias, where every community defines what is "auxiliary source" or "metadata". Each geographical extent and data source has its specific contribution but many approaches limit themselves to two of them and ignore the other ones. This narrows down their potential. It often comes from the fact that one spatial extent is often a master extent, from which the core information is extracted. The slave  one(s) is(are) only inserted for a specific step (supervision or alternative input source), without (i) being appropriately handled and (ii) retroaction loop, for the benefit of this slave extent.
2. Limited two-way interactions.
Few initiatives adopt a back-and-forth or retroaction strategy. Slave level(s)  can help improving the master one in terms of spatial, temporal, semantic information

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


## Customising

When using Alembic as a theme means you can take advantage of the file overriding method. This allows you to overwrite any file in this theme with your own custom file, by matching the file name and path. The most common example of this would be if you want to add your own styles or change the core style settings.

To add your own styles copy the [`styles.scss`](https://github.com/daviddarnes/alembic/blob/master/assets/styles.scss) into your own project with the same file path (`assets/styles.scss`). From there you can add your own styles, you can even optionally ignore the theme styles by removing the `@import "alembic";` line.

If you're looking to set your own colours and fonts you can overwrite them by matching the variable names from the [`_settings.scss`](https://github.com/daviddarnes/alembic/blob/master/_sass/_settings.scss) file in your own `styles.scss`, make sure to state them before the `@import "alembic";` line so they take effect. The settings are a mixture of custom variables and settings from [Sassline](https://medium.com/@jakegiltsoff/sassline-v2-0-e424b2881e7e) - follow the link to find out how to configure the typographic settings.
