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

This three-year project (4/1/2021 to 3/31/2024) was a collaborative effort between the [University of Idaho Library](https://www.lib.uidaho.edu/) and [Alfred W. Bowers Laboratory of Anthropology (AWBLA/Bowers Lab)](https://www.uidaho.edu/class/anthrolab) to digitize the Donald E. Crabtree Lithic Technology Collection. This preeminent collection includes lithic (stone) items created by Crabtree and the documents, slides, and photographs related to his work. This collection also includes unprovenanced lithic artifacts created by Native and Indigenous people, artifacts which Crabtree surface collected or which were given to him by others. We estimate the collection is about 15% Indigenous created. 

Donald E. Crabtree (1912-1980) was an influential American experimental archaeologist, who's innovative efforts helped establish the field of experimental archaeology. Throughout his life, Crabtree developed his hobby into a true mastery of flintknapping, complete with his own distinct styles, technical innovations, and signature creative practices, along with a truly world class knowledge and understanding of stone tools and their creation.  

 {% include feature/image.html objectid="https://objects.lib.uidaho.edu/crabtree/small/ce_cd_d4_3508-a_sm.jpg" width="75" alt="A flintworked stone, the stone is red and heart shaped" caption="Crabtree was particulary well-known for his incredible free form eccentrics, many of which are at scales of 1 to 2 inches or less" %}_Browse more Crabtree [eccentrics](artifacts/browse.html#eccentric)._

Crabtree continues to be a major influence in experimental archaeology today, with his legacy living on in the form of his many incredible original flintknapped pieces, his textbook "An Introduction to Flintworking" - which is still an authoritative resource on lithics terminology, and in the living knowledge he passed onto participants in his field school, knowledge which those participants have in many cases passed along to their children and students.

{% include feature/image.html objectid="ce_731_item7;" %}

While there is no doubt that Crabtree is an incredible archaeologist and arguably artist of the highest order, some of the common practices of his time, such as surface collecting, create complicated legacies within the collection that must be contended with as it is shared in contemporary times. Crabtree lived in an era of the real erasure of Native American lives, cultures, and histories via explict laws, resettlement policies, and discrimination and brutality. At the same time, the dominant culture often simulatenosuly celebrated the imitation and performance of Native arts, crafts, and tradition by non-Native people. This is the complicated tablaeu in which Crabtree lived and worked, and through which now we must seek to understand his collection and accomplishments. 

{% include feature/image.html objectid="ce_b83_f3-item1-030;ce_b83_f3-item1-028;" %}
*For much of the history of modern archaeology, surface collecting such as seen here, has been a common practice. Surface collecting can happen as both part of formal archaeological work, wherein found items are documented and carefully classified, and, in more recreational ways or even looting, wherein objects are taken with financial gains in mind. Today's views in archaeology are that found items in the field should be photographed and reported to local cultural heritage authorities, and above all, left in the field as found.* 

Crabtree was also someone who in many ways was an outsider or rebel of sorts, in his case to mainstream academia. He first earned his reputation through his incredible skill for flintknapping, versus formal credentials and accolades. Throughout his life he held several occupations, all while still working and developing his flintknapping skill and knowledge with the help of a global network of colleagues and friends. Even a quick scan through his archives reveals Don as a person who loved to travel and explore, and who counted friends around the world as his colleagues and peers. These widespread roots demonstrate Crabtree's breadth and reach, and also add an additional layer of complication when it comes to working with these artifacts by modern standards. Crabtree's collection contains a consternating mix of original pieces by Crabtree, pieces he surface collected here in North America, and pieces sent to him by friends and colleagues from around world, some of which were likewise orignal creations and others that were found in the field and sent to him.

{% include feature/image.html objectid="ce_b81_f19-item2;" %}

As we sought to open up this hidden collection, it became evident that we would need to engage in difficult conversations to attempt to do right by both Crabtree, and the Native and Indigenous knowledges explicitly and implictly found in the collection. Even if we only considered the lithic items Crabtree himself created, there is no doubt that he was inspired by and learned from Native and Indigenous knowledge, practices, and people, both directly and via the study of artifacts. Many contemporary conversations in galleries, libraries, archives, and museums focus on repatriation of Native and Indigenous belogings as the primary solution or intervention. The Crabtree Collections presented two major challenge in this respect, namely - 1) how can the Native and Indigenous knowldges and histories that Crabtree built on with his original creations be recognized? and, 2) what is the most ethical way to engage with the Indigenous created points and items that cannot have proper provenance for repatriation established?

These questions are not eaisly answered or resolved. Instead we approachd them by searching for ways to constructively critique this collection and its themes, most clearly through our interviews with Advisory Board members. With this critique, we sought to be candid about cultural and knowledge appropriation and surface collecting or looting within archaeological practice and avocational flintknapping, as well as push archaeology and librarianship toward greater honesty and openness when creating digital collections. 

While we had initially conceptualized that the website would contain some of the exemplary Native or Indigenous created pieces, as the project progressed and the grant team learned more about this collection and the obscured histories of the unprovenanced artifacts, it became clear that we needed to take a different approach with these items. As such, we decided not to share any 2D images or 3D models of unprovenanced artifacts created by uncredited Native and Indigenous people on the project website. This decision was based on many conversations with our Advisory Board members, our own interrogation of the ethics of archaeology and librarianship/archival science, self-reflection of our own ethics and morals in relation to this collection, and recent changes to the United States’ Native American Graves Protection and Repatriation Act ([Fitz Gibbon, 2023](https://culturalpropertynews.org/nagpra-major-changes-proposed-for-2023-to-native-american-repatriation-law/ )). The complete metadata including unprovenanced items will be available on this website, and all photos and 3D models will be preserved by the University of Idaho’s Center for Digital Inquiry and Learning (CDIL).

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
