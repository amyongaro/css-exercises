# Class and ID Selectors
Knowing how to add class and ID attributes to HTML elements, as well as use their respective selectors, is invaluable. It's important to practice using them.

There are several elements in the HTML file provided, which you will have to add either class or ID attributes to, as noted in the outcome image below. You will then have to add rules in the CSS file provided using the correct selector syntax. Look over the outcome image carefully, and try to keep in mind which elements look similarly styled (classes), which ones may be completely unique from the rest (ID), and which ones have slight variations from others (multiple classes).

It isn't entirely important which class or ID values you use, as the focus here is on being able to add the attributes and use the correct selector syntax to style elements. For the colors in this exercise, try using a non-keyword value (RGB, HEX, or HSL). The properties you need to add to each element are:

* **All odd numbered elements**: a light red/pink background, and a list of fonts containing `Verdana` and `DejaVu Sans` with `sans-serif` as a fallback
* **The second element**: blue text and a font size of 36px
* **The third element**: in addition to the styles for all odd numbered elements, add a font size of 24px
* **The fourth element**: a light green background, a font size of 24px, and bold

Quick tip: in VS Code, you can change which format colors are displayed in RGB, HEX, or HSL by hovering over the color value in the CSS and clicking the top of the popup that appears!

> ### Note:
> Part of your task is to add a font to _some_ of these items. Your browser's font's might be different than the one displayed in the desired outcome image. As long as you confirm that the fonts _are_ being applied to the right lines any differences are okay for this exercise.

## Desired Outcome
![desired outcome](./desired-outcome.png)


### Self Check
- Do the odd numbered `p` elements share a class?
- Do the even numbered `div` elements have unique IDs?
- Does the Number 3 element have multiple classes?

## My Original Answer (before looking at the answer)

<body>
    <p>number 1 - i'm a class!</p>
    <div class="second">number 2 - i'm one id.</div>
    <p id="third">number 3 - i'm a class, but cooler!</p>
    <div class="fourth">number 4 - i'm another id.</div>
    <p>number 5 - i'm a class!</p>
</body>

/* styles.css */

p {
    background-color: hsl(360, 60%, 80%);
    font-family: "Verdana", "DejaVu Sans", sans-serif;
}

.second {
    color: rgb(0, 0, 255);
    font-size: 36px;
}

#third {
    font-size: 24px;
}
.fourth {
    background-color: hsl(120, 60%, 70%);
    font-size: 24px;
    font-weight: bold;
}

# What I did as the answer...