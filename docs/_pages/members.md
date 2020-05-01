{% for aperson in docs.data.members %}
{% if aperson.github_image_id %}
{% endif %}
{{ aperson.name }}

{{ aperson.organization }}

{{ aperson.excerpt }}
{% endfor %}
