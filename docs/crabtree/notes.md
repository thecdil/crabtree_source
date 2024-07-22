# custom layouts

- 3d_model --> parent records for 3d_model items. The model files are in child records. 3d_model parents may also have artifact_image and image children. The layout displays the image gallery plus ability to load models.
- 3d_model_child --> this isn't actually used as a layout, the 3d_model layout pulls these items in for download
- artifact_image --> this layout supports single image items, or "multiple" style records with child images for multiple images of points from different angles. Importantly, these are different from standard CB multiple items, because they display and download the parent record as the first item on the page, not just the children.
- image --> this layout is for child multiple images only

# metadata notes

The metadata is split into three sets found in "_data": 

- crabtree_artifacts.csv (6914 rows) items flintknapped by Crabtree or given to him, excluding unprovenanced indigenous creators. Used to generate the "Crabtree Flintknapping" section of the site.
- crabtree_archives.csv (4411 rows) personal Crabtree archives items such as documents, letters, and slides. Used to generate the "Crabtree Archives" section of the site.
- crabtree_no_publish.csv (3953 rows) artifact and archive items that after review were considered not suitable for publication, due to lack of provenance, sensitive content, or issues with the digitized files. These records are not directly visible on the site, but are included in data outputs for download.

# object notes

Artifacts:

- a batch of items marked "no" in "publish" column were originally removed (crabtree_publish_no.csv).
- a batch of items by indigenous creators were removed.
- after review, a batch of "no" publish items created by Crabtree were re-added to the collection (crabtree_to_be_added_2024-06-20.csv).
- "crabtree_missing_multiple.csv" items are in the collection (except where removed for indigenous creators), but appear to be missing a related image.

On libobjects:
- 3012 pdf
- 11468 .jpg
- 14476 _sm.jpg smalls
- 14476 _th.jpg thumbs
- 144 .mtl
- 144 .obj
- 145 .stl
- 143 .x3d

metadata:
- 13010 metadata records
- 2113 publish = no records 

extensions count in metadata:
- jpg	9437
- mtl	135
- obj	135
- pdf	3007
- stl	135
- x3d	134
- (blank)	27 (rows with no matching file)

problems:
- 27 metadata records with no matching file 
- 18 id matches 'a' but no matching 'b'
- 3 id matches 'b' but no matching 'a'

display_template counts:
- 3d_model	135
- 3d_model_child	539
- crabtree_multiple	3917
- image	5409
- multiple	1
- pdf	3009

group counts:
- archive 4410
- artifact 4082
- (blank) 4518 (child objects)

# prep notes

on server, jpg of same name exist:
CE_CB_D4_8469-a.NEF  
CE_CB_D4_8469-b.NEF
(deleted)

CE_B81_F28-Item1.jpg;CE_B81_F28-Item1.pdf
same item exists as single jpg cover and pdf of full document
removed single, kept pdf and updated metadata

for f in *.JPG; do mv "$f" "${f%.JPG}.jpg"; done

2023-10 

- created a unique objectid column for every row based on identifier.
- created parentid for model files
- deduplicated, there was 212 duplicate rows. removed 108 duplicates.
- set up a parentid column for items that are related as a compound object. These are currently only for 3D models (each compound item has a parent with jpg image, plus children representing each 3d format option) and for points images (where an item has multiple images like -a, -b, -c, -d, etc). (note to Julia, these are marked as "crabtree_multiple" display_template and aren't compatible with default "multiple" template). There could be some additional items that are compound objects in the archival items, but there isn't a way to infer that from the identifiers as far as I could tell.
- linked items on the server to the metadata. There is a column "matching_objects" with the filename, plus links to the server items in "object_location", "image_small", "image_thumb".  The items with "publish?" value "no", are removed from the server, so could have a matching_objects, but do not have links. The "object_comments" column notes a few special cases (such as 27 rows which do not have a matching file on the server, the 2113 that were removed from the server). 
