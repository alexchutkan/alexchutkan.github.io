---
theme: jekyll-theme-minimal
title: Home
---

# Rules & Posts

Welcome to College Football Pickem, pick a week, and comment your choices, scores are decided by the rules below. You must format your post as followed, or your post will be removed or ignored for results. The links to each week are displayed AFTER the rules. Please read these before you post.

1. Pick your winners for each game.

2. Rank ALL games from most confident to least confident, points are awarded based on confidence positions.

3. Comment your picks below the post as shown, with your winner being shown in parentheses.

- Team A v. Team B (TEAM A)

- Team C v. Team D (TEAM D)

- Team X v. Team Y (TEAM Y)

If all of your picks were correct for the above example, you would receive 5 points total, with the top pick being worth 3 points, the second game being 2, and the last one. Put games that you are confident in the results towards the top of your list.


<ul>
    {% for post in site.posts %}
        <li>
            <a href="{{ post.url }}">{{ post.title }}</a>
        </li>
    {% endfor %}
</ul>
