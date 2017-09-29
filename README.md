## Common Operations
- Insert
- Delete
- Update
- Search
---
### Arrays
```
int num[100];
```
---
### Linked list
```
typedef struct node {
  
  int n;
  struct node *next;

} node;
```
<img src="http://www.cs.usfca.edu/~srollins/courses/cs112-f08/web/notes/linkedlists/ll2.gif" width="400">

---
### Hash map (AKA hash table)
```
#define MAX_NUM_ALPHA           26
#define LENGTH                  32

typedef struct alpha
{
    char word[LENGTH];
    struct alpha *pNext;    
} 
node;

// Hash Table (Chaining using linked-list)
node *pTable[MAX_NUM_ALPHA] = { NULL };
```
<img src="http://www.cse.unt.edu/~donr/courses/2050/images/Figure1249.gif" width="400">

---
### Tree
```
typedef struct node {

  int n;
  struct node *left;
  struct node *right;

} node;
```
<img src="http://2.bp.blogspot.com/-jVJb1Yjem3Y/UJEqsa6S1nI/AAAAAAAAFK4/DoJekCAOTXA/s1600/bst.png" width="400">

---
### Stack (last-in, first-out)
```
typedef struct {

  int *numbers;
  int size;
  
} stack;
```
<img src="https://www.tutorialspoint.com/data_structures_algorithms/images/stack_representation.jpg" width="400">

#### Operations
- Push
- Pop

---
### Queue (first-in, first-out)
```
typeded struct {

  int front;
  int *numbers;
  int size;
  
} queue;
```
<img src="https://netmatze.files.wordpress.com/2014/08/queue.png" width="400">

#### Operations
- Enqueue
- Dequeue

A stack and queue are both abstract data types, where we can implement them in any number of different ways but expect the same properties and operations.
