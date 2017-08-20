## Commonly used data structures

### Arrays

### Linked list
```
typedef struct node {
  
  int n;
  struct node *next;

} node;
```
![ll](http://www.cs.usfca.edu/~srollins/courses/cs112-f08/web/notes/linkedlists/ll2.gif)
#### Operations
- Insert
- Delete
- Update
- Search

### Stack (last-in, first-out)
```
typedef struct {

  int *numbers;
  int size;
  
} stack;
```
![s](https://www.tutorialspoint.com/data_structures_algorithms/images/stack_representation.jpg)
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
![Q](https://netmatze.files.wordpress.com/2014/08/queue.png)
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
```
