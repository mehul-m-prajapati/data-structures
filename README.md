### Common Operations
- Insert
- Delete
- Update
- Search

### Arrays

### Linked list
```
typedef struct node {
  
  int n;
  struct node *next;

} node;
```
<img src="http://www.cs.usfca.edu/~srollins/courses/cs112-f08/web/notes/linkedlists/ll2.gif" width="400">

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

### Queue (first-in, first-out)
```
typeded struct {

  int front;
  int *numbers;
  int size;
  
} queue;
```
<img src="https://netmatze.files.wordpress.com/2014/08/queue.png" width="400">
### Operations
- Enqueue
- Dequeue

- A stack and queue are both abstract data types, where we can implement them in any number of different ways but expect the same properties and operations.

### Hash map (AKA hash table)



### Tree
```
typedef struct node {

  int n;
  struct node *left;
  struct node *right;

} node;
``1
