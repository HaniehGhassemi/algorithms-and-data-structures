## 🔗 Insert a Node After a Given Value

### Code Implementation

```javascript
current = head

while current.next.next != null:
    current = current.next

current.next = null
```

### Visual Representation

```
head -> [3] -> [8] -> [9] -> [11] -> [18] -> null
```

## 🗑️ Delete the Last Node

### Code Implementation

```javascript
current = head

while current.next.next != null:
    current = current.next

current.next = null
```

### Visual Representation

```
head -> [3] -> [8] -> [9] -> [11] -> null
```
