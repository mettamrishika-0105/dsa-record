All 10 C programs compiled with GCC using `-std=c11 -Wall -Wextra -pedantic`. Experiment 4 was linked with `-lm` for `pow()`.

| Experiment | Sample test | Verified result |
|---|---|---|
| 1. Array operations | Insert 25 at index 2, delete index 1 | `10 20 25 30 40 50`, then `10 25 30 40 50` |
| 2. Employee records | Two records; search ID 101 | `Found: 101 Arun Manager 55000.00` |
| 3. Infix to postfix | `(A+B)*(C-D)` | `AB+CD-*` |
| 4. Postfix evaluation | `23+4*` | `Result = 20.00` |
| 5. Simple queue | Enqueue 10, 20; display; dequeue; display | `10 20`, then `20` remains |
| 6. Priority queue | Insert `(10,3)`, `(20,1)`, `(30,2)`; delete | Removes `20` with priority `1`; remaining entries are 10 and 30 |
| 7. Singly linked list | Append 10, 20; prepend 5; delete 10 | `5 -> 10 -> 20 -> NULL`, then `5 -> 20 -> NULL` |
| 8. Circular queue | Enqueue 10, 20, 30; dequeue once | `10 20 30`, then `20 30` |
| 9. BST traversals | Insert `50 30 70 20 40 60 80` | In-order `20 30 40 50 60 70 80`; pre-order `50 30 20 40 70 60 80`; post-order `20 40 30 60 80 70 50` |
| 10. BFS and DFS | Graph edges `0-1, 0-2, 1-3, 2-4, 3-4`, start 0 | BFS `0 1 2 3 4`; DFS `0 1 3 4 2` |

**Status: 10/10 sample tests passed.**
