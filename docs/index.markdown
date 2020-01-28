---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Answers to Exercises  

{% for item in site.data.pdfs%}
  <a href="{{ site.baseurl }}/assets/pdfs/{{ item.pdf}}" >{{ item.name }}</a>
{% endfor %}
<a href="http://essentialmicroeconomics.com/OnLineReview/onlinereview.htm" >ON-LINE MATH REVIEW</a>
