---
title: About
layout: page
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="https://www.uidaho.edu/-/media/UIdaho-Responsive/Images/class/special-programs/anthro-lab/banners/crabtree.jpg" %} 

{% include feature/nav-menu.html sections="About the Project;Donald E. Crabtree Lithic Technology Collection;Donald E. Crabtree Biography" %}

## About the Project

“Digitizing the Donald E. Crabtree Lithic Comparative Collection in 2D and 3D” was supported by a Digitizing Hidden Collections grant from the [Council on Library and Information Resources (CLIR)](https://www.clir.org/). The grant program is made possible by funding from the Mellon Foundation. This three-year project (4/1/2021 to 3/31/2024) was a collaborative effort between the [University of Idaho Library](https://www.lib.uidaho.edu/) and [Alfred W. Bowers Laboratory of Anthropology (AWBLA/Bowers Lab)](https://www.uidaho.edu/class/anthrolab) to digitize the Donald E. Crabtree Lithic Technology Collection. This preeminent collection includes lithic (stone) items created by Crabtree and the documents, slides, and photographs related to his work. This collection also includes unprovenanced lithic artifacts created by Native and Indigenous people, artifacts which Crabtree surface collected or which were given to him by others.

As we sought to open up this hidden collection, it became evident that we would need to engage in difficult conversations. Even if we only considered the lithic items Crabtree created, there is no doubt that he was inspired by and learned from Native and Indigenous knowledge, practices, and people, both directly and via the study of artifacts. Acknowledging that Crabtree could not have created these unique and innovative items without first learning from Native and Indigenous people challenges the incorrect and pervasive belief that knowledge cannot be culturally appropriated if it is used in a “positive” way and separated from its source. Furthermore, although the majority of these lithic items are Crabtree’s creations, this collection does include unprovenanced Native and Indigenous artifacts gathered via surface collection or via gifts from colleagues, artifacts whose histories and creators are unknown to us. This knowledge has compelled the grant team to find ways to constructively critique this collection and its themes, most clearly through our interviews with Advisory Board members. With this critique, we sought to be candid about cultural and knowledge appropriation and surface collecting or looting within archaeological practice and avocational flintknapping as well as push archaeology and librarianship toward greater honesty and openness when creating digital collections.

This website was built with assistance from the [University of Idaho’s Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu/) and was generated using CollectionBuilder, an open source, minimal infrastructure platform developed by a team of librarians at the University of Idaho.

Tthis project website includes approximately 3,264 2D photosand 117 3D models of lithic items created by Crabtree and 4,736 documents, photographs, negatives, and slides from Crabtree's personal archives.

In total, 1,618 2D images and 46 3D models will not be actively shared on the project website as they are unprovenanced artifacts created by uncredited Native and Indigenous people. This decision not to share these items is based on our conversations with Advisory Board members, our own interrogation of the ethics of archaeology and librarianship/archival science, and recent changes to the United States’ Native American Graves Protection and Repatriation Act. Since these artifacts are unprovenanced, we were unable to confirm whether they were funerary, sacred, or of cultural patrimony, and even if they were not any of these things, we determined it would be unethical to display the facsimiles of these artifacts on the project website because we didn’t have permission from their creators or their associated Tribes. In an effort to avoid the further erasure of Native and Indigenous flintknapping knowledge in this collection and to uphold our agreement with CLIR, all metadata for these artifacts will be downloadable on the project website and all 2D photos and 3D models will be preserved by the [University of Idaho’s Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu/).

### People

<div class="row mt-3">
{% for i in site.data.crabtree_people %}
<div class="col-md-6">
    <div class="card mb-3">
        <div class="card-body">
            <h4 class="card-title">{{ i.staff }}</h4>
            <p class="card-text">{{ i.bio }}</p>
        </div>
    </div>
</div>
{% endfor %}
</div>
