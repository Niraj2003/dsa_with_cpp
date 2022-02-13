---
id: QAPVSnCg22gAK7rDVWj33
title: 4 _delete_node_recursive
desc: ''
updated: 1644767656956
created: 1644767656956
stub: false
isDir: false
---
# 8. Delete Node recursive
Created Friday 17 January 2020

Node* deleteNodeRec(Node *head, int i) 
{
if(head==NULL && i!=0)
return head;
    
if(i==0)
{
if(head==NULL)
return NULL;
        
Node* p = head->next;
delete head;
return p;
}
    
head -> next = deleteNodeRec(head->next, i-1);
}


* Using the same invariant for LL's as in insertNodeRec.
* If head is NULL, return NULL; handles both cases for overrun or empty null. Being NULL has only one consequence.
* deleteNodeRec has only one** one base** case, and a warning case(that's not a base case as such, it's an invalid input thing).
* We are deleting the node we are sitting on. So we wait for i to be 0.



