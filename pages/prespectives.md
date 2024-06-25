---
title: Native Perspectives on Flintknapping
layout: page
permalink: /perspectives.html
---

## Native Perspective on Flintknapping

One of our main goals when creating this project was to form an Advisory Board of Native and Indigenous artists, researchers, scholars, and graduate students with expertise and/or interests in art, archaeology/anthropology, history, libraries/archives, and/or digital collections. The scope and tasks for our Advisory Board shifted throughout the course of this project, but we eventually settled on forming a group who would come together to discuss topics related to the digitization of lithic artifacts, the presentation of Native and Indigenous provenanced artifacts on the website, and opportunities for challenging the colonial narratives that surround flintknapping today. 

In addition to these group meetings, we also felt it would be instrumental to provide our Advisory Board members with an opportunity to share their expertise as it related to this project - and as a result, our idea to conduct individual interviews with each Advisory Board member was created. When conducting these interviews, each of our seven Advisory Board members were asked the same initial five questions, with the remaining questions focused on their own areas of expertise or research.

On the following pages, you’ll be able to access each of our seven interviews with our Advisory Board members. These interviews are presented using Oral History as Data, a unique tool that allows you to watch or listen to the interview and read the transcript at the same time.

The views and opinions expressed in these interviews are those of the participants and do not necessarily reflect the views or opinions of others involved or any entities that they are part of. The participants’ views and opinions are based on their own personal and professional perspectives and expertise at the time of recording.

### Advisory Board Interviews

<div class="row mt-3">
{% for i in site.data.crabtree_interviews %}
<div class="col-md-6">
    <div class="card mb-3">
        <div class="card-body">
            <h4 class="card-title"><a href="{{ '/items/' | append: i.objectid | append: '.html' | relative_url }}" class="text-dark">{{ i.interviewee }}</a></h4>
            <p class="card-text">{{ i.bio }}</p>
            <a href="{{ '/items/' | append: i.objectid | append: '.html' | relative_url }}" class="btn btn-sm btn-outline-primary">View Interview</a>
        </div>
    </div>
</div>
{% endfor %}
</div>
