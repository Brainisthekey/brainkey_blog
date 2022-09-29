---
layout: activity-posts
title: CodeEurope
date: 2022-05-30 23:18 +0800
last_modified_at: 2022-05-30 01:08:25 +0800
---
Company Representative
{: .message }

<div>
{%- if site.code-europe-img contains "://" -%}
    {%- assign code-europe-img = site.code-europe-img -%}
{%- else -%}
    {%- assign code-europe-img = site.code-europe-img | relative_url -%}
{%- endif -%}
{%- if site.code-europe-video contains "://" -%}
    {%- assign code-europe-video = site.code-europe-video -%}
{%- else -%}
    {%- assign code-europe-video = site.code-europe-video | relative_url -%}
{%- endif -%}
</div>

<img src="{{ code-europe-img }}" style="width:455px;height:570px" alt="" />{: .align-left}

It was a great chance to attend the **Code Europe** meetup and it was super exciting.
Pleasant atmosphere, interesting lectures, and most importantly great people around me! Thanks STX Next for the opportunity to be here.
Special thanks for the organization and promotion Tomasz Nowakowski and Agnieszka Ołowska, looking forward to the next events! 🤩

**#CodeEurope #STXNext #PythonMeetup**
<br><br><br>
<iframe
    width="560"
    height="315"
    src="{{ code-europe-video }}"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen>
</iframe>{: .align-right}

<br><br><br><br><br><br><br><br><br><br><br><br><br>
