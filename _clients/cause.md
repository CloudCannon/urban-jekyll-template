---
name: Cause Template
subtitle: Not for profit template for Jekyll
external_url: https://github.com/CloudCannon/cause-jekyll-template
image_path: /images/clients/cause.jpg
---

Not for profit themed template for Jekyll. Browse through a [live demo](#TODO).
Increase the web presence of a not for profit or cause website with this configurable theme.

CloudCannon was made by [CloudCannon](http://cloudcannon.com/), the Cloud CMS for Jekyll.
Find more templates and themes at [Jekyll Tips](http://jekyll.tips/templates/).

Learn Jekyll with step-by-step tutorials and videos at [Jekyll Tips](http://jekyll.tips/).

## Features

* Pre-built pages
* Pre-styled components
* Configurable footer
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* SEO tags
* Google Analytics
* [Donorbox](https://donorbox.org/)
* [MailChimp](https://mailchimp.com/)

## Setup

1. Add your site details in `_config.yml`.
2. Add your Google Analytics to `_config.yml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Jekyll locally).

## Develop

Cause was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## Editing

Cause is already optimised for updating pages, company details and footer elements in CloudCannon.

## SEO Tag

This site uses the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) plugin. You should at least set a title in front matter on each page. Have a look at the [project page](https://github.com/jekyll/jekyll-seo-tag) for more options.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/) is a third party website analytics tool. To install:
1. Add your Google Analytics key to `_config.yml`
2. Run your site in production `JEKYLL_ENV=production`. This is the default in CloudCannon and GitHub Pages.

## Donorbox

[Donorbox](https://donorbox.org/) is a third party embeddable donation form for websites. To install:

1. Set up a campaign on Donorbox
2. Copy the embed code from the Dashboard screen
3. Paste it into `donation_embed` in the `index.html` front matter

## Mailchimp

[Mailchimp](https://mailchimp.com/) is a third party embeddable newsletter for websites. To install:

1. Set up a campaign on Mailchimp
2. Find the embed code for the sign up form
3. Copy the `<form>`'s action url
4. Paste it into `newsletter_action` in the `index.html` front matter

### Company details

* Reused around the site to save multiple editing locations.
* Set in the *Data* / *Company* section.
