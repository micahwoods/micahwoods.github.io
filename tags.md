---
layout: page
title: Post archive
share-img: "https://c2.staticflickr.com/2/1753/42051209314_7ddb8e9c39_b_d.jpg"
---

These are the top 5 posts on this site, ranked by total pageviews.

1. [Is carbon the next frontier in fertilization?](https://www.asianturfgrass.com/2018-05-31-is-carbon-the-next-frontier-in-fertilization/)

2. [This one simple trick can transform putting greens from usually good to consistently great](https://www.asianturfgrass.com/2019-06-25-one-simple-trick-better-greens/)

3. [New MLSN cheat sheet](https://www.asianturfgrass.com/2018-02-03-new-mlsn-cheat-sheet/)

4. [This will make you rethink what you throw in the spray tank](https://www.asianturfgrass.com/2017-07-06-rethink-throw-spray-tank-si/)

5. [Sand topdressing to match grass growth](https://www.asianturfgrass.com/2017-08-20-topdress-and-growth-potential/)

---
<!-- Get the tag name for every tag on the site and set them
to the `site_tags` variable. -->
{% capture site_tags %}{% for tag in site.tags %}{{ tag | first }}{% unless forloop.last %},{% endunless %}{% endfor %}{% endcapture %}

<!-- `tag_words` is a sorted array of the tag names. -->
{% assign tag_words = site_tags | split:',' | sort %}

<!-- Build the Page -->

<!-- List of all tags -->
<ul class="tags">
  {% for item in (0..site.tags.size) %}{% unless forloop.last %}
    {% capture this_word %}{{ tag_words[item] }}{% endcapture %}
    <li>
      <a href="#{{ this_word | cgi_escape }}" class="tag">{{ this_word }}
        <span>({{ site.tags[this_word].size }})</span>
      </a>
    </li>
  {% endunless %}{% endfor %}
</ul>

<!-- Posts by Tag -->
<div>
  {% for item in (0..site.tags.size) %}{% unless forloop.last %}
    {% capture this_word %}{{ tag_words[item] }}{% endcapture %}
    <h2 id="{{ this_word | cgi_escape }}">{{ this_word }}</h2>
    {% for post in site.tags[this_word] %}{% if post.title != null %}
      <div>
        <span style="float: left;">
          <a href="{{ post.url }}">{{ post.title }}</a>
        </span>
        <span style="float: right;">
          {{ post.date | date_to_string }}
        </span>
      </div>
      <div style="clear: both;"></div>
    {% endif %}{% endfor %}
  {% endunless %}{% endfor %}
</div>
