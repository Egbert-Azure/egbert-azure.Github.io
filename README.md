---
jekyll_exclude: true
---

# egbert-azure.Github.io
Egbert's personal website
My website is where I post everything about chess and my experience as a "senior chess improver".
I also share games and tournaments with my results and games for replay

## Jekyll Theme

The theme is simple but configuration is outdated and it has some flaws I need to correct:
- favicon.ico: the original favicon icon is missed in the distribution. I replaced with a favicon.ico from the web (a chesspiece = knight)
-fontawesome is used for icons in this theme, but the folder fontawesome is empty but has a icons.svg which seems to be outdated, actual version is `6.4.2`

`````` json
---
---
<?xml version="1.0" encoding="UTF-8"?>

<!--
Font Awesome Free 5.12.0 by @fontawesome - https://fontawesome.com
License - https://fontawesome.com/license/free (Icons: CC BY 4.0, Fonts: SIL OFL 1.1, Code: MIT License)
-->


<svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
{% assign keys = 'navigation,external' | split: ',' %}
{% for key in keys %}
{% for link in site[key] %}
  {% assign icon = link.icon %}
  {% assign svg = site.data.font-awesome.icons[icon].svg | first %}
  <symbol id="{{ icon }}" viewBox="0 0 {{ svg[1].width }} {{ svg[1].height }}"><path d="{{ svg[1].path }}" /></symbol>
{% endfor %}
{% endfor %}
</svg>
```````

- the gemfile was without webrick, jekyll-feed and jekyll-font-awesome but works with the below

- archive and sitemap are in the theme but not in the gemfile

``````
source "https://rubygems.org"

gem "jekyll", "~> 4.2.0"
gem 'wdm', '>= 0.1.0' if Gem.win_platform?
gem 'webrick', '~> 1.7', '>= 1.7.0'
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap", "~> 1.4"
  gem "jekyll-archives", "~> 2.2"
end
``````

- disqus configuration was wrong; this needs to be added:

``````
{% if page.comments != false %}

  <div id="disqus_thread"></div>
  <script>
    var disqus_config = function () {
      this.page.url = '{{ page.url | absolute_url }}';
      this.page.identifier = '{{ page.url | absolute_url }}';
    };
    (function() {
      var d = document, s = d.createElement('script');
      s.src = 'https://{{ site.disqus.shortname }}.disqus.com/embed.js';
      s.setAttribute('data-timestamp', +new Date());
      (d.head || d.body).appendChild(s);
    })();
  </script>
  <noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript" rel="nofollow">comments powered by Disqus.</a></noscript>
{% endif %}
``````

To get archive to work, I needed to modify index.html:

``````
---
layout: post
title: "Latest Blog"
image: /assets/imges/bK.png
comments: false
---
<img src="assets/images/chesspieces/wikipedia/bK.png" style="width: 5%;">

{% if site.show_excerpts %}
  {% include home.html %}
  <p><a href="/archive/" style="text-align: center;">View Full List</a></p>
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
``````

and added Blog Archives to _config.yml
