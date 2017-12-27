# BUCKS BY 90
![bucks by 90 bitches](https://ocio.osu.edu/sites/all/themes/custom/ociomega/images/osu-logos/osu-stacked.svg)

Welcome to College Football Pickem, pick a week, and comment your choices, scores are decided by the rules on the rules page.

<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>