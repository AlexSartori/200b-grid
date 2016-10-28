# 200b-grid
##### A CSS grid system in 200 bytes!

---

- Include my CSS:

    `<link rel="stylesheet" href="200b-grid.min.css" />`


- Classes to use:
  - `row` = full-width container
  - `col-s` = small column (25%)
  - `col-m` = medium column (33.33%)
  - `col-l` = large column (50%)
  
  
- Create a row and insert columns:
```html
    <div class="row">
       <div class="col-s"><p>col-s</p></div>
       <div class="col-s"><p>col-s</p></div>
       <div class="col-s"><p>col-s</p></div>
       <div class="col-s"><p>col-s</p></div>
    </div>

    <div class="row">
        <div class="col-m"><p>col-m</p></div>
        <div class="col-m"><p>col-m</p></div>
        <div class="col-m"><p>col-m</p></div>
    </div>

    <div class="row">
        <div class="col-l"><p>col-l</p></div>
        <div class="col-l"><p>col-l</p></div>
    </div>
```


- Result:

    ![alt tag](http://i.imgur.com/H8A1HAS.png)




---
*Alex Sartori http://alexsartori.github.io*
