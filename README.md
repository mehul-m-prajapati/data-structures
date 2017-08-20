## Commonly used data structures

### Array
### Linked list
```
typedef struct node {
  
  int n;
  struct node *next;

} node;
```
![ll](http://www.cs.usfca.edu/~srollins/courses/cs112-f07/web/notes/linkedlists/ll4.gif)

#### Operations
- Insert
- Delete
- Update
- Search

### Queue (first-in, first-out)
### Stack (last-in, first-out)
```
typedef struct {

  int *numbers;
  int size;
  
} stack;
```
#### Operations
- Push
- Pop

![s](https://www.tutorialspoint.com/data_structures_algorithms/images/stack_representation.jpg)

```
typeded struct {

  int front;
  int *numbers;
  int size;
  
} queue;
```
### Operations
- Enqueue
- Dequeue

![Q](https://netmatze.files.wordpress.com/2014/08/queue.png)

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
