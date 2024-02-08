# custom layouts

- 3d_model
- 3d_model_child --> this isn't actually used as a layout, the 3d_model layout pulls these items in for download
- crabtree_multiple --> these are multiple images of points from different angles

# object notes

objects:
17293 files 
- 2240 removed
15053 files on server

metadata:
15251 metadata records
-2113 publish = no records 
13010 metadata records

27 metadata records with no matching file 
18 id matches 'a' but no matching 'b'
3 id matches 'b' but no matching 'a'
13090 records with matching file 

display_template counts:
3d_model	135
3d_model_child	539
crabtree_multiple	3917
image	5409
multiple	1
pdf	3009

# prep notes

on server, jpg of same name exist:
CE_CB_D4_8469-a.NEF  
CE_CB_D4_8469-b.NEF
(deleted)

CE_B81_F28-Item1.jpg;CE_B81_F28-Item1.pdf
same item exists as single jpg cover and pdf of full document
removed single, kept pdf and updated metadata

2023-10 

- created a unique objectid column for every row based on identifier.
- created parentid for model files
- deduplicated, there was 212 duplicate rows. removed 108 duplicates.
- set up a parentid column for items that are related as a compound object. These are currently only for 3D models (each compound item has a parent with jpg image, plus children representing each 3d format option) and for points images (where an item has multiple images like -a, -b, -c, -d, etc). (note to Julia, these are marked as "crabtree_multiple" display_template and aren't compatible with default "multiple" template). There could be some additional items that are compound objects in the archival items, but there isn't a way to infer that from the identifiers as far as I could tell.
- linked items on the server to the metadata. There is a column "matching_objects" with the filename, plus links to the server items in "object_location", "image_small", "image_thumb".  The items with "publish?" value "no", are removed from the server, so could have a matching_objects, but do not have links. The "object_comments" column notes a few special cases (such as 27 rows which do not have a matching file on the server, the 2113 that were removed from the server). 
