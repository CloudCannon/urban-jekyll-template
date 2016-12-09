---
name: Malt Template
subtitle: Event marketing template for Jekyll
external_url: https://github.com/CloudCannon/malt-jekyll-template
image_path: /images/clients/malt.jpg
---

Event marketing template for Jekyll. Browse through a [live demo](https://whispering-boat.cloudvent.net/).
Increase the web presence of your event with this configurable theme.

CloudCannon was made by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.
Find more templates and themes at [Jekyll Tips](http://jekyll.tips/templates/).

Learn Jekyll with step-by-step tutorials and videos at [Jekyll Tips](http://jekyll.tips/).

## Features

* Pre-built page
* Pre-styled components
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* SEO tags
* Google Analytics
* [EventBrite](https://www.eventbrite.com/)
* Contact Form
* Featured
* Image Gallery

## Setup

1. Add your site details in `_config.yml`.
2. Add your Google Analytics to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Malt was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Malt is already optimised for updating pages, company details and footer elements in CloudCannon.

## SEO Tag

This site uses the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) plugin. You should at least set a title in front matter on each page. Have a look at the [project page](https://github.com/jekyll/jekyll-seo-tag) for more options.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/) is a third party website analytics tool. To install:

1. Add your Google Analytics key to `_config.yml`.
2. Run your site in production `JEKYLL_ENV=production` (the default for CloudCannon and GitHub Pages).

## EventBrite

[EventBrite](https://www.eventbrite.com/) is a third party embeddable event module for websites. To install:

1. Create an event on EventBrite.
2. Copy the Ticket Form embed code from the Widgets menu item.
3. Paste it into `eventbrite_embed` in `_config.yml`.

## Image gallery / Featured

The image gallery is populated by a front matter array in `index.html`. To add items just copy the existing structure.
