# Weeks

Welcome to College Football Pickem, pick a week, and comment your choices, scores are decided by the rules on the rules page.

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>