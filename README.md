sale_category_list_view_extended
================================

This module extends the list view in Sales >> Product Categories & Attributes > product category and public product category view. It adds the following columns to the views:

Public Product Category:
+ ID
+ Parent Category
+ Sequence

(Internal) Product Category:
+ ID
+ Parent Category
+ Sequence
+ Left Parent
+ Right Parent

This is useful for importing data into a new database for the first time. You can setup your category tree for public and internal and the ID's are located so that importing in bulk into a specific category(ies) is made easier.
