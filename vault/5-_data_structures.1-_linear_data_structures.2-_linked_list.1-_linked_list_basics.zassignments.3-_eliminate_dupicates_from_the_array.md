---
id: Hmh5uKwqnS7Fbb2BegWY2
title: 3 _eliminate_dupicates_from_the_array
desc: ''
updated: 1644767656956
created: 1644767656956
stub: false
isDir: false
---
# 3. Eliminate dupicates from the array
Created Saturday 18 January 2020


* Doing step by step.
* For empty or uni list return;
* We are going to delete the next element from the current. The empty and uni takes care that the head is never deleted.
* while(trav->next!=NULL), i.e till we are the last node.

{
if (trav->next->data = trav->data)
{
node* to_be_deleted = trav->next;
trav->next = trav->next->next;
delete to_be_deleted;
}
// do not move forward as there may be more than 2 duplicates in a row. Move only if we find that the next is different.
else
trav = trav->next;
}

