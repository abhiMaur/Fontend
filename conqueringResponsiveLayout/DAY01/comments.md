# DAY 01

## Percentages vs Fixed widths

    By default all block level elements have a width of 100%.
    if we set width in % then the element resize with the viewport.

## Percentages on the child

    Always set width of a child as a percentage to prevent overflow in a responsive page.
    you can use the rule overflow: hidden, but will lose content.

## Why it's a good idea to avoid heights

    Your block element adjusts its height by deafault to prevent overflow, setting a fixed height creaates an overflow of content outside the parent.
    Use paddiing if you want some spacing below your child.
    You can also use min-height, max-height to control unwanted shrinking and stretching.

## em VS rem
    
    rem calculates relative to the root of the webpage,
    em calculated relative to its parent element.