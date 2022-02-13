---
id: kOz4DRVCRCpxF7UtYjteO
title: 1 _linear_search_in_ll
desc: ''
updated: 1644767656956
created: 1644767656956
stub: false
isDir: false
---
# 1. Linear Search in LL
Created Friday 17 January 2020

int indexOfNIter(Node *head, int n) 
{
Node* trav = head;
for(int i=0; trav!=NULL; i++) // i is only for counting the indexes
{
if(trav->data==n)
return i;
trav = trav -> next;
}
// Node not present or empty list
return -1;
}


* Easy.


