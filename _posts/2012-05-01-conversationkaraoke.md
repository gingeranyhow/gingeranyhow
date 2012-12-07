---
layout: custom_project
image: /img/projects/karaoke/girl-in-woods.jpg
video_1: /video/small_karaoke_vid.mp4
title: Conversation Karaoke
tags: ['performance', 'video']
categories : [projects, row2]
smallphoto-1: /img/projects/karaoke/cat-instagram.jpg
smallphoto-2: /img/projects/karaoke/girl-in-woods.jpg
smallphoto-3: /img/projects/karaoke/girl-on-beach.jpg
smallphoto-4: /img/projects/karaoke/zen-guy.jpg
---
<div>
  <div class="grid_4">
    <h2 class="project_title">{{ page.title }}</h2>
    <div class="longer-expl">
      <p>Here are four eample selections from a larger Conversation Karaoke canon. In Conversation Karaoke, two participants come on stage and speak the conversation as it comes on the screen.</p>
      <p>These selections are technology-focused, and were created for a Tech Talk presented at the May episode of <a href="http://oaklandnightslive.com/" src="Link to Karaoke Conversation">Oakland Nights... Live!</a>.</p>
      <p>Enjoy the video sample to the right, or screengrabs below</p>
    </div>
  </div>

  <div class="grid_8">
      <object classid="clsid:02BF25D5-8C17-4B23-BC80-D3488ABDDC6B" codebase="http://www.apple.com/qtactivex/qtplugin.cab" width="720" height="526">
        <param name="src" value="{{ page.video_1 }}" />
        <param name="autoplay" value="false" />
        <param name="type" value="video/quicktime"  width="720" height="526"/>
        <embed src="{{ page.video_1 }}"  width="600" height="438" scale="tofit" autoplay="false" type="video/quicktime" pluginspage="http://www.apple.com/quicktime/download/"></embed>
    </object>
  </div>
  <div class="clear"></div>
</div>

<div>
  <div class="grid_6">
    <a href="{{ post.url }}">
        <img class="project-image" src="{{ page.smallphoto-1 }}" width="440">
      </a>
  </div>

  <div class="grid_6">
    <div class="lowlight_text">
      <a href="{{ post.url }}">
        <img class="project-image" src="{{ page.smallphoto-2 }}" width="440">
      </a>
    </div>
  </div>
  <div class="clear"></div>
</div>

<div class="grid_6">
  <a href="{{ post.url }}">
      <img class="project-image" src="{{ page.smallphoto-3 }}" width="440">
    </a>
</div>
<!-- end .grid_6 -->

<div class="grid_6">
  <div class="lowlight_text">
    <a href="{{ post.url }}">
      <img class="project-image" src="{{ page.smallphoto-4 }}" width="440">
    </a>
  </div>
</div>
<!-- end .grid_6 -->


<!-- <img src="/img/projects/karaoke/cat-instagram.jpg" />
<img src="/img/projects/karaoke/girl-in-woods.jpg" />
<img src="/img/projects/karaoke/girl-on-beach.jpg" />
<img src="/img/projects/karaoke/zen-guy.jpg" /> -->


