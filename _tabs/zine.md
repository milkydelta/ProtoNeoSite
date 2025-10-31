---
order: 4
icon: fas fa-newspaper
layout: default
title: The Zine

---

![image](/assets/img/zine/output.png){: .w-50 .right}

{% assign zines = site.posts | where:"category","Zine" %}
{% assign issue = zines[0].title | strip | split: " " %}
# The Zine - Issue {{issue[1]}}

The Zine is our magazine chock full of interesting articles written by our members.
With a whopping 140 pages of content you are sure to find something that interests you.
You can fine older issues in the [archives](/archives)

[Read the Zine]({{zines[0].url}}){: .btn .btn-primary}

