## TASK : สร้าง procedure หาผลรวมของทุกสมาชิกใน List

- FN Prototype : list => number

#### example

```
(procedure-name (list 1 2 3))
> 6

(procedure-name (list 1))
> 1

(procedure-name (list 1))
> 0

```

- ลองปรับ procedure ให้คืนค่าข้อความเป็น list ว่างเปล่า

```rkt
(procedure-name (list))
> "Invalid argument, expect not empty list"
```
