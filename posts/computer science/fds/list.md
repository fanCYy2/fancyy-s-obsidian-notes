---
title: 链表
published: 2026-06-01
tags:
  - computers_science
  - fds
---
## 单链表
### 初始化
``
```
List initList() {
    List head = (List)malloc(sizeof(struct Node));
    head->next = NULL;
    return head;
}
```
