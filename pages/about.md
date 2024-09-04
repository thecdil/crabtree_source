---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://objects.lib.uidaho.edu/crabtree/crabtree-banner.jpg" %} 

{% include feature/nav-menu.html sections="About the Project;Project Staff;Acknowledgements;Questions" %}

## About the Project

This project was supported by a Digitizing Hidden Collections grant from the [Council on Library and Information Resources (CLIR)](https://www.clir.org/). The grant program is made possible by funding from the Mellon Foundation. 

This three-year project (4/1/2021 to 3/31/2024) was a collaborative effort between the [University of Idaho Library](https://www.lib.uidaho.edu/) and [Alfred W. Bowers Laboratory of Anthropology (AWBLA/Bowers Lab)](https://www.uidaho.edu/class/anthrolab) to digitize the Donald E. Crabtree Lithic Technology Collection. This preeminent collection includes lithic (stone) items created by Crabtree and the documents, slides, and photographs related to his work. This collection also includes unprovenanced lithic artifacts created by Native and Indigenous people, artifacts which Crabtree surface collected or which were given to him by others.

As we sought to open up this hidden collection, it became evident that we would need to engage in difficult conversations. Even if we only considered the lithic items Crabtree created, there is no doubt that he was inspired by and learned from Native and Indigenous knowledge, practices, and people, both directly and via the study of artifacts. Acknowledging that Crabtree could not have created these unique and innovative items without first learning from Native and Indigenous people challenges the incorrect and pervasive belief that knowledge cannot be culturally appropriated if it is used in a “positive” way and separated from its source. 

Furthermore, although the majority of these lithic items are Crabtree’s creations, this collection does include unprovenanced Native and Indigenous artifacts gathered via surface collection or via gifts from colleagues, artifacts whose histories and creators are unknown to us. This knowledge has compelled the grant team to find ways to constructively critique this collection and its themes, most clearly through our interviews with Advisory Board members. With this critique, we sought to be candid about cultural and knowledge appropriation and surface collecting or looting within archaeological practice and avocational flintknapping as well as push archaeology and librarianship toward greater honesty and openness when creating digital collections. 

As this project progressed and the grant team learned more about this collection and the obscured histories of the unprovenanced Native and Indigenous artifacts, it became clear that we needed to take a different approach with these items. As such, we decided not to share any 2D images or 3D models of unprovenanced artifacts created by uncredited Native and Indigenous people on the project website. This decision was based on many conversations with our Advisory Board members, our own interrogation of the ethics of archaeology and librarianship/archival science, self-reflection of our own ethics and morals in relation to this collection, and recent changes to the United States’ Native American Graves Protection and Repatriation Act ([Fitz Gibbon, 2023](https://culturalpropertynews.org/nagpra-major-changes-proposed-for-2023-to-native-american-repatriation-law/ )). The complete metadata including unprovenanced items will be available on this website, and all photos and 3D models will be preserved by the University of Idaho’s Center for Digital Inquiry and Learning (CDIL).

## Project Staff

<div class="about-narrowed-content">
{% for i in site.data.crabtree_people %}
<div class="card mb-3">
    <div class="card-body">
        <h4 class="card-title">{{ i.name }}</h4>
        <p class="card-text">{{ i.bio }}</p>
    </div>
</div>
{% endfor %}
</div>

## Acknowledgements

So many people have supported this project at various stages, and without them, it wouldn't be what it is today. These include Evan Peter Williamson, Kevin Dobbins, Olivia Wikle, Klytie Xu, Devin Becker, and Julia Stone, our current and former colleagues in the [University of Idaho’s Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu/), who shared their digitization, preservation, and CollectionBuilder expertise with us. We also want to thank [Samantha Porter](https://amaaze.umn.edu/samantha-porter), who wrote a letter of support and graciously shared her time and photogrammetry expertise; [Julia Haines](https://anthropology.cornell.edu/julia-jong-haines), who gave us permission to adapt her [photogrammetry workflow](https://scholarslab.lib.virginia.edu/blog/documentation-photogrammetry/); [Alex Nyers](https://obsidianlab.com/), who investigated whether geologic or chemical sourcing was possible for objects coated prior to photogrammetry; and Stacey Camp (Associate Professor Anthropology, Michigan State Unviersity) and Loren Davis (Professor, Oregon State University), who wrote letters of support.

We also want to give a shout out to Esther Kim, whose help, insight, and humor were instrumental.

Last but not least, we want to thank anonymous grant reviewer number 2, who when critiquing our first round grant proposal stated "1000 models seems incredibly ambitious..." We appreciate your honesty.

### Questions?

Please reach out to the [Alfred W. Bowers Laboratory of Anthropology](mailto:awbla@uidaho.edu) if you have any questions about this collection.
