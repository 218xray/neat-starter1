{% if location.items %}
    <ul class="absolute hidden pt-1 text-gray-700 dropdown-content">
    {% for item in location.items %}
    <li><a class="inline-block px-3 py-1 text-gray-500 no-underline transition bg-white border text-ml hover:text-indigo-500 min-w-32" href="{{ item.url }}">{{ item.text }}</a></li>
    {% endfor %}
    </ul>
{% endif %}