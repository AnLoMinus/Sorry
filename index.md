---
layout: default
title: ברוך הבא לפרויקט Sorry
---

<div dir="rtl">

היי! זהו אתר הבלוג של פרויקט *Sorry* – מקום לעבודה על סליחה, עצבנות,
התחדשות ושיפור.

כדי לראות את כל השירים, קטגוריות ומידע נוסף השתמש בתפריט למעלה.

> קישורים מהירים:
> - [קטגוריות סליחה](#)
> - [פוסטים חדשים](posts/)
> - [מאגר GitHub](https://github.com/AnLoMinus/Sorry)

<hr />

## פוסטים עדכניים

<ul>
{% for post in site.posts %}
  <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a> – {{ post.date | date: "%d.%m.%Y" }}</li>
{% endfor %}
</ul>

</div>
