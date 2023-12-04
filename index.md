---
layout: default
title: "Home"
---

<!---FOR EVERYONE-->

<!---START Hero (Plain Text)-->
<!---Hero Title-->
{% capture home-hero-title %}
Transform to Open Science
{% endcapture %}
<!---Hero Description-->
{% capture home-hero-description %}
NASA's Transform to Open Science (TOPS) initiative is designed to transform agencies, organizations, and communities to an inclusive culture of open science. TOPS's first priority is to develop the infrastructure to train scientists and researchers as part of our 5-year program. The open science curriculum will introduce those beginning their open science journey to important definitions, tools, and resources; and provide participants at all levels recommendations on best practices.
{% endcapture %}
<!---END Hero-->


<!---START Four Column Orange CTA (Plain Text)-->
<!---Four Column Orange CTA Titles-->
{% assign home-fourcta-title-one = "Enroll in Curriculum" %}
{% assign home-fourcta-title-two = "Sign Up For Newsletter" %}
{% assign home-fourcta-title-three = "Attend TOPS Events" %}
{% assign home-fourcta-title-four = "Explore Our GitHub" %}
<!---Four Column Orange CTA Descriptions-->
{% assign home-fourcta-desc-one = "Increase the impact of your research and enhance your resume and proposals with Open Science 101." %}
{% assign home-fourcta-desc-two = "Please join the TOPS email list to hear about open science activities, stories, and news." %}
{% assign home-fourcta-desc-three = "Attend conferences with TOPS to learn about open science and the Open Science 101 curriculum." %}
{% assign home-fourcta-desc-four = "Engage with our community, learn more about open science, and contribute to our curriculum." %}
<!---Four Column Orange CTA Links-->
{% assign home-fourcta-link-three = "https://github.com/nasa/Transform-to-Open-Science/blob/main/docs/Area1_Engagement/Outreach/tops_conferences.md" %}
{% assign home-fourcta-link-four = "https://github.com/nasa/Transform-to-Open-Science/" %}
<!---END Four Column Orange CTA-->


<!---START What is TOPS-->
<!---What is TOPS Title (Plain Text)-->
{% capture home-whatistops-title %}
What is TOPS?
{% endcapture %}
<!---What is TOPS Description (Markdown)-->
{% capture home-whatistops-description %}
The Transform to Open Science (TOPS) mission is a NASA initiative designed to rapidly transform agencies, organizations, and communities to an inclusive culture of open science. TOPS is part of NASA’s Open-Source Science Initiative. NASA's TOPS mission will allow us to create a scientific culture that is ready for 21st century challenges.
{% endcapture %}
<!---What is TOPS Enroll Now Text (Plain Text)-->
{% capture home-whatistops-linkone_text %}
Enroll Now
{% endcapture %}
<!---What is TOPS Learn More Text (Plain Text)-->
{% capture home-whatistops-linktwo_text %}
Learn More
{% endcapture %}
<!---What is TOPS Learn More Link-->
{% capture home-whatistops-linktwo_url %}
#test2
{% endcapture %}
<!---END What is TOPS-->


<!---START Recent Posts-->
<!---What is TOPS Title (Plain Text)-->
{% capture home-posts-title %}
Recent Posts
{% endcapture %}
<!---Recent Posts Description (Markdown)-->
{% capture home-posts-description %}
Explore blog posts to discover compelling open science success stories and gain valuable insights into the evolving landscape of transparent and collaborative research. Engaging with these narratives provides a firsthand account of the positive impact open science can have on various fields, inspiring a deeper appreciation for its principles and potential benefits.
{% endcapture %}
<!---Recent Posts Tell Your Story Text (Plain Text)-->
{% capture home-posts-linkone_text %}
Tell Your Story
{% endcapture %}
<!---Recent Posts View All Text (Plain Text)-->
{% capture home-posts-linktwo_text %}
View All
{% endcapture %}
<!---Recent Posts Tell Your Story Link-->
{% capture home-posts-linkone_url %}
https://forms.gle/X4omhrAhhGZYMs6c7
{% endcapture %}
<!---END Recent Posts-->


<!---START TOPS Strategies-->
<!---TOPS Strategies (Plain Text)-->
{% capture home-strat-title %}
TOPS Strategies
{% endcapture %}
<!---TOPS Strategies Description (Markdown)-->
{% capture home-strat-description %}
TOPS Open Science mission strategy is centered around fostering a collaborative and transparent research ecosystem,  increasing awareness of Open Science in Action, highlighting the greater impact of scientific efforts and more equitable access to science results.
{% endcapture %}
<!---Engagement Description-->
{% capture home-strat-engagement-desc %}
TOPS engages with researchers and institutions by attending conferences, publishing stories, and expanding knowledge of open science.
{% endcapture %}
<!---Capacity Sharing Description-->
{% capture home-strat-capacity-desc %}
Promotes the exchange of knowledge, data, and resources through the open science 101 curriculum, workshops, events, cohorts, and more.
{% endcapture %}
<!---Incentives Description-->
{% capture home-strat-incentives-desc %}
Encourages and rewards research utilizing open science practices through OS101 badging, high profile awards, and funding opportunities.
{% endcapture %}
<!---Coordination Description-->
{% capture home-strat-coordination-desc %}
Emphasizes collaboration with the broader community to ensure efforts align with the global advancement of open and accessible research.
{% endcapture %}
<!---END TOPS Strategies-->




<!---FOR DEVELOPER ONLY (UNLESS YOU FEEL BRAVE)-->

{% assign home-fourcta-link-one = site.baseurl | append: "/" | append: site.enrollbutton %}
{% assign home-fourcta-link-two = site.baseurl | append: "/" | append: site.signupbutton %}

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