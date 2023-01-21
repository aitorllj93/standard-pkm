# Artem Kirsanov - My Simple Note-taking setup 
#types/reference #status/needs-review 

Source:: https://www.youtube.com/watch?v=E6ySG7xYgjY
Author:: Artem Kirsanov

```embed
title: 'watch?v=E6ySG7xYgjY'
image: 'https://img.youtube.com/vi/E6ySG7xYgjY/maxresdefault.jpg'
description: ''
url: 'https://www.youtube.com/watch?v=E6ySG7xYgjY'
```

### The Benefits of the System don't increase with complexity

The Benefits of the System don't increase with complexity, in fact most often quite the opposite. Tinkering with tags and thinking how to best structure your notes can distract you from what actually matters

The key idea behind [[Zettelkasten]] is that you don't impose an artificial structure on the system. You don't create folders to separate the topics, instead, you put everything in one place and **let the structure emerge by itself through interconnections**

### Map of Content

[[Map of Content]](MoC)  is **a note containing links to other notes**. It's a meta note. It can be thought of as an index of notes on a specific topic, question, perspective, or area of interest. Just like a table of contents

### Folder Structure

1) Zettelkasten -> Atomic "idea" notes.
2) [[Reference]] Notes -> Used to reference books, articles
3) Files -> attachments
4) [[Templates]] -> templates
```dataview  
LIST FROM "Notes" WHERE Reference AND Reference = this.file.link
```