---
# Page settings
layout: default
keywords:
comments: false

# Hero section
title: Contribute to this guide
description: This guide lives from people sharing their knowledge. Everything here is open source and under a free Creative Commons license. Help to develop the content further.

# Author box
# author:
#     title: About Author
#     title_url: '#'
#     external_url: true
#     description: Author description

# Micro navigation
micro_nav: false

# Page navigation

---

# How to add content to this guide
To contribute to this guide, install this page locally and then create a pull request. You can find instructions on how to do this in the `README.md`.

Content should be in [Markdown](https://daringfireball.net/projects/markdown/) format and you shouldn’t remove `.yml` comments on top of the `.md` files, errors may occur if you remove them.

<div class="callout callout--info">
    <p><strong>Format your content</strong> Content should be in <a href="https://daringfireball.net/projects/markdown/">Markdown</a> format and you shouldn’t remove <code>.yml</code> comments on top of the <code>.md</code> files, errors may occur if you remove them.</p>
</div>

## Create a new special interest guide

To create a new guide for special interest users, e.g. 'EO for pets 🐶', duplicate the `example-guide` directory. Give the folder suitable name. In the inner of `example-guide` you can find another folder. This is the first section of your guide. Give the folder also a suitable name, like 'Why dogs should use satellite data'. Place the content for this section in the `index.md` of your section directory.

## Publish your new guide

To publish your guide and display it on the homepage you have to add your pages to the `grid-navigation:` section. Please, take a look at the example:

<div class="example"></div>
<div class="language-html highlighter-rouge"><div class="highlight"><pre class="highlight"><code>
- title: My new guide
      excerpt: Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt.
      links:
        - title: Section 1 title
          url: '/section-1/'

</code></pre></div></div>