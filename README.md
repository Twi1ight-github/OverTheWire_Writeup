---
description: >-
  เอกสารฉบับนี้จัดทำขึ้นเพื่อเป็นการสรุปข้อมูลการศึกษา Basic Linux Command
  สำหรับตัวผู้จัดทำและอาจจะเป็นแนวทางให้กับผู้อื่นที่มีความสนใจจะศึกษา Linux
  Command
---

# OverTheWire\[Bandit] Writeup

## Level 0

คือการ ssh เข้าไปยัง server **bandit.labs.overthewire.org** port **2220** โดยใช้ username bandit0 และ password bandit0

```
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

พอเข้ามาแล้วก็จะเป็นแบบนี้

<figure><img src="https://lh3.googleusercontent.com/Bltaxaw6LHUG5CDb14P0nSJOYZEPJYsjOP-RsCdIBtPKV9VYSFYyG7k70SRWTWZNl9vpQwKbR-soef4yKSsu5MzV5hewaJcb3d5kqkz-9QtW7-sb3DsuB5o7ZfoousN6SnaClxyn-YnSjqhJKgIeI3qcr3PrPgvu8HB7cZw6uGYxL37rH49ZGG4K9A" alt=""><figcaption></figcaption></figure>

## Level 0->1

เมื่อเข้าไปยังserver แล้ว ให้ใช้ command ls -al เพื่อดูว่ามี file อะไรบ้าง

<figure><img src="https://lh6.googleusercontent.com/oaIYA8JEq7j51PagkxS0uJEF5rqhjut0fLGDbZkf54M9aJNUJZTzmxSknOUF6NQnOKBwaIXymjJcAcROBV1h7taMPIZNaugLCffgixBepYl13dLxqHP7TNrOdwNJjpCiuZfBi6iGRK_GwYC_eiGCZWOW4g27Zly1VJUjkLQCwIuXvwdLC1kqQYMjDA" alt=""><figcaption></figcaption></figure>
