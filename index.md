---
layout: default
title: "Home"
---

{% capture first-section %}

## First Section

First section text

{% endcapture %}

{% capture second-section %}

## Second Section

Second section text

{% endcapture %}

<!---Content for you to edit-->

<!---Plain Text-->
{% capture home-hero-title %}
Transform to Open Science
{% endcapture %}

<!---Plain Text-->
{% capture home-hero-description %}
NASA's Transform to Open Science (TOPS) initiative is designed to transform agencies, organizations, and communities to an inclusive culture of open science. TOPS's first priority is to develop the infrastructure to train scientists and researchers as part of our 5-year program. The open science curriculum will introduce those beginning their open science journey to important definitions, tools, and resources; and provide participants at all levels recommendations on best practices.
{% endcapture %}

{% assign home-fourcta-title-one = "Enroll in Curriculum" %}
{% assign home-fourcta-title-two = "Sign Up For Newsletter" %}
{% assign home-fourcta-title-three = "Explore TOPS Events" %}
{% assign home-fourcta-title-four = "Enroll Our GitHub" %}

{% assign home-fourcta-desc-one = "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et." %}
{% assign home-fourcta-desc-two = "In massa tempor nec feugiat nisl pretium fusce id. Scelerisque viverra mauris in aliquam. Quam id leo." %}
{% assign home-fourcta-desc-three = "Facilisi cras fermentum odio eu feugiat pretium. Bibendum at varius vel pharetra. Quis lectus nulla." %}
{% assign home-fourcta-desc-four = "Id semper risus in hendrerit gravida rutrum quisque non tellus. Semper eget duis at tellus at. Consequat." %}


<!---No need to worry about any of this unless you know what you are doing-->

{% assign home-fourcta-icon-one = "fa-solid fa-chalkboard-user" %}
{% assign home-fourcta-icon-two = "fa-brands fa-readme" %}
{% assign home-fourcta-icon-three = "fa-solid fa-calendar-days" %}
{% assign home-fourcta-icon-four = "fa-brands fa-github" %}

{% capture home-fourcta-titles %}{{ home-fourcta-title-one }}#{{ home-fourcta-title-two }}#{{ home-fourcta-title-three }}#{{ home-fourcta-title-four }}{% endcapture %}
{% assign home-fourcta-titles-split = home-fourcta-titles | split: "#" %}

{% capture home-fourcta-descs %}{{ home-fourcta-desc-one }}#{{ home-fourcta-desc-two }}#{{ home-fourcta-desc-three }}#{{ home-fourcta-desc-four }}{% endcapture %}
{% assign home-fourcta-descs-split = home-fourcta-descs | split: "#" %}

{% capture home-fourcta-icons %}{{ home-fourcta-icon-one }}#{{ home-fourcta-icon-two }}#{{ home-fourcta-icon-three }}#{{ home-fourcta-icon-four }}{% endcapture %}
{% assign home-fourcta-icons-split = home-fourcta-icons | split: "#" %}

{% include template.html %}
{% include home/hero.html %}