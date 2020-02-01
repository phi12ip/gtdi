# data-model

## stage 1

``` rust
struct todoItem {
    id: u64,
    uuid: GUID,
    subject: Subject,
    dueDate: [DateTime],
    projects: [Project],
    contexts: [Context],
    isCompleted: Bool,
    completedDate: DateTime,
    isArchived: Bool,
    priority: Priority,
    idNote: [noteItem::GUID]
}
```


## stage 2
``` rust   
struct noteItem {
    id: u64
    uuid: GUID,
    projects: [Projects]
    idTodo: [todoIdem::GUID],
    
} 
```
## stage 3
``` rust
calendarItem: {

}
```
