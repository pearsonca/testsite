---
---
collection testing
{% for t in site.my_test %}
{{ forloop.index }} : {{ t.testdata }}
{% endfor %}
