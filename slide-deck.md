---
theme: uncover
class:
  - lead
  - invert
paginate: true
---

[//]: # (© 2025 by James McMahon. All Rights Reserved.)

[//]: # (run using `marp slide-deck.md -o slides.html --html --allow-local-files -w`)

# Virtual Threads

https://github.com/JamesMcMahon/spring-boot-demo-virtualthread

---

## What are Threads?

- threading as a concept
- going into what an OS thread is

---

### The problem with Threads

- overhead

---

### Java examples of Threading and it's limit

- classic Tomcat HTTP server threading

---

## How to solve this?

- give example of how node.js server works

---

### Reactive Java intro

- way to port over reactive concepts to java

---

### The cons of Reactive Java

- learning curve
- replaces things you usally have in the standard java programming model
- what color is your function?

---

## Virtual Threads

- have your cake and eat it too
- same programming model as java
- no "colored" functions

---

### How is the performance in practice?

- refer to research

---

### Not a pancea

- good for IO blocking apps
- cpu bound apps don't get much benefit
- talk about backpressure

---

#### backpressure

- maybe needs it's own slides, it's complex

---

## Wrap up

- TODO