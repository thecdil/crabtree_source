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

In total, this project website includes 2D photos of # of lithic items created by Crabtree; # of unprovenanced lithic items created by Native and Indigenous peoples; and # of documents, photos, and slides. This website also includes 3D models of # of lithic items created by Crabtree; these models can be viewed on the site as well as downloaded for printing.

This website was built with assistance from the [University of Idaho’s Center for Digital Inquiry and Learning (CDIL)](https://cdil.lib.uidaho.edu/) and was generated using CollectionBuilder, an open source, minimal infrastructure platform developed by a team of librarians at the University of Idaho.

### People

<div class="row mt-3">
{% for i in site.data.crabtree_people %}
<div class="col-md-6">
    <div class="card mb-3">
        <div class="card-body">
            <h4 class="card-title">{{ i.staff }}</h4>
            <p class="card-text">{{ i.bio }}</p>
            <a href="{{ '/items/' | append: i.objectid | append: '.html' | relative_url }}" class="btn btn-sm btn-outline-primary">View Interview</a>
        </div>
    </div>
</div>
{% endfor %}
</div>

Leah Evans-Janke (Ph.D. Historical Archaeology; Co-principal investigator) was the Collections Manager at the Alfred W. Bowers Laboratory of Anthropology for 25 years. In this role, Evans-Janke acted as steward to 750 archaeological and historic collections; led public outreach efforts; oversaw digitization efforts; facilitated research requests; supervised lab assistants; and served as PI or co-PI on various contracts and grants.   

Marco Seiferle-Valencia (Co-principal investigator) is the Open Education Librarian at the University of Idaho Library. In this role, Seiferle-Valencia collaborates with faculty to develop innovative, culturally responsive digital content. Through previous positions as the Digital Scholarship Outreach Librarian (Michigan State University) and University Library Associate (University of Michigan Libraries), Seiferle-Valencia has developed expertise in digital scholarship, digitization, culturally responsive humanities work, and photography. He is also the Technical Director and Co-Founder of the “Chicana por mi Raza Digital Memory Collective.” 

Jylisa Kenyon (Co-principal investigator) is the Social Sciences Librarian at the University of Idaho Library. In this role, she serves as the liaison to the Department of Sociology/Anthropology; manages the Library’s social science collections; provides information literacy instruction within social science courses; and conducts research consultations for students, faculty, and staff across disciplines.

Robert (Lee) Sappington (Key project staff) has a lifelong interest in lithic technology.  He met Don Crabtree in 1975 and worked with him on locating obsidian sources in Idaho and elsewhere until 1980.  He completed his UI master’s thesis on the pre-contact Lydle Gulch site on the Boise River in 1981 and his WSU doctoral dissertation on the 11,000-year archaeological record of the Clearwater River Region in 1994.   He taught numerous courses at UI from the 1990s to the present including Lithic Technology and has been the chair of more than 50 MA committees.  He is now an Emeritus Associate Professor of Anthropology. Throughout this project, Sappington served as an advisor and created in-depth metadata for the artifacts that were digitized in 3D.

Allison Fashing (Key project staff) served as the Digitization Manager at the Alfred W. Bowers Laboratory of Anthropology, where she had worked on and off since her freshman year at the University of Idaho. During this grant-term position, she managed three student employees and the creation of the digital data of the Crabtree Collection. Leading the team, she focused on creating 3D models using photogrammetry as well as facilitating 2D artifact photography, metadata creation and social media posts.

Timothy Mace (Key contributor) is a laboratory technician at the Alfred W. Bowers Laboratory of Anthropology, where he has worked on and off since his Master’s studies at the U of I. He currently updates archaeological collections for long term storage and research use, facilitates research, manages the Pacific Northwest Anthropological Archive, and assists in office management. In connection with the Crabtree Collection, Mace has helped with some photogrammetry as well as 3D printing based upon the models created.

Chloe Dame, Jessica Holler, and Savannah Johnson (Key project staff) worked as undergraduate Digitization Assistants and completed all required digitization assigned by the grant team, including mixed archival documents, photographs, slides, and negatives. They also took the lead on creating social media posts.

Evan Williamson (Key contributor) built our project website using CollectionBuilder and built a 3D model viewer for use on the website.

Julia Stone (Key contributor) supported the development of the project website.

Olivia Wikle (Key contributor) oversaw the preservation of all AWBLA files once they are transferred to the Center for Digital Inquiry and Learning (CDIL) and has organized and documented their directory structure in CDIL’s digital archive to ensure continued preservation and future dissemination.

Kevin Dobbins (Key contributor) participated in the weekly transfer of files from the AWBLA to CDIL and offers knowledge and expertise for scanning large documents as well as creating batch processing actions within Adobe Photoshop.

Klytie Xu (Key contributor) participated in the weekly transfer of files from the AWBLA to CDIL.

Brittany McNeill (College Fiscal Officer, University of Idaho Library) served as the main financial contact for this project and maintained a pay-period tracking sheet to monitor the expended wages and fringe for each employee.
