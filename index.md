---
layout: page
title: الفصل الدّراسي المفقود من دراستك لعلوم الكمبيوتر
---

<div dir="rtl">

تتعلّم أثناء دراستك لعلوم الكمبيوتر الكثير من الموضوعات المتقدمة ، بدءًا من أنظمة التشغيل إلى التعلم الآلي ، ولكن هناك موضوعٌ مهمٌ نادرًا ما تتم تغطيته ، وبدلاً من ذلك يُترك للطلاب ليكتشفوه بأنفسهم عند دخولهم سوق الشغل: و هذا الموضوع هو إتقان إستعمال أدوات البرمجة. سنعلمك في التّالي كيفية إتقان سطر الأوامر ، واستخدام محرر نصوص قوي ، واستخدام الميزات الرائعة لأنظمة التحكم في الإصدار ، وأكثر من ذلك بكثير!


يقضي الطلاب مئات الساعات في استخدام هذه الأدوات خلال فترة تعليمهم (والآلاف خلال حياتهم المهنية) ، لذا فمن المنطقي جعل تجربة استعمالها سلسة وخالية من الاحتكاك قدر الإمكان. إنَّ إتقان هذه الأدوات لا يُمكّنك فقط من قضاء وقت أقلّ في اكتشاف كيفية تطويعها حسب إرادتك ، ولكنه يتيح لك أيضًا حلَّ المُشكلات التي كانت تبدو في السابق معقدة بشكل مستعصي عن الحلّ.

</div>

Read about the [motivation behind this class](/about/).

{% comment %}
# Registration

Sign up for the IAP 2020 class by filling out this [registration form](https://forms.gle/TD1KnwCSV52qexVt9).
{% endcomment %}

# Schedule

{% comment %}
**Lecture**: 35-225, 2pm--3pm<br>
**Office hours**: 32-G9 lounge, 3pm--4pm (every day, right after lecture)
{% endcomment %}

<ul>
{% assign lectures = site['2020'] | sort: 'date' %}
{% for lecture in lectures %}
    {% if lecture.phony != true %}
        <li>
        <strong>{{ lecture.date | date: '%-m/%d' }}</strong>:
        {% if lecture.ready %}
            <a href="{{ lecture.url }}">{{ lecture.title }}</a>
        {% else %}
            {{ lecture.title }} {% if lecture.noclass %}[no class]{% endif %}
        {% endif %}
        </li>
    {% endif %}
{% endfor %}
</ul>

Video recordings of the lectures are available [on
YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J).

# About the class

**Staff**: This class is co-taught by [Anish](https://www.anishathalye.com/), [Jon](https://thesquareplanet.com/), and [Jose](http://josejg.com/).
**Questions**: Email us at [missing-semester@mit.edu](mailto:missing-semester@mit.edu).

# Beyond MIT

We've also shared this class beyond MIT in the hopes that others may
benefit from these resources. You can find posts and discussion on

 - [Hacker News](https://news.ycombinator.com/item?id=22226380)
 - [Lobsters](https://lobste.rs/s/ti1k98/missing_semester_your_cs_education_mit)
 - [/r/learnprogramming](https://www.reddit.com/r/learnprogramming/comments/eyagda/the_missing_semester_of_your_cs_education_mit/)
 - [/r/programming](https://www.reddit.com/r/programming/comments/eyagcd/the_missing_semester_of_your_cs_education_mit/)
 - [Twitter](https://twitter.com/jonhoo/status/1224383452591509507)
 - [YouTube](https://www.youtube.com/playlist?list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J)

# Translations

- [Chinese: missing-semester-cn.github.io](https://missing-semester-cn.github.io/)
- [Turkish: missing-semester-tr.github.io](https://missing-semester-tr.github.io/)

Note: these are external links to community translations. We have not vetted
them.

Have you created a translation of the course notes from this class? Submit a
[pull request](https://github.com/missing-semester/missing-semester/pulls) so
we can add it to the list!

## Acknowledgements

We thank Elaine Mello, Jim Cain, and [MIT Open
Learning](https://openlearning.mit.edu/) for making it possible for us to
record lecture videos; Anthony Zolnik and [MIT
AeroAstro](https://aeroastro.mit.edu/) for A/V equipment; and Brandi Adams and
[MIT EECS](https://www.eecs.mit.edu/) for supporting this class.

---

<div class="small center">
<p><a href="https://github.com/missing-semester/missing-semester">Source code</a>.</p>
<p>Licensed under CC BY-NC-SA.</p>
<p>See <a href="/license/">here</a> for contribution &amp; translation guidelines.</p>
</div>
