---
title: "Frequently Asked Questions"
url: /FAQs/index.html
layout: base

---
# Welcome to the Histwo FAQs  
[Return to Histwo Home](https://Histwo.github.io)

Here is where you'll find answers to questions about the Creator, His servants, and the fundamental mysteries of existence—including questions like:  

- Why does the Creator allow suffering?
- The meaning of life, the universe, and everything
- Why was the universe created?
- Are we alone in the universe?
- Where are we going after this life?
- If the future is predestined, why should I...?

At this time, answers are provided to the questions the Creator has most frequently received and shared with His servants, as well as those His servants commonly encounter while interacting with His creation—you, the readers—whether online or in person.

Below is a list of answered questions, though it is not exhaustive. The "short answer" is shown, you can view a full answer by clicking the question.  New answers will be added regularly.

**Note:** Due to the nature of our current mission, we are not accepting question submissions online. However, the Creator hears all prayers and is the Supreme Editor of Histwo. If you wish to have a question posted here, the safest way to ask is by submitting it in prayer to the Supreme Editor (using whatever name you typically use).

[Return to Histwo Home](https://Histwo.github.io)

<h2>Answered Questions</h2>
<ul class="post-list">
    {%- assign date_format = site.minima.date_format | default: "%b %-d, %Y" -%}
    {% for faq in site.faqs %}
    <li>
    <span class="post-meta">{{ faq.date | date: date_format }}</span>
    <h3>
        <a class="post-link" href="{{ faq.url | relative_url }}">
        {{ faq.question | escape }}
        </a>
    </h3>
        {{ faq.short_answer }}
    </li>
    {%- endfor -%}
</ul>
<p>0823</p>
