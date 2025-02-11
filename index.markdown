---
layout: default
---

Recent work demonstrated how we can design and use coding strips, a form of comic strips with corresponding code, to enhance teaching and learning in programming. However, creating coding strips is a creative, time-consuming process. Creators have to generate stories from code (code->story) and design comics from stories (story->comic). We contribute CodeToon, a comic authoring tool that facilitates this code-driven storytelling process with two mechanisms: (1) story ideation from code using metaphor and (2) automatic comic generation from the story. We conducted a two-part user study that evaluates the tool and the comics generated by participants to test whether CodeToon facilitates the authoring process and helps generate quality comics. Our results show that CodeToon helps users create accurate, informative, and useful coding strips in a significantly shorter time. Overall, this work contributes methods and design guidelines for code-driven storytelling and opens up opportunities for using art to support computer science education.

<br/>

------

## CodeToon
CodeToon (<a href="https://codetoon.uwaterloo.ca/" target="_blank">https://codetoon.uwaterloo.ca/</a>) is a flexible authoring tool that allows users to automatically or manually generate comics from code.

## SCALABILITY
CodeToon scales to any code input, as it uses (Python) interpreter in the backend. CodeToon parses code and transpiles it into comic (programming language -> visual language). As will be explained later, comic was also designed to scale to any code input.

## COMIC DESIGN
Automatically generated comic is designed to show code semantics and execution steps. As can be seen from the demo, it can help students in several ways, e.g,. teach how to trace execution steps.


See <span class="sys-name">CodeToon</span> in action in this Video Demo.

{% if site.video %}
<div class="video-wrapper">
  <iframe src="{{site.video}}&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>
{% endif %}

## Presentation

See UIST'22 Presentation.

{% if site.video %}
<div class="video-wrapper">
  <!-- <iframe src="{{site.talk}}&color=white&rel=0&modestlogo=1" id="yt-video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
  <iframe width="560" height="315" src="https://www.youtube.com/embed/VkC54ZNO_HU?si=Ad0H_UwrBv8SqfmR&amp;start=8770" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
{% endif %}

------

## Bibtex
<pre>
@inproceedings{suh2022codetoon,
  title={CodeToon: Story Ideation, Auto Comic Generation, and Structure Mapping for Code-Driven Storytelling},
  author={Suh, Sangho and Zhao, Jian and Law, Edith},
  booktitle={Proceedings of the 35th Annual ACM Symposium on User Interface Software and Technology},
  pages={1--16},
  year={2022}
}
</pre>