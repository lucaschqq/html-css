# CSS selectors and which rule wins: my answers

## 1. When must you use a class selector, and not an element selector?
    We use a class selector and not an element selector when we want to change or style a specific HTML tag instead of all of them.

## 2. What does the space mean in `.material-shelf p`?
    The space in '.material-shelf p' is to find the <p> in every element that has the class="material-shelf". 

## 3. What does `>` mean in `.quick-nav > a`?
    The '>' in '.quick-nav > a is to find every 'a' that has an element with class="quick-nav" as the direct parent.

## 4. Why must a button link have a `:hover` style and a `:focus` style?
    A button link must have a ':hover' style and a ':focus' style so that it gives visible feedback and easier accessibility when someone uses a link. 

## 5. If `a` and `.quick-nav > a` both set `color` on a navigation link, which selector wins in the stylesheet of this lesson?
     If 'a' and '.quick-nav > a' both set 'color' on a navigation link,'.quick-nav > a' wins because it is more specific.
