# wed-intro-inline-vs-block-example

Short demo based on block-level vs inline question.

#### Project Structure

```
wed-intro-inline-vs-block-example/  
├── css
│ └── style.css
├── imgs/  
│ └── block-level.png
│ └── inline-level.png  
└── README.md
```

---
#### Additional Information

HTML elements are categorized into two main display types by default: block-level elements and inline elements. These categories determine how elements behave in the document flow, specifically regarding line breaks and space occupation.

Block-level Elements:

- **Starts on a new line:**
    
    A block-level element always begins on a new line in the browser.
    
- **Takes up full available width:**
    
    By default, block-level elements occupy the entire width of their parent container.
    
- **Examples:**
    
    Common block-level elements include `<p>` (paragraph), `<div>` (division), `<h1>` to `<h6>` (headings), `<ul>` (unordered list), `<ol>` (ordered list), and `<li>` (list item).
    
- **Can contain other block and inline elements:**
    
    Block-level elements can serve as containers for both other block-level elements and inline elements. 
    

Inline Elements:

- **Does not start on a new line:**
    
    Inline elements appear in line with the surrounding text and do not force a new line break.
    
- **Takes up only necessary width:**
    
    Inline elements only occupy the horizontal space required by their content. 
    
- **Examples:**
    
    Common inline elements include `<a>` (anchor/link), `<span>` (generic inline container), `<strong>` (strong importance), `<em>` (emphasis), `<img>` (image), and `<button>` (button).
    
- **Cannot contain block-level elements:**
    
    Inline elements are typically used for styling or adding functionality to small portions of text and cannot contain block-level elements.



Key Differences Summarized:


|Feature|Block-level Elements|Inline Elements|
|---|---|---|
|New Line|Starts on a new line|Does not start on a new line|
|Width|Full available width|Only content's width|
|Containment|Can contain block/inline|Cannot contain block|
|Margin/Padding|Top/bottom margin/padding accepted|Top/bottom margin/padding generally not applied (except for font size)|
