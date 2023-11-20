---
layout: default
title: "Home"
---

<!---FOR EVERYONE-->

<!---Hero (Plain Text)-->
{% capture home-hero-title %}
Transform to Open Science
{% endcapture %}

<!---Four Column Orange CTA (Plain Text)-->
{% capture home-hero-description %}
NASA's Transform to Open Science (TOPS) initiative is designed to transform agencies, organizations, and communities to an inclusive culture of open science. TOPS's first priority is to develop the infrastructure to train scientists and researchers as part of our 5-year program. The open science curriculum will introduce those beginning their open science journey to important definitions, tools, and resources; and provide participants at all levels recommendations on best practices.
{% endcapture %}
<!---Four Column Orange CTA Titles-->
{% assign home-fourcta-title-one = "Enroll in Curriculum" %}
{% assign home-fourcta-title-two = "Sign Up For Newsletter" %}
{% assign home-fourcta-title-three = "Attend TOPS Events" %}
{% assign home-fourcta-title-four = "Explore Our GitHub" %}
<!---Four Column Orange CTA Descriptions-->
{% assign home-fourcta-desc-one = "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et." %}
{% assign home-fourcta-desc-two = "In massa tempor nec feugiat nisl pretium fusce id. Scelerisque viverra mauris in aliquam. Quam id leo." %}
{% assign home-fourcta-desc-three = "Facilisi cras fermentum odio eu feugiat pretium. Bibendum at varius vel pharetra. Quis lectus nulla." %}
{% assign home-fourcta-desc-four = "Id semper risus in hendrerit gravida rutrum quisque non tellus. Semper eget duis at tellus at. Consequat." %}
<!---Four Column Orange CTA Links-->
{% assign home-fourcta-link-one = "#test1" %}
{% assign home-fourcta-link-two = "#test2" %}
{% assign home-fourcta-link-three = "https://github.com/nasa/Transform-to-Open-Science/blob/main/docs/Area1_Engagement/Outreach/tops_conferences.md" %}
{% assign home-fourcta-link-four = "https://github.com/nasa/Transform-to-Open-Science/" %}

<!---What is TOPS-->
<!---What is TOPS Title (Plain Text)-->
{% capture home-whatistops-title %}
What is TOPS?
{% endcapture %}
<!---What is TOPS Description (Markdown)-->
{% capture home-whatistops-description %}
The Transform to Open Science (TOPS) mission is a NASA initiative designed to rapidly transform agencies, organizations, and communities to an inclusive culture of open science. TOPS is part of NASA’s Open-Source Science Initiative. NASA's TOPS mission will allow us to create a scientific culture that is ready for 21st century challenges.
{% endcapture %}
<!---What is TOPS Link One Text (Plain Text)-->
{% capture home-whatistops-linkone_text %}
Enroll Now
{% endcapture %}
<!---What is TOPS Link Two Text (Plain Text)-->
{% capture home-whatistops-linktwo_text %}
Learn More
{% endcapture %}
<!---What is TOPS Link One URL-->
{% capture home-whatistops-linkone_url %}
#test1
{% endcapture %}
<!---What is TOPS Link Two URL-->
{% capture home-whatistops-linktwo_url %}
#test2
{% endcapture %}

<!---FOR DEVELOPER ONLY (UNLESS YOU FEEL BRAVE)-->

{% assign home-fourcta-icon-one = "fa-solid fa-chalkboard-user" %}
{% assign home-fourcta-icon-two = "fa-brands fa-readme" %}
{% assign home-fourcta-icon-three = "fa-solid fa-calendar-days" %}
{% assign home-fourcta-icon-four = "fa-brands fa-github" %}

{% capture home-fourcta-titles %}{{ home-fourcta-title-one }}#{{ home-fourcta-title-two }}#{{ home-fourcta-title-three }}#{{ home-fourcta-title-four }}{% endcapture %}
{% assign home-fourcta-titles-split = home-fourcta-titles | split: "#" %}

{% capture home-fourcta-descs %}{{ home-fourcta-desc-one }}#{{ home-fourcta-desc-two }}#{{ home-fourcta-desc-three }}#{{ home-fourcta-desc-four }}{% endcapture %}
{% assign home-fourcta-descs-split = home-fourcta-descs | split: "#" %}

{% capture home-fourcta-links %}{{ home-fourcta-link-one }},{{ home-fourcta-link-two }},{{ home-fourcta-link-three }},{{ home-fourcta-link-four }}{% endcapture %}
{% assign home-fourcta-links-split = home-fourcta-links | split: "," %}

{% capture home-fourcta-icons %}{{ home-fourcta-icon-one }}#{{ home-fourcta-icon-two }}#{{ home-fourcta-icon-three }}#{{ home-fourcta-icon-four }}{% endcapture %}
{% assign home-fourcta-icons-split = home-fourcta-icons | split: "#" %}

{% include home/hero.html %}
{% include home/whatistops.html %}
{% include home/posts.html %}
{% include home/strategies.html %}
{% include home/OS101.html %}
{% include home/events.html %}