---
title: "Post: Modified Date"
last_modified_at: 2016-03-09T16:20:02-05:00
categories:
  - Post Formats
tags:
  - Post Formats
  - readability
  - standard
---

a = int(input())
A = a
count = 0
while True:
    count += 1
    x = a//10
    y = a%10
    z = x + y
    a = int(str(a%10)+str(z%10))
    if A == a :
        break
print(count)