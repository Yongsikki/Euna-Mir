---
sticker: emoji//2b50
alias: 
---
```dataview
Table author as Author, ("![|100](" + cover + ")") as Cover, category as Category, rating as Raiting
From "Bookshelf"
Where contains(rating, "⭐⭐⭐⭐⭐")
```
