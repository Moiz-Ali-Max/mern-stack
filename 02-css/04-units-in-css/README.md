# Units in CSS
1. Absolute Unit
2. Percentage Unit
3. Relative Unit
    1. Relative to font-size
    2. Related to Document

### 1. Absolute Unit
- mm (fixed): 
- cm (fixed):
- in (fixed): 
- px (fixed): smallest single unit of image is pixel. 1/96 of an inch

### 2. Percentage Unit
- div {width: 10%;}: it depends on the percentage of it's parent. E.g.,
```
<div> 
I am parent div
    <div>I am child div </div> - 10% of 500px
</div> - it is 500 x 500

```

### 3. Relative Unit
1. Relative to Font Size
    - em: relative to parent font-size
        ```
        parent div font-size is 18
        then if child font size is 1em, then it will be 1*18
        ```
    - rem: relative to root (HTML)

2. Relative to ViewPort
    - vw: 1*100 width of viewport
    - vh: 1*100 height of viewport